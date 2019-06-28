
# Instructions

## Development Environment
You can either work online, via MyBinder, or locally.

### MyBinder

Go to: https://mybinder.org/v2/gh/keckelt/Python-Scatterplot-Matrix/master
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/keckelt/Python-Scatterplot-Matrix/master)
 and open the *template* notebook.

### Local
Checkout this repo and change into the folder:
```
git clone https://github.com/keckelt/Python-Scatterplot-Matrix.git
cd Python-Scatterplot-Matrix/
```

You can reuse the conda environment from the tutorial:
```
conda activate python-tutorial
```

Then launch Jupyter :
```
jupyter notebook
```

Goto http://localhost:8888/ and open the *template* notebook.

## Tasks
1. Inspect the data and attributes, e.g., with [head()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html), and [dtypes](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes).
3. Select a couple of attributes (e.g., those of 2017) and create a [scatterplot matrix](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.plotting.scatter_matrix.html).
4. Create a color-coded scatterplot matrix using the same attributes and an additional categorical attribute, e.g. with [seaborn](https://seaborn.pydata.org/generated/seaborn.pairplot.html#seaborn.pairplot).
4. Iinterpret the results.
5. Download the notebook as HTML and submit it.
