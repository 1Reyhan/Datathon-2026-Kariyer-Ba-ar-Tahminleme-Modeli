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

![ SAYISAL DEĞİŞKENLERİN DAĞILIM ANALİZİ](images/1.SAYISAL DEĞİŞKENLERİN DAĞILIM ANALİZİ.png)
![ EKSİK DEĞER ANALİZİ](images/ozellikler_gorsel.png)
![ AYKIRI DEĞER ANALİZİ](images/ozellikler_gorsel.png)
![ HEDEF DEĞİŞKEN (TARGET) DETAYLI DAĞILIM ANALİZİ](images/ozellikler_gorsel.png)
![ KATEGORİK SÜTUNLAR VE HEDEF ETKİ ANALİZİ](images/ozellikler_gorsel.png)
![ GÜVENLİ KATEGORİK ENCODING OPERASYONU](images/ozellikler_gorsel.png)
![ KÜRESEL SİNYAL ANALİZİ VE GEÇİCİ KORUMA ALTINA ALMA](images/ozellikler_gorsel.png)
![ SENTENCE-BERT MODELİNİN YÜKLENMESİ VE REHBER EMBEDDING MATRİSİNİN HAZIRLANMASI](images/ozellikler_gorsel.png)
![ VERİNİN KALİTE KONTROLÜ VE VERİ BÜTÜNLÜĞÜ DENETİMİ ](images/ozellikler_gorsel.png)
![TEMEL MODELLERİN OPTİMİZE EDİLMİŞ OTOMATİK EĞİTİMİ](images/ozellikler_gorsel.png)
!LİDERLİK TABLOSU VE KARŞILAŞTIRMA PANELİ](images/ozellikler_gorsel.png)
