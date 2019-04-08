# Visualizing and Analyzing Earth Science Data Using PyViz and PyData - 30-45 min

Earth Science presents interesting issues of large, multi-dimensional datasets stored in
a variety of idiosyncratic file formats. In this talk, we'll work through some specific
workflows and explore how various tools - such as intake, dask, xarray, and datashader -
can be used to effectively analyze and visualize these data. Working from within the
notebook, we'll iteratively build a product that is interactive, scalable and
deployable.


## Case Study: Heat and Street Trees

<a href=https://mybinder.org/v2/gh/jsignell/pydata_ann_arbor_2019/master ><img src=https://mybinder.org/badge_logo.svg width=300/></a>

<img src="./assets/thresholded.png" width=50%/>  <img src="./assets/trees_and_temp.png" width=45%/>

Recreating the work in this blog post: http://urbanspatialanalysis.com/urban-heat-islands-street-trees-in-philadelphia/

## To run locally

```bash
conda env create -f environment.yaml
conda activate trees
jupyter notebook
```

<a href=https://mybinder.org/v2/gh/jsignell/pydata_ann_arbor_2019/master ><img src=https://mybinder.org/badge_logo.svg width=300/></a>

### About me
I am a software developer at Anaconda Inc. currently working on developing best
practices for Python-using earth scientists. I work on visualization tools within the
PyViz ecosystem and data ingestion and analysis tools in the broader PyData world. I
live in Philadelphia and previously did hydrology research at Princeton - studying
lightning and rain patterns, water movement through the landscape, and streamflow.
