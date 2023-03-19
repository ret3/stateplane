# stateplane
reference tables for United States state plane projections

This project will provide cross-reference data to connect the name and European Petroleum Survey Group (EPSG) code or US state plane projection to the county-level geographic divisions it contains. These data are best accessed using the Federal Information Processing Series (FIPS) code for the state-level and county-level divisions concatenated into a single five-character text string (e.g., 48301 for Loving County (301) in Texas (48)). 

Current and deprecated FIPS codes will be included for historical purposes.
EPSG codes correspond to projections with meters as the unit of measure.
County-level division names have been standardized to remove periods, apostrophes, and diacritical marks. Only upper case letters, lower case letters, spaces, and hyphens are inclued. Attempting joins by the name field is urgently cautioned against nonetheless.
