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

- **Pd.set_option:**  Is used to configure the display of pandas DataFrames within an interactive Python environment, making data easier to review and analyze by adjusting how much of the DataFrame is shown and how it is formatted.

 ### - Import ML libraries

```python
# Machine Learning
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
from sklearn.model_selection import train_test_split, cross_val_score, GridSearchCV
from sklearn.preprocessing import RobustScaler, scale
from sklearn.linear_model import LinearRegression, Ridge, RidgeCV, Lasso, LassoCV, ElasticNet, ElasticNetCV
from sklearn import model_selection

import warnings
warnings.filterwarnings("ignore")
```
