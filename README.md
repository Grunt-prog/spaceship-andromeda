# spaceship-andromeda machine learning prediction


In this data analysis task, several steps were undertaken to gain insights and make predictions using machine learning models. The process began with Exploratory Data Analysis (EDA) to understand the structure and characteristics of the dataset. This involved examining the data's distribution, identifying any outliers, and exploring relationships between variables. Data visualization techniques, such as histograms, scatter plots, and box plots, were used to aid in this exploration.

Next, the dataset was subjected to data-cleaning procedures. Missing values were handled by replacing them with the median value, Which is a common approach when dealing with numerical data. This ensured that the dataset was complete and ready for further analysis.

Popular algorithms like Random Forest, Gradient Boost Classifier, Decision Tree, LinearSVC, and Kneighbours were applied to build predictive models. These models were selected due to their ability to handle complex relationships and perform well in classification tasks. The dataset was divided into training and testing sets to accurately evaluate the models' performance.

Label encoding was used to transform categorical variables into numerical representations, which are easier for machine learning models to process. This encoding technique assigns a unique numeric label to each category, enabling the models to understand and utilize the categorical information effectively.

Overall, through the steps of EDA, data visualization, data cleaning, model selection, handling missing values, and label encoding, a comprehensive analysis was performed on the dataset, and predictive models were developed to make accurate predictions based on the available data

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

**NOTE: 

submission_output.csv contains prediction for the test.csv

The notebook was in the name of spaceship-andromeda.ipynb**
