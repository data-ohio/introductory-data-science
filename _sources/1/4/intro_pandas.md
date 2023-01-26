(sec:intro_pandas)=
# Introduction to Pandas

As mentioned in the introduction in {ref}`sec:languagelibraries`, the `datascience` library is designed as an educational tool, to help students learn data science concepts.
The text  [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text` uses this library.
As much as possible, we use this text for our readings, but it does not have everything that we need.

Out in the real world, the
[Pandas](https://pandas.pydata.org/) python data analysis library is used instead. 
Consequently, the other texts we use are based on `pandas`, as are plotting libraries and other libraries that we will need.
So:
* You will need to know how to convert a `datascience.Table` into a `pandas` object so that other libraries can use it.
* You will need to know enough `pandas` to understand the readings that use it.

The `datascience` library includes conversion methods:
* [Table.from_df](http://www.data8.org/datascience/_autosummary/datascience.tables.Table.from_df.html#datascience.tables.Table.from_df)  converts a `pandas.DataFrame` into a `datascience.Table`, as in `tbl=Table.from_df(df)`. 	
* [Table.to_df](http://www.data8.org/datascience/_autosummary/datascience.tables.Table.to_df.html#datascience.tables.Table.to_df) converts a `datascience.Table` into a `pandas.DataFrame`, as in `df=tbl.to_df()`.


You can load `pandas` into a python session with

    import pandas as pd
	
Our readings are from [Learning Data Science](http://www.textbook.ds100.org/) {cite}`DATA100text` and mostly teach us how to use `pandas` to do the things we already learned to do with `datascience` in {numref}`sec:organize`.
- [6. Working With Dataframes Using pandas](http://www.textbook.ds100.org/ch/06/pandas_intro.html)
  * [6.1. Subsetting](http://www.textbook.ds100.org/ch/06/pandas_subsetting.html)
  * [6.2. Aggregating](http://www.textbook.ds100.org/ch/06/pandas_aggregating.html)
  * [6.3. Joining](http://www.textbook.ds100.org/ch/06/pandas_joining.html)
  * [6.4. Transforming](http://www.textbook.ds100.org/ch/06/pandas_transforming.html)


```{admonition} Reading Questions
:class: important
* If `mydata` is a `datascience` `Table`, then we have learned the following methods:
  * `mydata.column("Name")`
  * `mydata.relabeled("Name","name")`
  * `mydata.with_column("Age",agearray)`
  * `mydata.select("Name","Favorite Color")`
  * `mydata.drop("Hometown")`
  * `mydata.sort("Age")`
  * `mydata.where("Age",are_above(30))`
  * `mydata.apply(abs,"Age")`
  * `mydata.group("Hometown")`
  * `mydata.join("Hometown",stateindex,"City")`
  
  Now suppose `mydata` is a `pandas` `DataFrame`. 
  How would you accomplish the same things?
```




```{admonition} Further Resources
* From [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) {cite}`BEUZEN:2021`:
  * [Chapter 7: Introduction to Pandas](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter7-pandas.html)
    * [2. Pandas Series](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter7-pandas.html#pandas-series)
    * [3. Pandas DataFrames](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter7-pandas.html#pandas-dataframes)
	
* From the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) {cite}`VANDER:2016`
  * [3. Data Manipulation with Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)
    * [Introducing Pandas Objects](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html)
    * [Data Indexing and Selection](https://jakevdp.github.io/PythonDataScienceHandbook/03.02-data-indexing-and-selection.html)
	* [Combining Datasets: Concat and Append](https://jakevdp.github.io/PythonDataScienceHandbook/03.06-concat-and-append.html)
	* [Combining Datasets: Merge and Join](https://jakevdp.github.io/PythonDataScienceHandbook/03.07-merge-and-join.html)


* From the [pandas project](https://pandas.pydata.org/):
  * [Getting started tutorials](https://pandas.pydata.org/docs/getting_started/intro_tutorials/)
  * [User Guide](https://pandas.pydata.org/docs/user_guide/index.html#user-guide)
  * [API reference (documentation)](https://pandas.pydata.org/docs/reference/index.html)
```
