# Bölüm 09: t Testi I (Tek Örneklem ve Bağımlı Örneklemler)

## 1. Kavramsal Çerçeve
$$t = \frac{\bar{D}}{s_D / \sqrt{n}}, \quad df = n - 1$$

## 2. Python Uygulaması
```python
from scipy import stats
on = [50, 55, 60, 65]
son = [60, 65, 70, 75]
print(stats.ttest_rel(son, on))
```