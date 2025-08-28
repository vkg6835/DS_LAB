Titanic Dataset Analysis
This Jupyter Notebook performs a basic statistical analysis of the Titanic dataset. It explores passenger class distribution, survival probabilities based on gender, and the correlation between age and fare.

Contents
Part I: Frequency Table

Calculates and displays the absolute, relative, and cumulative frequency of passengers in each class (First, Second, Third).

Part II: Joint, Marginal, and Conditional Probabilities

Creates a contingency table (two-way table) for passenger sex versus survival.

Computes the following probabilities:

Joint probability of being female and surviving.

Marginal probabilities of being female and of surviving.

Conditional probabilities of surviving given the passenger was female, and of being female given the passenger survived.

Part III: Correlation Analysis

Calculates the Pearson correlation coefficient between passenger age and fare.

Visualizes the correlation using a heatmap and a scatter plot.

Provides an interpretation of the correlation.

Bonus Task

Visualizes the survival rate by passenger class using a stacked bar chart.

Provides a comment on the relationship between passenger class and survival.

How to Run
To run this notebook, you will need to have Python installed along with the following libraries:

pandas

seaborn

matplotlib

You can install these libraries using pip:

pip install pandas seaborn matplotlib

Once the libraries are installed, you can open and run the q1_my.ipynb file in a Jupyter Notebook environment.

Expected Output
The notebook will print out the results of the analysis for each part and display three plots:
A heatmap showing the correlation between age and fare.
A scatter plot of age versus fare.
A stacked bar chart showing survival counts by passenger class.

A stacked bar chart showing survival counts by passenger class.
