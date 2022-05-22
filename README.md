# Housing_price_prediction

This is one of the projects I work on as I follow Aurelien Geron's Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow, Copyright 2019 Aurélien Géron, 978-1-492-03264-9. You can get yourself a copy of the book [here](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291).

I built a Machine Learning project on predicting California housing price based on the StatLib library. It is a full-on project that goes through framing the problem, analyzing data, using regression algorithms on the training data, evaulating algorithm performance, and then testing it on the test data. Also looks into pipelining the project.

## To do an end-to-end Machine Learning project we need to do the following steps
1. Understand the requirements of the business.
2. Acquire the dataset.
3. Visualize the data to understand it better and develop our intuition.
4. Pre-process the data to make it ready to feed to our ML model.
5. Try various models and train them. Select one that we find best.
6. Fine-tune our model by tuning hyper-parameters
7. Present your solution to the team.
8. Launch, monitor, and maintain your system.

## Project overview

* A machine learning regression model that is trained on California Housing Prices dataset from the StatLib repository.
* We are doing supervised learning here and our aim is to do predictive analysis
* During our journey we'll understand the important tools needed to develop a powerful ML model
* Our aim is to play with tools like cross validation, GridSearchCV, RandomizedSearchCV, Linear Regressions, Decison Trees, Random Forests, Support Vector Machines and Pipelines to reach our goal
* We'll evaluate the performance of each of our model using RMSE and also tune hyper parameters to further optimize our model
* We'll validate our predictions against our test dataset and conclude our learnings

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib  
**ML Book:** https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291

## Results
The best model we found was the RandomForestRegressor. We obtain the best solution by setting the max_features hyperparameter to 6 and the n_estimators hyperparameter to 100. The RMSE score for this combination is 49,095$.
