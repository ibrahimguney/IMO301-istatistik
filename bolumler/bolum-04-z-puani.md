# Bölüm 04: Standart Normal Dağılım ve z Puanı

## 1. Kavramsal Çerçeve
$$z = \frac{X - \bar{X}}{s}$$
Ortalaması 0, standart sapması 1 olan standart normal dağılım dönüşümüdür.

## 2. Python Uygulaması
```python
from scipy import stats
z = (85 - 70) / 10
print(f'z puani: {z:.2f}, Yuzdelik Dilim: %{stats.norm.cdf(z)*100:.1f}')
```