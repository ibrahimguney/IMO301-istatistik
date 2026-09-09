# Bölüm 06: Hipotez Testi I (Tek Örneklem z Testi)

## 1. Kavramsal Çerçeve
* $H_0: \mu = \mu_0$
* $H_1: \mu \neq \mu_0$
$$z_{hesap} = \frac{\bar{X} - \mu_0}{\sigma / \sqrt{n}}$$

## 2. Python Uygulaması
```python
from scipy import stats
z_hesap = (54 - 50) / (10 / (36**0.5))
p_val = 2 * (1 - stats.norm.cdf(abs(z_hesap)))
print('z:', z_hesap, 'p-degeri:', p_val)
```