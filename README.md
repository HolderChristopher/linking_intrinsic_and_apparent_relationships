# linking_intrinsic_and_apparent_relationships
This project focuses on the research from the following journal article:

Holder, C. and Gnanadesikan, A.: Can machine learning extract the mechanisms controlling phytoplankton growth from large-scale observations? – A proof-of-concept study, Biogeosciences, 18, 1941–1970, https://doi.org/10.5194/bg-18-1941-2021, 2021.


The original version of the code (including scripts, functions, and source files) listed in the article can be found in the following Zenodo repository:

Christopher Holder, & Anand Gnanadesikan. (2020). Dataset and scripts for manuscript "Can machine learning extract the mechanisms controlling phytoplankton growth from large-scale observations? – A proof of concept study" (2021_02_05) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4511337


The original code from the article uses MATLAB. This scripts used in the particular Github project translate the MATLAB code into Python using Jupyter notebooks. Because a random number generator is used in two different programming languages, the results seen in this project may differ very slightly from the results listed in the manuscript. However, the main results and conclusions remain the same.

# Files
The file Scenario1.ipynb contains the code for Scenario 1 including downloading the data from Zenodo, prepping the data for analysis, training the machine learning models, and some of the preliminary performance results of the models (as of April 20, 2022). More code will be added at a later date that includes the figures, including the sensitivity analyses.

The file Scenario1_Data_Exploration.ipynb does a bit more in-depth data exploration than the original Scenario1.ipynb file, including correlation analysis and looking at the variables of each month as colored contour plots. More code may be added later on.
