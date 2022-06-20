# Introduction to Python

 [Python](https://www.python.org/) is a general-purpose, high-level programming language. It is very popular.

Our first set of readings, from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, introduce the first programming concepts and how one does them in python.
- [3. Programming in Python](https://inferentialthinking.com/chapters/03/programming-in-python.html)
  * [3.1. Expressions](https://inferentialthinking.com/chapters/03/1/Expressions.html)
  * [3.2. Names](https://inferentialthinking.com/chapters/03/2/Names.html)
  * [3.3. Call Expressions](https://inferentialthinking.com/chapters/03/3/Calls.html)
	  %	* (Not section 3.4.)
- [4. Data Types](https://inferentialthinking.com/chapters/04/Data_Types.html)
  * [4.1. Numbers](https://inferentialthinking.com/chapters/04/1/Numbers.html)
  * [4.2. Strings](https://inferentialthinking.com/chapters/04/2/Strings.html)
  * [4.3. Comparisons](https://inferentialthinking.com/chapters/04/3/Comparison.html)


```{admonition} Reading Question
:class: important
* What is the difference between `2`, `"2"`, `two`, and `"two"`? 
```

Our second set of readings is also from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, and introduces sequence and table data types.
The examples here use the python `datascience` library, which was created for the [DATA 8 The Foundations of Data Science](http://data8.org/) course at the University of California at Berkeley. 
> The datascience package is an open source Python package that helps make programming more accessible to all students, regardless of background. As a pedagogical aid, the package is designed to help students more intuitively conduct data science techniques without first spending considerable time directly learning more complex tools such as pandas or matplotlib. At Berkeley, these other packages are introduced in further upper-division coursework such as Data 100.
> 
> [source](http://data8.org/zero-to-data-8/datascience.html)

If you want to try the examples in these readings, first do

    from datascience import *

In {numref}`sec:intro_pandas` we will learn about the more complex and more powerful `pandas` library.
- [3. Programming in Python](https://inferentialthinking.com/chapters/03/programming-in-python.html)
  * [3.4. Introduction to Tables](https://inferentialthinking.com/chapters/03/4/Introduction_to_Tables.html)
- [5. Sequences](https://inferentialthinking.com/chapters/05/Sequences.html)
  * [5.1. Arrays](https://inferentialthinking.com/chapters/05/1/Arrays.html)
  * [5.2. Ranges](https://inferentialthinking.com/chapters/05/2/Ranges.html)
  * [5.3. More on Arrays](https://inferentialthinking.com/chapters/05/3/More_on_Arrays.html)
	
```{admonition} Reading Question
:class: important
* How would you use `np.arange` to create `array([ 1.5,  1. ,  0.5,  0. , -0.5])`?
```

## Further resources

* From [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) {cite}`BEUZEN:2021`:
  * [Chapter 1: Python Basics](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html)
    * [2. Basic Python Data Types](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#basic-python-data-types)
    * [3. Lists and Tuples](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#lists-and-tuples)
    * [4. String Methods](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#string-methods)
    * [5. Dictionaries](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#dictionaries)
    * [6. Empties](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#empties)
    * [7. Conditionals](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter1-basics.html#conditionals)
  * [Chapter 2: Loops & Functions](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html)
    * [1. for Loops](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html#for-loops)
    * [2. while loops](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html#while-loops)
    * [3. Comprehensions](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html#comprehensions)
    * [5. Functions](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html#functions)
  * [Chapter 5: Introduction to NumPy](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter5-numpy.html)
    * [2. NumPy Arrays](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter5-numpy.html#numpy-arrays)
    * [3. Array Operations and Broadcasting](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter5-numpy.html#array-operations-and-broadcasting)
    * [4. Indexing and slicing](https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter5-numpy.html#indexing-and-slicing)

* From [python.org](https://www.python.org/):
  * [Python for Beginners](https://www.python.org/about/gettingstarted/)
  * [The Python Tutorial](https://docs.python.org/3/tutorial/)
  * [Python Documentation](https://docs.python.org/3/)
  
