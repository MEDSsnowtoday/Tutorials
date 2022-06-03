# Tutorials for Processing, Analyzing, and Visualizing Snow Data

### Authors: Ryan Munnikhuis, Julia Parish, Marie Rivers

## Motivation

Three Python-based tutorials were created to help users through downloading, accessing, processing, and visualizing the [National Snow and Ice Data Center's (NSIDC) Snow Today](https://nsidc.org/reports/snow-today) snow cover and albedo datasets. The tutorials use 19 year's (2001-2019) worth of snow cover and albedo datasets for the California Sierra Nevada Mountain Range. 
 
These tutorials provide steps to:
- Download snow cover and albedo datasets 
- Access snow cover and albedo data and metadata
- Process and create basic visualizations of the datasets
- Convert datasets to alternative file types 
- Create an interactive map of raster layers 
- Create interactive charts of snow cover and albedo

## Installation

Required packages and python version to run tutorials:

|            |            |                |
| ---------- | -----------| ---------------|
| python 3.8 |  gdal      |  h5py          | 
| imageio    |  leafmap   |  matplotlib    |
| numpy      |  pandas    |  plotly        |
| rasterio   |  rioxarray |  wget          | 


## Usage

Python tutorials were created to increase the usability of the UCSB Earth Research Institute’s (ERI) Snow Property Inversion from Remote Sensing (SPIReS) model HDF5 files. These files contain snow cover fraction and snow albedo data. The three tutorials are intended for an audience with basic Python experience. Previous understanding of multidimensional climate data is not required. The first tutorial focuses on walking users through the steps to downloading and opening HDF5 files and exploring the metadata. The second tutorial provides instructions on calculating averages and anomalies, converting the data to GeoTIFFs with correct projection information, and visualizing the data on a map. These GeoTIFFs can be either individual files or raster stacks. The third tutorial focuses on visualizing snow statistical values on charts. While the tutorials only use historic data from 2001 to 2019, the skills gained from the tutorials can be applied to present data.

## References

Bair, E. H., Stillinger, T., & Dozier, J. (2021). Snow Property Inversion From Remote Sensing (SPIReS): A Generalized Multispectral Unmixing Approach With Examples From MODIS and Landsat 8 OLI. IEEE Transactions on Geoscience and Remote Sensing, 59(9), 7270–7284. https://doi.org/10.1109/TGRS.2020.3040328

Stillinger, T., Bair, N., Colee, M., Davis, B., Dozier, J. 2022. Remotely-sensed products. Snow research at UC Santa Barbara and The Cold Regions Research and Engineering Laboratory (CRREL) and University of California Santa Barbara (UCSB) Energy Site. Last accessed: 2022/05/22. https://snow.ucsb.edu/index.php/remotely-sensed-products/

