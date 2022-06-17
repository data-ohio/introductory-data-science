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

* Material from [Python Programming for Data Science](https://www.tomasbeuzen.com/python-programming-for-data-science/README.html) was included as "Further resources" in sections 1.3.1 Introduction to Python and 1.3.2 Introduction to Pandas
  * Should any of it be moved to the main "Readings"? Some is more advanced than needed, at least at that point in the course.
  * There are [practice exercises](https://www.tomasbeuzen.com/python-programming-for-data-science/practice-exercises/chapter1-basics-practice.html#) that could be adapted or used.
* Evaluate and incorporate material from	
  * [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
