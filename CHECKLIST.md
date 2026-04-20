# Ödev Kontrol Listesi (10 Adım)

## 1. Veri Setinin Yüklenmesi

- [x] Veri seti seçildi (Breast Cancer)
- [x] `X` ve `y` oluşturuldu
- [x] pandas DataFrame/Series dönüşümü yapıldı
- [x] İlk 5 satır görüntülendi

## 2. Veri Seti Kalite Kontrolleri

- [x] Missing value analizi yapıldı
- [x] Veri tipi (dtype) incelemesi yapıldı
- [x] Outlier analizi yapıldı

## 3. Keşifsel Veri Analizi (EDA)

- [x] Temel istatistikler çıkarıldı
- [x] Korelasyon analizi ve heatmap çizildi

## 4. Veri Ölçeklendirme (Scaling)

- [x] Ölçeklendirme ihtiyacı gerekçelendirildi
- [x] StandardScaler yaklaşımı benimsendi (leakage kontrolü ile)

## 5. Veri Setinin Bölünmesi

- [x] Stratified train/validation/test bölünmesi yapıldı (70/10/20)
- [x] Ölçeklendirme split sonrası ve sadece train üzerinde `fit` edilerek uygulandı

## 6. Özellik Seçimi ve Boyut İndirgeme

- [x] PCA uygulandı (bileşen sayısı ödev kuralına göre seçildi)
- [x] LDA uygulandı (iki sınıflı problem için 1 bileşen)

## 7. Makine Öğrenmesi Modellerinin Kurulması

- [ ] 5 farklı model tanımlandı ve eğitildi (ham/PCA/LDA temsilleri)

## 8. Validation Performanslarının Ölçülmesi

- [ ] Validation metrikleri hesaplandı (Accuracy, Precision, Recall, F1, ROC-AUC)
- [ ] Sonuçlar tek tabloda karşılaştırıldı
- [ ] En iyi model/temsil seçildi

## 9. En İyi Modelin Test Üzerinde Değerlendirilmesi

- [ ] Test performansı raporlandı
- [ ] Confusion matrix çizildi
- [ ] ROC curve çizildi

## 10. XAI – SHAP Açıklanabilirlik Analizi (Zorunlu)

- [ ] SHAP summary plot üretildi
- [ ] SHAP bar plot ile önem sıralaması çıkarıldı
