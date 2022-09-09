# Bokeh in Jupyter Notebooks

Welcome to [Bokeh](https://bokeh.org/) in Jupyter Notebooks!

Bokeh is a Python interactive visualization library for large datasets that
natively uses the latest web technologies. Its goal is to provide elegant,
concise construction of novel graphics in the style of Protovis/D3, while
delivering high-performance interactivity over large data to thin clients.

These Jupyter notebooks provide useful Bokeh examples and a tutorial to get
started. You can download the repository and execute `jupyter notebook` from
your terminal to try out the notebooks locally on your own machine.

Alternatively, you can immediately launch live versions of the Tutorial
notebooks in your browser on [mybinder.org](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb).

Please visit the [Bokeh web page](https://bokeh.org) for
more information and full documentation, and the [Bokeh Discourse](https://discourse.bokeh.org/)
for community discussion.

[Geeks-for-Geeks: interactive data visualization with bokeh](https://www.geeksforgeeks.org/python-bokeh-tutorial-interactive-data-visualization-with-bokeh/)

## Clone or download the repo

First get local copies of the tutorial notebooks:

```
$ git clone https://github.com/bokeh/bokeh-notebooks.git
```

Or download from: https://github.com/bokeh/bokeh-notebooks/archive/master.zip

## Install the dependencies

This tutorial has been tested on:

* bokeh 1.4.0
* pandas 0.25.2
* notebook 6.0.1
* phantomjs 2.1.1
* pillow 6.1.0
* selenium 3.8.0

```shell
pip install -upgrade bokeh pandas phantomjs pillow selenium
```

NOTE: Run this in the `tutorial` directory where `environment.yml` file is.

## Get the sample data

Bokeh has a [sample data](https://docs.bokeh.org/en/latest/docs/installation.html#sample-data) download that gives us some data to build demo visualizations. To get
it run the following command at your command line:

```bash
$ bokeh sampledata
```

or run the following from within a Python interpreter:

```python
import bokeh.sampledata
bokeh.sampledata.download()
```

### Install Datashader and Holoviews (optional)

Some optional sections require the additional packages Flask, Datashader, and Holoviews.
These  can be installed with:

```bash
$ conda install -c pyviz datashader holoviews flask
```

## Run the Jupyter notebook

From this folder run jupyter notebook, and open the *[00-Introduction_and_Setup.ipynb](00-Introduction_and_Setup.ipynb)* notebook.
