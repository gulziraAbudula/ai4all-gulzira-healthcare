# Healthcare Facility Resilience to Power Outages in United States

In the AI4ALL Ignite program, we worked on an AI project designed to address the critical challenge of natural disasters disrupting both energy supply and health services. It proposes developing an emergency power allocation model, especially drawing from renewable energy sources, for mobile health units and backup systems in the U.S. The purpose of the project was to apply machine learning techniques to address a real-world problem while promoting responsible and ethical use of AI.


## Problem Statement <!--- do not change this line -->

Can we accurately predict which U.S. health entities are most vulnerable during a hazardous natural disaster and the amount of renewable emergency power allocated for mobile backup units?

## Key Results <!--- do not change this line -->

This system
1. Enabled proactive energy support planning for healthcare systems during emergencies
2. Ensured equitable and efficient response through AI integration
3. Integrated diverse data sources, including:
      - Meteorological APIs
      - Federal risk indexes
      - Healthcare infrastructure datasets   
4. Bridged a vital gap between AI, healthcare, and environmental preparedness


## Methodologies <!--- do not change this line -->

To accomplish this, we used two real-world energy datasets from Kaggle. For electricity consumption forecasting, we applied a Linear Regression model to the Smart Meter Electricity Consumption dataset, analyzing consumption patterns across households. For fault event prediction, we used a Random Forest classifier on the Smart Grid Asset Monitoring dataset, which included sensor data such as voltage, current, and frequency.

Trained a Linear Regression model using the Smart Meter dataset to predict daily electricity consumption based on temperature, humidity, wind_speed and average past consumption. The model achieved R-squared of 0.12.
Applied a Random Forest model to classify fault events using the Smart Grid Asset dataset, achieving 86.11% accuracy and an F1-score of 0.8054. The model demonstrated strong performance in handling both numerical and categorical features through one-hot encoding.


## Data Sources <!--- do not change this line -->

Smart Meter Electricity Consumption Dataset: https://www.kaggle.com/datasets/ziya07/smart-meter-electricity-consumption-dataset?utm_source=chatgpt.com
Smart Grid Asset Monitoring Dataset: https://www.kaggle.com/datasets/ziya07/smart-grid-asset-monitoring-dataset

## Technologies Used <!--- do not change this line -->

Python – Core programming language used for data processing, analysis, and model development.
pandas – For data cleaning, transformation, and exploration.
NumPy – For efficient numerical operations and array handling.
scikit-learn – For implementing machine learning models including Linear Regression and Random Forest.
Matplotlib / Seaborn – For data visualization and plotting trends.
Google Colab – For interactive development, visualizations, and presenting project work.
Kaggle Datasets – Used real-world datasets from Kaggle for energy consumption forecasting and asset monitoring.


## Authors <!--- do not change this line -->

This project was completed in collaboration with:
- Tram Tran (tramtran.helen@gmail.com)
- Chelsea Ross (chelsearosscr21@gmail.com)
- David Nintang (djnintang@gmail.com)
- Sumodha (sp230@rice.edu)
- Gulzira Abdullah (gzabudula21@gmail.com)
