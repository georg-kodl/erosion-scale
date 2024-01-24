# RCode & Data for the research study erosion-scale
Kodl et al. 2024 - Arctic tundra shrubification can obscure increasing levels of soil erosion in NDVI assessments of land cover derived from satellite imagery
https://doi.org/10.1016/j.rse.2023.113935

Iceland / Soil Erosion Monitoring / UAV / Landsat-Sentinel-PlanetScope / Mixed Pixel Assessment / Shannon evenness index (SHEI) / Probability density function (PDF) / Landsat NDVI timeseries

SHEI:
SHEI is an index that can be used to assess pixel mixture. A land cover map and a grid of different sizes of the same extent as the land cover map is required.
Land cover maps for the SHEI analysis used in the below study can be accessed here --> https://doi.org/10.17630/f1e25320-7c79-4876-9719-4c1131cd8ed4
A sample grid of 30 m for site Sval3 is provided. Grids for studied land cover maps can be created within R or using QGis "Create grid" function.

PDF:
RCode for plotting and calculating patch sizes as probability density function (R_calc-patch-size_plot-pdf).
CSV file is provided with calculated patch sizes (patchsize_eroshr_ice21.csv). Patch sizes can also be calculated using the Code, with available land cover maps from the study (see above)

NDVI Timeseries:
GEE code is provided for downloading NDVI data from Landsat-5/7/8, including cloud mask (L5_ndvi-timeseries_GEE, L7_ndvi-timeseries_GEE, L8_ndvi-timeseries_GEE)
RCode (R_ndvi-timerseries_filter-plot) for filtering of downloaded and cleaned NDVI values (ts_ndvi_sites.csv) is provided.
