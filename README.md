# PowerCo Customer Churn

## Does Price Sensitivity Influence PowerCo's Customer Churn?

In this machine learning project, I used a Random Forest classifier to determine which factors had the greatest impact on PowerCo's customer churn. PowerCo is a power utility company that needed to know why some of their customers were leaving them for other utility companies. I completed this project as a Forage job simulation for Boston Consulting Group. Technologies I used for this project included mainly Python data science libraries, such as Pandas, NumPy, Scikit-Learn, MatPlotLib, Seaborn, and Scipy in Jupyter Notebooks. I also used Microsoft Word and PowerPoint to complete the email and executive summary. Other skills that I practiced are listed with each task below.

## Project Tasks

This project included five main tasks.

### 1. Send an email to the associate director with a summary of my approach

I was tasked with sending an email to the associate director of the company, PowerCo, to request the data we would need for running the hypothesis testing and analysis. The final draft of the email I wrote is found in the pdf document titled, "email-associate-director.pdf". To complete this task, I completed the following:

- Gained an understanding the business problem
- Determined the client data needed for the analysis
- Described the actions I would take to complete the analysis & testing

### 2. Exploratory Data Analysis (EDA)

I The executed my EDA code using the Jupyter Notebook file "exploratory-analysis-power-co.ipynb", where I took the following steps:

- Imported the price and customer data, as well as needed libraries.
- Data Distribution: Found the data for the target variable is unbalanced.
- Data Analysis: Ran descriptive statistics and correlations of the attributes with churn, and I wrote a python function that calculates the proportion of clients for churned in each quartile of a given attribute.
- Data visualization: Defined several python functions to repeatedly create proportional bar charts for different attributes.

### 3. Feature Engineering

Feature enginering was executed in the Jupyter Notebook file titled "feature-engineering-power-co.ipynb", where I completed the following actions;

- Combined the data: I merged the data sets to enable comparing price and customer churn.
- Split the data: I split the data in to training and test data to enable us to test the accuracy of the final model.
- Created New features: I created a Python function that simultaneously creates features for the difference in price between price periods, and creates a chart to showing the results on a proportional bar chart. Other features I created calculated the difference between the maximum and minimum prices for both power and energy price attributes.
- Analyzed New Features: I used the correlations, differences and proportions to determine which attributes had more influence on churn.

### 4. Predictive Modeling

Predictive Modeling was executed in the Jupyter Notebook file titled "predictive-modeling-power-co.ipynb", where I executed the following steps:

- Explained reasons attributes were included in the final model.
- Trained a Random Forest classifier to predict customer churn
- Fine tuned the model using RandomizedSearchCV, and plotted a confusion matrix.
- Evaluated the accuracy of the predictions using accuracy, precision and recall to demonstrate how accurately the model has performed. The model predicted churn with 90 percent accuracy.
- I plotted the importance of the selected features on a horizontal bar chart, revealing the most important features.

### 5. Executive Summary

- Created a visually appealing slide with only the most important information
- Revealed the factors that influence churn the most
- Described actions that would likely decrease churn

In all, I learned a great deal and gained valuable skills.
