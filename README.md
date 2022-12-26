# Welcome to leafmap

[![image](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://demo.leafmap.org)
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://gishub.org/leafmap-colab)
[![image](https://mybinder.org/badge_logo.svg)](https://gishub.org/leafmap-binder)
[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/giswqs/leafmap/blob/master/examples/notebooks/00_key_features.ipynb)
[![image](https://img.shields.io/pypi/v/leafmap.svg)](https://pypi.python.org/pypi/leafmap)
[![image](https://img.shields.io/conda/vn/conda-forge/leafmap.svg)](https://anaconda.org/conda-forge/leafmap)
[![image](https://pepy.tech/badge/leafmap)](https://pepy.tech/project/leafmap)
[![image](https://github.com/giswqs/leafmap/workflows/docs/badge.svg)](https://leafmap.org)
[![image](https://github.com/giswqs/leafmap/workflows/Linux%20build/badge.svg)](https://github.com/giswqs/leafmap/actions)
[![image](https://img.shields.io/lgtm/grade/python/g/giswqs/leafmap.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/giswqs/leafmap/context:python)
[![image](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![image](https://img.shields.io/badge/YouTube-Channel-red)](https://youtube.com/@giswqs)
[![image](https://img.shields.io/twitter/follow/giswqs?style=social)](https://twitter.com/giswqs)
[![status](https://joss.theoj.org/papers/10.21105/joss.03414/status.svg)](https://doi.org/10.21105/joss.03414)

**A Python package for geospatial analysis and interactive mapping in a Jupyter environment.**

-   GitHub repo: <https://github.com/giswqs/leafmap>
-   Documentation: <https://leafmap.org>
-   PyPI: <https://pypi.org/project/leafmap>
-   Conda-forge: <https://anaconda.org/conda-forge/leafmap>
-   Leafmap tutorials on YouTube: <https://youtube.com/@giswqs>
-   Free software: [MIT license](https://opensource.org/licenses/MIT)

## Introduction

**Leafmap** is a Python package for interactive mapping and geospatial analysis with minimal coding in a Jupyter environment. It is a spin-off project of the [geemap](https://geemap.org) Python package, which was designed specifically to work with [Google Earth Engine](https://earthengine.google.com) (GEE). However, not everyone in the geospatial community has access to the GEE cloud computing platform. Leafmap is designed to fill this gap for non-GEE users. It is a free and open-source Python package that enables users to analyze and visualize geospatial data with minimal coding in a Jupyter environment, such as Google Colab, Jupyter Notebook, and JupyterLab. Leafmap is built upon several open-source packages, such as [folium](https://github.com/python-visualization/folium) and [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) (for creating interactive maps), [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) and [whiteboxgui](https://github.com/giswqs/whiteboxgui) (for analyzing geospatial data), and [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) (for designing interactive graphical user interface [GUI]). Leafmap has a toolset with various interactive tools that allow users to load vector and raster data onto the map without coding. In addition, users can use the powerful analytical backend (i.e., WhiteboxTools) to perform geospatial analysis directly within the leafmap user interface without writing a single line of code. The WhiteboxTools library currently contains **500+** tools for advanced geospatial analysis, such as [GIS Analysis](https://jblindsay.github.io/wbt_book/available_tools/gis_analysis.html), [Geomorphometric Analysis](https://jblindsay.github.io/wbt_book/available_tools/geomorphometric_analysis.html), [Hydrological Analysis](https://jblindsay.github.io/wbt_book/available_tools/hydrological_analysis.html), [LiDAR Data Analysis](https://jblindsay.github.io/wbt_book/available_tools/lidar_tools.html), [Mathematical and Statistical Analysis](https://jblindsay.github.io/wbt_book/available_tools/mathand_stats_tools.html), and [Stream Network Analysis](https://jblindsay.github.io/wbt_book/available_tools/stream_network_analysis.html).

## Statement of Need

There are a plethora of Python packages for geospatial analysis, such as [geopandas](https://github.com/geopandas/geopandas) for vector data analysis and [xarray](https://github.com/pydata/xarray) for raster data analysis. However, few Python packages provide interactive GUIs for loading geospatial data in a Jupyter environment. It might take many lines to code to load and display geospatial data with various file formats on an interactive map, which can be a challenging task for novice users with limited coding skills. There are also some notable Python packages for visualizing geospatial data in a Jupyter environment, such as [plotly](https://github.com/plotly/plotly.py) and [kepler.gl](https://docs.kepler.gl/docs/keplergl-jupyter). However, plotly is designed for displaying static data, which lacks bidirectional communication between the front-end and the backend. Kepler.gl provides unique 3D functionality for visualizing large-scale geospatial datasets, but it lacks tools for performing geospatial analysis, such as hydrological analysis and LiDAR data analysis. In contrast, leafmap provides many convenient functions for loading and visualizing geospatial datasets with only one line of code. Users can also use the interactive GUI to load geospatial datasets without coding. Leafmap is intended for anyone who would like to analyze and visualize geospatial data interactively in a Jupyter environment. It is particularly suited for novice users with limited programming skills. Advanced programmers can also find leafmap a useful tool for analyzing geospatial data and building interactive web apps.

