---
layout: post
title:  "My Thoughts on Various Programming Languages"
---

**What are your thoughts on R vs whatever other software you've used?**

Over the years I have dabbled in a few different langauges typically encountered in the data science and statistics fields. By very nature of the statisitics degree, I would say my in depth knowledge of R has grown to the point it has become my "goto" language. For instance, if I needed to run a random forest model, R would be my first choice. That being said, I have been applying what I learn in R to Python. Just to maintain a diversity of skills. In a lot of ways, the two languages overlap quite a bit, really just differing in syntax and some data object types. I only say this since I use both languages to complete the similiar tasks (KNN, charts, linear regression, etc). That does not mean they are the same. R is definately a langauge built specifically for data analysis, whereas, Python is a more general purpose language. One give away is the fact
that to do tasks that are built into base R, Python must import a package (for example, base R can handle linear algebra but Python needs the Numpy package, or Pandas for data frames). Due to being a general purpose language, Python tends to have more functionality for tasks that are not necessary for data analysis, Django for web development or Pygame for game developement. Personally, for creating reports and documents, I would turn to R. For general scripting I would use Python, especially since more people would more likely be familiar with Python thanR. In addition to R and Python, SAS deserves an honorable mention. I love the proc report feature. But due to licensing, code sharing and reviewing is limited. Other languages I have used are Julia and MATLAB (gnuoctave). Those two are great for graphing functions in my opinion but I have not used those two for more than that.

**What functionality do you like about R?**  

The main thing I like about R is the reduced need to import libraries to do basic data handling. Data frames and matrices are handled well in base R and the plotting function is very capable. All my python code starts with the same four lines regardless of the task:

- import numpy as np
- import pandas as pd 
- import os
- import matplotlib.pyplot as plt

Base R already contains student's t, normal dist, etc. With Python you can't do that without the scipy, scikit-learn, or statistics modules.

**What parts do you miss about your other language?**

Since I tend to use Python and R mainly, and for the similiar purposes, I do not really feel one is really lacking in anything over the other. As mentioned before, I do wish they handled equation graphing as Julia and MATLAB. In those, all I need to do it program in an equation and out pops a graph. Whereas with R and Python I need to apply a function to a data object and plot the output of that.

**Do you consider R a difficult language to learn? (If you knew R prior to the course, describe your experience when first learning it.)**

I do not think R is that difficult to learn. The brackets used in R definately help make stable code on first try. One wrong indent in Python can cause some misery, especially for first time programmers. I starting using R as part of the masters program and found it quite intuitive for most things but I did know Python prior to using R. Switching to R was more of a syntax change than a "new" language. On the flip side, the similarities can be a hindrance though (`len` and `length` or `True` and `TRUE`). On a final note on thing I immediately liked was that I did not need to pull in as many modules or packages as I find myself doing in Python.
