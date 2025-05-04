# IS537_Final_Project
This is the repository that contains my final project for IS 537, Theory &amp; Practice of Data Cleaning, at the iSchool at UIUC. It examines the data quality and cleaning of 2 publicly available network directories provided by 2 different nonprofit organizations focused on impact driven work. Beyond being a cleaning project, it also aims to answer the question, "What gaps and trends exist in career area interest and global representation across the 2 nonprofit professional networks focused on impact-driven work, and how does data quality impact these insights?"

# Requirements
This is a Python project, using Python 3.7 and utf-8 encoding. Originally made in PyCharm 2023.2. Uses Jupyter notebooks, csv files, and html files.

Packages used Throughout Project: 
* import pandas as pd
* from scipy.stats import zscore
* from ydata_profiling import ProfileReport
  * ydata_profiling will likely need a pip install:
    !pip install ydata-profiling[notebook]
* import numpy as np
* import re
* import matplotlib.pyplot as plt
* import seaborn as sns

# How to Run The Project
## Step 1: Load the Project
Clone the repository to your local device, or to a codespace. Help with this can be found here: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository 
## Step 2: Part_1_Import_Merge_Clean.ipynb
Open the notebook titled "Part_1_Import_Merge_Clean.ipynb". Before you run the whole notebook, make sure that your importations work, especially for ydata-profiling. Data importation will pull from the 'data' subdirectory. All required importations are listed in the Requirements section above. You can run each block one-by-one, or click the run-all button on your chosen codespace, if that option is available to you. From start to finish, this notebook takes you through the data cleaning & writing the html data quality reports, and the end of the notebook is signified by writing the new cleaned, combined csv 'combined_data_cleaned.csv' to the 'data' subdirectory.
## Step 3: Part_2_Research_Question.ipynb
After you complete "Part_1_Import_Merge_Clean.ipynb", open the notebook titled "Part_2_Research_Question.ipynb". This notebook uses the cleaned dataset from Part 1, answers the research question posed, and summarizes the findings.
## Step 4: CFI & HIP Quality & Ethics.ipynb AND "Pre-Cleaning CFI Quality Report.html" + "Pre-Cleaning HIP Quality Report.html"
After both Part_1 and Part_2 notebooks are complete and you have all the context that is needed, you can open the final parts of this project. Open "CFI & HIP Quality & Ethics.ipynb". Simultaneously, on your chosen web browser, open the html files titled "Pre-Cleaning CFI Quality Report.html" and "Pre-Cleaning HIP Quality Report.html". The html files are too big to view inside a codespace, or within Github.

To open the html files in a browswer from PyCharm: 
* right click on the html file
* Click "Open In", then select "Browser", and pick your browser of choice.

This final notebook takes you through the written explanation of the Pre-Cleaning Quality reports, combined with the knowledge gained from Parts 1 & 2. It is an overall quality and ethics assessment of the datasets, and makes quality and ethics recommendations
