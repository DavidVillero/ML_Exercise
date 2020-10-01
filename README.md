[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DavidVillero/ML_Exercise.git/master)

## NOTE: If you are unable to set up the environment to run the training material, please use the Binder link above to build a stand alone container. This will allow you to go through the notebooks. However, this should not be used for active development! Also, I would recomend forking this repo if you intent to use the Binder launch link.

# Data Science Training Exercise
This repo contains a series of jupyter notebooks with documented data model example from start to end.


## Installation
Clone this repository: `git clone https://github.com/DavidVillero/ML_Exercise.git`<br />

1) In windows, I recomend to Install a console emulator: <br />
   http://cmder.net/ <br />
   download the full version. The full version will include git as well as your typical unix command tools. <br />
2) to install environment: `conda env create -f environment.yml`<br />
3) to activate enviroment: `activate rapid`<br />

## The problem at hand:
Financial institutions often like to perfrom risk analysis on outstanding loans, and they typically do so by categorizing the individuals that might default on their loans. In this exercise, we want to create a model that predicts when an institution or individual will default on their loan.


 > Folder structure options and naming conventions for software projects

### Top-level directory layout

    .
    ├── Cleaning_Data.ipynb          # notebook
    ├── LOAN_DEFAULT_MODELS.ipynb          # notebook
    ├── environment.yml             # Conda env for this training
    └── README.md
    
