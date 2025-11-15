# Data cleaning Master

![Dashboard Preview](https://github.com/dhrubad304-eng/python-data-cleaner/blob/ea866c2d1ce4e5158c69aedb317076d233885985/python.img.jpeg)

### **Blinkit Analysis Projec**
A simple Python script that automatically cleans CSV and Excel datasets.
It checks file paths, removes duplicates, handles missing values, and saves a cleaned version of the dataset.

#### **Libraries Used**
- import pandas as pd
- import numpy as np
- import time
- import openpyxl
- import os
- import random
- import xlrd

#### **Why these libraries?**
- pandas : reading, cleaning, and processing data
- numpy : numeric operations
- time : adding wait delays
- openpyxl : reading Excel (.xlsx) files
- os : checking file paths
- random : generating random wait times
- xlrd : support for older Excel formats

#### *Features:*
- Supports CSV and Excel (.xlsx) files
- Detects and exports duplicate rows
- Removes all duplicate entries
- Fills missing numeric values with column mean
- Drops missing values for non-numeric columns
- Saves cleaned dataset as:
  <data_name>_clean_data.csv

### **Author & Contact**
- Dhruba Debnath
- EX - BDA-(DATA) at Urban Company | MBA in Marketing 
- Email: dhrubad304@gmail.com
- LinkedIn: https://www.linkedin.com/in/dhruba-debnath/?skipRedirect=true
