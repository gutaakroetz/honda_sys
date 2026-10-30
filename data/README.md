# Data

Raw data files are stored locally and are not version-controlled.

## NHTS 2022

Download from: https://nhts.ornl.gov/

Expected folder structure:

```
data/
└── NHTS/
│   └── csv/
│       ├── tripv2pub.csv
│       ├── perpub.csv
│       ├── hhpub.csv
│       ├── vehpub.csv
│       └── LDT2022pub.csv
└── tl_2024_us_state/
    ├── tl_2024_us_state.shp
    └── ... (associated shapefile components)
```

## Census TIGER State Shapefile

Download from: https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html

File used: `tl_2024_us_state.shp` — contains `DIVISION` field for Census Division assignment.
