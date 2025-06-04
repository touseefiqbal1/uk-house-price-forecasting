The accurate prediction of UK house prices remains essential for all parties involved including planning 
entities, lending organizations and residential householders but the marketplace exhibits multiple moving 
components like seasonal patterns and geographical differences together with its pandemic-induced 
disruption which makes traditional forecasting methods less reliable. This dissertation studies the House 
Price Index (HPI) data in the UK across January 2010 to December 2023 to accomplish three objectives: 
(i) measure spatial variations and temporal trends between regions and (ii) break down HPI fluctuations 
into primary components of trend, seasonality and cyclical movements and (iii) determine the most precise 
time-series forecasting solution which handles only time-based variables. The final set of models includes 
ARIMA in addition to Random Forest and Support Vector Regression and two XGBoost variants that 
employ (a) autoregressive data lags and (b) hedonic-inspired component price lags after completion of 
extensive preprocessing steps. A 2023 hold-out test set served to evaluate the final performance of tuned 
hyper-parameters through Mean Absolute Error (MAE) and Root Mean-Squared Error (RMSE). 
Exploratory analysis proves that prices differ more between northern and southern areas while annual 
patterns remain stable across all countries post-pandemic. The hedonic-lag XGBoost model delivers 
superior performance than all competing models (RMSE ≈ £1,258 and MAE ≈ £1,099) by providing 67% 
better results than other alternatives and over 80% improvement compared to ARIMA.
