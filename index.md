## US Highway Map 
### Interactive Folium map to see US highways and their traffic.

The green lines are select US highways and the red dots are select sensor stations that calculate traffic volume data.

This map is created using publicly available data from the [US census website](https://www2.census.gov/geo/tiger/TIGER2021/PRIMARYROADS/) and the [US Traffic Volume data](https://www.fhwa.dot.gov/policyinformation/tables/tmasdata/) to create an interactive map to show select US highways and their computed daily traffic volumes.

The code using geopandas and pandas to work on GIS data and then aggregates & manipulates traffic volume data across multiple traffic stations.

After that Folium is used to create an interactive map

<iframe src="map.html" height="500" width="500"></iframe>

See the full code [here](https://github.com/sshourie/Folium_map/blob/main/Map.ipynb). 

You can explore this map [as its own web page here](map.html).