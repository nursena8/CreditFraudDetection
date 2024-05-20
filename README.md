# Kullanılan Kütüphaneler:
numpy,pandas,seaborn,matplotlib,scikit-learn,keras
# Credit Card Fraud Detection

## Veri seti:
Bu proje, kredi kartının kullanıldığı her yerde bulunan kredi kartı dolandırıcılık tespitini amaçlamaktadır. Bankalarda, e-commerce (e-ticaret siteleri) ve kredi kartının geçtiği her yerde karşımıza çıkabilir.

### Amaç:
- Kredi kartı dolandırıcılık tespiti yaparak tahminde bulunmak ve tespit etmektir.
- Sınıflandırma projesidir. Makine öğrenmesi kullanılacaktır.
- v1 - v29 feature değişkenleri standardize edilmiştir.
- İşlem yapılan yer, lokasyon, site gibi değerler gizlenmiştir.
- Bizden beklenen, bu v sütunlarından önemli olanları bulup dolandırıcılığa sebep verenleri tespit etmektir.

### Veri Seti Açıklaması:
- Veri seti, kredi kartı işlemlerini içermektedir.
- 'id' sütunu primary key'dir.
- 'v1' - 'v29' sütunları gizlenmiş feature'lardır, yani müşteriye ait herhangi bir özelliktir.
- 'amount' sütunu, ücret miktarını belirtir. 'class' sütunu ise 1 ise sahtekarlık vardır, 0 ise yoktur demektir.

## Veri Analizi ve Ön İşleme
### Veri Seti Yükleme:
Veri setini yüklemek ve ilk analizleri yapmak için pandas kütüphanesi kullanılmıştır.
### Veriyi Keşfetme:
Çeşitli görselleştirmeler ve istatistikler ile veri analizi yapılmıştır.
### Veriyi Dönüştürme:
Verinin ölçeklenmiş bir şekilde geldiiği için verilerin ölçeklenmesi sağlanmıştır.
### Veriyi modelleme:
Verinin varsayılan parametrelele modellenip nasıl bir tepki verdiğine bakılmıştır.
### Dengesiz veri setini temizleme:
Undersampling tekniğiyle verinin model için doğru şekle getirlimesi sağlanmıştır.
### Veriyi modelleme:
Verinin En iyi parametrelerle modellenip tekrar kurulması sağlanmıştır.
### Veriyi neural network ile tekrar modelleme:
Verinin keras kütüphanesi kullanılarak tekrar modellenmesi sağlanmıştır.
### Model değerlendirmesi:
Modelin çeşiti metrikler ile ölçülüp tekrar değerlendirmesi ile modelin karşılaştırılması sağlanmıştır.
### Sonuçlar:
Modelin derin öğrenme ile doğruluk değerinin %97 ye ulaşmıştır.logistic regression ve svc gibi modellerde daha %94 ,93 gibi değerlere ulaşmıştır.
Modele en çok etki eden önemli featurların bulup çıkarılması sağlanmıştır.




















































































