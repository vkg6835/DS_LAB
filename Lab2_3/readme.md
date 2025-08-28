NYC Yellow Taxi Trip Data Analysis

This project provides a descriptive analysis of a sample dataset of NYC Yellow Taxi trips. The analysis is performed using both Python (in a Jupyter Notebook) and R to demonstrate data handling, statistical analysis, and visualization in both languages.

Files Included

DS_Lab2.ipynb: A Jupyter Notebook containing the Python code for the analysis.

Lab2.R: An R script containing the R code for the analysis.

yellow_tripdata_sample.csv: A sample CSV file with 995 records of NYC Yellow Taxi trip data.

Python Analysis (DS_Lab2.ipynb)

This notebook walks through loading the data, calculating descriptive statistics, and generating various plots to visualize the data distribution and relationships between variables.

Key Analyses in Python:

Descriptive Statistics: Calculation of mean, median, mode, standard deviation, variance, skewness, and kurtosis for key numerical fields.

Visualizations:

Histograms and Frequency Polygons

Box Plots and Violin Plots

Density Plots

Hypothesis Testing:

One-sample t-test

Two-sample t-test

Chi-square test

Correlation Analysis: Pearson correlation tests and a correlation matrix heatmap.

Time Series Analysis: A plot showing the daily trip counts.

Hourly Variation: A box plot showing the distribution of fare amounts by the hour of the day.

How to Run the Python Notebook:

Prerequisites: Make sure you have Python and Jupyter Notebook installed. You will also need the following libraries:

pandas

numpy

matplotlib

seaborn

scipy

pyarrow (optional, for faster CSV reading)

Installation: You can install these libraries using pip:

pip install pandas numpy matplotlib seaborn scipy pyarrow

Execution:

Place DS_Lab2.ipynb and yellow_tripdata_sample.csv in the same directory.

Open your terminal or command prompt, navigate to that directory, and run jupyter notebook.

Open DS_Lab2.ipynb and run the cells sequentially.

R Analysis (Lab2.R)


This R script performs a similar descriptive analysis of the taxi trip data, showcasing R's capabilities for statistical analysis and plotting with ggplot2.

Key Analyses in R

Descriptive Statistics: Calculation of mean, median, mode, standard deviation, variance, skewness, and kurtosis.

Visualizations:

Histograms and Frequency Polygons

Box Plots and Violin Plots

Density Plots

Hypothesis Testing:

One-sample t-test

Two-sample t-test

Chi-square test

Correlation Analysis: Pearson correlation tests and a correlation matrix heatmap.

Time Series Analysis: A plot of daily trip counts.

Hourly Variation: A box plot of fare amounts by the hour.

How to Run the R Script:

Prerequisites: You need to have R and preferably RStudio installed. You will also need the following R packages:

dplyr

ggplot2

moments

readr

psych

reshape2

lubridate

GGally

Installation: You can install these packages from the R console:

install.packages(c("dplyr", "ggplot2", "moments", "readr", "psych", "reshape2", "lubridate", "GGally"))

Execution:

Place Lab2.R and yellow_tripdata_sample.csv in the same directory.

Set your working directory in R/RStudio to this folder.

Source the Lab2.R script to run the analysis. The plots will be displayed in the Plots pane.
