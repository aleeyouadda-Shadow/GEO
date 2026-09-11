# Data-notes

## GRID3_NGA_operational_wards_v3
-Source: https://data.grid3.org
-  Downloaded: 08/09/2026
- 8,809 features, polygons
- Columns: ward_name (text), lga name (text). state (text)
- No nulls in ward_name
- Covers my LGA fully
## OSM roads, extracted via QuickOSM
- Query: highway=* within Ibadan North extent
- Extracted: 11/09/2026
- 88,507 features, lines
- Many have no surface tag, so paved and unpaved cannot be separated everywhere
- Coverage looks good in the built-up area, sparse at the edges