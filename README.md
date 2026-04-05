# Ontario Crime Analytics & Forecasting (2021–2024)

This project analyzes and forecasts crime trends across Ontario cities using official Statistics Canada data.

## Objectives
- Clean and prepare raw crime data
- Perform exploratory data analysis (EDA)
- Segment cities using K-Means clustering and PCA
- Apply hypothesis testing (t-test)
- Compare Linear Regression vs Random Forest
- Forecast crime trends using Exponential Smoothing

## Tools
Python, Pandas, Matplotlib, Scikit-learn, Statsmodels, Excel

## Key Insights📊
- Toronto consistently shows the highest crime volume
- Statistically significant difference between Toronto and Windsor (p < 0.05)
- Random Forest (R² = 0.944) outperformed Linear Regression
- Forecast shows rising crime trend into 2025

## Visualizations

### Heatmap of Crime by City and Year
![Heatmap](https://github.com/user-attachments/assets/d1aafd23-cf52-49de-a936-1251840c468d)

## Key Insights📊
1. Toronto consistently reports the highest crime values, rising steadily from 2021 (511k) to 2024 (688k).
2. Kitchener–Waterloo and London maintain moderate but stable crime levels over the years.
3. Guelph and Windsor remain the lowest crime cities, with only slight year-on-year increases.
4. The colour gradient emphasizes Toronto’s dominance in total crime volume annually.
5. The overall trend shows incremental crime growth across all cities from 2021 to 2024.

### PCA Clustering
![PCA](https://github.com/user-attachments/assets/e336ece0-d08a-4265-b169-a51ae8cd3f7c)

## Key Insights📊
1. Toronto is clearly isolated, indicating a distinct crime profile—likely due to its high volume of incidents.
2. Kitchener–Waterloo and London are grouped, sharing similar mid-level crime patterns.
3. Guelph and Windsor cluster together, suggesting low and consistent crime levels.
4. Clustering helps segment cities for targeted policy or resource allocation based on crime behaviour similarities.

### Model Comparison
![Model](https://github.com/user-attachments/assets/9d8afe9b-7d73-4d9d-b6d0-e205701c4519)

## Key Insights📊

## Linear Regression
R² = -96.01 → Model fit is extremely poor
RMSE = 14,951
Struggled to handle categorical variables like City and Violations
Prediction: 33,093 incidents for Toronto, 2024 (Assault level 1)

## Random Forest Regression
R² = 0.944 → Strong predictive performance
RMSE = 360.43
Effectively captured nonlinear relationships
Prediction: 25,183 incidents for the same input

## Key Insights📊
Random Forest outperformed Linear Regression significantly, making it a more reliable model for forecasting crime counts across city, year, and violation dimensions.

### Forecast for 2025
![Forecast](https://github.com/user-attachments/assets/2ae03116-95a0-40fc-8724-2d272bd2205f)

## Key Insights📊

## Methodology
1. Applied Exponential Smoothing on yearly crime totals (2021–2024)
2. Used trend-based modelling to forecast crime volume

## Trend Insight
1. A clear upward trend is observed across 2021 to 2024
2. Indicates sustained growth in total reported crimes annually
   
## Forecast for 2025
Predicted Total Crimes: 504,272 incidents
Suggests a further increase in 2025, reinforcing the need for preventive policy measures

## Author
Umang Sehgal  
Post Graduate in Business Analytics – Conestoga College
