(sec:traditional_plots)=
# Traditional Plots

```{admonition} Learning Outcome
:class: tip
Students will be able to classify and summarize data using traditional plots.
````

```{admonition} Sample Tasks:
* Before undertaking any activity, students must answer the following questions:
  * What are you trying to show?
  * Does a trendline, heat map, time series, etc. make sense in this case?
  * Why will one type of graph work better than another?
  * Emphasize that the data and analysis must tell the story, and the charts are a helpful tool to tell the story.
  * State with clarity what you are trying to say.
 
{cite}`TMM026`
```

Our first reading, from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, shows how to do traditional scatter plot and line graphs using the `Table` class in the `datascience` library.
* [7. Visualization](https://inferentialthinking.com/chapters/07/Visualization.html) 
  * Initial material on Scatter Plots and Line Graphs
  * [7.3. Overlaid Graphs](https://inferentialthinking.com/chapters/07/3/Overlaid_Graphs.html) 

```{admonition} Reading Questions
:class: important
* Would it make sense to do `actors.plot('Number of Movies', 'Total Gross')`?
* Can you overlay a scatter plot on a line graph?
```

Our second set of readings, from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text`, walks through examples that use plots to try to understand data.
It runs through examples of several different types of plots and discusses which are appropriate for which purposes.
* [10. Exploratory Data Analysis](http://www.textbook.ds100.org/ch/10/eda_intro.html)
  * [10.1. Feature Types](http://www.textbook.ds100.org/ch/10/eda_feature_types.html)
  * [10.2. What to Look For in a Distribution](http://www.textbook.ds100.org/ch/10/eda_distributions.html)
  * [10.3. What to Look For in a Relationship](http://www.textbook.ds100.org/ch/10/eda_relationships.html)
  * [10.4. Guidelines for Exploration](http://www.textbook.ds100.org/ch/10/eda_guidelines.html)
  * [10.5. Example: Sale Prices for Houses](http://www.textbook.ds100.org/ch/10/eda_example.html)


```{admonition} Reading Questions
:class: important
* What is the coolest type of plot in these readings?
* When should you apply a logarithm transform before plotting?
```
	
## Further Resources
	
### Plotting via Matplotlib

These readings, from the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`, explain how to plot using the `matplotlib` library. 
Matplotlib is a (the?) standard plotting library in python.
Typically you load it in a python session with

    import matplotlib.pyplot as plt
	
The plotting in `pandas` is built on top of `matplotlib`.
* [4. Visualization with Matplotlib](https://jakevdp.github.io/PythonDataScienceHandbook/04.00-introduction-to-matplotlib.html)
  * [Simple Line Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.02-simple-scatter-plots.html)
  * [Simple Scatter Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.02-simple-scatter-plots.html)
  * [Customizing Plot Legends](https://jakevdp.github.io/PythonDataScienceHandbook/04.06-customizing-legends.html)	
  * [Customizing Colorbars](https://jakevdp.github.io/PythonDataScienceHandbook/04.07-customizing-colorbars.html)	
  * [Multiple Subplots](https://jakevdp.github.io/PythonDataScienceHandbook/04.08-multiple-subplots.html)
	
```{admonition} Reading Question
:class: important
* How do you set a label for the y-axis on a plot?
```

* From [matplotlib.org](https://matplotlib.org/):
  * [Tutorials](https://matplotlib.org/stable/tutorials/index.html)
    * [Quick Start](https://matplotlib.org/stable/tutorials/introductory/usage.html)
    * [Pyplot tutorial](https://matplotlib.org/3.5.0/tutorials/introductory/pyplot.html)
  * [Documentation](https://matplotlib.org/stable/index.html)

### Plotting via Seaborn

Seaborn is a plotting library built on top of `matplotlib` to automatically give nice plots for statistical data in pandas dataframes.
Typically you load it in a python session with

    import seaborn as sns

* From [seaborn.pydata.org](https://seaborn.pydata.org/index.html)
  * [Introduction](https://seaborn.pydata.org/introduction.html)
  * [Tutorial](https://seaborn.pydata.org/tutorial.html)
  * [Documentation](https://seaborn.pydata.org/api.html)
