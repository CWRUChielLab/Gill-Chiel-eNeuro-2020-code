Gill-Chiel-eNeuro-2020-code
===========================

|Binder badge|

This repository holds code that performs analyses and generates figures published in

Gill JP, Chiel HJ (in press) Rapid adaptation to changing mechanical load by ordered recruitment of identified motor neurons. eNeuro.

Data for this project is stored in a sister repository on GIN: https://gin.g-node.org/jpgill86/Gill-Chiel-eNeuro-2020-data

To install dependencies and launch the Jupyter notebook, install conda_ and then run the following::

    cd Gill-Chiel-eNeuro-2020-code
    conda env create -f environment.yml -n Gill-Chiel-eNeuro-2020-code
    conda activate Gill-Chiel-eNeuro-2020-code
    jupyter notebook Gill-Chiel-eNeuro-2020-code.ipynb

You may then execute the entire notebook from top to bottom, which will

1. Download all of the data files from GIN_ (~97 MB)
2. Generate figure files
3. Generate tables of statistics

.. |Binder badge| image:: https://mybinder.org/badge_logo.svg
    :target: https://mybinder.org/v2/gh/CWRUChielLab/Gill-Chiel-eNeuro-2020-code/master?filepath=Gill-Chiel-eNeuro-2020-code.ipynb

.. _conda:  https://docs.conda.io/projects/conda/en/latest/user-guide/install/
.. _GIN:    https://gin.g-node.org/jpgill86/Gill-Chiel-eNeuro-2020-data
