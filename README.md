# Smart Cartography
Ideas on the principles of Smart Cartography

## Principles of Smart Cartography

### A map should serve one purpose
  - A good map should have a singular purpose or goal. For example, the primary purpose of modern, general web-map products (Google Maps, Bing Maps, Apple Maps, OSM) is to serve as the base atlas for an area, helping users find and route to specific locations. Their cartography (line colors, stroke width, label placement, etc.) is designed around this main goal. As such, they may be less well-suited to serve as the background for another data layer (bird migrations, economic development zones).

### User-centered
  - Maps are made with a purpose, with focus on the map user, the map `percipient` (Robinson). Does the map require a complex legend or interpretive preamble to be understood or can the percipient quickly assess the information they need?

### Accessibility
  - As best as possible, maps should be designed with maximum accessibility in mind. This includes: using a color palette for maximum contrast that is also aesthetically pleasing, appropriately sized labels (toponyms) based on map scale. Here the concept of `redundant cartography` can be useful to use multiple visual styles (stroke width AND color) to convey the same data.

### Sensible Projections
  - Not all maps need (or should use) the Web Mercator projection. Modern mapping libraries can support many map projections, and while Web Mercator is easy and ubiquitous, its distortion of area and shape may be impractical for some maps. For example a global choropleth map may be more effective with a Robinson projection (https://bl.ocks.org/mbostock/3710566).

### Fast
  - A map with a singular purpose that is focused on the end user should be `fast`. It should be easy to read, interpret, and take action based on the current visualization (e.g., *this* location is has more X than *that* location).

### Beautiful
  - A map designed based on Smart Cartographic principles should look good.

## Concepts
- [Figure-ground](https://en.wikipedia.org/wiki/Figure-ground_in_map_design)
- [Redundant Cartography](http://www.mdpi.com/2220-9964/7/1/8)
- [Arthur H. Robinson](https://en.wikipedia.org/wiki/Arthur_H._Robinson)

## Resources
  - [Color Brewer](http://colorbrewer2.org/)

### Inspiration
- http://www.intergeo.de/intergeo-en/press/downloads/press_releases/2017/pm_2017_04_26.php

