# Scaling and Standardizing data

When data is going to be used within a statistical model (like we will see in {numref}`Section %s <sec:3_models>`) or for machine learning (like we will see in {numref}`Section %s <sec:4_learning>`) one often first applies a transformation.
The most common transformations are:

* Min-Max scaling: One subtracts the minimum and then divides by the range to obtain data with minimum 0 and maximum 1.
* Standardizing (also called converting to a standard score or a Z-score): One subtracts the mean and then divides by the standard deviation to obtain data with mean 0 and standard deviation 1.

Our readings, from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page), describe these scalings and others.
* [Feature scaling](https://en.wikipedia.org/wiki/Feature_scaling)
* [Standard score](https://en.wikipedia.org/wiki/Standard_score)

```{admonition} Questions
:class: important
* How would you apply Min-Max scaling to a column in a `Table` and add the result as a new column?
* How would you Standardize a column in a `Table` and add the result as a new column?
```
