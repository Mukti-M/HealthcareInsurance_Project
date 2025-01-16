## Project - Healthcare Insurance

**Healthcare Insurance Project** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation predicting insurance costs to provide actionable insights for stakeholders, such as insurance providers, policymakers, and healthcare institutions.This project leverages data analytics,feature engine, and visualization techniques to uncover patterns and relationships between various factors affecting insurance charges.The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

<img src="https:/workspace/HealthcareInsurance_Project/HealthInsurance.jpg" alt="Healthcare Insurance Project" width="600" height="250" style="border:5px solid;">

## Dataset Content
* Dataset Source (https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance).
This dataset contains information on the relationship between personal attributes (age, gender, BMI,smoking habits), geographic factors, and their impact on medical insurance charges. It can be used to study and analyse how these features influence insurance costs and implementing various analysis tools to develop different models for estimating healthcare expenses.

## Business Requirements
* Describe your business requirements
* Descriptive Statistics which Display basic statistics such as average insurance charges by age, gender, and region.
* Correlation Analysis to  Visualise correlations between different attributes and insurance charges.
* Predictive Analysis to  Develop and visualise predictive reports for estimating insurance costs.
* Geographic Analysis to Visualise the impact of geographic regions on insurance charges.


## Hypothesis and how to validate?
* Hypothesis 1:
 Statement- Estimating Average insurance charges by age, gender.
	Validation-
     Perform a Basic statistical comparison between the average charges influenced by age and gender.
     Visualize the difference using boxplots or bar plots.
* Hypothesis 2:
 Statement- BMI significantly influences insurance charges, with higher BMI leading to higher charges.
    Validation-
	         Use correlation analysis to measure the relationship between different attributes and insurance charges.
           Create a regression model and assess the significance of BMI and Region affects insurance charge cost.
* Hypothesis 3-
	Statement- Insurance charges vary significantly across geographic regions.
   Validation:
           Visualize regional variations with bar charts or boxplots.
* Hypothesis 4-
	Statement -  Predictive reports for estimating insurance costs impacted by different attributes 
  	Validation- 
	          Build a TreeMap, Area Plot and Box plot to evaluate predicative insurance charges influenced by region.
	          


## Project Plan
* Project scope - The Healthcare Insurance Project aims to analyse insurance cost drivers, predict charges, and provide actionable insights through advanced analytics and machine learning models. The project targets insurance providers, healthcare institutions, and policymakers to improve decision-making and optimize strategies.
* Objectives -
Data Exploration and Insights- Identify key attributes influencing healthcare insurance costs.
Predictive Analytics- Develop models to estimate insurance charges based on customer profiles.
Visualisation- Create user-friendly visualizations to present findings effectively.
Ethical Compliance- Ensure data privacy, fairness, and unbiased analysis.
* Deliverables -
Data Cleaning and Preprocessing- Handle missing, duplicates, and inconsistent data.
Encode categorical variables and normalize numerical features.
Exploratory Data Analysis (EDA)- Descriptive statistics, correlation analysis, and key trends.
Visualisations for regional insights.
Predictive Analysis Models- Develop and visualise reports for cost prediction (e.g., Treemap).
Interactive Dashboards- Visualisation of insurance cost drivers and predictions.
Region-wise analysis, analysis of Personal attributes affecting insurance cost like age,sex,bmi.
Final Report- Comprehensive documentation of methodology, results, and recommendations.



## The rationale to map the business requirements to the Data Visualisations

| Business Requirement       | Visualization Type  |  Purpose   |
| :-------------: |:-------------:| :-----:|
| Identify high-cost regions | Treemap | how regions with the highest average insurance charges. |
| Understand the impact of region     | Scatterplot, Boxplot, Barplot | Compare insurance charges for different regions. |
| Correlation analysis of factors | Heatmap, Scatterplot  | Highlight relationships between attributes like BMI, age, and charges.|
| Analyse age-related trends in costs | Area Plot, Bar chart  |  Display changes in average charges across different age groups.|

## Analysis techniques used in the project are
* Descriptive Statistics gives uderstanding of basic statistics such as average insurance charges by age, gender, and region.
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
	- Acknowledge the source of the dataset and describe any modifications made.
  -  Disclose limitations in the data, such as missing values, potential inaccuracies, or limited representation of certain groups.
* Encourage periodic re-evaluation of the model as new data becomes available to 
  maintain accuracy and fairness.


## Development Roadmap
* Challenges faced during working project -
Data Quality Challenges
      * Missing Values: The dataset contained missing entries across several columns.
       Duplicate Records: Presence of duplicate rows could skew analysis and model performance.
      * Incorrect Data Types: Some categorical variables were not properly encoded, leading to errors in processing.
      * Outliers and Inconsistent Data: Extreme values in variables like BMI and charges could distort statistical analyses and model training
Strategies implemented to handle Data processing challanges -
Data Cleaning
    *  Handling Missing Values- isnull().sum(). Utilized median imputation for numerical columns and mode imputation for categorical columns to maintain data integrity without introducing bias.
    *  Removing Duplicates- Employed drop_duplicates() in pandas to eliminate duplicate records, ensuring the dataset's uniqueness.
Data encoding -
    *  Categorical Variable Encoding - Converted categorical variables (sex, smoker, region) to appropriate formats using one-hot encoding and label encoding to facilitate seamless integration into machine learning models.
    *  Feature Engineering- Created new features such as BMI categories to enhance the model's ability to capture nonlinear relationships.
Statistical Analysis - Performed exploratory data analysis (EDA) to identify outliers using box plots and scatter plots.
Technical Challenges - 
      * Library Deprecations and Warnings- Encountered deprecation warnings from libraries like pandas and plotly, which could disrupt the workflow.
      * Code Errors and Bugs- Faced various errors such as KeyError, TypeError, and          IndentationError during data manipulation and visualization stages.
      * Visualisation Constraints- Difficulty in customizing visualisations (e.g., resizing images, 
      managing hover data) using Markdown and Plotly.
* Strategies implemented to overcome Technical challenges 
Staying Updated- 
       * Library Updates - Regularly updated libraries (plotly, pandas, etc.) to their latest versions to benefit from bug fixes and updated functionalities.
       * Error Handling and Debugging:
       * Systematic Debugging - Utilized detailed error messages to identify and rectify issues, such as replacing incorrect functions (pd.get_var to pd.get_dummies) and fixing syntax errors.
       * Code Reviews and Testing - Implemented thorough code reviews and debugging to catch and resolve bugs early in the development process.
       * Warnings Management: Employed the warnings module in Python to selectively ignore non-critical warnings, ensuring a cleaner output without suppressing important alerts.
Visualisation and Reporting Challenges -
      * Effective Communication- Creating visualizations that are both informative and easily interpretable by users(stakeholders) with varying levels of technical expertise.
      * Customisation Limitations- Overcoming the limitations of visualisation libraries (e.g., Markdown's inability to handle image resizing) to produce professional and clear reports.
      * Interactive Visualizations - Balancing the interactivity of visualisations with performance and compatibility across different platforms.
Strategies to overcome -
      * Plotly for Interactivity-  Utilised Plotly's interactive features to create dynamic visualisations that allow stakeholders to explore data insights in-depth.
      * Seaborn and Matplotlib for Clarity- Employed Seaborn and Matplotlib for creating clear and aesthetically pleasing static plots when interactivity was not required.Visualisation and Reporting Challenges
Task Management - 
      * Project Board - Used tools like kanban board to organize tasks, assign responsibilities, and monitor progress. 
To implement new skills and learn new tools will follow below points - 
      * Structured Learning- Enroll in relevant online courses (e.g., Coursera, edX, DataCamp).
      * Hands-On Projects- Undertake new projects or add features to existing ones to practice and solidify skills.
      * Networking and Knowledge Sharing- Join professional communities, attend webinars, and participate in hackathons to stay updated on industry trends.


## Main Data Analysis Libraries
*import numpy as np    # importing numpy functions
*import pandas as pd   # importing panda functions
*import matplotlib.pyplot as plt  # importing for plotting different analysis visualisation
*import seaborn as sns            ## built in libraryoffers built-in themes and colour palettes for 
                                    styling matplotlib graphics to differtiate data insight for better understanding
*sns.set_style('whitegrid')       # setting up style 
*from sklearn.pipeline import Pipeline
*from feature_engine.encoding import OneHotEncoder   #  Categorical Variable Encoding
*import plotly.express as px     # importing for interacive web based plotting different analysis visualisation
* import warnings   # to suppress non critical warnings if any

## Credits 

The content has been referred by open source eg. google site. The dataset referred from kaggle open source site and study material referred by LMS and SME data coach learning sessions.

### Content 

*  The Text was taken from Kaggle and written after analysing the dataset and business requiremnts for data insights to visulise reports on Insurance cost influenced by different attributes for future decision making. Some of time used AI tool to understand the concept and more undersatnding.
* some of references sites used for coding-
  https://plotly.com/python/
  https://feature-engine.trainindata.com/en/latest/user_guide/imputation/index.html
  https://seaborn.pydata.org/
  https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.html

### Media

- The images used for the gallery page were taken from open-source site like Google. 

## Acknowledgements
* Thank you code Institute giving this opportunity for explore dataset using different analsyis tools and visualise reports.
Thank you Vasi who guided and supported throughout to trubleshoot the issue. Thank you Neil for his coaching and guidance on Data analytics concepts which help to understand various tools, library, function tools to analyse dataset and Visualise user interactive reports for future decision making. Thank you all my classmates who provided support through this project.
