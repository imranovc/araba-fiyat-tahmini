<<<<<<< HEAD
# 🚗 Araba Fiyat Tahmini Projesi

Bu proje, Türkiye otomobil pazarındaki araç fiyatlarını etkileyen faktörleri analiz ederek, makine öğrenimi algoritmalarıyla araç fiyatlarını tahmin etmeyi amaçlamaktadır.

## 📊 Proje Amacı

Türkiye'deki araç satış verilerini kullanarak:
- Fiyatları etkileyen değişkenleri belirlemek,
- Verileri analiz etmek ve temizlemek,
- Makine öğrenimi modelleriyle güvenilir fiyat tahminleri yapmak hedeflenmiştir.

## 📁 Kullanılan Veri Seti

**Turkey_car_market.csv** veri seti; araçların marka, model, yıl, kilometre, yakıt türü, vites tipi, durumu, motor gücü, renk gibi özelliklerini içermektedir.

## 🧹 Veri Ön İşleme Adımları

- Eksik verilerin doldurulması veya silinmesi
- Kategorik değişkenlerin sayısallaştırılması (One-Hot Encoding)
- Aykırı değerlerin temizlenmesi (IQR yöntemi)
- Özellik ölçekleme (Normalization/Standardization)
- Verinin eğitim/test setlerine ayrılması

## 📈 Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🤖 Kullanılan Makine Öğrenimi Algoritmaları

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor

Tüm modeller `GridSearchCV` ile hiperparametre optimizasyonuna tabi tutulmuştur.

## 📌 Performans Değerlendirme

Modeller aşağıdaki metriklerle değerlendirilmiştir:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Skoru

## 🏁 Sonuç

- Modeller karşılaştırılmış ve en iyi performans gösteren algoritma belirlenmiştir.
- Random Forest algoritması, fiyat tahmini açısından en başarılı sonuçları vermiştir.

## 📂 Proje Yapısı

araba-fiyat-tahmini/
├── turkey_car_market.csv
├── analiz.ipynb
├── model.py
├── README.md
└── ...


## 👤 Geliştirici

**İmran Ovacı**  

=======
# araba-fiyat-tahmini
Araç fiyatlarını tahmin eden makine öğrenmesi projesi
>>>>>>> 53f7de94768f3b0d01f14e21140186da3ab292d0
