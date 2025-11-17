Bu proje, Iris veri setini kullanarak çiçek türlerini sınıflandıran basit bir sinir ağı modelinin Java ile sıfırdan kodlanmış halidir. Her bir çiçek türü için birer adet olmak üzere üç nöron kullanılmıştır ve model hiçbir hazır ML kütüphanesi olmadan Perceptron mantığıyla eğitilmektedir.

## Nasıl Çalışır?

- Girdi olarak Iris veri setinin dört özelliği kullanılır:  
  **sepal width, sepal length, petal width, petal length**
- Üç nöronun çıktıları hesaplanır ve en yüksek değer tahmin kabul edilir.
- Yanlış tahminde doğru nöronun ağırlıkları artırılır, yanlış nöronunki azaltılır.
- Eğitim, seçilen **lambda** değeri için 20, 50 ve 100 epok boyunca gerçekleştirilir.
- Eğitim süreci bittiğinde doğruluk yüzdesi hesaplanır.

## Parametreler

Test edilen öğrenme oranları:

- **0.005**
- **0.01**
- **0.025**

Her biri 20, 50 ve 100 epok için otomatik olarak denenir.
