# Miniconda Commands

- conda info
  - all information
- conda update conda
  - for updating itself
- conda update python
  - for updating python or any other package name replaced by  "python" in command.
- conda env list
  - list of all environments
- conda list
  - list of installed packages
- conda install spyder
  - for installin any package
- conda create -n pandas_env
  - for creating the environment named 'pandas env'
- conda activate pandas_env
  - to activate the environment
- conda deactivate
  - to deactivate the current environment and go back to default(base)
- pip install pandas numpy
  - for installing more than one libraries.
- create --clone pandas_env --name pandas_env2
  - for creating a copy
- conda list --explicit > pandas_env.txt
  - save the text format file

(Assignment: How to use this file for creating an environment.)

- conda install --yes --file requirements.txt
  -  using the txt file which contains the packages needed install.
- conda create -n new_env biopython
  - for creating  an environment with specific package.
- conda search python
  - for searching  the particular package
- ctrl+c
  - for stopping any command
- conda env remove --name pandas_env
  -  for removing the whole environment.
- conda remove --name pandas_env python
  -  for uninstalling the python from the particular environment.
- conda install --channel conda-forge python=3.4
  - for installing specific version
- where python
  -  showing the path of python installed in system.
- pip install numpy==1.11