Housing is a test Machine Learning model I have made to conduct a detailed research on different machine learning models. And experimenting how they respond to tuning various hyperparameters and attributes. 
This project also deals with adding new attributes, removing attributes that are found to be crucial(median_income in this case).
RandomForest regressor was found to be the most accurate of the three, followed by decision tree and linear regression.
Transformer functions like, fit(), transform(), fit_transform() were explicitly defined in this projects. Attributes like rooms__per_household, bedrooms_per_room etc were added using ColumnTransformer.
Numerical and categorical pipelines have been defined and merged into a full pipeline where various subsets of main dataset were tested.

![pandas_main_data](https://user-images.githubusercontent.com/67424908/117529771-29eb4700-aff7-11eb-8892-8cba1a8322ec.png)
