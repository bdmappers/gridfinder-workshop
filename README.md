# gridfinder-workshop

Temporary repository for [Data Science Africa Workshop 2019](http://www.datascienceafrica.org/).

Please see full repository here: https://github.com/carderne/gridfinder

## Instructions
1. Clone/download this repo:
    ```
    git clone https://github.com/carderne/gridfinder-workshop.git
    cd gridfinder-workshop
    ```
2. Clone/download the [gridfinder](https://github.com/carderne/gridfinder) repo and ensure it is available in the Python path:
    ```
    git clone https://github.com/carderne/gridfinder.git
    export PYTHONPATH="$PWD/gridfinder"
    ```
3. Install requirements into a Python 3.6+ virtual environment:
    ```
    conda config --show channels
    conda config --append channels conda-forge 
    conda install --file conda_requirements.txt 
    ```
Or with pip: `pip install -r requirements.txt`

4. Copy provided input data files into the `data/` directory.
