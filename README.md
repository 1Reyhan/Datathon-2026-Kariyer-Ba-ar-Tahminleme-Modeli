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

### 1. Sayısal Değişkenlerin Dağılım Analizi
![Sayısal Değişkenlerin Dağılım Analizi](images/1.png)
<br><br>

### 2. Eksik Değer Analizi
![Eksik Değer Analizi](images/2.png)
<br><br>

### 3. Aykırı Değer Analizi
![Aykırı Değer Analizi](images/3.png)
<br><br>

### 4. Hedef Değişken (Target) Detaylı Dağılım Analizi
![Hedef Değişken Analizi](images/4.png)
<br><br>

### 5. Kategorik Sütunlar ve Hedef Etki Analizi
![Kategorik Sütunlar ve Hedef Etki Analizi](images/5.png)
<br><br>

### 6. Güvenli Kategorik Encoding Operasyonu
![Güvenli Kategorik Encoding Operasyonu](images/6.png)
<br><br>

### 7. Küresel Sinyal Analizi ve Geçici Koruma
![Küresel Sinyal Analizi](images/7.png)
<br><br>

### 8. Sentence-BERT Modeli ve Embedding Hazırlığı
![Embedding Hazırlığı](images/8.png)
<br><br>

### 9. Veri Kalite Kontrolü ve Bütünlük Denetimi
![Veri Kalite Kontrolü](images/9.png)
<br><br>

### 10. Temel Modellerin Optimize Edilmiş Otomatik Eğitimi
![Eğitim 1](images/10.1.png)
![Eğitim 2](images/10.2.png)
![Eğitim 3](images/10.3.png)
![Eğitim 4](images/10.4.png)
![Eğitim 5](images/10.5.png)
<br><br>

### 11. Liderlik Tablosu ve Karşılaştırma Paneli
![Liderlik Tablosu](images/11.png)
<br><br>
