# gridfinder-workshop

Temporary repository for [Data Science Africa Workshop 2019](http://www.datascienceafrica.org/).

Please see full repository here: [gridfinder](https://github.com/carderne/gridfinder)

## Instructions
Clone/download this repo:

    git clone https://github.com/carderne/gridfinder-workshop.git
    cd gridfinder-workshop

Clone/download the [gridfinder](https://github.com/carderne/gridfinder) repo:

    git clone https://github.com/carderne/gridfinder.git

The directory structure should look as follows:

    gridfinder-workshop/
    |-- data/
    |-- gridfinder/
    |-- outputs/
    |-- README.md
    |-- gridfinder-workshop.ipynb
    |-- ...

Install requirements into a Python 3.6+ Conda virtual environment:

    conda create --name gf_env
    conda activate gf_env
    conda config --show channels
    conda config --append channels conda-forge 
    conda install --file conda_requirements.txt 

Or with pip (only do this if you're *not* using Conda):

    mkdir gf_env
    python3 -m virtualenv gf_env
    source gf_env/bin/activate
    pip install -r requirements.txt

Copy provided input data files into the `data/` directory:

    cp /path/to/data/files data/
