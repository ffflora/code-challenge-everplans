### Purpose of this Repo

This repository is for solving the code challenge from Everplans, solutions are all included in the `code_challenge.ipynb` file. 

### Environment: 

In order to run this Jupyter Notebook file, please prepare your Anaconda environment locally. (Quick Link: [Jupyter/IPython Notebook Quick Start Guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html))

### Goal

This notebook contains three parts, the first two parts are as code challenge's requested, and the last part contains simple EDA graphs.
There are three output files, all will be saved into the directory `output/`.

Instructions are as follows:

> ##### Create a dataset that has 1 record for each unique user ID, with the following dimensions and measures:
>
> - Date of activation. (user may or may not have activated).  
> - total_logins: The total number of times the user has logged in.   
> - total_vault_events: The total number of times a user has done the add_to_vault event.  
> - time_to_activate: The number of seconds it took for teh user to go from create to activate.  
>
>
> ##### Create a dataset that aggreates by month (use activation month) based on the previous dataset, which provides the following dimensions and measures:
>
> - activation_month (can be any reasonable format, string or date)
> - average_days_to_activate: Mean of time_to_activate stated in days(use of decimal places is fine)
> - average_logins: Mean of total_logins



### Skills

Exploratory Data Analysis, Data Visualization

### Requirements 

Requirement Packages are listed in the `Requirements.txt` file, run 

```
pip install -r requirements.txt
```

to install all the packages, or just run the first cell of the notebook file. 



### Possible future steps 

With the current dataset, there are more EDA and Data Viz could be done, such as

- Line chart(or stacked line chart) of Users' registration/activation/add_to_vault trends over time
- New users over time
- Total users over time
- Add_to_vault events over login events 
- ... 