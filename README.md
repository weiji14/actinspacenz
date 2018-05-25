# [Act In Space NZ 2018](https://actinspace.nz/)

Using Artificial Intelligence to develop new applications from Earth Observation data.

# Getting started

## Quickstart

Launch Binder (Interactive jupyter notebook in the cloud).

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/weiji14/actinspacenz/master)

## Installation

Start by cloning this [repo-url](/../../)

    git clone <repo-url>
    cd nz_space_challenge
    conda env create -f environment.yml

## Running the jupyter lab/notebook session

    source activate actinspacenz
    python -m ipykernel install --user --name actinspacenz  #to install conda env properly
    jupyter kernelspec list --json  #see if kernel is installed
    jupyter lab
