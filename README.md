# Machine_Learning_Tablet_dataset
“In the first phase, the studies to be carried out are data recognizing and digesting (EDA) visualization.
covers all processes. Whether the target variable of the data set is evenly distributed
disintegration should be examined and interpreted. On the other hand, correlation matrices should be drawn and
Correlation coefficients between variables that seem significant should be interpreted. in the dataset
values ​​of numerical variables such as mean, median, standard deviation should be displayed and
should be interpreted. Numerical and categorical variables with ideal techniques and tools
should be visualized and the parts considered important should be interpreted.
In the second stage, the preprocessing part of the dataset should be performed. If under preprocessing
If there are missing data in the data set, filling these missing data with logical reasons
is expected. In order for the target variable not to lose its significance during this process,
It is expected that the data will be examined and filled in specific to the target variable. Also at this level
categorical variables can be ordered or unordered (nominal)
Appropriate digitization procedures should be carried out according to
In the third phase, our target variable is to make machine learning models.
The “Price Range” variable and other variables to help us estimate this variable
be separated into dependent and independent variables. dependent and independent
“train_test_split” method with variables 75% training and 25% testing
should be separated using GaussianNB, DecisionTree and KNN models with training set
should be trained and a complexity matrix should be drawn for each model, and accuracy score should be obtained.
Comparison of success status between models should be made. The success of the models
F1_Score, Precision, Recall values ​​for evaluation are "classification_report"
must be printed through.
11.05.2022
By default, the team leader DecisionTree algorithm (criterion = “gini”) parameter
value, but for this problem, parameter parameter (criterion = “entropy”)
He assured the team that the success would increase if they changed it to be In addition to this
As a result, it is stated that the number of neighbors is very critical for the KNN algorithm and it can range from 2 to 15.
try to record the score of the model in each trial by trying each number as the number of neighbors.
recommends. With the change of the number of neighbors, the score of the model will also change, and each neighbor
It should be visualized by drawing a plot of the model score corresponding to the number of
has requested
