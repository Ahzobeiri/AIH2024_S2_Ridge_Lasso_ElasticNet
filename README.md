# ElasticNet_for_House_Price_Kaggle_competition
**Offered in the Class of Artificial Intelligence, April 13, 2024 | Faculty of New Sciences and Technologies, University of Tehran**

# Intruductions
Linear regression is a foundational tool in statistics, but it's not without its challenges. Two significant issues that can compromise the performance and interoperability of a linear regression model are **multicollinearity** and **overfitting**. 



### - Import Required Packages

```python
# General Libraries
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import statsmodels.api as sm
```

- [statsmodels.api](https://www.statsmodels.org/stable/api.html): A library which is used for statistical modeling and tests in Python.

 ### - Notebook Settings
 ```python
pd.set_option("display.max_columns", None)
pd.set_option("display.max_rows", None)
pd.set_option("display.width", 500)
pd.set_option("display.float_format", lambda x: "%.4f" % x)
```
