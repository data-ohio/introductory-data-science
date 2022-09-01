(sec:wrangling)=
# Data Wrangling

The data we collect (as in {numref}`sec:collect_data`) may not be in a usable form. 
It may have errors, missing values, etc. that need to be _cleaned_ before it can be _organized_ (as in {numref}`sec:organize`).
The process of cleaning and organizing data is sometimes called _data wrangling_.

Our readings, from [Principles and Techniques of Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text`, go through this data wrangling process of cleaning and organizing data.
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
* If your data file says that someone's age is 237, what should you do?
* How do you convert `20160513` to the date `2016-05-13`?
```


## Further resources
* From [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) {cite}`BEUZEN:2021`:
  * [Chapter 8: Basic Data Wrangling With Pandas](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html)
    * [1. DataFrame Characteristics](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#dataframe-characteristics)
    * [2. Basic DataFrame Manipulations](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#basic-dataframe-manipulations)
    * [3. DataFrame Reshaping](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#dataframe-reshaping)
    * [4. Working with Multiple DataFrames](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter8-wrangling-basics.html#working-with-multiple-dataframes)

* From the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`
  * [3. Data Manipulation with Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)
    * [Handling Missing Data](https://jakevdp.github.io/PythonDataScienceHandbook/03.04-missing-values.html)
