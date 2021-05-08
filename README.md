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

hist() method draws a graph, it relies on Matplotlib which itself relies on user specified backend. Here, %matplotlib inline to create district to attribute graph.

Splitting the dataset into test and training set of ratio 20:80 respectively
The most common and efficient splitting method is using stratified shuffle split. It indexes the data set and randomly chooses a test and training set. It does not vary through many run unlike train_test_split().
   Using train_test_split:
   
   ![image](https://user-images.githubusercontent.com/67424908/117530419-bc411a00-affa-11eb-8b0d-ff294755d8d4.png) 
   ![image](https://user-images.githubusercontent.com/67424908/117530432-cbc06300-affa-11eb-9946-c6a901ff4b7e.png)

   ![image](https://user-images.githubusercontent.com/67424908/117531091-725a3300-affe-11eb-8e58-aaeb528c25ad.png)
   ![image](https://user-images.githubusercontent.com/67424908/117531101-7c7c3180-affe-11eb-8e6f-3d228303ad56.png)
   
Scatter plot of california:
    where circles represent the population of district, C represents the price of house in each district, CMAP is a function that uses color                                         represent the prices; blue being low, red being high
    
   ![image](https://user-images.githubusercontent.com/67424908/117531141-a897b280-affe-11eb-817d-f36d1a7e6fff.png)



