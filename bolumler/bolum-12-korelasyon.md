# Bölüm 12: Korelasyon Analizi

## 1. Kavramsal Çerçeve
* **Pearson Korelasyonu ($r$):** $-1 \le r \le +1$

## 2. Python Uygulaması
```python
from scipy import stats
x = [2, 4, 6, 8, 10]
y = [40, 50, 65, 75, 90]
print(stats.pearsonr(x, y))
```