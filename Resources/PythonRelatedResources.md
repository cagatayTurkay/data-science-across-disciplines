# On Python and Python related resources

![image-20200930114332193](/Users/cagatayturkay/Library/Application Support/typora-user-images/image-20200930114332193.png)

### Why Python?

Python (https://www.python.org/) is a widely used general-purpose, high-level programming language.  Python supports multiple programming paradigms, including  object-oriented, imperative and functional programming or procedural  styles. It is both powerful, simple, flexible, and extendible.

We will be using one of the latest version of the language which is  3.8. Python has an extensive standard library which provides lots of  functionality. What makes Python more powerful is the collection of  packages that are contributed by many around the world. [PyPi](https://pypi.python.org/pypi) is the place to get access to many of these packages.

What makes Python suitable for data science applications is the great libraries it is equipped with. It has gained popularity in scientific  computing and data analysis due to these libraries. A number of very  important packages are as follows:

**Scipy:** [SciPy](http://scipy.org/) contains modules for optimization, linear algebra, statistics,  specialised mathematics, integration, interpolation, signal and image  processing, and other tasks common in science and engineering. We will  make use of a number Scipy functions whenever we need the functionality.

**Numpy:** [Numpy](http://www.numpy.org/) adds support for large, multi-dimensional arrays and matrices, along  with a large library of high-level mathematical functions to operate on  these arrays. It is highly efficient to make basic data operations with  Numpy, we will mostly use it to subset data, make basic mathematical  calculations, etc.

**Pandas:** [Pandas](http://pandas.pydata.org/) is a Python library to enhance data manipulation and analysis. It is  great for data wrangling, merging, basic analytical tasks with tabular  datasets and time series. It is Python's answer to statistical  computation package R.

**Scikit-learn:** [Scikit-learn](http://scikit-learn.org/stable/) is a package that will provide us basic machine learning capability and supports tasks like regression, classification, clustering, dimension  reduction, etc.

**Statsmodels:** [Statsmodels](http://statsmodels.sourceforge.net/) will help us to estimate statistical models, and perform statistical  tests. An extensive list of descriptive statistics, statistical tests,  plotting functions, and result statistics are available for different  types of data and each estimator.

**Matplotlib:** [Matplotlib](http://matplotlib.org/) will provide us basic plotting and visualising functionality to have a quick look at our data and results.

**Seaborn:** [Seaborn](https://seaborn.pydata.org/) emerged as a highly popular plotting library that works reasonably well with Pandas data formats. It offers a range of plots and easy to adapt examples.

**Altair:** [Altair](https://altair-viz.github.io/index.html) is gaining increasing popularity as the most versatile visualisation library for Python. It sits on the shoulder of a visualisation specification language called [Vega-Lite](http://vega.github.io/vega-lite/). It is possible to build complex interactive plots with it and also share over the web.

Normally Python do not come with these packages and you need to download and [install these packages yourself.](https://docs.python.org/3.4/install/) This process is usually straightforward but might be tricky at times.  Luckily, there is a strong Python community that generates easy to  install packages that are available for download, a [very good repository is here](http://www.lfd.uci.edu/~gohlke/pythonlibs/). But remember that you need to be careful which Python version you are using.

In this module, we get around the burden of all these installations by using a pre-packaged Python environment called [Anaconda](https://www.anaconda.com/download/). What comes with Anaconda is the standard Python distribution and most  of the necessary packages for data analysis. If you need to read more,  the [Anaconda documentation](https://docs.continuum.io/anaconda/) pages are a good start.

## Python related resources:

Although we try to cover the basics in Python programming in this  tutorial, some of you, especially those who are new to Python, might  benefit from some external tutorials which cover the basics. There are  many resources online but here are some good links:

- **codecademy** has a free tutorial: http://www.codecademy.com/en/tracks/python
- **Wikibooks for Python**: [http://en.wikibooks.org/wiki/Non-Programmer%27s_Tutorial_for_Python_3](http://en.wikibooks.org/wiki/Non-Programmer's_Tutorial_for_Python_3)
- **Learnpython** even has an interactive console on the web: http://www.learnpython.org/

### Textbooks

As textbooks for the coding side these two resources are really good:

- **Python for Data Analysis by Wes McKinney** (the original author of Pandas) [[link to the e-book on library](http://encore.lib.warwick.ac.uk/iii/encore/record/C__Rb3473202)] [1st edition of the book is free to download from the [pandas page](https://pandas.pydata.org/)]
  - This book is great for supporting most DS processes where you would be carrying out through Pandas. It doesn't go into more Machine Learning or Data Mining kind of modelling topics. But it goes into some advanced topics such as Time Series analysis and points to libraries such as statsmodels and scikit-learn as a move into modelling. And see the last chapters for some examples
-  **Python Data Science Handbook by Jake VanderPlas** [[link to the html version](https://jakevdp.github.io/PythonDataScienceHandbook/)] and all the [associated material is here](https://github.com/jakevdp/PythonDataScienceHandbook) on a GitHub repository
  - This book goes much further into more Machine Learning heavy operations and covers topics that are not covered in the first book. For instance, there is a detailed overview on how you can [work with PCA](https://jakevdp.github.io/PythonDataScienceHandbook/05.09-principal-component-analysis.html) and the chapters are written nicely and there is always code to complement them. It is however not so detailed on exploratory data analysis phase as the first book and do not always make great use of Pandas functionality.  

So you can use these two books in a complementary way to support your learning within the coding labs. 

And here are some further books that can help you with your learning.

- **Data science from scratch : first principles with Python** **/ Joel Grus** -- http://encore.lib.warwick.ac.uk/iii/encore/record/C__Rb3426067
  - Especially Chapter 2: A Crash course in Python to help with the preparations -- https://ebookcentral.proquest.com/lib/warw/reader.action?docID=5750897&ppg=33

- Hunt, J., 2019. *A Beginners Guide to Python 3 Programming*. Springer. http://encore.lib.warwick.ac.uk/iii/encore/record/C__Rb3404588


### Online APIs and documentations

You will hear us mentioning the importance of using online resources and library documentations. For instance, for scikit-learn, I start with the  [User Guide](https://scikit-learn.org/stable/user_guide.html) or the [API](https://scikit-learn.org/stable/modules/classes.html). For Pandas, [the user guide](https://pandas.pydata.org/docs/user_guide/index.html#user-guide) is the best and again [the API](https://pandas.pydata.org/docs/reference/index.html) is a very useful starting point. For seaborn the [API](https://seaborn.pydata.org/api.html) is pretty good with in-built examples. Of course, if you are using a different library, you need to rely on what the authors are providing online so the quality might vary -- that's the joy of open source, community led development but the standards have risen substantially over the last years so you often get very good guidance.