# Haber Metinlerini Makine Öğrenmesi ile Sınıflandırma

Bu proje, çeşitli kategorilerdeki haber metinlerini sınıflandırmak için makine öğrenmesi modelleri kullanılarak gerçekleştirilmiştir. AG News veri kümesi üzerinde çalışılmış ve farklı algoritmalar ile performans karşılaştırmaları yapılmıştır.

---

## 🧾 Veri Kümesi

- **Kaynak:** [Kaggle - AG News Classification Dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset)
- **İçerik:**
  - `Class Index`: 1 (Dünya), 2 (Spor), 3 (İş), 4 (Bilim/Teknoloji)
  - `Title`: Haber başlığı
  - `Description`: Haber açıklaması

---

## 🧪 Uygulanan Yöntemler

### 📌 Veri Ön İşleme
- Küçük harfe dönüştürme
- URL, rakam ve noktalama temizliği
- Boşlukların temizlenmesi
- TF-IDF ile metinlerin sayısal vektörlere dönüştürülmesi

### 🧠 Kullanılan Makine Öğrenmesi Modelleri
- `Multinomial Naive Bayes`
- `Logistic Regression`
- `LinearSVC` (Destek Vektör Makineleri)

### 📊 Değerlendirme Metrikleri
- Doğruluk (Accuracy)
- Karmaşıklık Matrisi (Confusion Matrix)
- Model karşılaştırması görselleştirme (barplot)
