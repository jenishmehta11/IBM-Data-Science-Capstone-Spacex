# IBM Data Science Capstone Project - SpaceX

## Introduction

In this capstone, we aim to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches at a cost of $62 million, significantly lower than other providers, who charge upwards of $165 million. This cost advantage comes primarily from SpaceX’s ability to reuse the first stage of their rockets. By accurately predicting the success of the first stage landing, we can estimate the launch cost and provide valuable insights for companies seeking to compete with SpaceX.

This capstone project immerses you in a real-world data science scenario. You will step into the role of a Data Scientist working for a startup aiming to break into the commercial space launch industry. Your mission is to build a machine learning pipeline that leverages historical launch data to predict landing outcomes, guiding your company’s competitive strategy. In the process, you’ll follow the full Data Science methodology involving data collection,data wrangling,Exploratory Data Analysis,Data Visualization,Model Development,Model evaluation, reporting your results to stakeholders.


## Business Problem
SpaceX’s dominance in the market is largely due to its reusable rocket technology, drastically lowering costs. If your startup can accurately predict the likelihood of a successful first-stage landing, you’ll gain a strategic edge — enabling smarter, more competitive bids for satellite launches and commercial space missions. With this information, your company can optimize pricing strategies, assess launch risks, and better position itself against SpaceX and other launch providers.

## Objective
Build machine learning models to predict the likelihood of the Falcon 9 first stage landing successfully and compare which model performs the best.
Leverage exploratory data analysis (EDA) and visualizations to derive insights into the factors influencing landing outcomes.
Use model predictions to estimate launch costs, empowering the startup to make competitive and data-driven business decisions.

## Tools & Technologies
Python: For data analysis, visualization,building dashboards(dash and plotly) and model building (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn).
SQL: For data querying and manipulation.

## Project Workflow
1. Data Collection: Gather historical SpaceX launch data through APIs and web scraping.
2. Data Wrangling & Cleaning: Clean and preprocess the data, handling missing values, outliers, and inconsistencies.
3. Feature Engineering: Transform categorical variables (e.g., launch sites, rocket versions) and normalize numerical data.
4. Exploratory Data Analysis (EDA): levaraging the functions of sql and python for data querying,manipulation and visualization.
5. Model Development: Train and evaluate multiple machine learning models (Logistic Regression, DecisionTree, SVM and KNN) to predict landing success.
6. Model Optimization: Use techniques like GridSearchCV and cross-validation to fine-tune hyperparameters and maximize performance.
7. Results Interpretation: Analyze model outputs, interpret feature importance, and present findings to inform business decisions.

## Results:
1. Data Collection & Exploration: Collected and cleaned SpaceX launch data, exploring features like launch site, payload, booster version, and landing outcomes.
2. Predictive Modeling: Built and tested four models — Logistic Regression, SVM, Decision Tree, and KNN — to predict landing success.
3. Model Evaluation: Used cross-validation and performance metrics (accuracy, confusion matrices). The Decision Tree model outperformed the others.
4. Visualization: Created visualizations to reveal feature relationships, aiding in understanding the key factors driving success.

## Insights:
1. Key Success Factors: Payload mass, launch site, booster version, and orbit type significantly influence landing outcomes.
2. Model Performance: The Decision Tree model was the most accurate, making it the best choice for predicting success.
3. Trends Over Time: Success rates improved over the years, showcasing SpaceX’s technological advancements.
4. Landing Patterns: Analyzing landing outcomes highlights the unique challenges of different landing techniques and locations.

## Conclusion
This project demonstrates the powerful intersection of data science and aerospace engineering. By leveraging historical launch data and predictive modeling, we created a tool that empowers companies to compete more effectively in the commercial space industry. With accurate landing predictions, startups can make smarter financial decisions, mitigate launch risks, and challenge industry leaders like SpaceX with confidence.
