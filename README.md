# First stage Rocket land Prediction

To determine the price of a rocket launch and predict first stage of a rocket

In this project I will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


### ✅ **Slide Title: Final Project Summary – SpaceX Launch Analysis & Prediction**



### 📌 Executive Summary:
This project explores SpaceX launch records, uncovering insights through interactive visualizations and applying machine learning to predict launch success.



### 🔍 Introduction:
We aim to analyze SpaceX missions, identify trends in successful launches, and build a predictive model using classification algorithms.



### 🧹 Data Collection & Wrangling:
- Data sources: SpaceX CSV datasets (launch data, mission outcomes, booster versions, etc.)
- Cleaned, transformed, and one-hot encoded categorical features.



### 📊 EDA & Visual Analytics:
- Launch success rate by site and orbit visualized using Seaborn and Plotly.
- Interactive visualizations (Pie Charts, Scatter Plots, Line Graphs) for launch site comparisons and payload trends.



### 📈 Predictive Analysis Methodology:
- Standardized features with `StandardScaler`.
- Split into training/testing sets.
- GridSearchCV used to optimize parameters across:
  - Logistic Regression
  - SVM
  - Decision Tree
  - KNN


### 📉 EDA Visualization Results:
- Payload mass vs launch success correlation
- Orbit success rates
- Flight number vs success trends
- Yearly launch success rate



### 🧾 SQL-Based EDA:
- Queried unique launch sites, booster performance, and payload thresholds.
- Identified first successful landing on ground pad.
- Joined SQL queries with Pandas for deeper insights.



### 🗺️ Interactive Map (Folium):
- Clustered SpaceX launch site markers
- Integrated launch success as color-coded pins
- Used `MarkerCluster` plugin for overlapping coordinates



### 📊 Plotly Dash Dashboard:
- Dropdown for site selection
- Dynamic Pie Chart for success/failure
- Payload range slider
- Scatter plot showing payload vs launch success



### 🧠 Predictive Analysis Results:
- **Logistic Regression Accuracy**: 83.3%
- **SVM Accuracy**: 83.3%
- **KNN Accuracy**: 83.3%
- **Decision Tree Accuracy**: 77.8%
- Logistic, SVM & KNN performed best with consistent accuracy.



### 🧠 Conclusion:
- Most launches succeed at certain payload ranges and sites.
- Predictive models can reliably classify mission success.
- Insights help inform launch planning and booster recovery strategies.



### ✨ Creativity & Innovation:
- Custom styling on Dash dashboard
- Multiple machine learning comparisons
- Real-world mission simulation with SQL + ML


