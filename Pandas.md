### Pandas.DataFrame.dropna

怎么使用pandas包中的dropna？

What does the dropna do is basically removing the missing values!

It has five parameters:

* dropna (axis = ?)
  * We can choose to drop the rows or columns where has missing values
* dropna (how = ?)
  * we can shoose to drop the rows or columns where all data are missing, say **how = all**. 
* dropna (thresh = n)
  * We choose to keep the rows with at least n number of non-NA values.

* dropna (subset = ['name', 'toy'])
  * We choose to drop both name columns and toy columns where has missing values.

* 