---
name: Analysis of UFO Sightings
tools: [Python, Altair, vega-lite]
description: This is a homework assignment
---

# Analysis of UFO Sightings

## Time Series of UFO Sightings

### Description:
The time series plot visualizes the number of UFO sightings over the years, providing insight into the trend of sightings over time.

### Design Choices:
For this plot, I used a bar chart to represent the number of sightings for each year. The x-axis represents the years, and the y-axis represents the count of sightings. I chose a simple color scheme for the bars to maintain clarity and focus on the trend.

### Data Transformations:
In the analysis, I converted the date-time column to a datetime format and extracted the year to create a new column representing the year of each sighting.

### Interactivity:
I added interactivity to the plot by enabling users to hover over the bars to see the year and count of sightings. This interactive feature helps users easily explore the data and understand the distribution of sightings over the years.

---

## Geographic Distribution of UFO Sightings

### Description:
The geographic distribution plot visualizes the locations of UFO sightings on a map, providing insight into where sightings are concentrated geographically.

### Design Choices:
For this plot, I used a map projection with circles representing the sightings' locations. The size and color of the circles encode the count of sightings at each location, with larger and darker circles indicating a higher number of sightings. I chose a color scheme that emphasizes the intensity of sightings while maintaining readability.

### Data Transformations:
In the analysis, I used latitude and longitude coordinates to plot the sightings on the map. Additionally, I aggregated the data to calculate the count of sightings for each location.

### Interactivity:
The map is interactive, allowing users to zoom in and out and pan across different regions to explore the distribution of sightings worldwide. This interactivity enhances the user experience by enabling them to focus on specific regions of interest.

### Links:
https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv
```
```
<div class="left">
<a class="m-1 btn btn-outline-primary btn-2 " href="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv">
  The Data
</a>
</div>

<div class="right">
<a class="m-1 btn btn-outline-primary btn-2 " href="python_notebooks/analysis.md">
  The Notebook
</a>
</div>
