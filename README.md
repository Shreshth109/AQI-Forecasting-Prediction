<h1 align="center"> AQI Forecasting and Prediction System using Machine Learning and Time Series Models</h1>

<p align="center">
  <b>Location:</b> Patna, India<br>
  <b>Dataset Source:</b> National Clean Air Programme (NCAP)
</p>


## Overview
This project focuses on **forecasting and predicting Air Quality Index (AQI)** using historical air pollution data of **Patna** from **2015–2023**.  
The dataset has been collected from the **National Clean Air Programme (NCAP)** under the **Central Pollution Control Board (CPCB)**.  

The model predicts future AQI levels, classifies air quality categories (Good, Moderate, Poor, etc.), and analyzes seasonal pollution trends along with the dominant pollutants responsible for variations in air quality.

---

## Objectives
- Forecast **future AQI values** using **time series models**.  
- Classify air quality into CPCB-defined categories using **machine learning**.  
- Perform **Exploratory Data Analysis (EDA)** to identify **major pollutants per month**.  
- Visualize **seasonal and monthly variations** in pollution levels for Patna.  

---

## Methodology
1. **Data Collection:**  
   - Daily AQI data for **Patna (2015–2023)** obtained from **NCAP**.  
   - Includes concentrations of six key pollutants:  
     **PM₂.₅, PM₁₀, NO₂, SO₂, CO, and O₃**.  

2. **Data Preprocessing:**  
   - Handled missing values and outliers.  
   - Converted dataset into a **time series format** for forecasting.  

3. **Model Development:**  
   - Applied **Prophet model** for AQI forecasting.  
   - Used **Random Forest Classifier** for AQI category prediction (*Good, Satisfactory, Moderate, Poor, Very Poor, Severe*).  
   - Achieved an **R² score of 0.73** for AQI forecasting.  

4. **Exploratory Data Analysis (EDA):**  
   - Identified **dominant pollutants** across months.  
   - Visualized **seasonal pollution variations** using Matplotlib and Seaborn.  

5. **Future Scope:**  
   - Implementation of **LSTM (Long Short-Term Memory)** for deep learning–based forecasting.  
   - Integration into a **web dashboard** for real-time visualization.

---

## Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Prophet, Matplotlib, Seaborn  
- **Techniques:** Time Series Forecasting, Classification, Exploratory Data Analysis (EDA)  
- **Dataset Source:** NCAP (Patna, 2015–2023)

---

## Results
- Achieved **R² = 0.73** for AQI forecasting.  
- Identified **PM₂.₅** and **PM₁₀** as the most dominant pollutants during winter months.  
- Observed **seasonal air quality variations** — poorest during **November–January**, and best during **July–September**.  

---

## Conclusion
The project demonstrates how **machine learning and data-driven modeling** can effectively forecast AQI trends and help authorities make informed environmental decisions.  
This approach can assist policymakers and citizens of **Patna** in understanding pollution dynamics and planning corrective measures.

---

## Future Enhancements
- Add **LSTM model** for advanced time-series forecasting.  
- Create a **Streamlit or Power BI dashboard** for interactive AQI visualization.  
- Include **meteorological factors** (temperature, humidity, wind speed) for more accurate predictions.

---

##  Author
**Kumar Shreshth**  
Civil Engineer | Data & Environmental Analytics Enthusiast  

---

## Keywords
AQI Forecasting · Patna · NCAP · CPCB · Time Series · Machine Learning · Random Forest · Prophet · Pollution Analysis
