# Bölüm 10: t Testi II (Bağımsız Örneklemler)

## 1. Kavramsal Çerçeve
$$t = \frac{\bar{X}_1 - \bar{X}_2}{s_p \sqrt{\frac{1}{n_1} + \frac{1}{n_2}}}$$

## 2. Python Uygulaması
```python
from scipy import stats
grup1 = [70, 75, 80, 85]
grup2 = [60, 65, 68, 72]
print(stats.ttest_ind(grup1, grup2))
```