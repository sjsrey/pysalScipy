# Geographic Data Science with PySAL and the pydata stack

## Bio

[Sergio Rey][http://sergerey.org/] is professor of geographical sciences and core faculty member of the GeoDa Center for Geospatial Analysis and Computation at the Arizona State University. His research interests include open science, spatial and spatio-temporal data analysis, spatial econometrics, visualization, high performance geocomputation, spatial inequality dynamics, integrated multiregional modeling, and regional science. He co-founded the Python Spatial Analysis Library (PySAL) in 2007 and continues to direct the PySAL project.  Rey is a fellow of the spatial econometrics association and editor of the journal Geographical Analysis.

[Dani Arribas-Bel](http://darribas.org) is Lecturer in Geographic Data Science and member of
the Geographic Data Science Lab at the University of Liverpool (UK). Dani is interested in 
undestanding cities as well as in the quantitative and computational methods required 
to leverage the power of the 
large amount of urban data increasingly becoming available. He is also part of the team
of core developers of PySAL, the open-source library written in Python for spatial
analysis. Dani regularly teaches Geographic Data Science and Python courses at the 
University of Liverpool and has designed and developed several workshops at different
levels on spatial analysis and econometrics, Python and open source scientific
computing.

## Prerequisite skills

The workshop is based on a course taught to Geography undergraduates with no
previous programming experience, but compressed into the appropriate length. Some statistical
background and familiarity with Python are recommended to follow along comfortably, but
there is no requirement to be knowledgeable in the Python geospatial stack.

## Description of the tutorial

This two-part tutorial will first provide participants with a gentle
introduction to Python for geospatial analysis, and an introduction to version
PySAL 1.11 and the related eco-system of libraries to facilitate common tasks
for Geographic Data Scientists. 
The
first part will cover munging geo-data and exploring relations over space.
This includes
importing data in different formats (e.g. shapefile, GeoJSON), visualizing,
combining and tidying them up for analysis, and will use libraries such as `pandas`,
`geopandas`, `PySAL`, or `rasterio`. The second part will provide a gentle
overview to demonstrate several techniques that allow to extract geospatial
insight from the data. This includes spatial clustering and regression and point 
pattern analysis, and will use libraries such as `PySAL`, `scikit-learn`,
or `clusterpy`. A particular emphasis will be set on presenting concepts
through visualization, for which libraries such as `matplotlib`, `seaborn`,
and `folium` will be used.

## Detailed outline

### Part I

1. Software and Tools Installation (10 min)

2. Spatial data processing with PySAL (45 min)

   a. Input-output

   b. Visualization and Mapping

   c. Spatial weights

3. Exercise (10 min.)

4. ESDA with PySAL (45 min)

   a. Global Autocorrelation

   b. Local Autocorrelation

   c. Space-Time exploratory analysis

5. Exercise (10 min)

### Part II

1. Spatial clustering a (30 min)

    a. Geodemographic analysis

    b. Regionalization

2. Exercise (10 min)

3.  Spatial Regression (30 min)

    a.  Overview

    c.  Basic spatial regression: spatial lag and error model

4. Exercise (30 min)

5. Point Patterns (30 min)

   a. Kernel Density Estimation visualization
 
   b. Centrography and distance based statistics

6. Exercise (10 min)

## Installation materials

Participants should have installed the following dependencies:

* [Anaconda](https://www.continuum.io/downloads) or
  [MiniConda](http://conda.pydata.org/miniconda.html) Python distributions for
  Python 2.7. See installation instructions on the links.
* `git`
* A `conda` environment loaded with all the dependencies can be installed by
  running the `pydata.sh` script available as part of the `envs` repository
  ([Girhub link](https://github.com/darribas/envs)). To install it, follow
  these instructions:
    
    - Clone the repository on your machine: 
    
    `> git clone https://github.com/darribas/envs.git`

    - Navigate into the folder:

    `> cd envs`

    - Run the script:

    `> bash pydata.sh`

## Background materials

An extensive collection of noteboks and slides related to this tutorial may be
found in the following two url's:

* [PySAL notebooks](https://github.com/pysal/notebooks)
* [Geographic Data Science course](http://darribas.org/gds15/) at the
  University of Liverpool.

