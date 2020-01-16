# gridfinder-workshop
Repository for Facebook/World Bank session at [Data Science Africa Workshop 2019](http://www.datascienceafrica.org/).

The workshop content is in `gridfinder-workshop.ipynb`.

This workshop is based on [gridfinder](https://github.com/carderne/gridfinder), an algorthim for predicting the location of medium-voltage grid lines, based on work by Facebook Data for Good, the World Bank Group, and others.

## Installation
Clone/download this repo:

    git clone --recursive https://github.com/carderne/gridfinder-workshop.git
    cd gridfinder-workshop

Then run the following (unless you're on a Linux/macOS machine and prefer to use pip):

    conda env create -f environment.yml
    conda activate gf_env

Copy provided input data files into the `data/` directory and then run the Jupyter Notebook:

    jupyter notebook

If all goes well it should open in your browser showing the `gridfinder-workshop` directory contents. If it doesn't, you might need to copy paste the URL (something like `http://localhost:8888/?token=blabla`). Open `gridfinder-workshop.ipynb` and you're ready!
