# Appliances_Machine_Learning

**Background**Energy efficiency can be achieved by understanding past energy usage and predicting future consumption under specific conditions. 

**Methode** In this notebook, I predict appliance energy usage using several machine learning models, including XGB Regressor, Random Forest Regressor, Extra Trees Regressor, HistGradient Boosting, Gradient Boosting Regressor, Multi-Layer Perceptron Regressor, KNeighbors Regressor, and Linear Regression. Each model’s predictions were evaluated using cross-validation, with performance measured by metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and R².

**Result** The results show that the XGB Regressor performed best, achieving an average RMSE of 64.434 ± 5.383 and an average R² of 0.606 ± 0.054. The data also indicate a significant difference in appliance usage between periods of cold and normal Thermal Humidity Index (THI) conditions when cold the energy usage of appliances tends to be lower.

**Recommendation** :
1. Conduct further observations, ideally covering a full seasonal cycle.
2. Add more detailed measurements or separate sensors for energy usage.
3. Explore and discuss additional strategies for reducing electricity consumption to achieve greater energy efficiency.
4. Use the XGB Regressor model, as it can explain approximately 60% of the variation in energy usage.
