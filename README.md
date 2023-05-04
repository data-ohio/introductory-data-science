# Introductory Data Science

... a textbook

See [the posted html version](https://data-ohio.github.io/introductory-data-science/intro.html)

## Collaborator Instructions

### Building the book 

See the [JupyterBook general building instructions](https://jupyterbook.org/en/stable/start/build.html)

From the parent of introductory-data-science, do

    jupyter-book build introductory-data-science
	
To force removal of the previous built version so everything is rebuilt, do

    jupyter-book clean introductory-data-science
	
To check the result, open `introductory-data-science/_build/html/index.html` in a browser.
	
### Publishing to GitHub Pages

See the [JupyterBook general posting instructions](https://jupyterbook.org/en/stable/start/publish.html)

From within introductory-data-science, do

    ghp-import -n -p -f _build/html

### To-Do List

* 2.2 is supposed to have more on the visual effect of outliers.
  It is not clear how to do that since regression has not been covered yet.
* [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) has 
  [practice exercises](https://www.tomasbeuzen.com/python-programming-for-data-science/practice-exercises/chapter1-basics-practice.html#) that could be adapted or used.

