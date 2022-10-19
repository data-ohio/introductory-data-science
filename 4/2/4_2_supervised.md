(sec:supervised_learning)=
# Supervised Learning

```{admonition} Learning Outcome
:class: tip
Students will be able to classify data using supervised machine learning techniques, search for and define a function that describes how different measured variables are related to one another and utilize predictive techniques such as linear regression.
```

```{admonition} Sample Tasks
* Differentiate between supervised and unsupervised learning.
* Identify, or give an example of, an unsupervised learning technique.
* Identify, or give an example of, a supervised learning technique.
* Classify data using K-nearest neighbors.
* Classify discrete data using the Naive Bayes algorithm.
* Use simple linear regression analysis to predict the value of a response variable based on a given explanatory variable.
* Interpret the y-intercept and make inferences about the slope of a simple linear regression equation.
* Evaluate the assumptions of regression analysis and know what to do if the assumptions are violated.
* Interpret the correlation coefficient.
* Describe the purpose of multiple linear regression.
* Input variable information and data for multiple linear regression.
* Describe and discern the data assumptions required for multiple linear regression.
* Interpret scatterplots and probability plots concerning the data assumptions for multiple linear regression.
* Write a prediction equation and make predictions based on a multiple linear regression model.
* Use a command such as lm() in R to perform multiple linear regression.
* Use logistic regression to describe the relationship between an explanatory variable and a dichotomous response variable.
* Compare and contrast logistic regression and ordinary least squares regression.
* Fit a logistic model and use the model to estimate the odds from a single probability.
* Describe the statistical model of logistic regression with a single explanatory variable.
* Identify the estimates of the regression parameters and write the equation for a fitted model.
* For a given logistic model, compute and interpret the threshold value.
* Use a command such as glm() in R to perform logistic regression.

{cite}`TMM026`
```
Our first readings, from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, explain the simplest statistical learning model of fitting a line to show the relationship between two features.
* [15. Prediction](https://inferentialthinking.com/chapters/15/Prediction.html)
  * [15.1. Correlation](https://inferentialthinking.com/chapters/15/1/Correlation.html)
  * [15.2. The Regression Line](https://inferentialthinking.com/chapters/15/2/Regression_Line.html)
  * [15.3. The Method of Least Squares](https://inferentialthinking.com/chapters/15/3/Method_of_Least_Squares.html)
  * [15.4. Least Squares Regression](https://inferentialthinking.com/chapters/15/4/Least_Squares_Regression.html)
  * [15.5. Visual Diagnostics](https://inferentialthinking.com/chapters/15/5/Visual_Diagnostics.html)
  * [15.6. Numerical Diagnostics](https://inferentialthinking.com/chapters/15/6/Numerical_Diagnostics.html)
	
```{admonition} Reading Questions
:class: important
* How do you calculate a *correlation coefficient*?
* Why is it called *least squares*?
```	
```{admonition} Thinking Question
:class: important
* How would an outlier affect the regression line?
```	

Our second readings, also from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, explain the simplest machine learning algorithm for classification.
* [17. Classification](https://inferentialthinking.com/chapters/17/Classification.html)
  * [17.1. Nearest Neighbors](https://inferentialthinking.com/chapters/17/1/Nearest_Neighbors.html)
  * [17.2. Training and Testing](https://inferentialthinking.com/chapters/17/2/Training_and_Testing.html)
  * [17.3. Rows of Tables](https://inferentialthinking.com/chapters/17/3/Rows_of_Tables.html)
  * [17.4. Implementing the Classifier](https://inferentialthinking.com/chapters/17/4/Implementing_the_Classifier.html)
  * [17.5. The Accuracy of the Classifier](https://inferentialthinking.com/chapters/17/5/Accuracy_of_the_Classifier.html)
  * [17.6. Multiple Regression](https://inferentialthinking.com/chapters/17/6/Multiple_Regression.html)

```{admonition} Reading Questions
:class: important
* What is the *k* in *k-nearest neighbors*?
* What is the difference between an *attribute* and a *feature*?
* How do you measure the accuracy of a classifier?
```	


```{admonition} Further Resource
This reading, from [5. Machine Learning](https://jakevdp.github.io/PythonDataScienceHandbook/05.00-machine-learning.html) in the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`, goes deeper into linear regression.
* [In Depth: Linear Regression](https://jakevdp.github.io/PythonDataScienceHandbook/05.06-linear-regression.html)  
```

```{admonition} Further Resource
These extra readings from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text` use Calculus and Linear Algebra concepts that are not expected for readers of this book.
* [15. Linear Models](http://www.textbook.ds100.org/ch/15/linear_intro.html)
  * [15.1. Simple Linear Model](http://www.textbook.ds100.org/ch/15/linear_simple.html)
  * [15.2. Fitting the Simple Linear Model](http://www.textbook.ds100.org/ch/15/linear_simple_fit.html)
  * [15.3. Multiple Linear Model](http://www.textbook.ds100.org/ch/15/linear_multi.html)
  * [15.4. Fitting the Multiple Linear Model](http://www.textbook.ds100.org/ch/15/linear_multi_fit.html)
  * [15.5. Feature Engineering](http://www.textbook.ds100.org/ch/15/linear_feature_eng.html)
```
