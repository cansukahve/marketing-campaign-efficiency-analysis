# 🚀 Marketing Campaign Efficiency & Funnel Analysis

Bu proje, bir perakende şirketinin müşteri verilerini ve kampanya sonuçlarını kullanarak pazarlama stratejilerini optimize etmeyi amaçlayan uçtan uca bir veri analizi çalışmasıdır. Veri temizleme aşamasından başlayarak, müşteri segmentasyonu, KPI hesaplamaları ve stratejik aksiyon önerilerini kapsar.

## 🎯 Proje Hedefleri
* Pazarlama bütçesinin en verimli kullanıldığı kanalları belirlemek.
* Müşteri segmentlerini (Yaş, Eğitim, Gelir) harcama alışkanlıklarına göre analiz etmek.
* Satış funnel'ındaki (huni) tıkanıklıkları tespit ederek dönüşüm oranlarını artıracak öneriler sunmak.

## 📊 Kullanılan Teknolojiler
* **Python 3.x**
* **Pandas & NumPy:** Veri manipülasyonu ve temizliği.
* **Matplotlib & Seaborn:** Veri görselleştirme.
* **Scipy:** İstatistiksel analiz ve korelasyon hesaplamaları.



## 🛠️ Veri Temizleme ve Hazırlık
* `Income` sütunundaki eksik veriler temizlendi.
* `Year_Birth` verisinden `Age` (Yaş) sütunu üretildi; aykırı değerler (outliers) filtrelendi.
* `Marital_Status` sütunu standardize edildi.
* 6 farklı harcama kalemi toplanarak `Total_Spent` metriği oluşturuldu.

## 📈 Öne Çıkan Bulgular (Insights)
* **Kanal Performansı:** Yüksek gelirli müşterilerin **Katalog** kanalını kullanma eğilimi %70 korelasyonla en yüksek seviyededir.
* **Segmentasyon:** PhD ve Master mezunu müşterilerin harcama ortalaması, diğer segmentlere göre anlamlı derecede yüksektir.
* **Huni Analizi:** Web sitesi ziyaretçi sayısı yüksek olsa da, bu ziyaretlerin satın almaya dönüşme oranında (Conversion Rate) dijital deneyim kaynaklı bir sızıntı tespit edilmiştir.
* **Kampanya Başarısı:** En yüksek dönüşüm son kampanyada (%15) alınırken, 2. Kampanyanın bütçe verimliliği en düşük seviyede kalmıştır.



## 💡 Stratejik Öneriler
1. **Bütçe Kaydırma:** Düşük performanslı 2. Kampanya bütçesinin, yüksek geri dönüş alınan 4. Kampanyaya aktarılması.
2. **Kişiselleştirilmiş Katalog:** Yüksek gelirli ve yüksek eğitimli segment için fiziksel katalog gönderimlerinin artırılması.
3. **UX İyileştirmesi:** Web sitesindeki "ziyaret/satış" dengesizliğini gidermek için ödeme sayfası ve kullanıcı yolculuğunun optimize edilmesi.

## 📂 Dosya Yapısı
* `Marketing_Campaign_Efficiency_&_Funnel_Analysis.ipynb`: Python analiz kodlarını içeren Jupyter Notebook.
* `marketing_campaign.csv`: Analizde kullanılan ham veri seti.
* `Dijital_Pazarlama_Analiz_ve_Strateji_Raporu.docx`: Detaylı iş analizi raporu.

---
**Not:** Bu proje, veri odaklı pazarlama kararları alma yetkinliklerini göstermek amacıyla hazırlanmış bir portfolyo çalışmasıdır.
