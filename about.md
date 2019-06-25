---
layout: page
title: About
---

The final product should
------

* Read EDF files
* Process and filter data from EDF files
* Visualize the processed data and display it in the browser

Difficulties in creating a single product that met the requirements forced us to break it down into two seperate projects

* The main project can read EDF files, and visualize a single signal at a time in the browser. It processes data from EDF files and streams the data , but the signal processing is limited and does not fulfil all the requirements of the project.
* A seperate project can process, filter and visualize a signal. It can only do so with a dynamically generated sine curve as we didn't have time to implement it in the main project.

Tools
------

Python
------
Python is a programming language that has been around for over two decades. 
There are many reasons for picking a programming language over another, but one of the requirements for this project are that it is to be written in python, and hence it shall be written in python.

PyCharm
------
PyCharm is an IDE developed by the company JetBrains, and made specifically for the Python programming language. 
Some of the pros of using PyCharm are that it provides coding assistance and the inspections can be set to follow the PEP 8 style guide which we use. 
It also has a built in version control integration, which makes working with github a breeze.

PipEnv
------
Even though pipenv is only two years old at the time of this writing, it has become the official recommended resource for managing package dependencies. 
In the past, the most common way to do this was combining the use of two tools, a package manager known as 'pip' on one hand, and a tool for managing virtual environments on the other. 
Pipenv simplifies things by combining the functionality of both tools into one, which reduces complexity. There are other great things about pipenv, like automatic documentation of dependencies when they are installed. 
The cherry on top is that the PyCharm has a built in support for pipenv, which reduces complexity.

Scrum
------
We use Scrum to manage our workflow. Scrum is an agile framework with emphasis on software development. 
The team makes backlog items for the product it is developing, and then selects a number of those items that it will be working on during the next two-week period. 
That two-week period is called a sprint and the goal is to have a shippable product at the end of each sprint. In the next sprint the team selects new items to work on, and the product is developed over time. 
The Scrum methodology also includes a number of different roles that are filled with members of the development team and the customer, depending on the role. 
There are also various meetings at set intervals with different purposes, like daily scrum, sprint review, sprint retrospective and so forth. Scrum also makes use of visual tools like burn-down charts to see if the product development is on schedule.

HoloViews
------
HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple. HoloViews allows you to use different plotting backends such as Matplotlib, Plotly and Bokeh. 
HoloViews is great to develop visualization applications as it allows you to get immediate output when you develop within a Jupyter Notebook. Deploying a HoloViews application is also simpler than deploying a pure Bokeh application.

Bokeh
------
Bokeh is an interactive visualization library that targets modern web browsers for presentation. 
Its goal is to provide elegant, concise construction of versatile graphics, and to extend this capability with high-performance interactivity over very large or streaming datasets. 
Bokeh fits our requirements as it works better with large datasets and streaming data than more popular data visualization libraries such as Matplotlib, which is good to make static graphs but performs poorly when working with streaming data in a web browser.

Jupyter Notebook
------
Jupyter Notebook is a web-based interactive computational environment for creating Jupyter notebook documents. Notebook document is a JSON document, following a versioned schema, and containing an ordered list of input/output cells which can contain and run python code. 
When using HoloViews within a notebook document you get instant results when you run a cell, which simplifies the process of developing visualization applications.

Plotting
------

Pyviz docs: http://pyviz.org/
Bokeh docs: https://bokeh.pydata.org/en/latest/
Holoviews docs: http://holoviews.org/
Holoviews Github issues: https://github.com/pyviz/holoviews/issues

