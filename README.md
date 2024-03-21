# Extract raster pixel values for a specific lat and long coordinate

## Description

This repository is developed to utilize specific latitude and longitude coordinates to extract EVI values calculated from HLS images. The extracted data is then plotted to verify the phenological phases.

## Dependencies management
The following comand can be used to recreate the conda enviroment with all the dependencies needed to run the code in this repository.
```
conda env create -f environment.yml
```
After creating the new enviroment (or you can use an existing one) you need to activate it and install the package in development mode. To do so, from the repository root, run the command below. It will install the package in development mode, so you can make changes to the code and test it without the need to reinstall the package.
```
pip install -e .
```# extract_pixels_values
