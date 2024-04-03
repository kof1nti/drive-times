# drive-time
A portfolio on Creating a driving strategy based on properly zoned areas.

Steps in creating a drive strategy in QGIS portfolio


[drive-time portfolio](https://kof1nti.github.io/drive-times/)

![](https://github.com/kof1nti/drive-times/blob/main/mapped%20sites.gif)

![](https://github.com/kof1nti/drive-times/blob/main/dvpath.gif)

# Highlights 
- Geocoding a list of the properties using webservice  geocode from MMQGIS plugin in QGIS
- Manually searching for the remaining adresses on google maps to get their coordinates for mapping as these addresses were confusing 
- Populating these locations on a google map and creating a webmap using qgis2web plugin
- A distance matrix for the origin to the destinations.Destinations which are in proximity will fall within a cluster for convenience during visits.
- Splitting distance matrix into groups as they were the maximum destinations which could be visited per drive.(in R studio)
- Making a drive path from an origin in Doylestown PA 
- Breaking drive times by locations into a reasonable path to ultimately get sites visited over the course of an n day period.

 


### Takeaway
- Consideration 

A direction of travel can be applied to half the total number of sites. eg Northwise and Southwise, Eastwise and Westwise.
After which the cluster is done to avoid having a site within a cluster being far from others.
