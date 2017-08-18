# Local Authority District to HMCTS Regions Lookup

The main 

This repo contains a lookup table that contains the corredpondence between local authorities to HMCTS regions.  

This lookup table is particularly useful for geospacial analysis, such as aggregating statistics at the level of HMCTS regions, or identifying the HMCTS region that geographic units such as courts fall within.

To assist with geospatial analysis, this repository contains [code](https://github.com/moj-analytical-services/lookup_hmcts_regions/blob/master/How%20to%20produce%20shapefiles%20and%20geojson%20from%20the%20lookup.ipynb) that can be used to convert the lookup into common geospatial formats: PostGIS tables, shapefiles, geojson and topojson.

## How to use

You can view the file [here](https://github.com/moj-analytical-services/lookup_hmcts_regions/blob/master/lad_hmcts_region_lookup.csv), and download the file [here](https://raw.githubusercontent.com/moj-analytical-services/lookup_hmcts_regions/master/lad_hmcts_region_lookup.csv).

You can load it into R with the following command:
```
read.csv("https://raw.githubusercontent.com/moj-analytical-services/lookup_hmcts_regions/master/lad_hmcts_region_lookup.csv", stringsAsFactors = FALSE)
```

You can load into Python with the following commands

```
import pandas as pd 
pd.read_csv(https://raw.githubusercontent.com/moj-analytical-services/lookup_hmcts_regions/master/lad_hmcts_region_lookup.csv")
```

## Maintainer

The DaSH team maintains this repository.  See the [commit history](https://github.com/moj-analytical-services/lookup_hmcts_regions/commits/master) to identify the current maintainer.

## Latest updates

Please refer to the most recent [pull requests](https://github.com/moj-analytical-services/lookup_hmcts_regions/pulls?utf8=%E2%9C%93&q=) to see the latest changes to the lookup, and why the changes were made.
