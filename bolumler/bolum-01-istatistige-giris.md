# Bölüm 01: İstatistiğe Giriş ve Temel Kavramlar

## 1. Kavramsal Çerçeve
İstatistik; belirsizlik altında doğru karar verebilmek için verilerin toplanması, özetlenmesi ve analiz edilmesidir.

* **Evren (Kitle):** Araştırma kapsamındaki tüm elemanlar (Parametreler: $\mu, \sigma$).
* **Örneklem:** Evrenden yansız seçilen alt grup (İstatistikler: $\bar{X}, s$).
* **Ölçme Düzeyleri:**
  1. Sınıflama (Nominal)
  2. Sıralama (Ordinal)
  3. Eşit Aralıklı (Interval)
  4. Oranlı (Ratio)

## 2. Python Uygulaması
```python
import pandas as pd
df = pd.DataFrame({'Ogrenci': [1,2,3], 'Not': [65, 80, 95]})
print(df.describe())
```