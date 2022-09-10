# QUICK RECAP

## 1. What is Machine Learning ?
Machine learning is a process of extracting data patterns, the data patterns here have 2 types, namely: 
* Features (features): a collection of information about an object. 
* Target ( target ): the actual result / prediction of the feature. 

## 2. ML vs Rule Based System. 
The basic difference between machine learning and a rule based system can be compared to a spam email filter.
The traditional system is based on a set of characteristics that identify emails as spam, which has some drawbacks as spam emails keep changing over time and the system must be upgraded with these adjustments, and this process cannot be carried out due to code maintenance and other issues.
The ML system can be trained with features and targets extracted from the data to produce models that can predict new data. 
In summary, in a rule based system, we need to determine the data (features) and rules (rules) in our program and then generate an answer (target). As for the ML system, we only need to enter data (features) and targets and then generate rules that can be used to predict new data (features). 
From this we get that ML is more flexible than rule based systems.

## 3. Supervised Machine Learning.
SML is a type of machine learning where the data that we will input has features (matrix) and target (vector).
Mathematically it can be formulated as follows: g(X) y. The function g gets input in the form of a matrix X and then produces an output in the form of a vector close to y (the real target).
SML types: 
1. Regression (if the target is a number) 
2. Classification (if the target is a category) has 2 types:
> a. Binary (if the target is only 2 categories)
> b. Multiclass (if the target has more than 2 categories)
3. Ranking (if the target is a score associated with a particular item) is used in building a recommendation system.

## 4. CRISP-DM 
CRISP-DM is a methodology for organizing ML projects. Invented by IBM in the 90s. Steps: 
1. Business understanding: understand whether the project really requires ML. 
2. Understanding data (data understanding): analyze the data owned, whether it is enough to create an ML model or need additional data. 
3. Data preparation: cleans and prepares data so that it can be used to build ML models.
4. Modeling: build and train several models and then choose the best. 
5. Evaluation: measuring how well the performance of the model that we have built.
6. Deployment (deployment): deploy the final result for use by the user (user). 
Sometimes evaluation and deployment are done simultaneously.

