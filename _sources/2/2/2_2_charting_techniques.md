(sec:visualize_single_vs_two)=
# Single vs. Two or More Variables

```{admonition} Learning Outcome
:class: tip
Students will be able to select appropriate charting techniques based on the type of data and the number of variables they intend to present.
```

```{admonition} Sample Tasks
* Discuss differences between numerical and categorical data.
  - What types of charts are appropriate for numerical data?
  - What types of charts are appropriate for categorical data?
* Effects of outliers
  - Explain the difference between an explanatory variable and a response variable.
  - Generate a general hypothesis about the relationship between two variables.
  - Construct a scatter plot using a large data set containing 1000+ points.
  - Confirm that a trendline is appropriate for the data.
  - Build a linear model using the trendline.
  - Examine the outliers and decide if they should be included in the model.
  - If appropriate, remove the outliers, adjust model, plot a new trendline, and build a new model.
  - Compare the two plots, trendlines, and models.
  - Summarize the effects of the outliers on the response variable.
  
{cite}`TMM026`
```

Our first set of readings, from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, show how to use bar charts for categorical data and histograms for numerical data. 
Such charts are applied to a single column of data, and so illustrate the behavior of 1 variable.
%These are based on the `Table` class within the `datascience` library.
* [7. Visualization](https://inferentialthinking.com/chapters/07/Visualization.html) 
  * [7.1. Visualizing Categorical Distributions](https://inferentialthinking.com/chapters/07/1/Visualizing_Categorical_Distributions.html)
  * [7.2. Visualizing Numerical Distributions](https://inferentialthinking.com/chapters/07/2/Visualizing_Numerical_Distributions.html)
  * [7.3. Overlaid Graphs](https://inferentialthinking.com/chapters/07/3/Overlaid_Graphs.html)


```{admonition} Reading Questions
:class: important
* What is the *area principle* for visualizations?
* What makes a histogram different from a bar chart?
```

Our second set of readings are from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text` and are repeated from {numref}`sec:traditional_plots`. 
* The first of these also considers visualizing the behavior of 1 variable:
  * [10.2. What to Look For in a Distribution](http://www.textbook.ds100.org/ch/10/eda_distributions.html)
* The second of these considers visualizing the relationship between 2 variables:
  * [10.3. What to Look For in a Relationship](http://www.textbook.ds100.org/ch/10/eda_relationships.html)
  
```{admonition} Reading Questions
:class: important
* What is a rug plot?
* What is the difference between a histogram and a density plot?
* How can you illustrate the relationship between a categorical feature and a numerical feature?
```

```{admonition} Further Resources
See {numref}`sec:traditional_plots` for information on plotting with Matplotlib and Seaborn.
```
