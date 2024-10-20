# fish-classification
fish classification using ann architecture with kaggle dataset

https://www.kaggle.com/code/reyhansmeyyeyankolu/fish-classification



Kaggle'dan aldığım "A Large Scale Fish Dataset" veri seti kullanılarak balık sınıflandırma modeli geliştirdim. TensorFlow ve Keras ile derin öğrenme tabanlı bir yapay sinir ağı modeli eğiterek balık türlerini sınıflandırmayı hedefliyor. Veri seti, %80 eğitim ve %20 test verisi olarak ikiye ayrıldı. Eğitim verileri %80 eğitim, %20 doğrulama şeklinde bölündü. Model ANN mimarisi ve Sequential modeliyle oluşturuldu. Dense katmanlarla sinir ağı modeli oluşturulmuştur. 
Gerçek ve tahmin edilen sınıflar görseller ile karşılaştırılıyor. Doğru tahminler yeşil, yanlış tahminler kırmızı başlıkla gösteriliyor.
Modelde aşırı öğrenmeyi önlemek için L2 regularization ve Dropout kullanıldı.
 Modelin doğruluğu, hataları ve sınıflandırma başarı oranları test seti üzerinde ölçülmüş, sonuçlar görsellerle sunuldu.
 Doğru tahminler yeşil, yanlış tahminler kırmızı başlıkla gösterildi.
