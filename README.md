# Kalp Rahatsızlıkları Sınıflandırma Uygulaması

Bu proje, kalp rahatsızlıklarını sınıflandırmak için kullanılan bir uygulamadır. Proje, K-Nearest Neighbors (KNN), Decision Tree ve Random Forest algoritmalarını kullanarak bir sınıflandırma modeli geliştirmektedir. Bu README dosyası, proje hakkında genel bilgiler, kullanılan veri seti ve model eğitimi süreci hakkında bilgiler içermektedir.

## Veri Seti

Bu proje için kullanılan veri seti, kalp rahatsızlıklarını belirlemek için çeşitli özellikleri içerir. Veri seti, aşağıdaki kolonları içermektedir:

- `age`: Hastanın yaşı
- `sex`: Hastanın cinsiyeti (0: Kadın, 1: Erkek)
- `chest pain type`: Göğüs ağrısı tipi (0-3 arası değerler)
- `resting bp s`: Dinlenme kan basıncı (mmHg)
- `cholesterol`: Kolesterol seviyesi (mg/dl)
- `fasting blood sugar`: Açlık kan şekeri (0: Normal, 1: Yüksek)
- `resting ecg`: Dinlenme elektrokardiyografisi sonucu (0-2 arası değerler)
- `max heart rate`: Maksimum kalp atış hızı
- `exercise angina`: Egzersiz anjinası (0: Yok, 1: Var)
- `oldpeak`: Dinlenme ile egzersiz arasındaki ST depresyonu
- `ST slope`: Egzersiz ST segmentinin eğimi
- `target`: Hedef değişken, kalp rahatsızlığının varlığını belirtir (0: Yok, 1: Var)

## Model Eğitimi

Proje, scikit-learn kütüphanesinde bulunan KNeighborsClassifier, DecisionTreeClassifier ve RandomForestClassifier modellerini kullanarak üç farklı model oluşturur. Model eğitimi aşağıdaki adımlarla gerçekleştirilmiştir:

1. Veri Seti Hazırlığı: Veri seti önişleme adımlarıyla temizlenmiş ve eksik veriler doldurulmuştur.
2. Veri Keşfi ve Ön İşleme: Veri setinin genel istatistikleri incelenmiş, görselleştirilmiş ve gerekli ön işleme adımları uygulanmıştır.
3. Model Eğitimi: KNN, Decision Tree ve Random Forest modelleri eğitilmiş ve hiperparametre ayarlaması yapılmıştır.
4. Model Değerlendirmesi: Her model için karmaşıklık matrisi çizilmiş ve doğruluk oranları hesaplanmıştır.



Proje, veri setini kullanarak model eğitecek ve sonuçları ekrana yazdıracaktır.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasını inceleyebilirsiniz.

