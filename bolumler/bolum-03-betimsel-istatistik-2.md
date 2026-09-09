# Bölüm 03: Betimsel İstatistik II (Değişkenlik Ölçüleri)

## 1. Kavramsal Çerçeve
* **Ranj:** $X_{maks} - X_{min}$
* **Örneklem Varyansı ($s^2$):** $s^2 = \frac{\sum (X_i - \bar{X})^2}{n-1}$
* **Standart Sapma ($s$):** $s = \sqrt{s^2}$
* **IQR:** $Q_3 - Q_1$

## 2. Python Uygulaması
```python
import numpy as np
veriler = [50, 60, 65, 70, 85, 90]
print('Varyans:', np.var(veriler, ddof=1))
print('Standart Sapma:', np.std(veriler, ddof=1))
```