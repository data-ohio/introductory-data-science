(sec:wrangling)=
# Data Wrangling

The data we collect (as in {numref}`sec:collect_data`) may not be in a usable form. 
It may have errors, missing values, etc. that need to be _cleaned_ before it can be _organized_ (as in {numref}`sec:organize`).
The process of cleaning and organizing data is sometimes called _data wrangling_.

Our first reading, from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text`, goes through this data wrangling process of cleaning and organizing data.
* [9. Wrangling Dataframes](http://www.textbook.ds100.org/ch/09/wrangling_intro.html)
  * [9.1. Example: Wrangling CO2 Measurements from Mauna Loa Observatory](http://www.textbook.ds100.org/ch/09/wrangling_co2.html)
  * [9.2. Quality Checks](http://www.textbook.ds100.org/ch/09/wrangling_checks.html)
  * [9.3. Missing Values and Records](http://www.textbook.ds100.org/ch/09/wrangling_missing.html)
  * [9.4. Transformations and Timestamps](http://www.textbook.ds100.org/ch/09/wrangling_transformations.html)
  * [9.5. Modifying Structure](http://www.textbook.ds100.org/ch/09/wrangling_structure.html)
  * [9.6. Example: Wrangling Restaurant Safety Violations](http://www.textbook.ds100.org/ch/09/wrangling_restaurants.html)

```{admonition} Reading Questions
:class: important
* If one bit of data is missing from a row (say, a person's age), what can you do about it?
* What is imputation?
```

Our second set of readings are about *outliers*, which are points in the data that seem much different from the rest.
* From [Wikipedia](https://en.wikipedia.org/wiki/Main_Page), a general description of an [Outlier](https://en.wikipedia.org/wiki/Outlier)
* From [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`:
  * [7. Visualization](https://inferentialthinking.com/chapters/07/Visualization.html) section **Scatter Plots** gives an example where the average gross income per movie of one actor is exceptionally high.
  * [15.1.7. Correlation is Affected by Outliers](https://inferentialthinking.com/chapters/15/1/Correlation.html#correlation-is-affected-by-outliers) shows how correlation (which we will see in {numref}`sec:3_models`) can be affected by outliers.
* From [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text`:
  * [10.3.2. One Qualitative and One Quantitative Variable](https://learningds.org/ch/10/eda_relationships.html#one-qualitative-and-one-quantitative-variable) illustrates how (suspected) outliers are shown as dots on bax plots.
  * [11.1.1. Filling the Data Region](https://learningds.org/ch/11/viz_scale.html#filling-the-data-region) illustrates how treating outliers separately yields better visualizations.
  * [18.2. Wrangling and Transforming](https://learningds.org/ch/18/donkey_clean.html) shows how to remove outliers (outlying donkeys) in preparation for modeling the relationships between variables.
  

```{admonition} Reading Questions
:class: important
* If your data file says that someone's age is 237, what should you do?
* If your data file says that someone's income is 100 times the next largest income, what should you do?
* What is so special about C-3PO?
```

```{admonition} Further Resources
* From [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) {cite}`BEUZEN:2021`:
  * [Chapter 8: Basic Data Wrangling With Pandas](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html)
    * [1. DataFrame Characteristics](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#dataframe-characteristics)
    * [2. Basic DataFrame Manipulations](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#basic-dataframe-manipulations)
    * [3. DataFrame Reshaping](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#dataframe-reshaping)
    * [4. Working with Multiple DataFrames](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#working-with-multiple-dataframes)

* From the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`
  * [3. Data Manipulation with Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)
    * [Handling Missing Data](https://jakevdp.github.io/PythonDataScienceHandbook/03.04-missing-values.html)
```
