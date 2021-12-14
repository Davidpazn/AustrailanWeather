# AustrailanWeather
Second Assignment: Computational Learning

## Data-set source:
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

### Create Conda Environment
In order to execute the jupyter notebooks, it is convenient to create a conda environment. To tackle that, a requirements.txt file has been added to the repository.
Just execute:

#### conda create --name <env_name> --file requirements.txt

If you want to have this conda environment as a jupyter kernel, just to the following:
(in terminal)
#### pip3 install ipykernel
or 
#### conda install -c anaconda ipykernel

and then,
#### python -m ipykernel install --user --name=<env_name>
