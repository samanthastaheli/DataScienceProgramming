
## "Coding Challenge" Example

### Name: _Samantha Staheli_

### Instructions

_In the Final Coding Challenge I will ask you to complete problems about as challenging as what is shown below.  Plus, you will need to fit a machine learning model with data I provide._

_Remember, you will only have 60 minutes to work on the challenge! You will not be able to complete every question perfectly, but you should spend at least a little time on each question._

_Paste your answers and code inside this `.md` file._

--- 

### Practice Challenges

Start by loading these packages and data:

```python

import pandas as pd
import altair as alt
import numpy as np

dat = pd.read_csv('https://github.com/byuidatascience/data4missing/raw/master/data-raw/mtcars_missing/mtcars_missing.csv')

```

<br>

**Question 1:** Try recreating the chart below using the [mtcars missing](https://github.com/byuidatascience/data4missing/raw/master/data-raw/mtcars_missing/mtcars_missing.csv) data that you've already loaded.

- Note that `hp` has missing values, and you will have to replace them with the mean.
- Please drop all cars with a missing name.

![](practice_mtcars.png)

**Question 1 Answer:**

_Show your chart here._

**Question 1 Code:**

```
Paste your code here.
```

<br>

**Question 2:** Try writing code to recreate the following table.

- Have `cyl` on the rows and `carb` on the columns
- The values inside the table represent the number of cars with that particular `cyl`/`carb` combination.
- The `pd.crosstab()` function could be helpful, or maybe `pd.pivot_table()`.


|   cyl |   1 |   2 |   3 |   4 |   6 |   8 |
|------:|----:|----:|----:|----:|----:|----:|
|     4 |   5 |   6 |   0 |   0 |   0 |   0 |
|     6 |   2 |   0 |   0 |   4 |   1 |   0 |
|     8 |   0 |   4 |   3 |   6 |   0 |   1 |

**Question 2 Answer:**

_Show your table here._

**Question 2 Code:**

```
Paste your code here.
```

<br>

**Question 3:** On the Final Coding Challenge, I will also ask you to fit a Machine Learning Model.