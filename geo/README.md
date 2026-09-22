# Bundled geographic data

Data files shipped inside Flight Planning, published here so the
time-zone data derived from OpenStreetMap is available under its own
licence.

## Time-zone data — ODbL

`us_tz_shapes.bin` and the TZ column of `us_counties.txt` are derived
from OpenStreetMap data via timezone-boundary-builder release 2025d.
© OpenStreetMap contributors, available under the Open Database
License (ODbL) 1.0 — see LICENSE-ODbL.txt.

`build_geo.py` reproduces them from that release plus the county
outlines. `build_report.txt` records the exact inputs, their SHA-256
hashes, and the build settings.

## Everything else — public domain

The county outlines, GEOIDs, county names and the town list come from
the U.S. Census Bureau (cartographic boundary files and the Gazetteer)
and are in the public domain. They are not covered by the ODbL.

## Script licence

`build_geo.py` is MIT licensed.
