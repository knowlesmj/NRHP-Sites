# NRHP-Sites

### Chloropleth Map

---

This is a chloroplelth map that displays the relationship between the number of National Historic Sites according to the [NRHP](https://npgallery.nps.gov/nrhp) (date accessed: 03/20/24). The number of sites was then devided for each 100,000 person in the state, and then assigned to each correlating state within a GeoJSON file that was compiled on [geojson.io](https://geojson.io/#map=2/0/20). The baselayer for the map comes from the Stadia Stamen Toner Background and was incorporated using the leaflet library. The map represents each of the fifty states within the United States of America as individual polygon features. Web map features include a title, legend, and a hover feature that displays the per capita value for each state when the mouse is detected hovering over the state polygon. The classification system is arbitrary and is merely done in a way to display data, but in the future hopefully a classification system, properly Jenks Natural Breaks sytem, can be used to depict the data in a way that better represents the statistics.
