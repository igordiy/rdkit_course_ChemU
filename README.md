![PyPI - Python Version](https://img.shields.io/badge/python-3.8-green.svg)

This repository contains some basic information about installation of all necessary packages to be used in the RDkit tutorials. 

## Installation
Our tutorial requires conda, so first install Miniconda from [https://conda.io/miniconda.html](https://conda.io/miniconda.html). 
On Windows, macOS, and Linux, it is best to install Miniconda for the local user, which does not require administrator permissions and is the most robust type of installation.
After that, the installation process is kinda straightforward and could be made in the following steps:
1. `conda create -c conda-forge -n my-rdkit-env rdkit`
2. `conda activate my-rdkit-env`


If for some reason this does not work, try:
1. `cd [anaconda folder]/bin`
2. `source activate my-rdkit-env`
