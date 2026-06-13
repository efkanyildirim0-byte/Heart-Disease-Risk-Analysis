# Heart Disease Risk Factors & Machine Learning Analysis

Bu proje, 327 katılımcıdan oluşan anket verileri üzerinden kalp hastalığı risk faktörlerinin istatistiksel analizini ve makine öğrenmesi tahmin modellerini içermektedir.

## 🚀 Proje İçeriği ve Yapısı
* **Heart_Dataset_Cleaned.csv**: Analizde kullanılan temizlenmiş veri seti.
* **Büyük_Veri_Analizi_Final.ipynb**: Veri ön işleme, veri görselleştirme (6 farklı grafik), çapraz risk analizleri ve makine öğrenmesi (Logistic Regression & Decision Tree) kodlarını içeren Jupyter Notebook dosyası.
* **Proje_Raporu.pdf**: Hocanın şablonuna uygun olarak hazırlanmış, tüm kod çıktılarını, tabloları, tıbbi yorumları ve 1 sayfalık kısa özeti içeren resmi proje raporu.

## 📊 Öne Çıkan Bulgular
* **Yaş ve Tansiyon:** 50 yaş üstü bireylerde kalp hastalığı oranı **%51.15**'e çıkmaktadır. Hipertansiyon hastalarında ise bu oran **%58.14** ile zirvededir.
* **Model Performansı:** Kalp hastalığı tahmininde **Logistic Regression** modeli %71.21 doğruluk ve 0.790 ROC-AUC skoru ile en başarılı model olmuştur.
* **Klinik Sınırlılık:** Modellerin kalp hastalarını yakalama oranı (Recall: %32) düşük olduğundan, bu aşamada gerçek hayatta klinik karar destek sistemi olarak kullanılması uygun değildir.

## 🛠️ Kullanılan Teknolojiler
* Python 3
* Pandas & Numpy (Veri Yönetimi)
* Matplotlib & Seaborn (Veri Görselleştirme)
* Scikit-Learn (Makine Öğrenmesi ve Modelleme)
