# gridfinder-workshop

Temporary repository for [Data Science Africa Workshop 2019](http://www.datascienceafrica.org/).

Please see full repository here: [gridfinder](https://github.com/carderne/gridfinder)

## Instructions
Clone/download this repo:

    git clone --recursive https://github.com/carderne/gridfinder-workshop.git
    cd gridfinder-workshop

The [gridfinder](https://github.com/carderne/gridfinder) repo should come along with it and give you the following directory structure:

    gridfinder-workshop/
    |-- data/
    |-- gridfinder/
    |-- outputs/
    |-- conda_requirements.txt
    |-- gridfinder-workshop.ipynb
    |-- README.md
    |-- requirements.txt

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

Run the Jupyter Notebook:
    
    jupyter notebook

If all goes well it should open in your browser showing the `gridfinder-workshop` directory contents. If it doesn't, you might need to copy paste the URL (something like `http://localhost:8888/?token=blabla`). Open `gridfinder-workshop.ipynb` and you're ready!
