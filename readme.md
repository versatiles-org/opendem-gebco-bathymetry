# Bathymetry

Convert [Bathymetry Shapefiles from OpenDEM](https://www.opendem.info/download_bathymetry.html) to Vectortiles in a [Versatiles Container](https://versatiles.org/).

## Depths

| Zoom | Depths |
| ---- | ------ |
| 0-5  | 100,500,2000,6000,8000
| 6-9  | 50,100,200,500,1000,1500,2000,3000,4000,5000,6000,7000,8000,9000
| 10   | 25,50,100,200,250,500,750,1000,1250,1500,1750,2000,2500,3000,3500,4000,4500,5000,5500,6000,6500,7000,7500,8000,8500,9000,9500

## Run

`sh run.sh`

## Requirementrs

* `curl`
* `gdal`
* `node` or `bun`
* `tippecanoe`
* `mapshaper`
* `sqlite3`
* `jq`
* `versatiles`
