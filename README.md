# FieldShift

Agricultural decision support built for the NASA Space Apps Challenge. FieldShift shows what satellites
observe about a field and gives farmers a place to add their own knowledge. It supports local expertise;
it does not replace it.

**Status:** prototype. Map layers use real NASA GIBS imagery. The numbers on the Field Analysis page are
illustrative sample values and are not a validated crop model.

## Features
- Satellite field map with NASA GIBS layers (vegetation, land surface temperature, rainfall)
- Draw your own field boundary and see its area
- Pin notes to the map (water, soil, pests, planting). Stored only in the browser
- "Does this match what you see?" feedback on each alert
- Export a plain-text summary to share with a local adviser

## Run it
Open `index.html` in a browser. No build step and no API keys. Internet access is needed for map tiles.

## Credits and sources
Code and data used by this project, with their licenses as published by each project (please re-check before submitting):

| What | Used for | Link |
|---|---|---|
| Leaflet (BSD-2-Clause) | Interactive maps | https://github.com/Leaflet/Leaflet |
| Leaflet.draw (MIT) | Boundary drawing tools | https://github.com/Leaflet/Leaflet.draw |
| NASA GIBS / Worldview | NDVI, land temperature, rainfall map layers | https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal/gibs-api |
| GPM IMERG | Rainfall (planned/live layer) | https://gpm.nasa.gov/data/imerg |
| SMAP | Soil moisture (planned) | https://smap.jpl.nasa.gov |
| MODIS | Temperature and vegetation | https://modis.gsfc.nasa.gov |
| VIIRS | Vegetation monitoring (planned) | https://www.earthdata.nasa.gov/data/instruments/viirs |
| Esri World Imagery | Satellite basemap (see Esri terms of use) | https://www.arcgis.com/home/item.html?id=10df2279f9684e4a9f6a7f08febac2a9 |
| OpenStreetMap Nominatim | Place search (follow usage policy) | https://nominatim.org |
| Unsplash | Home page hero photo (Unsplash License) | https://unsplash.com |
| Google Fonts: DM Sans, Manrope | Typography (OFL) | https://fonts.google.com |
| NASA Space Apps Challenge | Event and challenge | https://www.spaceappschallenge.org |

## License
MIT. See `LICENSE`.
