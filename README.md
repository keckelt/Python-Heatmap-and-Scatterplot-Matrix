
# Instructions

## Development Environment
You can either work online, via MyBinder, or locally.

### MyBinder

Go to: https://mybinder.org/v2/gh/keckelt/Python-Heatmap-and-Scatterplot-Matrix/master?urlpath=lab
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/keckelt/Python-Heatmap-and-Scatterplot-Matrix/master?urlpath=lab)
 and open the *template* notebook.

### Local
Checkout this repo and change into the folder:
```
git clone https://github.com/keckelt/Python-Heatmap-and-Scatterplot-Matrix.git
cd Python-Heatmap-and-Scatterplot-Matrix/
```

You can reuse the conda environment from the tutorial:
```
conda activate python-tutorial
```

Then launch Jupyter :
```
jupyter lab
```

Goto http://localhost:8888/ and open the *template* notebook.

## Tasks

Perform the following tasks.
Then download the notebook as HTML and submit it.
You can use all or a subset of the data for the tasks. Additional data-wrangling may be necessary.

### Scatterplot Matrix

1. Inspect the data and attributes, e.g. with [head()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html), and [dtypes](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes).
2. Select more than two attributes attributes (e.g. those of 2017) and create a [scatterplot matrix](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.plotting.scatter_matrix.html).
3. Create a color-coded scatterplot matrix using the same attributes and an additional categorical attribute, e.g. with [altair](https://altair-viz.github.io/gallery/scatter_matrix.html).
4. Interpret the results.

### Heat map

1. Inspect the data and attributes, e.g. with [head()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html), and [dtypes](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes).
2. Select suitable attributes and visualise the data in a heatmap, e.g. with [seaborn](https://seaborn.pydata.org/generated/seaborn.heatmap.html)
3. Interpret the results.
