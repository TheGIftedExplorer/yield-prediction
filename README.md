# yield-prediction
This project focuses on predicting agricultural yield using historical weather data (temperature, rainfall) and reservoir metrics (water level, live storage, FRL). The dataset is aggregated by state and year, and various machine learning models — including linear regression, random forest, and neural networks — are used to evaluate performance. 
Built separate regressors (e.g., LinearRegression) to predict test set features (avg_temp, rainfall, etc.) only using year as input. Used these predicted features instead of true test features when predicting yield — mimicking deployment where future weather data isn’t known.

The goal is to understand the impact of environmental factors on yield and build robust, generalizable prediction models. This also helps the farmers to know the crop yield in advance to plan and choose a crop that would give a better yield.
