# Wine-Quality-Prediction-using-RandomForest-Model
### Predicting Wine Quality Using Machine Learning (Random Forest Regressor): An Analysis of South African Wines

The above program is a machine learning project that uses the Random Forest algorithm to predict the quality of wine based on several features such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol content.

The program starts by importing the wine dataset from a given URL and performing exploratory data analysis (EDA) to understand the data and its distribution. EDA includes visualizations such as histograms, boxplots, and scatter plots to analyze the distribution of the features and their correlation with the target variable (quality).

Next, the program checks for missing values and performs feature scaling to normalize the data. The skewness of the data is also checked, and corrections are made to improve the model's accuracy.

The Random Forest algorithm is then applied to the dataset using the scikit-learn library. The program splits the dataset into training and testing sets, fits the model on the training set, and evaluates its performance on the testing set using metrics such as accuracy and F1 score

finally a prediction is made using some data feed into the model.
