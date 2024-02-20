# Autocorrelation

This repository contains two jupyter notebooks, a txt file to be used as a template to import the data in a suitable manner, and the resulting strain and ACF maps

The procedure to plot the autocorrelation maps would be:

1 - Download the displacement values per voxel from Paraview to a csv file.
2 - Use the notebook "Data_for_ACF.ipynb" to import the csv file and optionally, the strains from our workflow.
3 - Make a copy of the "data_for_ACF.txt" file to use it as a template 
4 - Run completelly the notebook "Data_for_ACF.ipynb" and the new data_for_ACF.txt file will be updated with our new data
5 - Run the second notebook called "Strain map and Autocorrelation function description.ipynb" to obtain the strain and ACF maps
