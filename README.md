Install conda for python 3.7 with using this link:  
    https://www.anaconda.com/distribution/#download-section

  

After that create a env using this command:

  

    conda create --name MoleculeNet-OutPerforming-Default-Results python=3

  

Activate the env:

  

    conda activate MoleculeNet-OutPerforming-Default-Results

  
  

Install needed dependencies to this env using this command:

  

    conda install -c deepchem -c rdkit -c conda-forge -c omnia deepchem=2.1.0

Also, we need to understand how to define and use molecules in our code, so visit this link to get information about rdkit package:

    https://www.rdkit.org/docs/GettingStartedInPython.html

  

For now, I've added 2 ipython notebooks for example usage

- Graph Convolutions For Tox21

- Multitask Networks On MUV