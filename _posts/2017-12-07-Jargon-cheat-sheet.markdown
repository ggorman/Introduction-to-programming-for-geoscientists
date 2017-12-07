---
layout: post
title:  "Jargon cheat sheet"
date:   2017-12-07 14:00:00
categories: Lecture notes
---

## Data types:

* **float** - A decimal expansion of a number in ['floating point arithmetic'](https://en.wikipedia.org/wiki/Floating-point_arithmetic). Essentially, a float is a real number. Calling **float** on a number (e.g. an integer or string containing a number) will convert it to this format. Example: float(4) = 4.0 or float('5.2') = 5.2. However float('hello') will raise an error. (See lecture 1)

* **int** - An integer number, calling int() on on non-integer number rounds it down (truncates) to the nearest integer. (See lecture 1)

* **string** - A sequence of characters in quotation marks (" or '). Strings can also work like lists, in that you can call specific characters or sequences of characters from them using square brackets. Calling str() will turn a variable into a string. (See lecture 6)

## Container objects:

* **array** - Usually if you see 'array' in Python we are talking about a [numpy array](https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.array.html). NumPy and NumPy arrays are super important and you should use these whenever you can because it allows you to write code that runs as quickly as if you wrote it in a compiled language such as C/C++ or Fortran. It also enables you to use lots of cool scientific libraries that make you uber productive. You can apply functions to arrays, as opposed to lists. (See lecture 5) 

* **list** - A type of container that keeps Python elements (strings, ints, floats, lists, etc) in an ordered sequence using square brackets []. (See lecture 2)

* **tuple** - Kind of like a list of values, but one that cannot be modified once you have defined it. You can however add two tuples together to create a longer one. Tuples are defined by regular brackets: tuple = (value, value, ..., lastvalue). (See lecture 3)

* **dictionary** - A *non-ordered* container whose indices can be non-integer. Indices are referred to as *keys*, which have corresponding *values*. Both keys and values can have different types. Dictionaries are defined by curly brackets {}. (See lecture 6)

## Common functions:

* **linspace(start, stop, n)** - The function returns an array with n equally spaced values, starting with the value start and ending with the value stop. (See lecture 5)

* **range(start, stop, n)** - The function returns a list of values that starts with the value start, and then increments by n until it gets to stop-1. (See lecture 2)

* **len(list)** - Returns the length (number of elements) of a list, dictionary, array or tuple. (See lecture 2)

## Useful packages:

* **math** - Contains common mathematical functions and constants such as *exp*, *sin*, *pi*, *sqrt*. NOTE these functions cannot be evaluated on lists or arrays, only scalars (such as floats or ints). To apply mathematical expressions to arrays you need...

* **numpy** - Contains basically the same functions as math, but can actually apply them on arrays. This package also includes arrays themselves, so you need to import it whenever you deal with arrays in general.

* **pylab** - Package containing the tools used to plot. In a Jupyter notebook, you can just use the line %pylab inline to import the relevant plotting packages. If compiling Python from the command line, you need to import *matplotlib.pyplot*.

## Useful resources:

* **[Google](https:google.com)** - Every programming problem you run into, someone has seen it before...
* **[Python documentation](https://docs.python.org/3.6/index.html)** - Pretty much exactly what it says on the tin.
* **[Stackoverflow](https://stackoverflow.com)** - A website where users answer programming questions from other users. Pretty much any programming question in existence has been answered there already.

