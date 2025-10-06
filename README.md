# DHC-Intern-Task--Energy-Consumption-Time-Series-Forecasting
#  Energy Consumption Time Series Forecasting

###  Objective
Forecast short-term household energy usage using historical patterns.

### Dataset
**Household Power Consumption Dataset**  
(You can download from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption))

###  Steps Performed
1. Data loading and parsing (date-time conversion)
2. Data resampling (hourly)
3. Feature engineering (hour, day, weekend flag)
4. Exploratory Data Analysis (EDA)
5. Model building:
   - ARIMA
   - Prophet
   - XGBoost
6. Model evaluation (MAE, RMSE)
7. Visualization:
   - Actual vs. forecasted energy
   - Hourly and weekly patterns
   - Seasonal decomposition
   - Model comparison

###  Results
| Model | MAE | RMSE |
|--------|------|------|
| ARIMA | _0.706745_ | _1.054898_ |
| Prophet | _0.559932_ | _1.054898_ |
| XGBoost | _0.562992_ | _0.754348_ |
<img width="1002" height="470" alt="image" src="https://github.com/user-attachments/assets/1c40f6ef-3486-47f1-9f97-9b474ce9c19b" />

<img width="678" height="470" alt="image" src="https://github.com/user-attachments/assets/335ebb4b-4dd4-4365-ae01-9016a23b22a4" />

<img width="855" height="471" alt="image" src="https://github.com/user-attachments/assets/80ea128c-e951-49fc-957b-8f9ced9a944d" />

###  Skills Gained
- Time series forecasting  
- Feature engineering  
- Model evaluation & comparison  
- Visualization & storytelling


# Open in Jupyter or Colab
