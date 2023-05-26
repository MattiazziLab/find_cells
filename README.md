![Zenodo DOI](https://zenodo.org/badge/doi/10.5281/zenodo.7974567.svg)
# Simple tool to find yeast cell outlines

## Installation
### Using pip
Ensure you have at least python version 3.4 or newer
```bash
virtualenv find_cells_env
source find_cells_env/bin/activate
pip install -r requirements.txt
```
### Using conda
```bash
conda env create -f environment.yml
conda activate find_cells_env
```

## Usage
Start jupyter notebook
```bash
jupyter-notebook
```
Run find_cells.ipynb

See paper by Iyer K.R. _et al._ for input example. See comments in code for parameter adjustment to optimize object detection.
