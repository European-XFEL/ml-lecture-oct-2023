# ML tutorial for the HELIOS retreat of October 2023

Each Jupyter notebook contains a problem to be solved with ML. The data is described and can be obtained in each
notebook. Some of it is downloaded from somewhere, while others are simply randomly generated on-the-fly.

The following instructions show how to setup your environment, so that you can easily play with the data.

All the data used in the examples are produced on-the-fly for demonstration purposes, or are taken from public and open resources.

## Virtualenv setup

Using a virtual environment,
the setup would be the following (for an environment called `env`, but use the name
you prefer):

```
# create the environment env
python -m venv env

# load it
source env/bin/activate

# install some packages to get started
pip install numpy scipy pandas matplotlib jupyterlab scikit-learn torch gpytorch botorch

# play with the notebooks ...
jupyter lab

# when you are done:
deactivate
```

