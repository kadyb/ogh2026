# OpenGeoHub Summmer School 2026

This repository contains materials for the [OpenGeoHub Summer School 2026: "Data Science for Earth Observation"](https://opengeohub.org/2026/01/29/earth-observation-summer-school-2026/).

# Introduction

Learn how to process and analyze satellite data in R through two beginner-friendly remote sensing courses.
In the first course, you will detect floods in Sentinel-2 imagery using spectral indices (Part I) and
machine learning techniques (Part II). In the second course, you will use Landsat thermal infrared data
to investigate differences in land surface temperature across land-cover classes.

Both courses emphasize practical, hands-on learning. By the end, you will be able to work with satellite
imagery using modern tools and document your workflows in reproducible notebooks that support open and
transparent science.

# Requirements

You need to install [R](https://cloud.r-project.org/), [RStudio](https://posit.co/download/rstudio-desktop/) (preferably), and the required packages as follows:

```r
install.packages(c("terra", "rstac", "rpart", "rpart.plot"))
```

Please make sure everything is working properly before the workshop begins.

# Materials &#128681;

You can download interactive notebooks (.qmd) and static documents (.html) from this repository:

1. Flood detection using satellite data:
   - [Part 1: Introduction](https://kadyb.github.io/ogh2026/01_flood_detection_intro.html)
   - [Part 2: Machine learning](https://kadyb.github.io/ogh2026/02_flood_detection_ml.html)
2. [Analysis of land surface temperature based on thermal satellite data](https://kadyb.github.io/ogh2026/03_land_surface_temperature.html)

The dataset required for the second workshop is available in the [Zenodo repository](https://zenodo.org/records/21922843).

# Contact

If you have any questions or need help, please let me know at [Mattermost](https://mattermost.opengeohub.org/).
