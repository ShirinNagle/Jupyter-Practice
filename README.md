# Jupyter-Tasks

This Jupyter notebook, conatains the work related to solving 4 tasks, set by Lecturer Dr. Ian McLoughlin.
The tasks are listed below.
### Task 1

Write a Python function called sqrt^2 that calculates and prints to the screen the square root of 2 to 100 decimal places.  Your code should not depend on any module from the standard library1or otherwise.  You should research the task first and include references and a description of your algorithm.

### Task 2

The  Chi-squared  test  for  independence  is  a  statistical hypothesis test like at-test.  It is used to analyse whether two categorical variables are independent.  The Wikipedia article gives the table below as an example [4],stating the Chi-squared value based on it is approximately 24.6. Usescipy.stats to verify this value and calculate the associated pvalue.  You should include a shortnote with references justifying your analysis in a markdown cell.

||A|B|C|D|Total|
|---|---|---|---|---|---|
|White collar|90|60|104|95|349|
|Blue collar|30|50|51|20|151|
|No collar|30|40|45|35|150|
|Total|150|150|200|150|650|

### Task 3

The  standard  deviation  of  an  array  of  numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)).However,  Microsoft  Excel  has  two  different  versions  of  the  standard  deviation calculation,STDEV.P and STDEV.S.  TheSTDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x).  Research these Excel functions, writing a note in a Markdown cellabout  the  difference  between  them.   Then  use numpy to  perform  a  simulation demonstrating that the STDEV.S calculation is a better estimate for the standardd eviation of a population when performed on a sample.  Note that part of this task is to figure out the terminology in the previous sentence.

### Task 4

Use scikit-learn to  apply k-means  clustering  to Fisher’s  famous  Iris  data  set.   You  will  easily  obtain  a  copy  of  the  data  set  on-line.  Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.
