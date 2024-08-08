# Personal Finance Dashboard

Personal finance dashboard built with [Python Dash](https://dash.plotly.com/).

## Setup

Create a virtual environment with a preferred tool, e.g. [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html), [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html), [pipenv](https://pipenv.pypa.io/en/latest/#install-pipenv-today), [poetry](https://python-poetry.org/docs/#installation), etc., and install the required packages listed under the `tool.poetry.dependencies` section in the `pyproject.toml` file. 

For example, with [`poetry` & `conda`](https://python-poetry.org/docs/basic-usage/#using-your-virtual-environment), this can be done as follows:

```bash
$ yes | conda create --name personal_finance_dashboard python=3.11
$ conda activate personal_finance_dashboard
# Poetry detects and respects the activated conda environment
$ poetry install 
```

## Application 

To run the application entry point:

```bash
$ conda activate personal_finance_dashboard
$ poetry run python main.py
```
