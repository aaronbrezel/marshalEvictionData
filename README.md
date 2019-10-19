# Eviction Map For New York City 2017

## Right to Counsel

This map was made as a companion to a late-2018 series on Right To Counsel in New York City for [TheInk](http://theink.nyc/). You can find the full package and view the visualization [here](http://wp.me/p6OMlE-QI).

Right to Counsel is a new policy initiative passed in 2017 by the New York City Council intended to garuntee low income New Yorkers with legal representation during eviction proceedings. The end goal, according to city counselors and tenant's rights activists, is to even the legal playing field between landlords and tenants and keep people in their homes. Because Right to Counsel represents a significant change to housing court, it is being rolled out in stages across the city. When our map was published, just 15 zipcodes, three in each burrough, were eligeble. Our map represents these zipcodes in red. Since then, an additional zipcode has been added to each burrough.     

Our map also allows users to review neighborhood information relevant to Right to Counsel: population, median household income and eviction orders in 2017.   

## Data Sources

- The Eviction data comes from [NYC Open Data](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4/data)
- Population data comes from the [U.S. Census Bureau](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_10_DP_DPDP1&prodType=table)
- Medium household income data comes from the [U.S. Census Bureau](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_16_5YR_S1901&prodType=table)

The map was built in [Mapbox](https://www.mapbox.com/), the data for the layers came from the following sources
- Zip Code data came from [Open Data Delaware](https://github.com/OpenDataDE/State-zip-code-GeoJSON) (and the exact [NY State data](https://github.com/OpenDataDE/State-zip-code-GeoJSON/blob/master/ny_new_york_zip_codes_geo.min.json))
- Neighborhood Tabulation Area data came from [Baruch College](http://guides.newman.baruch.cuny.edu/nyc_data/nbhoods)
-
## Built with
The data was cleaned and combined in R and JavaScript. We created the map in [Mapbox](https://api.mapbox.com/styles/v1/willemdehaes/cjnro3cjp25wm2spbjt8tabc9.html?fresh=true&title=true&access_token=pk.eyJ1Ijoid2lsbGVtZGVoYWVzIiwiYSI6ImNqbmdqZ2hnYzAzb3ozd3F0aHcxM29idTkifQ.KCJrgwzjDOeW19ps9wyW2Q#10.0/40.713492/-73.897638/0) and used JavaScript and the Mapbox API to build to popups.

## Authors
[Aaron Brezel](https://github.com/aaronbrezel) - _clean and data population data, eviction data, NYC zip code data, map layout_  <br  />
[Willem Dehaes](https://github.com/wdehaes) - _map layers, layout & overlays, neighborhood tabulation data_

Amy Singer provided editorial oversight.
