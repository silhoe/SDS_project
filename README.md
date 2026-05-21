# SDS_project
Project 3 Urban Heat in Zurich (1985-2024)

## Author
Silja Höhener 
SDS21 - Programming with Spatial Data
Spring Semester 2026
University of Zurich (UZH)

## Topic
This project investigates long-term urban heat and vegetation changes in Zurich between 1985 and 2024 using Landsat raster data. 

The analysis focuses on:
- NDVI (Normalized Difference Vegetation Index)
- Thermal signal / LST proxy (TIR1)
- Temporal trends
- Spatial change detection

The project aims to analyze how vegetation density and urban heat patterns changed over time and if the both variables spatially relate to each other.

## Environment Setup
The project was developed using a conda environment in JupyterLab.

Required Python libraries:
- rioxarray
- pandas
- matplotlib
- numpy

Example setup:

```bash
conda create -n sds210 python=3.11
conda activate sds210

pip install rioxarray pandas matplotlib numpy
```

# Setup and Execution
1. Download the Landsat raster datasets from the SDS210 course website.
2. Store all .tif files inside the data/ folder.
3. Open the project in JupyterLab
4. Run the notebook XXXXXXXXXXXXXX to reproduce the analysis and figures. 

## Data
The raster data were provided on the course website and downloaded from the following Google Drive link:
https://drive.google.com/drive/folders/1SmEzlCAJJGYY-TdB58JX6ADvVxSQrMqj

The datasets are stored in the respository data/ folder

## Repository Structure
data/          # Landsat raster datasets
notebooks/     # Jupyter notebooks
figures/       # exported figures

Main notebook: 
 - fgofjg

