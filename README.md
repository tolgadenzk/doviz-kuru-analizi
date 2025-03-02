"# Döviz Kuru Analizi " 
# Döviz Kuru Analizi 

Bu proje, **Türkiye Cumhuriyet Merkez Bankasý (TCMB) API**'sini kullanarak **günlük döviz kurlarýný** çeker ve analiz eder.

## ?? Kullanýlan Teknolojiler:
- Python
- Pandas
- Matplotlib
- Requests (API Ýstekleri)
- XML Parsing (ElementTree)

##  Proje Ýçeriði:
- TCMB API’den **günlük döviz kurlarýný** çeker.
- **USD/TRY, EUR/TRY ve diðer para birimlerinin alýþ/satýþ fiyatlarýný** analiz eder.
- **Matplotlib ile grafik oluþturarak görselleþtirir.**

##  Kullaným:
1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install requests pandas matplotlib