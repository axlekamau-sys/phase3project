
# Chicago Traffic Crashes – Injury Prediction 🚗📊

##  Project Overview
This project analyzes historical traffic crash data from the City of Chicago to predict the primary contributory cause of a car accident. The goal is to provide insights for city planners, policymakers, and road safety authorities to reduce accidents and improve public safety.

Using machine learning, we explore factors such as weather, lighting, roadway conditions, speed limits, and temporal patterns to identify high-risk scenarios that are likely to lead to accidents or injuries.


---

##  Dataset

**Dataset Name:** Traffic_Crashes_-_Crashes.csv  
**Source:** City of Chicago Open Data Portal  
**Description:**  
Environmental conditions: Weather, lighting, road surface
Vehicle information: Number of units, speed limit
Crash timing: Hour, day of the week
Injuries: Severity and counts
Contributory causes: Primary and secondary causes of crashes

- ~746498 records (rows)
- ~49 original columns
- No personally identifiable information
- Covers multiple years of crash history

---

##  Project Objectives

Exploratory Data Analysis (EDA)

Crash trends hour by hour, day by day, month by month.

Checking on the weather, light and road surface conditions.

Determining accident causal patterns.

One Week Of Data Cleaning and Feature Engineering.

Handling missing values

Grouping unusual primary contributory causes as an OTHER category.

Categorical features which are one-hot encoded.

Modeling

Logistic Regression: Baseline model to model that is linear.

Random Forest: Model of Ensemble to identify complicated patterns and interaction.

Model Evaluation

Measures: Accuracy, Precision, Recall, F1-score.

Comparison on unseen test data models.

It was followed by confusion matrix analysis to determine wrongly classified causes.

Business Recommendations and insights.

Peak crash periods denote that the enforcement of a specific traffic is necessary.

The light conditions and visibility affect the risk of accidents.

High risk conditions, locations and times are some of the areas that can be targeted by road safety interventions.
---

## Key finding 
Some periods of the day (afternoon and evening) experience high rates of accidents.

Traffic patterns and driver behavior can predict the causes of crashes better than weather can.

Random Forest is a better model in predicting contributory causes than the Logistic Regression because it is capable of accommodating nonlinear effects


---

##  Tools & Technologies

# Tools & Libraries
- **Python** (3.10+)
- **Pandas** → data cleaning & analysis
- **Matplotlib** & **Seaborn** → visualizations
- **Jupyter Notebook** → interactive analysis

---

## Author
Kiragu Axle - Data Scientist

=======
# phase3project

=======
# phase3project

