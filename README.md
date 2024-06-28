# Customer Segmentation Project

This project aims to segment customers based on their attributes using K-means clustering. The dataset used is the Mall Customers dataset, which includes information about customers' age, gender, annual income, and spending score.

## Dataset Overview

- **Dataset Source:** [Mall Customers Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Attributes:**
  - Age: Customer's age.
  - Gender: Customer's gender.
  - Annual Income (k$): Customer's annual income in thousands of dollars.
  - Spending Score (1-100): Score assigned based on customer behavior and purchasing data.

## Exploratory Data Analysis

### Data Statistics

- **Shape of Dataset:** 200 rows, 4 columns
- **Missing Values:** None
- **Duplicates:** None
- **Data Types:**
  - Age: Integer
  - Annual Income (k$): Integer
  - Spending Score (1-100): Integer

### Data Visualization

- **Distributions and Relationships:**
  - Histograms and KDE plots for age, annual income, and spending score.
  - Violin plots to show distributions by gender.
  - Count plot for gender distribution.
  - Bar plots for age group distribution, spending score range, and annual income range.

## Customer Segmentation using K-means Clustering

### Elbow Method for Optimal Cluster Selection

- Used the Elbow method to determine the optimal number of clusters for:
  - Age vs. Spending Score
  - Age vs. Annual Income
  - Spending Score vs. Annual Income

### Results

- **Cluster Visualization:**
  - Scatter plots showing clusters based on selected attributes.
  - Centroids marked for each cluster.
