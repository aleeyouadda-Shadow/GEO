# Project Brief

## The question
Which ward in in Abuja metropolis in FCT Abuja has the least road network?
## Data I need

-The Data I need
-Data	Source
-Nigeria Ward Level Data: https: GRID3_NGA_operational_wards_v3.0 (July 2026)127mb //data.grid3.org/datasets/GRID3::grid3-nga-operational--wards-v3-0/about
Downloaded: 11/09/2026
8,809 features, polygons
-NGA LGA Data: NGA_LGA_Boundaries_2 (December 2020) 6.62mb https://data.grid3.org/datasets/GRID3::grid3-nga-operational-lga-boundaries/about
Downloaded: 11/09/2026
774 features, polygons
-NGA State Boundary Data: NGA_State_Boundaries_V2 (April 2024)645kb  https://data.grid3.org/datasets/GRID3::grid3-nga-operational-state-boundaries-/about
Downloaded: 11/09/2026
37 features, polygons
Columns: ward_name (text), lga name (text). state (text)
No nulls in ward_name
Covers my LGA fully
## OSM roads, extracted via QuickOSM
- Query: highway=* within Abuja extent
- Extracted: 11/09/2026
- 88,507 features, lines
- Many have no surface tag, so paved and unpaved cannot be separated everywhere
- Coverage looks good in the built-up area, sparse at the edges