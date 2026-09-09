# Bölüm 05: Örnekleme Dağılımı ve Merkezi Limit Teoremi

## 1. Kavramsal Çerçeve
Evren dağılımı ne olursa olsun, $n \ge 30$ olduğunda örneklem ortalamalarının dağılımı normale yaklaşır.
* **Standart Hata:** $SE = \frac{\sigma}{\sqrt{n}}$

## 2. Python Uygulaması
```python
import numpy as np
se = 15 / np.sqrt(36)
print('Standart Hata:', se)
```