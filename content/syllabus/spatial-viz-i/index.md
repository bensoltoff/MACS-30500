---
title: "Visualizing spatial data I"
date: 2022-11-07T12:25:00-05:00
publishDate: 2019-05-20T12:25:00-05:00
draft: false

aliases: ["/cm014.html", "/syllabus/geospatial-visualization/",
          "/syllabus/geospatial-visualization-raster-maps/"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_end: 2022-11-07T14:20:00-05:00
all_day: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors: []

# Abstract and optional shortened version.
abstract: ""
summary: "Identify components of geospatial visualizations, implement raster maps using ggplot2, and introduce geofaceting."

# Location of event.
location: "Kimball Hall B11"

# Is this a selected talk? (true/false)
selected: false

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: []

# Links (optional).
url_pdf: ""
url_slides: "/slides/visualize-spatial-i/"
url_video: ""
url_code: ""

# Does the content use math formatting?
math: false
---



## Overview

* Introduce the major components of a geospatial visualization
* Identify how to draw raster maps using `ggmaps` and `get_map()`
* Practice generating raster maps
* Demonstrate `geofacet` and `facet_geo()`

## Before class

* Read [Introduction to geospatial visualization](/notes/intro-geospatial-viz/)
* Read [Drawing raster maps with `ggmap`](/notes/raster-maps-with-ggmap/)

## Class materials

* [Practice drawing raster maps](/notes/raster-maps-practice/)

* [Mapping data in *The Truthful Art* by Alberto Cairo](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch10.html#ch10) - excellent chapter on designing data maps with lots of examples. Though really the entire book is useful if you do a lot of work with data visualizations of any type. **Cornell authentication required.**

## Additional resources

* [Learn Spatial Analysis](https://spatialanalysis.github.io/) - tutorials and workshops conducted by the Center for Spatial Data Science at the University of Chicago. Lots of materials developed using R.

## What you need to do after class

* [Obtain an API key](https://api.census.gov/data/key_signup.html) and [store it securely](/notes/application-program-interface/#census-data-with-tidycensus) on your computer. We will be using `tidycensus` next class, so you will save time if you set this up in advance.
