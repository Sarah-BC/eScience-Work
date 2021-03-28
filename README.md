# eScience-Work
This collection of Jupyter notebooks was developed by undergraduate students at the University of Washington as part of the OOI Cabled Array Value Added (CAVA) project, in collaboration with Rob Fatland at the eScience Institute. 

## Getting started with Conda and Jupyter Notebook
 - Download Anaconda (https://www.anaconda.com/distribution/#download-section)
 
 - In Anaconda terminal (Anaconda Powershell Prompt), use "jupyter notebook" to launch jupyter in a browser window if available.  If your anaconda does not have jupyter installed already, install Jupyterlab by executing "conda install -c conda-forge jupyterlab" 
 
 - Jupyter Notebook will display all files and folders from your personal drive and folders
 
 
 
## Notebooks in this repo:


### canon_explore.ipynb explores canonical data from the OOI RCA Oregon Slope Base shallow profiler CTD.

This Jupyter notebook exists to establish a canonical record of seawater measurements pertaining to coastal upwelling using data collected by the OOI RCA. Statistical analysis and data visualization of practical salinity is done within the notebook. 

This notebook completed an initial analysis of 1 week of salinity and temperature data at one location in the OOI RCA. More work can be done using code here to further explore the California Current upwelling system. 




### golive_library.ipynb contains functions necessary to run the modis.ipynb and modis-explore.ipynb notebooks.

This program was obtained from github.com/robfatland/chlorophyll and is maintained for the function of other notebooks in this collection.




### modis.ipynb compares data collected by the NASA MODIS Aqua satellite to data collected by the OOI RCA.

This Jupyter notebook uses MODIS chlorophyll a data to produce maps of sea surface chlorophyll a within a region off the Oregon coast.MODIS chlorophyll data can be compared to OOI RCA fluorescence data obtained near the surface.
This notebook is incomplete and is not currently under development.
Figures produced by this notebook contribute to the notebook named chlorophyll.ipynb on github.com/robfatland/chlorophyll.

#### Running MODIS notebook
- Ensure golive_library.py and modis.ipynb are in the same level of the same folder


 - In Anaconda terminal, you will need to install several python packages.  Use the command "conda install [package name]" and enter "y" when prompted.  Packages to install: netCDF4, xarray, numpy
 
   -If you are running on a Windows device, you will need to use a gitBASH shell.  Follow instructions at the following link for a proper download:https://carpentries.github.io/workshop-template/#shell.  Once BASH is installed, you will need to run "source Anaconda3/Scripts/activate Anaconda3/" in the first directory openned by BASH and then cd into the folder where your jupyter notebooks are contained before the "jupyter notebook" command will work to launch your notebook
   
   This collection of Jupyter notebooks was developed by undergraduate students at the University of Washington as part of the OOI Cabled Array Value Added (CAVA) project, in collaboration with Rob Fatland at the eScience Institute. 




### modis-explore.ipynb is a copy of modis.ipynb made for test edits. 

This notebook can be disregarded by users and is maintained for development purposes only.




### Plastic.ipynb is a collection of data and knowledge pertaining to marine plastic pollution. 

This notebook is largely incomplete and is not currently under development.
