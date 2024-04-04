# Pymaceuticals Inc. Data Analysis

## Overview 

This script prefroms analysis for Pymaceuticals Inc. The analysis examines effectiveness of different drug regimens for treating tumors in mice, as well as development of those tumors in mice over time. With the help of data manipulations such as data cleaning and summary statistics, the script visualizes and explores correlations in data by providing various graphs (bar, pie, sctatter, box, and linear). 

## Observations

- After performing an analysis and graphing on the outputs there are three observations that could be made:
    
    1) Treatment Efficency: The bar graph "Mouse Timepoints Across Drug Regimens" suggests that Capomulin and Ramicane may have better efficency. This conclusion is based on the fact that mice treated with those drugs have more timeponts, or in other words may live longer.
    
    2) Weight vs. Tumor Volume Correlation: The scatter plot with correlation line "Correlation Between Mouse Weight and Average Tumor Volume" shows positive correlation between weight of the mice and the avarage tumor volume. It may suggests that the weight is contributing factor to the growth of the tumor in mice.

    3) Capomulin Treatment for Mice l509: Based on a linear graph "Capomulin Treatment of Mice l509" we can assume its effectiveness. We can observe a significant decrease in tumor volume starting after 20 days of treatment. However, it is important to note that this success may be due to genetic or other individual properties of the l509. The mouse l509 could be used for additional genetic examination to understand what factors contributed to that success.

## Data
The dataset contains two CSV files:

  - Mouse_metadata.csv with information about the mice (mouse ID, drug regimen, sex, age, and weight).

  - Study_results.csv with the results of the study ( mouse ID, timepoint, tumor volume, and metastatic sites).

## Dependancies 

  - matplotlib.pyplot
  - pandas
  - scipy.stats
  - numpy
  - linregress (from scipy.stats)*

## Usage 

Before running the script please ensure that all libraries mentioned in "Dependancies" is installed in Python. After installing all the libraries and importing linregress from spicy.stats, run the the script.

## Visualizations

The sript creates various 







    
