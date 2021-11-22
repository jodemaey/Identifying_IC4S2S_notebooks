
# Identifying efficient ensemble perturbations for initializing subseasonal-to-seasonal prediction 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## General Information

These Jupyter notebooks come as a supplementary material to the article :

* Demaeyer, J., Penny, S. G., & Vannitsem, S. Identifying efficient ensemble perturbations for initializing subseasonal-to-seasonal prediction, submitted to JAMES, [https://doi.org/10.1002/essoar.10508037.1](https://doi.org/10.1002/essoar.10508037.1), under review, 2021.

and detail the computations performed to obtain the results therein.

These notebooks study the usage of various initialization methods for S2S ensemble predictions using [qgs](https://github.com/Climdyn/qgs) configured to run the coupled ocean-atmosphere [MAOOAM](https://github.com/Climdyn/MAOOAM) model.

More details are available inside the notebooks:

* [identifying_ic4s2s_weak-LFV.ipynb](./identifying_ic4s2s_weak-LFV.ipynb): study with a weak low-frequency variability in MAOOAM.
* [identifying_ic4s2s_strong-LFV.ipynb](./identifying_ic4s2s_strong-LFV.ipynb): study with a strong low-frequency variability in MAOOAM.

## About

Copyright (c) 2021 Jonathan Demaeyer

See [LICENSE.txt](./LICENSE.txt) for license information.

## Requirements

The present notebooks were tested on a computer with

    20 recent cpu cores,
    32 Gb of RAM,


## Installation

To install these notebooks, you must first [install the qgs model](https://qgs.readthedocs.io/en/latest/files/general_information.html#installation) and test that it works properly on your machine. Follow the instructions in the model documentation. Then you must move the notebooks in the notebooks directory and run it with jupyter-notebook. In the qgs model main folder, do:

    conda activate qgs
    cd notebooks
    jupyter-notebook

It will open a page in a web browser where you can open and then run the notebooks.

