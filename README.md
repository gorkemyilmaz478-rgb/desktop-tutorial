# İkinci El Araç Fiyat Tahmin Sistemi

## Proje Hakkında

Bu proje, makine öğrenmesi algoritmalarını kullanarak ikinci el araçların satış fiyatlarını tahmin etmeyi amaçlamaktadır. Kaggle platformundan alınan araç verileri analiz edilerek fiyat tahmini için farklı makine öğrenmesi modelleri geliştirilmiştir.

## Projenin Amacı

İkinci el araç piyasasında fiyatlar; aracın markası, modeli, üretim yılı, kilometresi ve teknik özellikleri gibi birçok faktöre bağlı olarak değişmektedir.

Projenin amacı, bu değişkenleri kullanarak araç fiyatlarını tahmin edebilen bir makine öğrenmesi sistemi geliştirmek ve farklı algoritmaların performanslarını karşılaştırmaktır.

## Kullanılan Veri Seti

**Used Car Price Prediction Dataset**

Kaynak: [Kaggle - Used Car Price Prediction](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset)

Veri setinde aşağıdaki değişkenler bulunmaktadır:

- Brand
- Model
- Model Year
- Mileage
- Fuel Type
- Engine
- Transmission
- Exterior Color
- Interior Color
- Accident
- Clean Title
- Price

## Kullanılan Teknolojiler

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Kullanılan Makine Öğrenmesi Algoritmaları

### 1. Linear Regression

Araç özellikleri ile satış fiyatı arasındaki doğrusal ilişkileri modellemek amacıyla kullanılmıştır.

### 2. Random Forest Regressor

Birden fazla karar ağacının sonuçlarını birleştirerek fiyat tahmini gerçekleştirmek amacıyla kullanılmıştır.

## Proje Aşamaları

1. Veri setinin temin edilmesi ve incelenmesi
2. Eksik verilerin kontrol edilmesi
3. Veri temizleme ve ön işleme
4. Keşifsel veri analizi ve görselleştirme
5. Eğitim ve test verilerinin ayrılması
6. Makine öğrenmesi modellerinin eğitilmesi
7. Tahmin sonuçlarının elde edilmesi
8. Model performanslarının karşılaştırılması

## Model Değerlendirme

Modellerin performansları aşağıdaki metrikler kullanılarak değerlendirilmiştir:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Determination Coefficient)

## Proje Ekibi

- Arda Fidancı
- Görkem Yılmaz
- Burak Kerem Çakubay

## Lisans ve Veri Kaynağı

Veri seti Kaggle üzerinden temin edilmiştir. Veri setinin lisansı: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
## Proje Yönetimi ve Geliştirme Süreci

Projenin geliştirme süreci GitHub Projects üzerinden Kanban yöntemiyle takip edilmektedir.

[Kanban Panosu](https://github.com/users/ardafidanci52-png/projects/2/views/1)

---

**Proje:** İkinci El Araç Fiyat Tahmin Sistemi  
**Geliştirme Ortamı:** Google Colab