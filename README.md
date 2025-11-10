# JB-internsihp-Analytics-for-Data-Products-IDEs
This repository contains my solution for task gived during my application to JB internship "Analytics for Data Products IDEs". It suggest to analyse a dataset with log information about opening and closing of a tool window.

## Repository contents

- **Toolwindow_Usage_Data.ipynb**  
  Jupyter Notebook with all the code used to load, clean and analyze the dataset.
  The notebook reads a CSV file into a pandas DataFrame and performs basic exploratory data analysis and statistical tests.

- **toolwindow_data.csv**  
  The raw dataset used in the notebook.

- **Analysis_Summary.pdf**  
  A written summary of the main steps and results of the analysis performed in the notebook.

## How to run the notebook
Ensure that the CSV file is accessible to the notebook in one of two ways:
 - keep `toolwindow_data.csv` in the **same folder** as  Jupiter Notebook script. In this case the default `file_path` variable in the notebook will work as is.
 - if you store the CSV somewhere else, update the `file_path` variable in the notebook to point to the new location.

For a overview of the results, you can read
**Analysis_Summary.pdf**.
