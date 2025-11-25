# 📡 Telco Customer Churn Prediction

Bu proje, bir telekomünikasyon şirketinin müşteri verilerini analiz ederek, hangi müşterilerin hizmeti bırakacağını (Churn) tahminlemeyi hedefler.

## 🎯 Proje Amacı
Müşteri kaybını önceden tespit ederek şirketin proaktif önlemler almasını sağlamak ve müşteri sadakatini etkileyen temel faktörleri belirlemek.

## 🛠 Kullanılan Teknolojiler
* **Python:** Veri analizi ve modelleme.
* **Pandas & NumPy:** Veri manipülasyonu.
* **Scikit-learn:** Makine öğrenmesi modelleri (Logistic Regression, Random Forest).
* **Seaborn & Matplotlib:** Veri görselleştirme.

## 📊 Önemli Bulgular
Veri analizi sonucunda müşterilerin ayrılmasına neden olan en büyük etkenler şunlardır:
1.  **Aylık ve Toplam Ücretler:** Fiyat hassasiyeti en yüksek faktör.
2.  **Abonelik Süresi (Tenure):** Yeni abonelerin ayrılma riski, uzun dönemli müşterilere göre çok daha yüksek.
3.  **Fiber Optik İnternet:** Fiber altyapı kullanan müşterilerde memnuniyetsizlik oranı dikkat çekici derecede yüksek.

## 📈 Model Performansı
İki farklı model ile çalışılmıştır:
* **Logistic Regression Accuracy:** %78.75
* **Random Forest Accuracy:** %78.54

Lojistik Regresyon, daha basit bir model olmasına rağmen bu veri setinde genel doğruluk açısından daha kararlı sonuçlar vermiştir.