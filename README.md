# MCOE Challenge 3

## Description

This is a task in which machine failures need to be predicted using a number of features such as sensor values, clusters in which the machines operate, machines' age etc. The task of predicting the failure was done with help of XGBoost model, but also using considerable data preprocessing.

## How to run?

The challenge itself is presented in Jupyter Notebook, so the only thing needed to run the code is to configure a python virtual environment and install the required packages.

### Ubuntu

To create the python virtual environment, open your terminal and run:

```
mkdir ~/.mcoe_c_venv && cd ~/.mcoe_c_venv
python3 -m venv mcoe_challenge
```

Now clone this repository and open a terminal in it. Activate the previously created environment and install the required packages with:

```
source ~/.mcoe_c_venv/mcoe_challenge/bin/activate
pip install -r requirements.txt
```

Now run `jupyter notebook`, find `data_manipulation.ipynb` and run it.
