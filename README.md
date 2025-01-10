# Project Healthcare Insurance

**Healthcare Insurance Project** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


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
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* Correlation Analysis : Visualise correlations between different attributes and insurance charges.
* Predictive Analysis : Develop and visualise predictive reports for estimating insurance costs.
* Geographic Analysis : Visualise the impact of geographic regions on insurance charges.

## Ethical considerations
* Follow GDPR guideline to protect dataset and maintain data integrity of person.

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


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

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank you code Institute giving this opportunity for explore dataset using different analsyis tools and visualise reports.
Thank you Vasi guided me to trubleshoot the issue. Thank you Neil for his coaching and guidance on Data analytics concepts which help to understand various tools, library to analyse dataset and Visualise user interactive reports for future decision making. Thank you all my classmates who provided support through this project.