# COVID-19 Cases and Vaccination Prediction in Bangladesh

[![DOI](https://img.shields.io/badge/DOI-10.34104/ajeit.022.01300139-blue)](http://dx.doi.org/10.34104/ajeit.022.01300139)

## Overview
Coronavirus disease 2019 (COVID-19) is a contagious disease caused by the virus SARS-CoV-2. The first case of COVID-19 in Bangladesh was detected on **8th March 2020**. Due to the high-density population and limited resources, COVID-19 cases have increased rapidly in the country.  

To help with national preparedness and action plans, this project uses **machine learning** to provide trend analysis and predict the likely number of cases and deaths in upcoming days. Additionally, it distributes Bangladesh into zones based on the number of cases to increase public awareness and investigates correlations between COVID-19 and other diseases.

## Features
- Trend analysis of COVID-19 cases and deaths.
- Prediction of future cases and fatalities using machine learning.
- Zone-wise distribution of Bangladesh according to COVID-19 cases.
- Correlation analysis with other diseases.
- High-accuracy ML algorithms applied:  
  - Linear Regression  
  - Polynomial Regression  
  - Extra Trees Classifier  
  - Decision Tree Regression  
  - Chi-Square Test  

## Dataset
The project uses COVID-19 datasets for Bangladesh, including daily reported cases, deaths, and vaccination data. The dataset is cleaned and preprocessed for machine learning models.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/covid-19-predictor-bd.git
    cd covid-19-predictor-bd
    ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```
3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the main prediction script:
    ```bash
    python covid_predictor.py
    ```
2. Visualize trend analysis and predictions using the provided plotting scripts.
3. Explore correlation analysis results.

## Results
- High-accuracy prediction of daily cases and deaths.
- Zone-wise distribution map of COVID-19 in Bangladesh.
- Insights into the correlation between COVID-19 and other diseases.

## References
- DOI: [10.34104/ajeit.022.01300139](http://dx.doi.org/10.34104/ajeit.022.01300139)  

## License
This project is licensed under the MIT License.
