# vcog_hps_ad

This work includes packages, scripts, and notebooks for the following article [A signature of cognitive deficits and brain atrophy that is highly predictive of progression to Alzheimer’s dementia](https://doi.org/10.1101/352344).

Here is a brief description of each item in the repository:
* **Proteus** - a Python package by [Christian Dansereau](https://github.com/cdansereau). Proteus was built on [scikit-learn](http://scikit-learn.org/stable/#) and it offers machine learning tools to make highly confident predictions
* **vcog_hpc_prediction_simulated_data.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia from cognitive and structural features using *simulated data*
* **simulation_script.py** - a Python script that generates simulated data from raw data 
* **simulated_data.csv** - a comma separated value file that contains simulated data 
* **spm_container** - an Octave package containing wrappers for [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) functions for segmentation and DARTEL 

It is rendered here using [Jupyter Book](https://github.com/jupyter/jupyter-book),
with compute infrastructure provided by the [Canadian Open Neuroscience Platform (CONP)](http://conp.ca).
