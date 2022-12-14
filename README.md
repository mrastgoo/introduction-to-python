# Introduction to Python language

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mrastgoo/introduction-to-python/HEAD)

We introduce here the Python language. 
The material presented are in reference form [scipy-lecture-notes](http://www.scipy-lectures.org/intro/index.html). 
To learn more about the language, consider going through the
excellent tutorials on https://docs.python.org/tutorial and scipy-lectures. 

Python is a **programming language**, as are C, Fortran, BASIC, PHP,
etc. Some specific features of Python are as follows:

* an *interpreted* (as opposed to *compiled*) language. Contrary to e.g.
C or Fortran, one does not compile Python code before executing it. In
addition, Python can be used **interactively**: many Python
interpreters are available, from which commands and scripts can be
executed.

* a free software released under an **open-source** license: Python can
be used and distributed free of charge, even for building commercial
software.

* **multi-platform**: Python is available for all major operating
systems, Windows, Linux/Unix, MacOS X, most likely your mobile phone
OS, etc.

* a very readable language with clear non-verbose syntax

* a language for which a large variety of high-quality packages are
available for various applications, from web frameworks to scientific
computing.

* a language very easy to interface with other languages, in particular C
and C++.

* Some other features of the language are illustrated just below. For
example, Python is an object-oriented language, with dynamic typing
(the same variable can contain objects of different types during the
course of a program).



See https://www.python.org/about/ for more information about
distinguishing features of Python.

In this course we will try to cover:
* basic types
* control flow
* functions
* reusing code
* input-output
* standard libraries
* object-oriented programming


## Requirements

Clone or save the zip folder of the git repository
   
```
        git clone https://github.com/mrastgoo/introduction-to-python
        

```

By installing [Anaconda3](https://www.anaconda.com/download/#linux) or miniconda3 you should have all the necessary packages.

Otherwise, make sure to have 

    * jupyter lab
    * jupyter notebook
    * numpy 
    * python 3.8
  
if you have anaconda or miniconda install 
1. Create your own environment 
   ```
        conda create --name py_intro -y python=3.8
   ```
2. Install the necessary packages
   ```
        pip install -r requirements.txt
   ```
3. Add a new [ipython kernel](https://ipython.readthedocs.io/en/stable/install/kernel_install.html) for your virtual env
   ```
        python -m ipykernel install --user --name py_intro --display-name py_intro
   ```


**In case of any problem in running the notebooks locally from your pc use `launch-binder` to access the notebooks**

