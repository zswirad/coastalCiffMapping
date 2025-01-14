# CliffDelineaTool: calibration and validation datasets
There are four calibration (AOIs #1-4) and four validation (AOIs #5-8) datasets. Each folder contains a DEM (<b>aoiX_dem.tif</b>), a polyline shapefile with cross-shore transects at 5 m intervals (<b>aoiX_transects.shp</b>), point shapefile with points spaced at 1 m intervals along the transects with the information on transect ID, elevation (m NAVD88) and distance from transect seaward end (m) (<b>aoiX_points.shp</b>), the <em>CliffDelineaTool</em> input document (<b>aoiX_points.txt</b>) that is the Attribute Table of the point shapefile, and point shapefiles representing true and modelled positions of the cliff base and top (<b>aoiX_base_true.shp, aoiX_top_true.shp, aoiX_base_modelled.shp, aoiX_top_modelled.shp</b>).
</br></br>
To generate the same outputs as those in <b>aoiX_base_modelled.shp, aoiX_top_modelled.shp</b> run <em>CliffDelineaTool</em> with the following settings:</br></br>
c1 = 1; c2 = 2; c3 = 4; c4 = 3; c5 = 0; c6 = 0</br></br>
AOI #1: MaxBaseElev = 5, NVert = 20, BaseSea = 12, BaseLand = 34, TopSea = 39, TopLand = 14, PropConvex = 0.5, SmoothWindow = 8</br></br>
AOI #2: MaxBaseElev = 9, NVert = 20, BaseSea = 13, BaseLand = 4, TopSea = 32, TopLand = 8, PropConvex = 0.4, SmoothWindow = 4</br></br>
AOI #3: MaxBaseElev = 5, NVert = 30, BaseSea = 9, BaseLand = 6, TopSea = 18, TopLand = 10, PropConvex = 0.1, SmoothWindow = 13</br></br>
AOI #4: MaxBaseElev = 5, NVert = 30, BaseSea = 15, BaseLand = 29, TopSea = 14, TopLand = 19, PropConvex = 0.6, SmoothWindow = 14</br></br>
AOI #5: MaxBaseElev = 5, NVert = 20, BaseSea = 20, BaseLand = 30, TopSea = 30, TopLand = 10, PropConvex = 0.2, SmoothWindow = 10</br></br>
AOI #6: MaxBaseElev = 5, NVert = 20, BaseSea = 20, BaseLand = 20, TopSea = 25, TopLand = 25, PropConvex = 0.8, SmoothWindow = 5</br></br>
AOI #7: MaxBaseElev = 7, NVert = 20, BaseSea = 20, BaseLand = 30, TopSea = 30, TopLand = 20, PropConvex = 0.5, SmoothWindow = 5</br></br>
AOI #8: MaxBaseElev = 5, NVert = 20, BaseSea = 15, BaseLand = 20, TopSea = 40, TopLand = 35, PropConvex = 0.5, SmoothWindow = 25

