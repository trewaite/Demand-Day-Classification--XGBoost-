# Demand-Day-Classification--XGBoost-
Demand Day Classifcation XGBoost

First crack at building features and implementing XGBoost algorithim to classify electricty demand days in Ontario. See other Demand Day Classification project (includes full pipline: data scraper, cleaning, feature creation, forecasting, classifcation and visualization)

Summary:
- Merging historical electricty demand data with weather data sets
- Creation of dummy variables for categorial features
- Feature creation (Heating degree days, cooling degree days, time variables such as day,month,dayofweek)
- GridSearch over possbile XGBoost parameters minimzing AUC
- Using XGBoost scale_pos_weight to deal with uneven target variables (many more 0's than 1's)
- Investigation of confusion matrix and importance on busines case (perfect recall achieved)
- Investigation of trees and performace over 10 fold cross validation
- Investigation of feature importance
