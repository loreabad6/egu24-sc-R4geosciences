These are the materials for the [short course "Introduction to R for the Geosciences" at EGU 2024](https://meetingorganizer.copernicus.org/EGU24/session/49442).

**When and where?** Wednesday, April 17, 19:00-20:00, **Room N1**

## Abstract

R is a free, open-source programming language popularly used for data science, statistical analysis, and visualization. Spatial data analysis has been strongly supported by the R community, that provides tools for data reading, writing and downloading, and for spatial processing, visualizing and modelling. The R-Spatial package ecosystem relies on common libraries for geospatial analysis such as GDAL, GEOS, and PROJ. In this workshop, we will introduce participants to spatial data analysis in R. For this, there will be demonstrations of key R packages like {sf}, {stars}, {terra} for vector and raster data processing. We will also focus on spatial data visualization using the {tmap} package. We will focus on datasets strongly used by the Geoscience community, including satellite imagery.

## Schedule

|   **Time**  |         **Topic**         |
|:-----------:|:-------------------------:|
| 19:00-19:10 | Introduction to R-Spatial |
| 19:10-19:30 |        Vector data        |
| 19:30-19:50 |        Raster data        |
| 19:50-20:00 |            Q&A            |

## Pre-requisites

### R installation

A working installation of R (follow [CRAN recommendations](https://cran.r-project.org/) for your set-up).

### R packages

Please run those commands inside the R console:

```r
# Install the remotes package from CRAN Repo
install.packages(remotes)

# Install workshop and its dependencies
remotes::install_github("loreabad6/egu24-sc-R4geosciences")
```

You can follow along in your own R script, or [clone the repository](https://github.com/loreabad6/egu24-sc-R4geosciences) to run the Quarto documents interactively.