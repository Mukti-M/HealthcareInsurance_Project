## Project - Healthcare Insurance

**Healthcare Insurance Project** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

<img src="https:/workspace/HealthcareInsurance_Project/HealthInsurance.jpg" alt="Healthcare Insurance Project" width="600" height="200" style="border:5px solid;">

## Dataset Content
* Dataset Source (https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance).
This dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits), geographic factors, and their impact on medical insurance charges. It can be used to study and analyse how these features influence insurance costs and implementing various analysis tools to develop different models for estimating healthcare expenses.

## Business Requirements
* Describe your business requirements
* Descriptive Statistics which Display basic statistics such as average insurance charges by age, gender, and region.
* Correlation Analysis to  Visualise correlations between different attributes and insurance charges.
* Predictive Analysis to  Develop and visualise predictive reports for estimating insurance costs.
* Geographic Analysis to Visualise the impact of geographic regions on insurance charges.


## Hypothesis and how to validate?
* Hypothesis 1:
Statement: Smokers have higher insurance charges compared to non-smokers.
	Validation:
     Perform a statistical comparison between the average charges of smokers and non-smokers.
     Visualize the difference using boxplots or bar plots.
Hypothesis 2:
Statement: BMI significantly influences insurance charges, with higher BMI leading to higher charges.
•	Validation:
	         Use correlation analysis to measure the relationship between different attributes and insurance charges.
              Create a regression model and assess the significance of BMI and Region affects insurance charge cost.
Hypothesis 3:
•	Statement: "Insurance charges vary significantly across geographic regions."
•	Validation:
               Visualize regional variations with bar charts or boxplots.
Hypothesis 4:
•	Statement: "Age and number of children have a smaller impact on charges compared to smoking status and BMI."
•	Validation:
	           Build a decision tree or random forest model to evaluate feature importance.
	           Analyze the effect sizes of these variables in a regression model.


## Project Plan
* Ensure Dataset is properly downloded and saved properly.
* Loading the dataset using pandas and Cleaned data handling the missing values. Transformed the cleaned dataset into new dataframe.
* Updating Kanban Board to see status of project workflow.
* Adding new feature category 'bmi' as per business requirement.
* Apply different analysis method to visualise data insights for insurance cost influenced by other data attributes.
* Visualisation of data insights reports helps to make business decisions and improve efficiency.

## The rationale to map the business requirements to the Data Visualisations
colons can be used to align columns.

| Business Requirement       | Visualization Type  |  Purpose   |
| :-------------: |:-------------:| :-----:|
| Identify high-cost regions | Treemap | how regions with the highest average insurance charges. |
| Understand the impact of region     | Scatterplot,Boxplot  | Compare insurance charges for different regions. |
| Correlation analysis of factors | Heatmap   | Highlight relationships between attributes like BMI, age, and charges.|
| Analyse age-related trends in costs | Line chart or bar chart  |  Display changes in average charges across different age groups.|

## Analysis techniques used
* Descriptive Statistics gives uderstanding of basic statistics such as average insurance charges by age, gender, and region
* Correlation Analysis used to Visualise correlations between different attributes and insurance charges.
* Predictive Analysis used to  Develop and visualise predictive reports for estimating insurance costs.
* Geographic Analysis used to Visualise the impact of geographic regions on insurance charges.

## Ethical considerations
* Follow GDPR guidelines to protect dataset and maintain data integrity of person.
* Engage with healthcare professionals, insurance industry experts, and ethicists to 
  ensure the project aligns with ethical and industry standards.
* Data Transperncy
   - Clearly explain the model's purpose, limitations, and      
     decision-making process to stakeholders and users.
   - Provide interpretability for predictions, especially in cases where decisions might significantly impact people's lives.
* Avoid using predictions to unfairly increase premiums for high-risk individuals 
  without offering pathways for mitigating risks (e.g., smoking cessation programs).
* Dataset Transparency
	Acknowledge the source of the dataset and describe any modifications made.
     Disclose limitations in the data, such as missing values, potential inaccuracies, or limited representation of certain groups.
* Encourage periodic re-evaluation of the model as new data becomes available to 
  maintain accuracy and fairness.


## Development Roadmap
* Some of challenges did face while creating new feature and Visualising Treemap Reports for data insights, with the help of and what strategies were used to overcome these challenges?
* Would like to learn differnt tools for analysing the dataset to visualise more detailed reports for better undestanding for data insights which beneficial for accuracy in decision making process.

## Main Data Analysis Libraries
*import numpy as np    # importing numpy functions
*import pandas as pd   # panda functions
*import matplotlib.pyplot as plt  # importing for plotting different analysis visualisation
*import seaborn as sns            # built in libraryoffers built-in themes and colour palettes for styling matplotlib graphics to differtiate data insight for better understanding.
*sns.set_style('whitegrid')
*from sklearn.pipeline import Pipeline
*from feature_engine.encoding import OneHotEncoder
*import plotly.express as px     # importing for interacive web based plotting different analysis visualisation


## Credits 

The content has been referred by open source eg. google site. The dataset referred from kaggle open source site and study material referred by LMS and SME data coach learning sessions.

### Content 

- The Text was taken from Kaggle and written after analysing the dataset and business requiremnts for data insights to visulise reports on Insurance cost influenced by different attributes for future decision making.

### Media

- The images used for the gallery page were taken from open-source site like Google. 

## Acknowledgements (optional)
* Thank you code Institute giving this opportunity for explore dataset using different analsyis tools and visualise reports.
Thank you Vasi guided me to trubleshoot the issue. Thank you Neil for his coaching and guidance on Data analytics concepts which help to understand various tools, library to analyse dataset and Visualise user interactive reports for future decision making. Thank you all my classmates who provided support through this project.