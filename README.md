# Data Visualization with Python #

In this series, we'll be introduced to three popular Python data visualization tools:

- matplotlib
- bokeh
- holoviews

If you're just using a standard Python distribution, you will be able to follow along with the first two libraries (matplotlib and bokeh) after running the following commands (preferrably inside a virtualenv).

```
$ pip install jupyter pandas numpy matplotlib bokeh
$ jupyter notebook # <- will launch a notebook server and jupyter application
```

If you're using conda, you can create a new environment with all the dependencies installed by running the following.

```
$ conda env create -f environment.yml
$ source activate pyviz
(pyviz) $ jupyter notebook --NotebookApp.iopub_data_rate_limit=100000000
```