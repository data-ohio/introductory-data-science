(sec:more_python)=
# More Python

This section continues {numref}`sec:intro_python` {ref}`sec:intro_python`,
with emphasis on python tools for cleaning data.

Our first readings, from [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`, are repeated from {numref}`sec:organize`.
They remind us how to define a function in python and how to apply a function to each entry in a column.
* [8. Functions and Tables](https://inferentialthinking.com/chapters/08/Functions_and_Tables.html)
  * [8.1. Applying a Function to a Column](https://inferentialthinking.com/chapters/08/1/Applying_a_Function_to_a_Column.html)

Our second readings describe the python string type `str` and some of its methods.
These methods are convenient for cleaning up various things that could be wrong with string entries in data.
* [3.1.2. Strings](https://python.readthedocs.io/en/latest/tutorial/introduction.html#strings)  from the python tutorial
* [4.7 Text Sequence Type — str](https://python.readthedocs.io/en/latest/library/stdtypes.html#text-sequence-type-str) documentation
  * [4.7.1. String Methods](https://python.readthedocs.io/en/latest/library/stdtypes.html#string-methods) In particular, look at
    * `str.lstrip`, `str.rstrip`, and `str.strip`, which can remove unwanted characters such as extra spaces, '$', or '%' from the start or end of a string
	* `str.lower`, `str.upper`, and `str.title`, which can change the case of letters in a string 
	* `str.replace`, which can replace characters in a string
	
```{admonition} Reading Questions
:class: important
* What combination of string methods can convert '$1,000,000' to '1000000'?
* What combination of string methods can convert ' athens, OH' to 'Athens'?
```

Our next readings are two python functions that can convert a string that looks like a number into a number.
* [int](https://python.readthedocs.io/en/latest/library/functions.html#int) converts a string into an integer, so `int('123')` returns `123`.
* [float](https://python.readthedocs.io/en/latest/library/functions.html#float) converts a string into a floating-point number, so `float('123.4')` returns `123.4`

```{admonition} Reading Questions
:class: important
* What will `int('123.4')` return?
* What will `int(123.4)` return?
* What will `float('2/3')` return?
* What will `float(2/3)` return?
```
% `int('123.4')` `float('2/3')` gives error


Our last readings describe the python `set` object. 
Converting a column in a Table to a set (as in `set(tbl.column('label'))` is a convenient way to see all distinct entries in a column.  
* [5.4 Sets](https://python.readthedocs.io/en/latest/tutorial/datastructures.html#sets) from the python tutorial
* [4.9 Set Types](https://python.readthedocs.io/en/latest/library/stdtypes.html#set-types-set-frozenset) documentation

```{admonition} Reading Questions
:class: important
* `'frog' in {'dog','frog'}`?
* `len(set(['a','b','c','a'])) == 4`?
```


```{admonition} Further Resource
See the Further Resources in {numref}`sec:intro_python`. 
```
