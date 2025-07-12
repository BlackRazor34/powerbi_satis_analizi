# Power BI ile Gelişmiş Satış ve Performans Analizi Dashboard'u

Bu proje, bir şirketin satış verilerini derinlemesine analiz etmek için geliştirilmiş interaktif bir Power BI dashboard'udur. Rapor, kaynak tablolarda yer alan **satış tutarı, satış adedi, maliyet** ve **kâr/zarar** gibi temel finansal alanları kullanarak, performansı hem genel düzeyde hem de çalışan ve ürün bazında detaylı bir şekilde görselleştirir.

<img width="1527" height="861" alt="Screenshot_2025_07_12-1" src="https://github.com/user-attachments/assets/3cc444bd-8df9-4f06-97d6-1bc9b13dfac0"/>

---

## 🚀 Canlı ve İnteraktif Dashboard

Raporun tüm interaktif özelliklerini deneyimlemek ve canlı verilerle etkileşime geçmek için aşağıdaki linki kullanabilirsiniz.

➡️ **[Canlı Raporu Görüntülemek İçin Tıklayın](https://app.powerbi.com/view?r=eyJrIjoiYTRmNTE4NDktZDBjOS00M2U4LTljNzMtMmEzYzQ5MmRjYmQ2IiwidCI6IjgxYWMzZmNiLTBlMzQtNDJmNS1iZThlLTdiOGQyMjg2MGUxYiIsImMiOjl9)**

---

## 🎯 Temel Özellikler ve Analizler

Bu dashboard, karar alıcılar için kritik öneme sahip şu analizleri sunmaktadır:

### 1. Finansal Performans Analizi
- **Doğrudan Kâr/Zarar Takibi:** Kaynak veriden gelen kâr/zarar, maliyet ve satış tutarı alanlarının zaman serisi grafikleri üzerinde dinamik olarak izlenmesi.
- **Yıllık ve Aylık Trendler:** Tüm temel metriklerin yıllara ve aylara göre karşılaştırmalı analizi.

### 2. Detaylı Çalışan ve Ürün Performansı
- **Çalışan-Ürün Matrisi:** Ayrı bir analiz tablosu sayesinde, **her bir çalışanın hangi üründen ne kadar adet ve tutarda satış yaptığını ve bu satışların maliyetini** gösteren detaylı raporlar.
- **Performans Değerlendirme:** Çalışanların ürün bazlı performansını görerek güçlü oldukları alanları ve potansiyel gelişim noktalarını belirleme.

### 3. İnteraktif Coğrafi Analiz
- **Bölgesel Satış Adedi Takibi:** Harita üzerinde interaktif olarak bölge seçimi yapma ve seçilen bölgeye ait **toplam satış adedini** anında görme.
- **Coğrafi Verimlilik:** Bölgeler arası satış performansı karşılaştırmaları yaparak pazar dinamiklerini anlama.

---

## 🛠️ Teknik Detaylar ve Veri Modeli

- **Platform:** Microsoft Power BI Desktop
- **Veri Modelleme:** Proje, ana satış işlemlerini içeren bir tablo ile çalışanların ürün bazlı satış detaylarını içeren ikinci bir tabloyu birleştiren ilişkisel bir veri modeline sahiptir. Bu yapı, analizlerde yüksek bir granülerlik (detay seviyesi) sağlar.
- **Veri Kaynakları:** Dashboard, içerisinde **Satış Tutarı, Satış Adedi, Maliyet** ve **Kâr/Zarar** gibi önceden hesaplanmış alanları barındıran tablolardan beslenmektedir.
- **DAX Kullanımı:** Veri modelindeki mevcut alanları zenginleştirmek ve zaman bazlı (Time Intelligence) hesaplamalar gibi ek analizler yapmak için DAX fonksiyonlarından yararlanılmıştır.

---

## 📖 Nasıl Kullanılır?

1. **Canlı Raporu Açın:** Yukarıdaki linki kullanarak dashboard'u açın.
2. **Bölgesel Analiz:** Harita üzerinde bir veya daha fazla bölgeye tıklayarak o bölgelerdeki toplam satış adedini anında görün.
3. **Detaylı İnceleme:** Çalışan veya ürün bazlı grafiklerde bir öğeye tıklayarak tüm raporun o seçime göre filtrelenmesini sağlayın ve bir çalışanın tüm ürünlerdeki performansını tek ekranda görün.
