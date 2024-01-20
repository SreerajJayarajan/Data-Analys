# IDS2018 Network Intrusion Detection System Dataset Analysis

## Overview

This GitHub repository contains a Jupyter Notebook (`.ipynb` file) that performs an analysis of the IDS2018 Network Intrusion Detection System dataset using PySpark. The dataset includes network traffic data with various features, and the analysis covers Spark SQL queries, PySpark functions, and analytical methods.

## Contents

1. **Introduction to PySpark**
    - Installation and configuration of PySpark in Colab
    - Loading the IDS2018 dataset into a Spark DataFrame

2. **Exploratory Data Analysis (EDA)**
    - Displaying the structure and top records of the dataset
    - Counting the total number of attacks per label
    - Utilizing Spark SQL to group and count attacks

3. **Spark SQL Queries**
    - Displaying the sum of minimum, maximum, and average length of flows for each attack category
    - Calculating the average packet length difference for each attack category
    - Analyzing the highest number of request counts for different protocols

4. **Data Visualization**
    - Visualizing the results of Spark SQL queries using bar plots

5. **Hypothesis Testing and Analytical Methods**
    - Performing hypothesis testing on mean flow duration between benign requests and other DDOS attacks
    - Descriptive statistics, correlation analysis, and various hypothesis testing scenarios

6. **Contributors**
    - Displaying the names and student IDs of the contributors

## Usage

To run the notebook, you can use Google Colab or any Jupyter Notebook environment that supports PySpark. Make sure to follow the instructions in the notebook for configuring and initiating PySpark.

## Dependencies

The notebook requires PySpark, Matplotlib, Seaborn, and other standard Python libraries. If using Colab, the necessary dependencies are installed within the notebook.

## Contributors

- Sreeraj Jayarajan
- Arya Murali
  
Feel free to explore and enhance the analysis in this notebook. Your contributions are welcome!
