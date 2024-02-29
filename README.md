
# Analysis Of Record for Calibration (AORC) version 1.1 Jupyter Notebook

<img src="https://github.com/NOAA-OWP/AORC/blob/master/docs/AORC_SS.jpg" alt="AORC ERDDAP">

**Description**:  
The Analysis Of Record for Calibration (AORC) is a gridded record of near-surface  weather conditions covering the continental United States and Alaska and their  hydrologically contributing areas. It is defined on a latitude/longitude spatial grid with a mesh length of 30 arc seconds (~800 m), and a temporal resolution of one hour.  Elements include hourly total precipitation, temperature, specific humidity, terrain-level  pressure, downward longwave and shortwave radiation, and west-east and south-north wind components. It spans the period from 1979 across the Continental U.S. (CONUS) and from 1981 across Alaska, to the near-present (at all locations). This suite of eight variables is sufficient to drive most land-surface and hydrologic models and is used as input to the National Water Model (NWM) retrospective simulation. While the native AORC process generates netCDF output, the data is post-processed to create a cloud optimized Zarr formatted equivalent for dissemination using cloud technology and infrastructure.  The data is currently hosted on NOAA Open Data Dissemination (NODD).

The Jupyter Notebook provides examples on how to access the AORC Zarr data.  A link to [NBViewer](https://nbviewer.org/github/NOAA-OWP/AORC/blob/master/ExploreZarr.ipynb) is included with the AORC NODD landing page.  

## Dependencies

Access to the AORC v1.1 NODD S3 bucket

## Installation

No installation needed.  Any Jupyter Notebook viewer can use the AORC notebook.

## Usage

The examples included in the notebook demonstrate how to access 1 year of data and multiple years of data

----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)

----