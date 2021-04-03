# [Act In Space NZ 2018](https://actinspace.org)

Developing a solution for maritime monitoring
using Artificial Intelligence on Earth Observation data.

![Boats detected from Sentinel 1 radar imagery](https://user-images.githubusercontent.com/23487320/113465691-ac319a00-9492-11eb-8114-90a122642b97.png)

Left: Sentinel 1 radar imagery, Center: ConvNet detected ships, Right: Groundtruth labels of ships

# Getting started

## Quickstart

Launch Binder (Interactive jupyter notebook in the cloud).
Data will be loaded via [Quilt](https://github.com/quiltdata/quilt). Cheers to [data2binder](https://github.com/quiltdata/data2binder)!

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
