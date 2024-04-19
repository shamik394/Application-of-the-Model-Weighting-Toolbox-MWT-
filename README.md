# Application-of-the-Model-Weighting-Toolbox-MWT-

Paths to each dataset that are currently in these scripts must be changed to the users own paths. 

Weights.csv - This files includes the varoius weights used in this analysis. If users develop new model weights you can change them in this file.

Plot_Maps.ipynb - This script allows a user to chose models from CMIP6 (using Intake ESGF)and plot them for any variable.This script also plots the data or the observation.This script also creates the model avg and their biases and plots them. 

Plot_Weights.ipynb - This script allows a user to plot the various weights in the exercise with a barplot.

BMA_Implementation.ipynb - This script allows a user to chose models from CMIP6 (using Intake ESGF) and perform BMA to estimate model weights.

Sanderson_Implementation.ipynb - This script allows a user to bring in skill scores from ILAMB and use them in the Sanderson Model Weighting Equation to estimate model weights. 

RMSE_all_models.ipynb - This script allows a user to calculate the different RMSE for all models (including model averages). 


Libraries and packages needed:

Step 1: Download mini conda from this site (https://docs.anaconda.com/free/miniconda/index.html) and check which version you need for your computer/machine. 

Step 2: Conda install (conda install -c conda-forge intake-esgf) for the Intake ESGF Catalog - for CMIP6 models

Step 3: Conda install (conda install -c conda-forge intake) - for ILAMB (International Land Benchmarking Package) to grab the skill scores

Step 4: Install remaining libraries (ie matplotlib and ipywidgets)

Step 5: Conda install dask (type that into the terminal and the downloable version)

Step 6: Pip intall scipy (type that into the terminal)

Step 7: Conda install panda as you will need this for the skill scores which will follow under here:
