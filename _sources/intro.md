# Introduction

> Introductory Data Science (IDS) is an emerging field that uses methods from statistics, mathematics, and computer science to find and communicate meaning in data. Due to the rapidly increasing role of data in commerce and science, data science has gained wide attention in a relatively short amount of time in the private sector, government, and academia. In the private sector, job advertisements for data scientists have proliferated. 
> ....
>
> The goal of this course is not to transform each student into a data scientist, but to give the student a sense of data literacy. That is, the ability to collect, analyze and derive meaningful information from data. This course does not require prior mathematical, statistical, or programming skills. 
>....
>
> Topic Areas:
> 1. Curation of Data – Data management and curation is a first step in IDS. This includes acquiring data from diverse formats and structures, cleaning data to prepare for data analysis and maintaining and sharing data files in a version control system.
> 2. Enhanced Data Visualization – Statistics and IDS often tell a story of data through informative pictures. Enhanced data visualizations go beyond the common graphs in introductory statistics to describe, explore and communicate insights from data.
> 3. Statistical Models, Estimation, and Prediction – Determining a functional relationship between numerical data and numerical/categorical data is at the center of statistical modeling in IDS. The focus is on using statistical models to describe relationships between variables, discerning between modeling for predictions and modeling for inference, and fitting, evaluating, and interpreting statistical models. Students familiar with statistical inference from introductory statistics are unavoidably sheltered from the mathematical rigor behind each hypothesis test. Simulation based probability and inference provides straightforward methods to make decisions with data without working through the mathematical details that underlie traditional statistical inference. The quality of a prediction model in terms of being able to forecast an expected outcome is measured through a loss function.
> 4. Applications of Data Science – Machine learning and statistical learning. Machine learning is the process of developing computer algorithms to search for and recognize patterns in data. Statistical learning additionally uses the expertise of a human analyst to craft appropriate models. There are two branches in machine/statistical learning: supervised learning and unsupervised learning.
> 5. Consumer of Data Science – The importance of ethical data science practice is critical to the validity of results in any IDS course. This includes problem-solving and the use of ‘big data’ which can accentuate cultural biases and differences and discussion of issues involving privacy, data security and societal impact.
>
> {cite}`TMM026`

## About this book

This book is designed to satisfy [TMM026-Introductory Data Science](https://www.ohiohighered.org/sites/default/files/uploads/transfer/policy/Introductory%20to%20Data%20Science%20Learning%20Outcomes%20%2812.3.21%29.pdf) {cite}`TMM026`, which is the Ohio Department of Higher Education's standard for transferability under [Ohio Transfer 36](https://www.ohiohighered.org/Ohio-Transfer-36).
Each section here corresponds to the Learning Outcome with the same number.
Sections {numref}`%s <sec:3_4_loss>`, {numref}`%s <sec:3_5_diagnostics>`, {numref}`%s <sec:3_6_estimation>`, and {numref}`%s <sec:4_4_sentiment>` are considered optional under TMM026 and are marked with a * in their title. 

We use [Python](https://www.python.org/) as the programming language, but do not assume the reader has any prior knowledge of Python or any programming experience.
Some of the suggested readings contain examples using the [R](https://www.r-project.org/) language, but the reader does not need to understand how those work.


Typically, someone writes a book because either
* they think they have something new and important to say, or
* they think they can explain better than existing books.

Neither are true for this book. 
Instead, the goal is to organize existing high-quality materials to support a course satisfying TMM026.
We rely on publicly available material from several sources and
would like to particularly acknowledge {cite}`DATA8text,DATA100text,BA-KA-HO:2021`.

## What is Data Science and why should you care about it?

As stated above, others have already exlained this well, so:

Readings:
* From [Computational and Inferential Thinking](https://inferentialthinking.com/chapters/intro.html) {cite}`DATA8text`:
  * [1. What is Data Science?](https://inferentialthinking.com/chapters/01/what-is-data-science.html)
    * [1.1. Chapter 1: Introduction](https://inferentialthinking.com/chapters/01/1/intro.html)
	* [1.2. Why Data Science?](https://inferentialthinking.com/chapters/01/2/why-data-science.html)
* From [Principles and Techniques of Data Science](http://www.textbook.ds100.org/intro.html) {cite}`DATA100text`:
  * [1. The Data Science Lifecycle](http://www.textbook.ds100.org/ch/01/lifecycle_intro.html)
    * [1.1. Asking a Question](http://www.textbook.ds100.org/ch/01/lifecycle_question.html)
	* [1.2. Obtaining Data](http://www.textbook.ds100.org/ch/01/lifecycle_obtain.html)
	* [1.3. Understanding the Data](http://www.textbook.ds100.org/ch/01/lifecycle_data.html)
	* [1.4. Understanding the World](http://www.textbook.ds100.org/ch/01/lifecycle_world.html)

## Acknowledgements

* Shadrack Afful Mensah contributed by evaluating material from {cite}`BEUZEN:2021` and {cite}`DATA100text` for inclusion.

## Bibliography
```{bibliography}
```
