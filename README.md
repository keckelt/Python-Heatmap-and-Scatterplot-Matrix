
# Instructions

## Development Environment
### MyBinder

Go to: https://mybinder.org/v2/gh/keckelt/Python-Scatterplot-Matrix/master
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/keckelt/Python-Scatterplot-Matrix/master)
 and open the *empty* notebook.

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

Goto http://localhost:8888/ and open the *empty* notebook.

## Tasks

1. Load the soccer.csv with [pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html)
2. Inspect the dataset, e.g. with [head()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html)
3. Select a couple of attributes (e.g., those of 2017) and create a [scatterplot matrix](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.plotting.scatter_matrix.html).
4. Make a screenshot and interpret the results
