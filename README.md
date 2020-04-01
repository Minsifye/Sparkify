# Spark Project: Sparkify
Sparkify is a fictional music streaming service like Spotify or Pandora. I will be using Sparkify Churn Prediction as a problem statement. 

Note: I am using PySpark for this project, with a tiny subset (128MB) of the full dataset available (12GB). And keeping deployment of this project on AWS Cluster for future works.

### A Udacity Data Scientist Nanodegree Project


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing) 


## Installation <a name="installation"></a>


- Python 3.5+ (I used Python 3.6)
- Libraries: NumPy, SciPy, Pandas, Sciki-Learn
- Pyspark SQL and Pyspark ML libraries.
- AWS account to run on cloud cluster(If want to do so).



## Project Motivation<a name="motivation"></a>

- Data Understanding: I began with Exploratory Data Analysis on my local machine with a small Sparkify dataset provided by Udacity.

- Data Preparation: During data preparation, I dealt with data challenges like missing values, data cleaning, imputing categorical variables and identifying a target variable to predict churned customers.

- Data Visualizations: Provided data visualization for a deeper understanding of Sparify customers.

- Modeling: I have used the Decision Tree Classifier, Random Forest Classifier and Gradient Boosting Classifier to train three models and comparing the outcomes before choosing the winning model.

- Evaluation Metric: In pySpark, we can not print the confusion matrix, instead, we have to use MulticlassClassificationEvaluator to evaluate accuracy and f1_score. We can also use BinaryClassificationEvaluator to calculate Area under the ROC curve and Area under the Precision-Recall.
- Results: After comparing all models on different evaluation metrics, Gradient Boosting performs better than the other two. You can see that f1-score for the Gradient boosting algorithm is 0.90, while Random Forest f1-score is 0.79.
- Deploy - I am not deploying this code anywhere right now. For now, it is available in jupyter notebook form only.
I have followed CRISP-DM process during this analysis. 


## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above points.  This notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  


## Results<a name="results"></a>

The main findings of the code can be found at the Medium post available [here]().


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to [Udacity](https://www.udacity.com/) Team for helping me to learn all these new things.

