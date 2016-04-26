---
title: Why Python and Jupyter Notebooks?
---
# Why Python and Jupyter Notebooks?

## Jupyter Notebooks

One of the most significant advances in the scientific computing arena is underway with the explosion of interest in Jupyter (formerly, IPython) Notebook technology. The scientific publication *Nature* recently featured [an article on the benefits of Jupyter Notebooks](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261) for scientific research. There are now Jupyter Notebooks on numerous topics in many scientific disciplines.  Here are a few examples of IPython Notebooks for science:

-   [LIGO Gravitational Wave Data](https://losc.ligo.org/s/events/GW150914/GW150914_tutorial.html)
-   Satellite Imagery Analysis ([Part 1](https://github.com/Unidata/blog-notebooks/blob/master/notebooks/Plotting_GINI_Water_Vapor_Imagery_Part1.ipynb), [Part 2](https://github.com/Unidata/blog-notebooks/blob/master/notebooks/Plotting_GINI_Water_Vapor_Imagery_Part2.ipynb))
-   [12 Steps to Navier-Stokes](https://github.com/barbagroup/CFDPython)
-   [Computer Vision](http://nbviewer.jupyter.org/github/ogrisel/notebooks/blob/master/Labeled%2520Faces%2520in%2520the%2520Wild%2520recognition.ipynb)
-   [Machine Learning](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%2520Machine%2520Learning%2520Notebook.ipynb)

The reason for Jupyter's immense success is it excels in a form programming called "literate programming".  Literate programming is a software development style pioneered by Stanford computer scientist, Donald Knuth. This type of programming emphasizes a prose first approach to programming where exposition with human-friendly text is punctuated with code blocks. It excels at demonstration, research, and teaching objectives especially for science. Literate programming allows users to formulate and describe their thoughts with prose, supplemented by mathematical equations, as they prepare to write code blocks. This mindset is the opposite of how we usually think about code. Over the years, we have seen closed-source, for-profit implementations of literate programming with software packages such as Mathematica, and Matlab.

With the clear advantages of literate programming in mind and with the advent of improved web browser technologies (e.g., HTML5), but with a paucity of open-source options, Brian Granger and Fernando Pérez created the IPython (now "Jupyter") Notebooks  web-based technology. Jupyter notebooks are a series of "cells" containing executable code (which was originally Python but later expanded to several other languages) or markdown, the popular HTML markup language for prose descriptions. In addition, there is LaTeX support for mathematical equations via [MathJax](https://www.mathjax.org/), a web browser enhancement for display of mathematics. These notebooks can be saved and shared in `.ipynb` JSON format for easy exchange with other researchers. In addition, they can be committed to version control repositories such as git and the code sharing site github. Also, Jupyter notebooks can be viewed with [nbviewer technology](http://nbviewer.jupyter.org/) which github now supports natively. Moreover, these notebook environments for writing and developing code have many niceties available in typical software development Interactive Development Environments (IDEs) such as code completion and easy access to help. This technology quickly gained popularity and in 2013 the IPython team won a [Sloan Foundation Grant](http://ipython.org/sloan-grant.html). The technology was generalized to allow for programming language "back-ends" to be plugged into the notebooks. "Jupyter" is a loose acronym meaning Julia, Python and R, but today, the technology supports [many programming languages](https://github.com/ipython/ipython/wiki/IPython-kernels-for-other-languages).

## Python and IPython

Before getting into "What is Python?", the advantages of Python were once succinctly summarized by a UCAR scientist:

> I have used a combination of Perl, Fortran, NCL, Matlab, R and others for
> routine research, but found out this general- purpose language, Python, can
> handle almost all in an efficient way from requesting data from remote on-line
> sites to statistics, and graphics.

### What is Python?

Python is a "batteries included" computer programming language. More concretely, Python is a programming language
that, in contrast to other programming languages such as C, Fortran, or Java, allows users to more readily focus and solve domain problems instead of dealing with the complexity of how a computer operates. Python achieves this goal by having the following attributes:

-   Python is a **high-level** language meaning that it abstracts underlying computer-related technical details.  For example, Python does not make its users think too much about computer memory management or proper declaration of variables and uses safe assumptions about what the programmer is trying to convey. In addition, a high-level language can be expressed in a manner closer to English prose or mathematical equations. Python is perfect for literate programming because of its lightweight, "low ceremony" nature.
-   Python is a **general-purpose** language meaning that it can be used for all problems that a computer is capable of rather than specializing in a specific area such as statistical analysis. Python can be used for both artificial intelligence and statistical analysis, for example. It can be used for a variety of heterogeneous tasks within a given work-flow, as the UCAR scientist described earlier.
-   Python is an **interpreted** language meaning that evaluation of code to obtain results can happen immediately rather than having to go through a time-consuming, compile and run cycle, and thereby speeding up the thinking and experimentation process. IPython is an interactive form of the Python language also invented by Fernando Pérez. These environments excel for rapid-prototype of code or simply quickly experimenting with new ideas.
-   Python has a standard library, and numerous third-party libraries yielding a vast array of existing codebases and examples for solving problems.
-   Python has many, many users which means that programmers can quickly find solutions and example code to problems with the help of Google and [Stackoverflow](https://www.stackoverflow.com).

These features, perhaps, come with a minor cost of reduced language performance, but this is a trade-off the vast majority of users are willing to make in order to gain all the advantages Python has to offer.

In addition, Python a rich ecosystem for scientific inquiry in the form of many proven, and popular open-source packages including:

-   [numpy](http://www.numpy.org/), a Python package for scientific computing
-   [matplotlib](http://matplotlib.org/), 2D plotting library which produces publication quality figures
-   [cartopy](http://scitools.org.uk/cartopy/), library providing cartographic tools for Python
-   [netcdf4-python](http://unidata.github.io/netcdf4-python/), a Python interface to the netCDF-C library

In summary, Python's pragmatic focus for getting work done makes it an excellent choice for science students and professionals.
