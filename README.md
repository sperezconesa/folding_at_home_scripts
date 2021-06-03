# Folding@Home Utility Scripts and Notebooks

This repository contains my scripts and notebooks to manage folding@home data.
Use them as you wish but beware of bugs! Please let me know if you find some bug
or problem and please share your improvemnts to the code!

## Current Files

+ `fah-progress.ipynb`: this notebook will download the leveldb of the workserver
and help-you study the state of your data.
+ `environment.yml`: this will install with conda the necessary libraries to run
the code of this repository.

## Install Environment


You must also install [leveldb](https://github.com/google/leveldb) to use the
fah-progress.ipynb.
``` bash
conda env create -f environment.yml
conda activate folding_at_home_scripts
ipython kernel install --user --name=folding_at_home_scripts
```
