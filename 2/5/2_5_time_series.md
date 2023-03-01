# Time Series Plots

```{admonition} Learning Outcome
:class: tip
Students will be able to develop an analytic model and trendline for a time series, and then predict the last n-tile of data in order to evaluate the effectiveness of their model.
```

```{admonition} Sample Tasks
* Avoid extrapolation
  - Build a model using a weather data set from 1900 to present.
  - Create a scatter plot using rain data and add a trendline.
  - Predict rainfall 1 week and 1 month into future.
  - Verify the accuracy of your model using the actual rainfall.
  - Add the updated data to your chart, and check to see if it falls within a standard deviation of the prediction.
  - Discuss why the prediction for 1 week was more accurate than for 1 month.

{cite}`TMM026`
```

The term [time series](https://en.wikipedia.org/wiki/Time_series) simply means data where time is taken as the independent variable. 
It gets its own name because using data collected over time to predict the future is such an important application.

Our first reading, from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text`, discusses using line plots to visualize time series.
%* [11. Data Visualization](http://www.textbook.ds100.org/ch/11/viz_intro.html)
%  * [11.4. Incorporating the Data Design](http://www.textbook.ds100.org/ch/11/viz_data_design.html)
* [11.4.1. Data Collected over Time](http://www.textbook.ds100.org/ch/11/viz_data_design.html#data-collected-over-time)

```{admonition} Reading Question
:class: important
* In the housing market crash, which percentile of houses did the worst ?
```

Our second reading, from the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`, first discusses tools within the `pandas` library for manipulating times, and then discussed the techniques of resampling, shifting, and windowing to make visualizations of time-series easier to understand. 
* [3. Data Manipulation with Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)
  * [Working with Time Series](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html)

```{admonition} Reading Question
:class: important
* When should one apply a rolling window to a time series?
```
```{admonition} Further Resources
See {numref}`sec:traditional_plots` for information on plotting with Matplotlib and Seaborn.
```

