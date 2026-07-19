# 🚀 Podyum Operasyonu: Logit-Space Optimized Stacking

Bu depo, Kaggle platformu üzerinde yürütülen tahmine dayalı modelleme (Predictive Modeling) projesi için geliştirilen optimize edilmiş toplu öğrenme (Stacking) algoritmalarını içermektedir.

## 📊 Kullanılan Teknolojiler ve Kütüphaneler
* **Dil:** Python
* **Veri İşleme:** Pandas, NumPy
* **Modelleme & Stacking:** 
  * LightGBM (`LGBMClassifier`)
  * XGBoost (`XGBClassifier`)
  * CatBoost (`CatBoostClassifier`)
  * Ridge Classifier (Meta-Model)
* **Validasyon:** Stratified K-Fold Cross-Validation
* **Ölçeklendirme:** StandardScaler

## 🛠️ Projenin Öne Çıkan Özellikleri
* **Logit-Space Optimizasyonu:** Gelişmiş toplu öğrenme (Stacking) mimarisi kullanılarak modellerin tahmin başarıları optimize edilmiştir.
* **Otomatik Dosya Tespiti:** Kod yapısı, Kaggle ortamındaki `/kaggle/input` dizini ile yerel çalışma ortamındaki `train.csv`/`test.csv` dosyalarını otomatik olarak tespit edecek şekilde dinamik olarak tasarlanmıştır.
* **Robust Doğrulama:** Sınıf dengesizliklerini ve modelin genelleme yeteneğini korumak amacıyla Stratified K-Fold yöntemi entegre edilmiştir.
