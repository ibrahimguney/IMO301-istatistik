# Bölüm 13: Basit Doğrusal Regresyon

## 1. Kavramsal Çerçeve
$$\hat{Y} = b_0 + b_1 X$$

## 2. Python Uygulaması
```python
from scipy import stats
x = [2, 4, 6, 8, 10]
y = [40, 50, 65, 75, 90]
model = stats.linregress(x, y)
print(f'Y = {model.intercept:.2f} + {model.slope:.2f}*X')
```