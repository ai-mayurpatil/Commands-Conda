# Conda Commands
Here are some commonly used Conda commands.
# 1. Basic Conda Commands
- ## If not working in git bash conda:
```bash
source activate
```
- ## Create a new environment:
```bash
conda create -n myenv python=3.8
```
- ## Activate an environment:
```bash
conda activate myenv
```
- ## Deactivate an environment:
```bash
conda deactivate
```
- ## List all environments:
```bash
conda env list
```
- ## Remove an environment:
```bash
conda remove -n myenv --all
```
# 2. Installing and Managing Packages
- ## Install a package:
```bash
conda install numpy
```
- ## Install a specific version of a package:
```bash
conda install numpy=1.18.5
```
- ## Update a package:
```bash
conda update numpy
```
- ## Uninstall a package:
```bash
conda remove numpy
```
- ## List installed packages in the current environment:
```bash
conda list
```
# 3. Environment Management
- ## Export an environment to a file:
```bash
conda env export > environment.yml
```
- ## Create an environment from a file:
```bash
conda env create -f environment.yml
```
- ## Clone an environment:
```bash
conda create --name newenv --clone myenv
```
# 4. Conda Updates
- ## Update Conda:
```bash
conda update conda
```
- ## Update Anaconda distribution:
```bash
conda update anaconda
```
# 5. Conda Channels
- ## Add a channel:
```bash
conda config --add channels conda-forge
```
- ## Remove a channel:
```bash
conda config --remove channels conda-forge
```
- ## List configured channels:
```bash
conda config --show channels
```
# 6. Miscellaneous
- ## Check Conda version:
```bash
conda --version
```
- ## Check information about the current environment:
```bash
conda info
```