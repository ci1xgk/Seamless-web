#### Start file – water depth or elevation (`.start`)

This file is used to set the initial conditions of the model either as water depth or water elevation. It must be an [Esri ASCII raster file](https://desktop.arcgis.com/en/arcmap/10.3/manage-data/raster-and-images/esri-ascii-raster-format.htm) with the same dimension and resolution (i.e. `ncols`, `nrows`, `xllcorner`, `yllcorner`, `cellsize`) of the DEM file, followed by space delimited 2D array of water depth or water elevation values.

To use the initial condition as water depth or water elevation, the keywords `startfile` or `startelev` must be included in `.par` file, respectively, followed by the name of the `.start` file to be read. An example of how to prepare `.start` file using QGIS is demonstrated for the Merewether case study in [_"Preparing the input data"_](/Merewether1-2.md). 


[back](/Merewether1.md)