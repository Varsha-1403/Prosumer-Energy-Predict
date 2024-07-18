# Prosumer-Energy-Predict
 
# Introduction
 
This project aims to address the issue of energy imbalance caused by prosumers, who both consume and generate energy. Prosumers' unpredictable energy usage poses significant challenges for energy companies, resulting in logistical and financial inefficiencies. The objective is to create a predictive model that can accurately forecast prosumers' energy usage to reduce these imbalances and associated costs.
 
The goal of this competition is to forecast the amount of electricity produced and consumed by Estonian energy customers who have installed solar panels.
 
# Abstract
 
The energy sector faces a significant challenge in managing energy imbalances, which occur when the predicted energy consumption and production do not align with actual usage. Prosumers, entities that both consume and generate energy, play a crucial role in this imbalance. Despite representing a small fraction of the total energy consumer base, the unpredictable nature of prosumers' energy usage results in considerable logistical and financial issues for energy companies. The goal of this competition is to develop an energy prediction model for prosumers to mitigate energy imbalance costs, enhancing the reliability and efficiency of the energy grid.
 
# Exploratory Data Analysis (EDA)
 
To get started with the challenge, performing Exploratory Data Analysis (EDA) is crucial. EDA helps to understand the underlying patterns, detect anomalies, and gather insights that can guide the model development process. Here are some steps you can take for EDA:
 
* Understand the Dataset: Begin by exploring the structure of the dataset. Check for the number of rows and columns, data types, and summary statistics.
* Visualize the Data: Use visualizations to identify trends and patterns. Plot graphs such as histograms, scatter plots, and time series plots to analyze the distribution and relationships between variables.
* Handle Missing Values: Identify and handle any missing values in the dataset. Decide on appropriate methods for imputation or removal of missing data.
* Feature Engineering: Create new features that might be useful for the predictive model. Consider temporal features, interactions between variables, and aggregations.
* Correlation Analysis: Check for correlations between features and the target variable. This can help in understanding which features might be more important for the model.
* Detect Anomalies: Identify any anomalies or outliers in the data that could affect the model's performance.
 
By thoroughly understanding the data through EDA, we are able build more accurate and robust predictive models.
 
# Model
 
We used models like Linear Regression, Auto Regression, SARIMA and Random Forest.
 
After comparing different models on different combinations of datsets we are able to conclude that Random Forest works the best.
 
# Notebook
* [Client, electricity prices and gas prices EDA and Model](/Notebook/client_electric_gas.ipynb)
* [historical weather and weather stations EDA](/Notebook/historical-weatherEDA.ipynb)
* [historical weather and weather stations Model](/Notebook/historical-datamodel.ipynb)
* [Forecast weather EDA and Model](/Notebook/eda_prediction.ipynb)
* [Finalizing model](/Notebook/finalizing_model.ipynb)
 
## Requirements
```
python3.12.3 -m venv predictenergy.venv
 
pip install -r requirements.txt
 
```
kaggle dataset link: https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers/