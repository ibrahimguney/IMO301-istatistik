# Bölüm 02: Betimsel İstatistik I (Merkezi Eğilim Ölçüleri)

## 1. Kavramsal Çerçeve
* **Aritmetik Ortalama ($\bar{X}$):** $\bar{X} = \frac{\sum X_i}{n}$
* **Medyan:** Sıralı dizideki tam ortadaki değer.
* **Mod:** En çok tekrarlanan değer.

## 2. Python Uygulaması
```python
import numpy as np
from scipy import stats
notlar = [60, 70, 70, 80, 90]
print('Ortalama:', np.mean(notlar))
print('Medyan:', np.median(notlar))
print('Mod:', stats.mode(notlar, keepdims=True).mode[0])
```