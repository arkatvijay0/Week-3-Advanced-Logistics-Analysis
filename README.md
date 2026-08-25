# Week 3 - Advanced Data Analysis and Visualization in Logistics

## Project Overview

This project focuses on advanced data analysis and visualization of logistics shipment data using Python.

The objective is to explore logistics data, identify important patterns and relationships, analyze shipment activity, detect potential anomalies, and derive data-driven insights that can support logistics and supply-chain decision-making.

---

## Objectives

* Perform exploratory data analysis (EDA) on logistics data.
* Calculate descriptive statistics and central tendency measures.
* Analyze distributions of numerical logistics variables.
* Identify relationships between numerical variables using correlation analysis.
* Analyze shipment volume trends over time.
* Detect potential outliers in logistics data.
* Create meaningful visualizations for logistics performance analysis.
* Derive analytical insights and practical recommendations.

---

## Dataset

The project uses a cleaned logistics dataset containing:

* **32,065 records**
* **26 variables**

The dataset represents logistics and shipment-related information suitable for exploratory analysis and visualization.

### Data Preparation

The following data preparation steps were performed:

* Standardized column names.
* Converted timestamp information into datetime format.
* Checked for missing values.
* Checked for duplicate records.
* Created date information for time-based analysis.
* Preserved valid observations and did not unnecessarily remove outliers.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Exploratory Data Analysis

The following analyses were performed:

### 1. Descriptive Statistics

Calculated:

* Mean
* Median
* Standard deviation
* Minimum
* Maximum

These measures were used to understand the central tendency and variability of numerical logistics variables.

### 2. Distribution Analysis

Histograms were used to examine the distributions of numerical variables and identify:

* Data concentration
* Variability
* Skewness
* Potential unusual observations

### 3. Correlation Analysis

A correlation matrix and heatmap were created to identify relationships between numerical logistics variables.

The strongest relationships were further investigated using a scatter plot.

### 4. Shipment Trend Analysis

Daily shipment volume was analyzed to identify:

* High-volume periods
* Low-volume periods
* Shipment fluctuations
* Potential capacity-planning requirements

### 5. Outlier Analysis

Box plots were used to identify unusually high or low observations.

Outliers were not automatically removed because extreme logistics observations can represent genuine operational cases.

---

## Visualizations

The project includes the following visualizations:

### Numerical Distributions

Shows the distribution of numerical logistics variables.

### Correlation Heatmap

Shows the strength and direction of relationships between numerical variables.

### Strongest Numerical Relationship

A scatter plot showing the strongest numerical relationship identified in the dataset.

### Daily Shipment Trend

Shows changes in shipment volume over time.

### Outlier Analysis

Uses box plots to identify potential unusual observations.

---

## Key Analytical Insights

The analysis provides insights into:

* Distribution and variability of logistics measurements.
* Relationships between numerical logistics variables.
* Shipment-volume fluctuations over time.
* Potential operational exceptions.
* Variables that may require further investigation.

The strongest correlation identified during the analysis was investigated using a scatter plot to better understand the relationship between the corresponding variables.

---

## Logistics Recommendations

Based on the analysis:

1. Monitor strongly correlated logistics variables to understand important operational relationships.
2. Use shipment-volume trends for resource and capacity planning.
3. Investigate extreme observations individually before deciding whether they represent errors or genuine operational cases.
4. Use the identified relationships as a starting point for future predictive logistics analysis.
5. Periodically repeat the analysis using updated shipment data to monitor changing operational patterns.

---


## Deliverables

### Dataset

Cleaned logistics dataset used for the analysis.

### Jupyter Notebook

Contains the complete Python workflow including:

* Data loading
* Data inspection
* Data cleaning
* EDA
* Statistical analysis
* Correlation analysis
* Visualization
* Outlier analysis

### Visualizations

Five final visualizations generated using Python.

### Report

A detailed DOC report containing the methodology, analysis, visualizations, interpretations, insights, and recommendations.

---

## Conclusion

This project demonstrates the application of Python-based exploratory data analysis and visualization techniques to logistics data.

The analysis provides a structured approach for understanding shipment patterns, identifying relationships between logistics variables, detecting unusual observations, and generating insights that can support data-driven logistics and supply-chain decisions.
