Code for Gill & Chiel 2020: Rapid Adaptation to Changing Mechanical Load by Ordered Recruitment of Identified Motor Neurons
===========================================================================================================================

|Binder badge|

This repository holds code that performs analyses and generates figures published in

    Gill, J. P., & Chiel, H. J. (2020). Rapid Adaptation to Changing Mechanical Load by Ordered Recruitment of Identified Motor Neurons. eNeuro, 7(3). https://doi.org/10.1523/ENEURO.0016-20.2020

Data for this publication used by this code is stored in a sister repository on GIN: https://gin.g-node.org/jpgill86/Gill-Chiel-eNeuro-2020-data

Instructions
------------

To install dependencies and launch the Jupyter notebook, install conda_ and then run the following::

    cd Gill-Chiel-eNeuro-2020-code
    conda env create -f environment.yml -n Gill-Chiel-eNeuro-2020-code
    conda activate Gill-Chiel-eNeuro-2020-code
    jupyter notebook Gill-Chiel-eNeuro-2020-code.ipynb

You may then execute the entire notebook from top to bottom, which will

1. Download all of the data files from GIN_ (~97 MB)
2. Generate figure files
3. Generate tables of statistics

Licensing
---------

The contents of this repository are released under the `Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License <LICENSE>`_.

.. |Binder badge| image:: https://mybinder.org/badge_logo.svg
    :target: https://mybinder.org/v2/gh/CWRUChielLab/Gill-Chiel-eNeuro-2020-code/master?filepath=Gill-Chiel-eNeuro-2020-code.ipynb

.. _conda:  https://docs.conda.io/projects/conda/en/latest/user-guide/install/
.. _GIN:    https://gin.g-node.org/jpgill86/Gill-Chiel-eNeuro-2020-data
