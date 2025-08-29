# Air Quality Measurement using AI/ML

## Project Overview
This project is part of my Edunet Foundation Internship under the topic Environment Monitoring and Pollution Control.  
The goal is to use AI/ML techniques to monitor and classify air quality levels using real-world pollution data.

## Aim
To preprocess air quality data, extract meaningful features, and classify air quality into categories (Good, Moderate, Unhealthy) as a step towards environmental monitoring and pollution control.

## Dataset
- Source: UCI Air Quality Dataset (https://archive.ics.uci.edu/ml/datasets/air+quality)  
- Features used:  
  - CO(GT) → Carbon Monoxide concentration  
  - NO2(GT) → Nitrogen Dioxide concentration  
  - C6H6(GT) → Benzene concentration  
  - T → Temperature  
  - RH → Relative Humidity  

- Target: Air Quality Category (Good, Moderate, Unhealthy) – computed using pollutant thresholds.

## Steps Implemented
1. Data Preprocessing  
   - Removed missing values (-200 replaced with NaN).  
   - Combined Date and Time into a single DateTime column.  
   - Cleaned feature columns.  

2. Feature Engineering  
   - Selected pollutants and weather indicators.  
   - Created a simplified AQI Category (Good / Moderate / Unhealthy).  

3. Future Work  
   - Train ML models (Logistic Regression, Random Forest, etc.) for AQI classification.  
   - Build a visualization dashboard (optional).  

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter Notebook / Google Colab  

## How to Run
1. Clone the repository:
   git clone https://github.com/your-username/air-quality-aiml.git
   cd air-quality-aiml
 
