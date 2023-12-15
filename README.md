# NDVI Assessment Around Santa Clara River
_Calculating NDVI using Landsat remote sensing data around the Santa Clara River area_

## Background
This analysis utilizes satellite data to calculate the normalized difference vegetation index (NDVI) for various plant communities. Looking at NDVI over time can uncover some of the phenological cycles, but more importantly, long-term trends that might be caused by climate change. The area of interest for this study is the Santa Clara River, which has ecological zones such as riparian forests, grasslands, and chaparral shrublands. 

## Repository Structure
```bash
├── data
│   ├── landsat_20180612.tif #landsat rasters, date in YYYYMMDD format at end of each filename
│   ├── Redlines #water channels within Ventura County
│   │   └── Redlines.shp
│   └── study_sites.shp #plant community study sites along river
├── docs #final analysis qmd, figures, and appearance 
│   ├── river-ndvi_files
│   │   ├── figure-html #maps and plots 
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── river-ndvi.html
│   └── river-ndvi.qmd
├── README.md
└── santa-clara-river-ndvi.Rproj
```

## Data & References
California Open Data Portal (2016), CA Geographic Boundaries [Data file] Available from: <https://data.ca.gov/dataset/ca-geographic-boundaries>. Access date: December 13, 2023.

NASA Landsat Science, Data Access [Data file] Available from <https://landsat.gsfc.nasa.gov/data/data-access/>. Access date: December 15, 2023.

"Santa Clara River." The Nature Conservancy, <www.nature.org/en-us/get-involved/how-to-help/places-we-protect/the-nature-conservancy-in-california-santa-clara-river-california-con/#:~:text=The%20Santa%20Clara%20River%20is%20a%20vital%20source%20of%20drinking,bustling%20Los%20Angeles%2DVentura%20region>. Accessed 15 Dec. 2023.

Ventura County Watershed Protection District (2023), Redlines [Data file] Available from: <https://ventura-county-watershed-protection-district-gis-data-vcwpd.hub.arcgis.com/search>. Access date: December 15, 2023.
