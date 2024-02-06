I have learned many things while working on this project, which involves analyzing YouTube comments.

First, install Python, and then install all the libraries needed for our project as mentioned below.

  --pip install pandas
  --pip install numpy etc

the import these all libraries 

notes: in jupiter notebook before install libraries use this ! symbol
filepath : path is enter as per your system

    import pandas as pd
    import numpy as np
    import seaborn as sns
    import matplotlib.pyplot as plt

A - How to read csv data or how to load data 
    remove the missing or null value 
    count the null value or missing value 
    find the missing value

B - Perform Sentiment Analysis
    !pip install textblob
    from textblob import TextBlob

C - Wordcloud Analysis of your data
    comment_negative
    comment_positive

D - How to emoji analysis
    !pip install plotly
    import emoji
    !pip install emoji==2.2.0

E - Collect Entire Data Youtube
    import os

E - How to export your data into (csv, json, db)
