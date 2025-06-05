# starbucks-calorie-prediction
Starbucks menüsündeki ürünlerin besin değerlerine göre kalori tahmini (ML modelleri ile)
#  Starbucks Kalori Tahmin Modeli

Bu projede Starbucks ürünlerinin besin değerlerine (yağ, karbonhidrat, lif, protein, şeker, kafein) göre kalori tahmini yapılmaktadır. Birden fazla makine öğrenmesi algoritması kullanılarak modeller karşılaştırılmıştır.

---

##  Veri Kümesi Kaynağı

- **Starbucks Besin Değerleri Veri Seti**  
  Kaynak: [Kaggle](https://www.kaggle.com/datasets)

---

## Kullanılan Özellikler

- Şeker (Sugars)
- Toplam Yağ (Total Fat)
- Protein
- Kafein (Caffeine)
- Porsiyon Boyutu (Serving Size)
- Karbonhidrat, Lif vb.

🎯 **Hedef Değişken:**  
- Kalori (Calories)

---

## Kullanılan Yöntem ve Teknikler

-  Veri temizleme ve ön işleme
-  Korelasyon analizi (heatmap)
-  Regresyon algoritmaları ile model oluşturma
-  Model değerlendirme metrikleri:
  - R² (Determinasyon Katsayısı)
  - RMSE (Kök Ortalama Kare Hata)
  - MAE (Ortalama Mutlak Hata)

---

##  Kullanılan Teknolojiler

- Python (Google Colab ortamında)
- Kütüphaneler:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`
  - `lightgbm`, `catboost`

---

##  Uygulanan Modeller
- Linear Regression
- Random Forest Regressor
- Gradient Boosting
- K-Nearest Neighbors (KNN)
- Support Vector Regressor (SVR)
- LightGBM
- CatBoost
- MLPRegressor (Yapay Sinir Ağı)

---

## Görselleştirme

- Korelasyon ısı haritası
- Scatter plot: Yağ vs Protein
- Histogramlar
- Tahmin edilen vs Gerçek Kaloriler (çizgi grafikleri)
- Pairplot & barplot'lar ile kategori bazlı analizler

---

##  Kullanım

- Google Colab üzerinden çalıştırılabilir.
- Kullanıcıdan yağ, protein, lif, karbonhidrat ve ürün tipi bilgisi alarak kalori tahmini yapılabilir.





