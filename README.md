# Azubi Project 1

## Working Setup
This replaces the setup below because geopandas is difficult to install with `pip`

- Download [anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

- We want a lean setup so use the command below to create the virtual environment named, Eg. `azubi`
  ```bash
  conda create --no-default-packages -n azubi python 
  ```
- Activate virtual enviroment.
```bash
conda activate azubi
```

## Install Project Requirements
Inside your activated environment, Install the project dependencies
```bash
pip install -r requirements.txt
```

## Launch the project notebook
```bash
jupyter notebook
```


## Setup
You can go ahead and use the virtual environment created with `virtualenv` if `anaconda` is too heavy for you.

Create an virtual environment. Click [here](https://virtualenvwrapper.readthedocs.io/en/latest/) to learn how to do that.

Activate virtual environment. Eg A virtual environment named **azubi**
```bash
workon azubi
```

## Install Project Requirements
Inside your activated environment, Install the project dependencies
```bash
pip install -r requirements.txt
```

## Launch the project notebook
```bash
jupyter notebook
```