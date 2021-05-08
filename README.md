Housing is a test Machine Learning model I have made to conduct a detailed research on different machine learning models. And experimenting how they respond to tuning various hyperparameters and attributes. 
This project also deals with adding new attributes, removing attributes that are found to be crucial(median_income in this case).
RandomForest regressor was found to be the most accurate of the three, followed by decision tree and linear regression.
Transformer functions like, fit(), transform(), fit_transform() were explicitly defined in this projects. Attributes like rooms__per_household, bedrooms_per_room etc were added using ColumnTransformer.
Numerical and categorical pipelines have been defined and merged into a full pipeline where various subsets of main dataset were tested.


Data types and names of attributes in the set:

  ![pandas_main_data](https://user-images.githubusercontent.com/67424908/117529771-29eb4700-aff7-11eb-8892-8cba1a8322ec.png)

Summary of numerical attributes using describe():
  ![image](https://user-images.githubusercontent.com/67424908/117529794-5d2dd600-aff7-11eb-96e2-d69512ba7f88.png)

In the above figure: count is number of X attributes
                     mean is the average/mean of numerical attributes
                     max is the highest value in a given attribute
                     std shows standard deviation
                     25%, 50%, 75% these values represent percentile, i.e for example 25% of districts have house_median_age lower than 18
                    
Graphical representation of describe():
   ![image](https://user-images.githubusercontent.com/67424908/117530013-856a0480-aff8-11eb-90d3-312e0102749d.png)

