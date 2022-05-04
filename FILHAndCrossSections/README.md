## Content of FILHAndCrossSections folder:

This folder contains jupyter notebooks for running the FILH (Finding Images from Linked Hydrology) tool and the NLDI xstool.


* FILH Tool.ipynb

  * This is the main file for the FILH tool. It contains all needed functions to filter hydrology data and return satellite images from USGS.
  * Three example use cases are included.

* GEE_images_for_ESOC_presentation.ipynb
  * This file generates images used for an ESOC presentation but can be used as a basic guild to Google Earth Engine (GEE).

* Get_dates_for_Stream_Flow_Discharge.ipynb
  * This notebook does the inial FILH step of getting dates to look for satellite images based on a hydrological constraint
  * This code is duplicated in FILH Tool.ipynb

* cross_section_for_USGS_gage.ipynb
  * Cross sections can be generated based on USGS gage locations from this notebook file.

* Cross_sections_for_shape_file.ipynb
  * An attempt was made at getting cross sections for arbiraty points along a river reach in this notebook.
  * The notebook is incomplete and does not work.
  * Shape files used for this can be found in the root directory.   
