# Python Libraries & Modules i've studied while learning Python

## Table of Contents
1. [Introduction](#introduction)
2. [String Module](#string-module)
3. [Statistics Module](#statistics-module)
4. [Random Module](#random-module)
5. [Time Module](#time-module)
6. [Shutil Module](#shutil-module)
7. [CSV Module](#csv-module)
8. [Datetime](#datetime-module)
9. [Math Module](#9-math-module)
10. [Pytz Module](#9-pytz-module)

## Introduction
I've studied these libraries & modules during learning proceedure of Python.
This file contains a short explanation, pip install and a link of the Python library & module. 
It only includes functions-methods for each library that i've used in PyLearn-Excercises.
I tried to avoid the most common and well known modules like numpy, pandas etc.

### 1. String Module
- Provides common string operations. A collection of string constants.
- To import "import string"
- Pip Install: pip install strings
- [String Module Documentation](https://docs.python.org/3/library/string.html)
- 🔻STRING Functions i've used:
    - string.digits(): Output: 0123456789.
    - string.ascii_uppercase(): Output: ABCDEFGHIJKLMNOPQRSTUVWXYZ.

### 2. Statistics Module
- Mathematical statistics functions. Functions for calculating mathematical statistics.
- To import "import statistics"
- Pip Install: pip install statistics
- [Statistics Module Documentation](https://docs.python.org/3/library/statistics.html#module-statistics)
- 🔻STATISTICS functions i've used:
    - fmean(): median of float numbers.
    - mean(): median of integer numbers.
    - mode(): the most occuring value.
    - multimode(): the most occuring 2 vlues.

### 3. Random Module
- The random module in Python provides functions for generating random numbers.
- To import "import random"
- Pip Install: pip install random
- [Random Module Documentation](https://docs.python.org/3/library/random.html)
- 🔻RANDOM functions i've used: 
    - random.randit(): generate a random integer.
    - random.random(): generates a random float num between 0-1.
    - random.choice(): chooses a random element from a list.
    - random.choices():random.choices(population, weights=None, k=1)
    - random.shuffle(): shuffles the list randomly.
    - random.sample():picks random element from an iterable without replacement.
    
### 4. Time Module
- Time module provides time related functions.
- To import "import time"
- Pip install: pip install TIME-python
- [Time Module Documentation](https://docs.python.org/3/library/time.html)
- 🔻TIME functions i've used:
    - time.sleep(): stops execution for the given number of seconds.
    - perf_counter():counts the time of a working proceedure- start, end

### 5. Shutil Module
- Shutil modeule offers copying, removing functions for files.
- To import "import shutil"
- Pip install: pip install shutil
- [Shutil Module Documentation](https://docs.python.org/3/library/shutil.html)
- 🔻Shutil functions i've used:
    - shutil.copy(): copies the source file or directory.
    - shutil.rmtree(path): deletes a directory containing files.

### 6. OS.path Module
- Os.path module has useful functions on pathnames.
- To import "import os"
- pip install: pip install os
- [OS.PATH Documentation](https://docs.python.org/3/library/os.path.html#module-os.path)
- 🔻os.path functions that i've used:
    - os.path.exists(): this checks if the named file exists on the given path .
    - os.path.basename(path): extracts the file name without extenstion from a path.
    - os.path.isfile():checks if a given path is a file.
    - os.path.isdir(): checks if a given path is a directory.
    - os.path.getsize(path): returns the size of a file in bytes.

### 7. CSV Module
- CSV: most common format for spreads, excel sheets, comma sperated data.
- CSV module implements classes to read and write tabular data in CSV format
- To import: import csv
- pip install: already included in Python
- [CSV Module](https://docs.python.org/3/library/csv.html)
- 🔻csv functions that i've used:
    - csv.reader(): is used to read from a CSV file row by row.
    - csv.writer(): is used to write to a CSV file row by row.
    - csv.DictReader() and csv.DictWriter(): are used when the CSV file has a header, allowing you to access data by column names.
    - writerow() and writerows(): are used to write rows to a CSV file.
    - writeheader(): is used to write the header row to a CSV file when using DictWriter.

### 8. Datetime Module
- Datetime module supplies classes to work with dates, time anda datetime.
- To import: "import datetime"
- pip install: already included in Python
- [Datetime Module](https://docs.python.org/3/library/datetime.html)
- 🔻Datetime functions that i've used:
    - datetime():creates datetime objects
    - datetime.now(): Returns the current local date and time.
    - strftime():Returns a string representing the date and time, formatted according to the specified format.
    - strptime():Parses a string representing a date and time according to a specified format.
    - fromisoformat(): Returns a string representing the date and time in ISO 
    - timedelta(): duration or difference between two dates or times.
    - datetime.astimezone(tz=None): Converts the datetime object from one timezone to another.
    - datetime.replace(tzinfo=tz): Replaces the timezone information of the datetime object.
    - datetime.(): (year, month, day, hour, minute, second): returns the written data.

### 9. Math Module
- Math Module: provides a set of mathematical functions and constants for mathematical operations.
- To import: "import math"
- pip install: pip install math
- [Math Module](https://docs.python.org/3/library/math.html)
- 🔻Math functions that i've used:
    - math.pow(x, y): Returns x raised to the power y
    - math.sqrt(): square root of a number
    - math.ceil(): ceils a number
    - math.floor(): floors a number
    - math.factorial(): factorial of a number
    - math.gcd(): greatest common diviser

### 9. Pytz Module
- Pytz module: creates aware datetime obj with timezone. All Olson timzones supported.
- To import: pip install "import Pytz
- pip install: pip install pytz
- [Pytz Module](https://pypi.org/project/pytz/)
- 🔻Math functions that i've used:
    - pytz.timezone(: gets tz info of an object.)


