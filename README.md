# NBA Hand/Wrist Fracture Study

This repository contains publication-safe aggregate materials for the NBA hand/wrist fracture study.

## Authors

- Ryan Zeitouny — Texas A&M University †
- Rohan Phadke — Baylor College of Medicine †
- Samer Salman — Baylor College of Medicine †
- Zane Salman — The University of Texas at Austin †
- Cristin Mathew — Memorial Hermann Health System

† These authors contributed equally and share first authorship.

## Current contents

- `tables/csv/` — 19 aggregate CSV result tables approved for public distribution.
- `tables/NBA_publication_safe_tables.xlsx` — publication-safe versions of the fracture-characteristic and location-subgroup tables, including small-cell disclosure controls.

Together, these files provide 21 publication-eligible aggregate tables.

## Disclosure controls

- Rare fracture categories were combined where aggregate arithmetic was valid.
- Location-specific outcome summaries were suppressed when subgroup `n < 5`.
- Identifiable player-level workbooks and recurrence-detail data are not included.

## Excluded data

`table_recurrence_details.csv` and all source/player-level Excel and Parquet files are intentionally excluded because they contain identifiable injury histories or individual performance records.

The repository contains aggregate outputs only. Identifiable player-level data are not publicly redistributed.
