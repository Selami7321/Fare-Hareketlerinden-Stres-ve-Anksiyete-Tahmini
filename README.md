# Fare-Hareketlerinden-Stres-ve-Anksiyete-Tahmini
Predicting Stress and Anxiety from Rat Movements


Bu proje, fare iskelet hareketlerinden yola çıkarak stres ve anksiyete seviyesini tahmin etmeyi amaçlayan bir makine öğrenmesi uygulamasıdır. Etiketlenmemiş pozisyon verilerinden anlamlı özellikler çıkarılarak, çeşitli sınıflandırma algoritmaları ile stres düzeyleri tahmin edilmiştir.

🔍 Kullanılan Modeller
Naive Bayes

Lojistik Regresyon

DNN (Derin Sinir Ağı)

GloVe + LSTM (Önceden Eğitilmiş Word Embedding ile Sekans Modellemesi)

📊 Değerlendirme Metotları
Karışıklık matrisleri (Confusion Matrix)

ROC ve AUC eğrileri

Öğrenme eğrisi (Learning Curve)

🛠 Özellikler
Pozisyon verilerinden istatistiksel öznitelik mühendisliği (x/y ortalama, varyans, min/max)

TF-IDF ve CountVectorizer ile vektörleştirme

Eğitim/test ayrımı ve model karşılaştırmaları

Görselleştirme ile model performansı analizi
