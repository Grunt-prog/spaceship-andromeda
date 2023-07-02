# spaceship-andromeda machine learning prediction
Explanatory Data Analysis (EDA)
Data Visualization
Data Cleaning
Trying different models, including:
Random Forest
Gradient Boost Classifier
and potentially other models not mentioned
Handling missing values by replacing them with the median
Label encoding categorical variables
Applying Principal Component Analysis (PCA) for dimensionality reduction
Achieving good accuracy with the Gradient Boost Classifier
Submission of the results
Overall, the process involved data exploration, cleaning, feature engineering, model selection, and evaluation, resulting in successful submission with high accuracy for the Gradient Boost Classifier.
Results:
**scatterplot of pca**

![image](https://github.com/Grunt-prog/spaceship-andromeda/assets/86661317/a0eff476-4524-4ccd-b8b5-871496fc3d3e)

**correlation heatmap**

![image](https://github.com/Grunt-prog/spaceship-andromeda/assets/86661317/d499f5ea-a9d3-4c3b-b4d0-0ab3121bed50)

**correlation between numerical features**

![image](https://github.com/Grunt-prog/spaceship-andromeda/assets/86661317/210389c4-f2c8-4e52-9af0-d4ff3ec0ad73)

**accuracies**

Model	Score

5	GradientBoosting	0.808666

1	LogisticRegression	0.794479

4	RandomForest	0.771089

3	DecisionTree	0.753834

2	LinearSVC	0.616564

0	KNeighbors	0.615414

**Sample_output**

	PassengerId	Transported

0	0013_01	True

1	0018_01	False

2	0019_01	True

3	0021_01	True

4	0023_01	True
