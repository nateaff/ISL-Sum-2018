# Preparation:

* Install [R](https://www.r-project.org/) and [Rstudio](https://www.rstudio.com/products/rstudio/download/)
* Watch the _Orientation_ video from [Datacamp's introduction to Rstudio](https://www.datacamp.com/courses/working-with-the-rstudio-ide-part-1)

----------------

# Notes:
Exercise number is followed by the subject or name of the dataset used in (parentheses).

The **Labs** and lab lectures can be read/viewed as needed for completing the exercises or clarifying how specific methods are used in R.

[Here is a link to videos and slides for each chapter](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/) (Length of each lecture is in parentheses)


Suggested time distribution for weekly tasks:

| Time   |  Activity   |
|--------|-------------|
| 1.5  	  | Lecture Videos     |
| 1.5     | Datacamp or Supplementary Tutorials			|
| 2 	 	  | Reading Slides/Textbook 			|
| 10 		  | Labs/Assignments 			|
| 5       | Tutoring/Lecture	|


------
# Week 1: Introduction

## Chapter 1: Introduction
* Opening Remarks and Examples (18:18)
* Supervised and Unsupervised Learning (12:12)

## Chapter 2: Statistical Learning
* Statistical Learning and Regression (11:41)
* Curse of Dimensionality and Parametric Models (11:40)
* Assessing Model Accuracy and Bias-Variance Trade-off (10:04)
* Classification Problems and K-Nearest Neighbors (15:37)
* Lab: Introduction to R (14:12)


### Datacamp:
* [Intro to R basics](https://www.datacamp.com/courses/free-introduction-to-r)
* [Vectors, Matrices](https://www.datacamp.com/courses/free-introduction-to-r)

## Exercises:
### Conceptual:
1, 2, 4, 5, 7

### Applied:
9 (Auto), 8 (College)

<!-- ----------------
## Tutoring :
1. Introdution to R studio and R
   Overview of organization of book
2. Using Rmarkdown and an Rmarkdown Template
3. Exercises and Lab -->

-------
# Week 2: Linear Regression

## Chapter 3: Linear Regression (slides, playlist)
* Simple Linear Regression and Confidence Intervals (13:01)
* Hypothesis Testing (8:24)
* Multiple Linear Regression and Interpreting Regression Coefficients (15:38)
* Model Selection and Qualitative Predictors (14:51)
* Interactions and Nonlinearity (14:16)
* Lab: Linear Regression (22:10)

### Datacamp: [Factors, Dataframes](https://www.datacamp.com/courses/free-introduction-to-r)

## Exercises:
Conceptual
1, 2, 3, 4

Applied:
8. (Auto)
9. (Auto)
13. (Simulation)

<!--
## Tutoring :
1. Lab/Datacamp related R tutorial
2. Linear model basics
3. Help with exercises and lab -->

--------

# Week 3: Introduction to Classification

## Chapter 4: Classification (slides, playlist)
*	Introduction to Classification (10:25)
*	Logistic Regression and Maximum Likelihood (9:07)
*	Multivariate Logistic Regression and Confounding (9:53)
* ~~Case-Control Sampling and Multiclass Logistic Regression (7:28)~~
*	Linear Discriminant Analysis and Bayes Theorem (7:12)    		
*	Univariate Linear Discriminant Analysis (7:37)  				
* ~~Multivariate Linear Discriminant Analysis and ROC Curves (17:42)~~
* Quadratic Discriminant Analysis and Naive Bayes (10:07)
* Lab: Logistic Regression (10:14)
* Lab: Linear Discriminant Analysis (8:22)
* Lab: K-Nearest Neighbors (5:01)



## Exercises:

###  Conceptual
1, 6, 8, 9


### Applied:
10. (Weekly)
12. (Write a function)
13. (Boston -- Choose at least two models)

<!--
## Tutoring :
1. Logistic Regression
2. Exercises, Interpreting logistic regression
3. Lab -->
--------

# Week 4:  Resampling and Cross-validation

## Chapter 5: Resampling Methods (slides, playlist)
* Estimating Prediction Error and Validation Set Approach (14:01)
* K-fold Cross-Validation (13:33)
* Cross-Validation: The Right and Wrong Ways (10:07)
* The Bootstrap (11:29)
* More on the Bootstrap (14:35)
* Lab: Cross-Validation (11:21)
* Lab: The Bootstrap (7:40)

### Datacamp: [Lists](https://www.datacamp.com/courses/free-introduction-to-r)

## Exercises:
### Conceptual:
3. (K-fold cross-validation)
4. (Bootstrap)

### Applied:
5. (Default, Logistic Regression and Cross-validation)
7. (Weekly, LOOCV loop)

--------

# Week 5: Model Selection and Regularization

## Chapter 6: Linear Model Selection and Regularization (slides, playlist)
* Linear Model Selection and Best Subset Selection (13:44)
* Forward Stepwise Selection (12:26)
* Backward Stepwise Selection (5:26)
* Estimating Test Error Using Mallow’s Cp, AIC, BIC, Adjusted R-squared * (14:06)
* Estimating Test Error Using Cross-Validation (8:43)
* Shrinkage Methods and Ridge Regression (12:37)
* The Lasso (15:21)													
* Tuning Parameter Selection for Ridge Regression and Lasso (5:27)  
* ~~Dimension Reduction (4:45)~~
* ~~Principal Components Regression and Partial Least Squares (15:48)~~
* ~~Lab: Best Subset Selection (10:36)~~
* Lab: Forward Stepwise Selection and Model Selection Using Validation Set (10:32)
* Lab: Model Selection Using Cross-Validation (5:32)
* ~~Lab: Ridge Regression and Lasso (16:34)~~

### Datacamp: Rmarkdown

## Exercises:
### Conceptual
1. (Subset selection)
2. (Lasso) (skip 2c.)

### Applied
8. (Simulated, subset selection)
10. (Simulated, train vs. test error)

--------

# Week 6: Decision Trees and Random Forest

## Chapter 8: Tree-Based Methods (slides, playlist)
* Decision Trees (14:37)
* Pruning a Decision Tree (11:45)
* Classification Trees and Comparison with Linear Models (11:00)
* Bootstrap Aggregation (Bagging) and Random Forests (13:45)
* Boosting and Variable Importance (12:03)
* Lab: Decision Trees (10:13)
* Lab: Random Forests and Boosting (15:35)


## Exercises:
### Conceptual
4. (Trees)
5. (Random Forest)

### Applied
7. (Boston, Random Forests)
9. (OJ, Trees)

### Project:
* Write up proposal for project
	* What data will be used?
	* What is the provenance of the data?
	* What questions do you want to answer?
	* What are the predictors and response variables?

--------

# Week 7:

## Chapter 10: Unsupervised Learning (slides, playlist)
*	~~Unsupervised Learning and Principal Components Analysis (12:37)~~
* ~~Exploring Principal Components Analysis and Proportion of Variance Explained (17:39)~~
*	K-means Clustering (17:17)
*	Hierarchical Clustering (14:45)
*	Breast Cancer Example of Hierarchical Clustering (9:24)
*	~~Lab: Principal Components Analysis (6:28)~~
*	Lab: K-means Clustering (6:31)
*	Lab: Hierarchical Clustering (6:33)"

## Exercises:
### Conceptual
2. (Hierarchical Clustering)
3. (Manual Kmeans)

### Applied
9. (USArrests, Hierarchical Clustering)

### Project
* Begin analysis
* Create exploratory plot
* Specify models, analyses that will be done

--------

## Week 8: Project and Presentation

### Project:
* Continue work on project
