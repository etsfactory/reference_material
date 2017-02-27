# General purpose of Python
## Basic materials / Introduction:
- Short
  - [Short guide for complete beginners](https://learnxinyminutes.com/docs/python3/) (with programming background)
  - [Code like a Pythonist](http://python.net/~goodger/projects/pycon/2007/idiomatic/)
  - Summary: [Python cheat sheet](https://drive.google.com/file/d/0ByIrJAE4KMTtWGZmQXBPai1NQWM/view) by Mark Graph
- Long
  - [Basic Tutorial Python 3](http://www.python-course.eu/python3_course.php)
  - [Official Python 3 documentation](https://docs.python.org/3/)
  - [Introduction to Python for Econometrics, Statistics and Numerical Analysis](https://www.kevinsheppard.com/Python_for_Econometrics) by Kevin Sheppard (covers some pretty advanced topics)
  - Book: [Learn Python the Hard Way: A Very Simple Introduction to the Terrifyingly Beautiful World of Computers and Code](https://books.google.es/books/about/Learn_Python_the_Hard_Way.html?id=xUtsAQAAQBAJ)

## Style Guides / Good Habits:
- [Guide Numpy-Style Docstrings](http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_numpy.html) related to this topic, we can also mentioned ([PEP 484](https://www.python.org/dev/peps/pep-0484/)) (Pandas uses the same style as Numpy for the docstrings, it is the most common one in scientific Python)
- Style guide: [PEP8](https://www.python.org/dev/peps/pep-0008/) (Pycharm follows this convention by default)
- [Naming convention](http://visualgit.readthedocs.io/en/latest/pages/naming_convention.html)
- Projects and packages
  - Structuring your project: [1](http://docs.python-guide.org/en/latest/writing/structure/) and [2](http://python-packaging.readthedocs.io/en/latest/minimal.html)
  - [5 simple rules for building great Python packages](https://pythontips.com/2013/09/16/5-simple-rules-for-building-great-python-packages/)
  - [Open sourcing a Python project the right way](https://jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/)
- Summary: [The Best of the Best Practices (BOBP) Guide for Python](https://gist.github.com/sloria/7001839)

## Frequent doubts:
- [How to loop like a Pythonist](http://treyhunner.com/2016/04/how-to-loop-with-indexes-in-python/)
- [How to think like a Pythonist](http://python.net/crew/mwh/hacks/objectthink.html#question)
- [Namespaces and variable scopes](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/scope_resolution_legb_rule.ipynb)
- [A collection of not-so-obvious Python stuff you should know!](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/not_so_obvious_python_stuff.ipynb)
- [Magic methods](https://github.com/RafeKettler/magicmethods/blob/master/magicmethods.markdown) (function between double underscore, ex: .\_\_str\_\_)
- [What are the “best practices” for using import in a module?](https://docs.python.org/3/faq/programming.html#what-are-the-best-practices-for-using-import-in-a-module) And those links ([A](http://softwareengineering.stackexchange.com/questions/187403/import-module-vs-from-module-import-function/187471) and [B](http://effbot.org/zone/import-confusion.htm)) for those who want further details
- [setup.py vs. requirements.txt](https://caremad.io/posts/2013/07/setup-vs-requirement/)

## Definitive guides to specific topics:
- [Modules and imports](https://pymotw.com/3/sys/imports.html) (pretty advanced content)
- [Static, class, abstract methods](https://julien.danjou.info/blog/2013/guide-python-static-class-abstract-methods)
- [Exceptions](https://julien.danjou.info/blog/2016/python-exceptions-guide)
- [Decorators (closures, scoping, etc.)](http://simeonfranklin.com/blog/2012/jul/1/python-decorators-in-12-steps/) (According to a comment: Reading this article is like eating a mushroom by Mario.)
- [All the above about decorators is wrong](https://github.com/GrahamDumpleton/wrapt/tree/develop/blog) (from the author of the wrapt module)

## Performance:
- [Performance tuning](http://blog.explainmydata.com/2012/07/expensive-lessons-in-python-performance.html)
- [The magic of timeit](https://ipython.org/ipython-doc/3/interactive/magics.html#magic-timeit)
- [Timing & profiling](http://pynash.org/2013/03/06/timing-and-profiling/)

# Accelerating Python
## Reflections:
- [Why Python is Slow: Looking Under the Hood](https://jakevdp.github.io/blog/2014/05/09/why-python-is-slow/)

## Some tools:
- [Numba vs Cython comparison series](http://jakevdp.github.io/blog/2012/08/24/numba-vs-cython/)
- [Numexpr](https://github.com/pydata/numexpr)

# IPython
- [What is IPython? (Python vs IPython vs Jupyter)](https://plot.ly/python/ipython-vs-python/)
- [Built-in magics reference](https://ipython.org/ipython-doc/3/interactive/magics.html)
- [Parallel computation with IPython](http://ipyparallel.readthedocs.io/en/stable/index.html)

# Scientific Python
[Scipy Lecture Notes](http://www.scipy-lectures.org/index.html)

## Numpy
### Books:
- [Numpy book](https://docs.google.com/viewerng/viewer?url=http://templatelab.com/wp-content/uploads/2015/09/numpybook.pdf)
### Arrays and matrices:
- [Numeric matrix manipulation](http://sebastianraschka.com/Articles/2014_matrix_cheatsheet.html) – The cheat sheet for MATLAB, Python NumPy, R, and Julia and performance comparisons
- [Numpy for Matlab users](https://docs.scipy.org/doc/numpy-dev/user/numpy-for-matlab-users.html)
- [Numpy array technicalities](https://www.johndcook.com//numpy_intro.pdf)
### Frequent doubts:
- What is [array_like](http://stackoverflow.com/questions/8216975/terminology-python-and-numpy-iterable-versus-array-like)?
### Performance:
- [Numpy](http://ipython-books.github.io/featured-01/)
- [pure Python vs Numpy](http://scipy.github.io/old-wiki/pages/PerformanceTips)

## Pandas
### General:
- [Things in Pandas I Wish I'd Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb)
- Summary: [Cheat Sheet: The pandas DataFrame Object](https://drive.google.com/file/d/0ByIrJAE4KMTtTUtiVExiUGVkRkE/view?pref=2&pli=1) by Mark Graph
- [Official documentation](http://pandas.pydata.org/pandas-docs/stable/) (Full but long documentation, including an [introduction of 10 minutes](http://pandas.pydata.org/pandas-docs/stable/10min.html) for the most impatient ones)
### FAQ:
- [Indexing and selecting](http://pyciencia.blogspot.com.es/2015/05/obtener-y-filtrar-datos-de-un-dataframe.html) (loc, iloc, at, iat, ix)
### Pandas internals:
- [Extending Pandas](http://pandas.pydata.org/pandas-docs/stable/internals.html)
- [Pandas under the hood](http://www.jeffreytratner.com/slides/pandas-under-the-hood-pydata-seattle-2015.pdf) (Block Manager, indexes, etc.)

## Plotting Charts and Graphics
### Matplotlib:
- [Matplotlib cheat sheet](https://drive.google.com/file/d/0ByIrJAE4KMTtT1FqTzdOekg2RUU/view)

## Python ecosystem
### General purpose packages/libraries
- [Awesome Python (curated list of Python packages)](https://github.com/uhub/awesome-python)
### Scientific Python
- [Keynote: State of the Tools | SciPy 2015 | Jake VanderPlas](https://www.youtube.com/watch?v=5GlNDD7qbP4)
