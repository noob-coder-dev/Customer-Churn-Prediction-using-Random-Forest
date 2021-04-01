# Customer-Churn-Prediction-using-Random-Forest

![Forest Image](https://www.birmingham.ac.uk/images/news/forest-900.jpg)

## Table of Content
* <a href="head1">Overview</a>
* <a href="head2">Motivation</a>
* <a href="head3">Technical Aspects</a>
  * <a href="head31">Data preprocessing</a>
  * <a href="head32">Implementation of Random Forest Classifier</a>
*  <a href="head5">To Do</a>
*  <a href="head6">Technology Used</a>
*  <a href="head7">Author</a>
*  <a href="head8">Credit</a>


## <a href="head1">Overview</a>
This is a simple and real-life problem solving implementation of *Random Forest Classifier* on Customer Churn Prediction in a bank. This model takes a preprocessed dataset, being trained on training set, next predicts on the test dataset with an accuracy around 85%.


## <a href="head2">Motivation</a>
It's big deal, for a bank, to continue the relationship with their promising customers as well as provide them offers depending on the fact if a particular customer will have an active a/c or not. That's why it's required to predict if the customer will churn or not. Hence,  a proper ,model will play a vital role to predict with high accuracy. 
Random forest is a very versatile algorithm capable of solving both classification and regression tasks.Also, the hyperparameters involved are easy to understand and usually, their default values result in good prediction. Random forest solves the issue of overfitting which occurs in decision trees.
One limitation of Random forest is, too many trees can make the processing of the algorithm slow.


## <a href="head3">Technical Aspects</a>
This project is divided into two parts:
1. Prepocessing and exploring the data insights using numpy, pandas, matplotlib, seaborn. It ends with saving the cleaned, ready-to-feed dataset in the directory by the name,'churn_data_simple.csv'.
2. Building and implementing the model on the 'churn_data_simple.csv' dataset
 * After scaling and spliting the data into *train* and *test* dataset, a random forest model built, with default hyperparameter, is implemented which's shown overfitting!
 * Checking the best range of value at which the model has comparatively high accuracy, individually for each of the so-called important hyperparameters of a random forest classifier.
 * Operate *random search* and *grid search cv*, to seek best hyperparameter combination.
 * Comparison of the performance of all models on basis of accuracy.


## <a href="head5">To Do</a>
1. Creating a pipeline implementation. 
2. Deploy a Flask web app on Heroku.
3. improving the accuracy value of the model further.

## <a href="head6">Technology Used</a>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## <a href="head7">Author</a>
<a href="www.linkedin.com/in/manojit-roy-8a93a1183">Manojit Roy</a>

## <a href="head8">Credit</a>
The dataset has been provided by Internshala Machine Learning Training.
