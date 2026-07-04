# Datathon-2026-Kariyer-Başarı-Tahminleme-Modeli


## 🎯 Problem
Kariyer verilerindeki yüksek değişkenlik, eksik değerler ve
metinsel geri bildirimlerin karmaşıklığı nedeniyle başarı
tahminlemesinde yüksek varyans ve overfitting riski.

##  Yaklaşım
Sızıntısız bir veri hattı (MICE Imputation) kuruldu. NLP
süreçlerinde Sentence-BERT ve SVD ile boyut indirgeme
kullanıldı. Model kararlılığı için 15 katmanlı "RepeatedKFold"
çapraz doğrulama ve "Optuna" tabanlı hiperparametre
optimizasyonu gerçekleştirildi. Nihai tahminler için Ridge
Stacking ve TTA (Test-Time Augmentation) içeren hibrit bir
ensemble yapısı kuruldu.

## 🛠 Kullanılan Teknolojiler
Python, Scikit-learn, XGBoost, LightGBM, CatBoost, Optuna,
Sentence-BERT, TruncatedSVD, Pandas, NumPy

## 📊 Önemli Bulgular
Diferansiyel blending ve dağılım hizalama (distribution
alignment) teknikleriyle, test seti üzerindeki varyans minimuma
indirilerek modelin genelleme başarısı artırıldı; yüksek boyutlu
metin ve yapısal veriler başarıyla entegre edildi.

## 🚀 Nasıl Çalıştırılır?
İlgili `.ipynb` dosyasını Jupyter Notebook veya Google Colab üzerinden açarak kodları inceleyebilirsiniz.

! SAYISAL DEĞİŞKENLERİN DAĞILIM ANALİZİ(images/1.png)
![ EKSİK DEĞER ANALİZİ](images/2.png)
![ AYKIRI DEĞER ANALİZİ](images/3.png)
![ HEDEF DEĞİŞKEN (TARGET) DETAYLI DAĞILIM ANALİZİ](images/4.png)
![ KATEGORİK SÜTUNLAR VE HEDEF ETKİ ANALİZİ](images/5.png)
![ GÜVENLİ KATEGORİK ENCODING OPERASYONU](images/6.png)
![ KÜRESEL SİNYAL ANALİZİ VE GEÇİCİ KORUMA ALTINA ALMA](images/7.png)
![ SENTENCE-BERT MODELİNİN YÜKLENMESİ VE REHBER EMBEDDING MATRİSİNİN HAZIRLANMASI](images/8.png)
![ VERİNİN KALİTE KONTROLÜ VE VERİ BÜTÜNLÜĞÜ DENETİMİ ](images/9.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/10.1.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/10.2.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/10.3.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/10.4.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/10.5.png)
!LİDERLİK TABLOSU VE KARŞILAŞTIRMA PANELİ](images/11.png)

