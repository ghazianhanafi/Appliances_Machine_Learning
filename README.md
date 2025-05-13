# Appliances_Machine_Learning

**Background**Energy efficiency can be achieved by understanding past energy usage and predicting future consumption under specific conditions. 

**Methode** In this notebook, I predict appliance energy usage using several machine learning models, including XGB Regressor, Random Forest Regressor, Extra Trees Regressor, HistGradient Boosting, Gradient Boosting Regressor, Multi-Layer Perceptron Regressor, KNeighbors Regressor, and Linear Regression. Each model’s predictions were evaluated using cross-validation, with performance measured by metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and R².

**Result** The results show that the XGB Regressor performed best, achieving an average RMSE of 64.434 ± 5.383 and an average R² of 0.606 ± 0.054. The data also indicate a significant difference in appliance usage between periods of cold and normal Thermal Humidity Index (THI) conditions when cold the energy usage of appliances tends to be lower.

**Recommendation** :
1. Conduct further observations, ideally covering a full seasonal cycle.
2. Add more detailed measurements or separate sensors for energy usage.
3. Explore and discuss additional strategies for reducing electricity consumption to achieve greater energy efficiency.
4. Use the XGB Regressor model, as it can explain approximately 60% of the variation in energy usage.

**Result Picture**

EDA

![lineplot](https://github.com/user-attachments/assets/883276ec-b4f2-4cc8-9be8-fd32a988eccb)
![lineplotday](https://github.com/user-attachments/assets/a37b7efa-3290-4135-a780-aaa7a447a1a6)
![Histogram](https://github.com/user-attachments/assets/f2607d9c-6d1e-4734-a656-abde8aa59633)
![Histogram 2 cat](https://github.com/user-attachments/assets/5d09376e-d5fb-4685-8dc7-a19642eb5e2e)
![correlation](https://github.com/user-attachments/assets/cee4bf14-3b81-4d06-bf71-4cc7eee1830d)
![THIpairplot](https://github.com/user-attachments/assets/b65408dd-056c-4c4d-8004-c4f056005b89)
![SpearmanCOrrelation](https://github.com/user-attachments/assets/e2c7e329-cf70-477c-a1d3-9d6124b53787)

RESULT

![RMSE](https://github.com/user-attachments/assets/3964f51c-0238-4ab8-a40d-131eeff8c7d0)
![R2](https://github.com/user-attachments/assets/4c10ae8b-3162-4636-8383-1c2ca76815f8)
![MAPE](https://github.com/user-attachments/assets/f6f93bff-6a51-4b17-8c79-a7dd54b51c84)
![MAE](https://github.com/user-attachments/assets/afc2d586-cd98-4c1f-89c0-0d667d9247cb)
![Runtime](https://github.com/user-attachments/assets/5e8de86b-d907-46a9-b678-cd520b458d10)

PREDICTION

![Predict1221](https://github.com/user-attachments/assets/4f381940-3cfc-46b2-856d-61bd791459ea)
![Predict412](https://github.com/user-attachments/assets/5ef5519e-31e8-42e3-bf74-a5d5b7f5e879)
![Predict-44](https://github.com/user-attachments/assets/695ab2e4-c8a3-4f77-ace1-ff614180e35a)


