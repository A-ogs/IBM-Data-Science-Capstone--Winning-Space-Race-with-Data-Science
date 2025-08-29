# Winning the Space Race with Data Science

## Project Overview

This project utilizes publicly available SpaceX launch data to extract insights and build tools that can assist emerging aerospace companies, such as a hypothetical "Space Y". The objective is to analyze historical mission data to identify key factors influencing launch outcomes and to develop predictive models and dashboards to support data-driven decision-making.

## Key Features

### Data Collection  
- Launch data was obtained from the SpaceX public REST API.  
- Additional information was extracted through web scraping from Wikipedia.  
- Data was filtered to include only Falcon 9 missions with single payloads and cores.  
- Data was cleaned and prepared using pandas.

### Exploratory Data Analysis (EDA)  
- Conducted using SQL, Matplotlib, and Seaborn.  
- Analysis included:
  - Payload success rates
  - Launch site performance
  - Orbit outcomes

### Interactive Visualizations  
- A Folium map displays launch sites and outcomes.  
- A Plotly Dash dashboard provides dynamic filtering and analysis of mission success rates.

### Predictive Modeling  
- Classification models were developed, including Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN).  
- Models were optimized using GridSearchCV.  
- The objective was to predict booster landing success using features such as payload, orbit, and launch site.

## Key Findings

- Launch success rates were approximately 77% at KSC and VAFB, and around 60% at CCAFS.  
- There is no strong correlation between payload mass and mission success. Booster version was identified as a more influential factor.  
- Success rates showed a notable upward trend after 2014.  
- The Support Vector Machine (SVM) model achieved the highest accuracy at 88.8%, with no false negatives in identifying successful landings.

## Repository Structure

- Data Collection - API  
- Data Collection - Web Scraping  
- Data Wrangling  
- EDA - Data Visualization  
- EDA - SQL  
- Interactive Map - Folium  
- Interactive Dashboard - Plotly Dash  
- Predictive Analysis  

## Author

Andrea Galvão
