# Bölüm 11: Parametre Tahmini ve Güven Aralıkları

## 1. Kavramsal Çerçeve
$$\bar{X} \pm t_{\alpha/2} \left(\frac{s}{\sqrt{n}}\right)$$

## 2. Python Uygulaması
```python
from scipy import stats
import numpy as np
veri = [70, 75, 80, 85, 90]
print(stats.t.interval(0.95, df=len(veri)-1, loc=np.mean(veri), scale=stats.sem(veri)))
```