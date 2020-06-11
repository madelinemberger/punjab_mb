### Outputs

This folder contains spatial data and csvs created by the `creating_polygons` script as well as the `updating_2019_data`. The contents are as follows:

**Spatial data:**

- `test_all.shp` this poorly named file contains all of the polygons, post cleaning and removal of problem ids, and missing data. It does not include the removal of large polygons that were clearly errorrs, since that was done in Arc. That file can be found in the ArcGIS folders. 
- `all_minus_sample` is just the full data set minus the 200 randomly sampled plots for verification
- `random_sample` is the 200 plots removed for verification
- `sc_burn_index_2019` is a dataset joined with a burn index created from JUST the 2019 spotcheck data
- `updated_2019_main_burn` is a shapefile that has been joined with the burn index created in `updating_2019_data` from the spotcheck and monitoring 
- `updated_2019_mon_sc` is an old file, this data has been updated



**CSV**

- `ids` these are lists of unique_ids that idenfity polygons that have been removed 
- `removed` is a complete list of polygons that were removed

