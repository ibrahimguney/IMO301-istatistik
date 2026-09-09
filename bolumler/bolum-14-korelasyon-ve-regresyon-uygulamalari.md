# Bölüm 14: Çoklu Regresyon ve Uygulamalar

## 1. Kavramsal Çerçeve
$$Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \dots + \epsilon$$

## 2. Python Uygulaması
```python
import statsmodels.api as sm
import pandas as pd
df = pd.DataFrame({'X1': [1,2,3,4], 'X2': [2,1,4,3], 'Y': [10,12,18,17]})
X = sm.add_constant(df[['X1', 'X2']])
print(sm.OLS(df['Y'], X).fit().summary())
```