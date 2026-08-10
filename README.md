# Ventnor City Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Ventnor City municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01410560, Inside Thorofare at Atlantic City
- PETSS / NOAA station: 8534836
- NAVD88 thresholds: 3.21 ft minor, 4.21 ft moderate, 5.21 ft major
- MLLW thresholds: 5.6 ft minor, 6.6 ft moderate, 7.6 ft major
- MLLW = NAVD88 + 2.39 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Ventnor City boundary at 5-foot resolution.
