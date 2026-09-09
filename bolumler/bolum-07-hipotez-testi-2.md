# Bölüm 07: Hipotez Testi II (Karar Hataları ve Testin Gücü)

## 1. Kavramsal Çerçeve
* **I. Tip Hata (\alpha):** $H_0$ doğruyken reddetmek.
* **II. Tip Hata (\beta):** $H_0$ yanlışken reddedememek.
* **Güç:** $1 - \beta$

## 2. Python Uygulaması
```python
from statsmodels.stats.power import zt_ind_solve_power
n = zt_ind_solve_power(effect_size=0.5, alpha=0.05, power=0.80)
print('Gereken n:', round(n))
```