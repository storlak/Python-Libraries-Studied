# Python Libraries & Modules i've studied while learning Python

## Table of Contents
1. [Introduction](#introduction)
2. [String Module](#String)
3. [Statistics Module](#statistics)
4. [Random Module](#random)
5. [Time Module](#time-module)
6. [Shutil Module](#shutil-module)
7. [CSV Module](#csv-module)

## Introduction
I've studied these libraries & modules during learning proceedure of Python.

This file contains a short explanation, pip install and  a link of the Python library & module. It includes 3 examples for each library. Examples are the functions that i've used in Py-Learn Excercises.

### String Module
- Provides common string operations. A collection of string constants.
- To import "import string"
- Pip Install: pip install strings
- [String Module Documentation](https://docs.python.org/3/library/string.html)
- 🔻STRING Functions i've used:
    - string.digits: Output: 0123456789.
    - string.ascii_uppercase: Output: ABCDEFGHIJKLMNOPQRSTUVWXYZ.
    - random.choice: chooses a random element from a list.

### Statistics Module
- Mathematical statistics functions. Functions for calculating mathematical statistics.
- To import "import statistics"
- Pip Install: pip install statistics
- [Statistics Module Documentation](https://docs.python.org/3/library/statistics.html#module-statistics)
- 🔻STATISTICS functions i've used:
    - fmean: median of float numbers.
    - mean: median of integer numbers.
    - random.choice: chooses a random element from a list.


### Random Module
- The random module in Python provides functions for generating random numbers.
- To import "import random"
- Pip Install: pip install random
- [Random Module Documentation](https://docs.python.org/3/library/random.html)
- 🔻RANDOM functions i've used: 
    - random.randit(): generate a random integer.
    - random.random(): generates a random float num between 0-1.
    - random.choice(): chooses a random element from a list.
    - random.shuffle(): shuffles the list randomly.
    
### Time Module
- Time module provides time related functions.
- To import "import time"
- Pip install: pip install TIME-python
- [Time Module Documentation](https://docs.python.org/3/library/time.html)
- 🔻TIME functions i've used:
    - time.sleep(): stops execution for the given number of seconds.
    - 

### Shutil Module
- Shutil modeule offers copying, removing functions for files.
- To import "import shutil"
- Pip install: pip install shutil
- [Shutil Module Documentation](https://docs.python.org/3/library/shutil.html)
- Shutil functions i've used:
    - shutil.copy(): copies the source file or directory.
    - shutil.rmtree(path): deletes a directory containing files.

### OS.path Module
- Os.path module has useful functions on pathnames.
- To import "import os"
- pip install: pip install os
- [OS.PATH Documentation](https://docs.python.org/3/library/os.path.html#module-os.path)
- os.path functions that i've used:
    - os.path.exists(): this checks if the named file exists on the given path .
    - os.path.basename(path): extracts the file name without extenstion from a path.
    - os.path.isfile:checks if a given path is a file.
    - os.path.isdir: checks if a given path is a directory.
    - os.path.getsize(path): returns the size of a file in bytes.

### CSV Module
- CSV: most common format for spreads, excel sheets, comma sperated data.
- CSV module implements classes to read and write tabular data in CSV format
- To import: import csv
- pip install: already included in Python
- [CSV Modul](https://docs.python.org/3/library/csv.html)
- csv functions that i've used:
    - csv.reader(): is used to read from a CSV file row by row.
    - csv.writer(): is used to write to a CSV file row by row.
    - csv.DictReader() and csv.DictWriter(): are used when the CSV file has a header, allowing you to access data by column names.
    - writerow() and writerows(): are used to write rows to a CSV file.
    - writeheader(): is used to write the header row to a CSV file when using DictWriter.