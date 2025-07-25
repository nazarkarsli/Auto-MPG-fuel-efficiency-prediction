# 🚘 Otomobil Yakıt Verimliliği Tahmin Sistemi (Auto MPG Prediction)

Bu proje, [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/9/auto+mpg) üzerinden alınan **Auto MPG veri setini** kullanarak, 1970–1980 yıllarında üretilmiş otomobillerin **yakıt verimliliğini (MPG)** tahmin etmek için bir **regresyon modeli** geliştirmektedir.

Makine öğrenmesi teknikleri kullanılarak, bir otomobilin teknik özelliklerinden yola çıkarak **galon başına kaç mil gideceği** tahmin edilmektedir. Özellikle otomotiv endüstrisi ve sürdürülebilir ulaşım üzerine çalışanlar için önemli bir analiz çalışmasıdır.

---

## 📊 Veri Kümesi Özellikleri

- **Toplam Gözlem Sayısı**: 398
- **Toplam Özellik Sayısı**: 8 giriş değişkeni + 1 hedef değişken (MPG)

###  Değişkenler:

| Değişken        | Açıklama                                           |
|------------------|----------------------------------------------------|
| `mpg`            | **Galon başına mil (miles per gallon)** – Hedef değişken |
| `cylinders`      | Silindir sayısı (motor gücü hakkında bilgi verir)   |
| `displacement`   | Motor hacmi (inç küp cinsinden)                    |
| `horsepower`     | Motor gücü (beygir gücü)                            |
| `weight`         | Araç ağırlığı (pound/lb cinsinden)                |
| `acceleration`   | 0–60 mph hızlanma süresi (saniye)                  |
| `model year`     | Üretim yılı (1970–1982 arası)                      |
| `origin`         | Üretim yeri: `1` = ABD, `2` = Avrupa, `3` = Japonya |
| `name`           | Araç modeli (isteğe bağlı açıklayıcı bilgi)       |

---

## Proje Amacı

Bu proje ile amaçlanan; veri setindeki teknik bilgilerden faydalanarak bir aracın **yakıt verimliliğini doğru şekilde tahmin edebilen bir model** ortaya koymaktır. Bu model;

- Veri temizleme (eksik değerler, `horsepower`)
- Özellik mühendisliği (kategorik kodlama)
- Regresyon modelleme (Linear Regression, Random Forest vs.)
- Model değerlendirme (MSE, R² skoru)
  
adımlarını kapsamaktadır.

---

##  Kullanılan Teknolojiler

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook



