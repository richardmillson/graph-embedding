# graph-embedding

Graph embedding is the construction of vector representations of graphs to perform tasks such as classification or clustering.
This repo contains experiments in constructing new graph embeddings,
including [a sparse selected motif embedding](motif-selection.ipynb).

## Installation

[`pipenv`](https://pipenv.pypa.io) can be used for dependency management.

To install the dependencies in a local virtual environment, run:
```console
python -m pip install pipenv
export PIPENV_VENV_IN_PROJECT=true
pipenv install
```

To plot graphs the `cairo` 2D graphics library is required.
It can be installed on Linux by running
```shell
sudo apt install libcairo2-dev
```
Windows installation instructions can be found [here](https://doc.courtbouillon.org/cairocffi/stable/overview.html#installing-cairo-on-windows).

To view and run the jupyter notebooks, run:
```shell
pipenv run jupyter notebook
```
