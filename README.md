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

If you got a `gf_env.zip` file, then copy it into the `gridfinder-workshop` folder and unzip it. Make sure that the `gf_env/` subfolder has a `python.exe` directly in it!

Then run the following:

    gf_env\Scripts\activate.bat
    conda-unpack

**Only if you didn't get the zip file** run the following:

    conda env create -f environment.yml
    conda activate gf_env

Copy provided input data files into the `data/` directory and then run the Jupyter Notebook:

    jupyter notebook

If all goes well it should open in your browser showing the `gridfinder-workshop` directory contents. If it doesn't, you might need to copy paste the URL (something like `http://localhost:8888/?token=blabla`). Open `gridfinder-workshop.ipynb` and you're ready!
