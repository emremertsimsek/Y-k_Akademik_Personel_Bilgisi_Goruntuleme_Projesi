Akademik Personel Veri Kazıma ve Filtreleme Projesi (Academic Staff Scraper & Filter)

Bu proje; YÖK Akademik sistemi üzerinden akademik personelin unvan, ad-soyad, bölüm, kitap ve tez bilgilerini dinamik olarak web scraping (veri kazıma) yöntemiyle toplayan, verileri **JSON** formatında saklayan ve kullanıcı dostu bir arayüzle filtreleme imkanı sunan tam kapsamlı bir uygulamadır.

Proje Bileşenleri

1. Python Scraper (Selenium & BeautifulSoup): YÖK Akademik sayfalarını otomatik olarak gezinerek akademisyen bilgilerini, yayınlarını ve tezlerini çeker[cite: 10, 12].
2. JSON Veri Seti (`kku_academic_personnel.json`): Toplanan verilerin yapılandırılmış bir şekilde saklandığı örnek çıktı dosyası[cite: 13].
3. İnteraktif Arayüz (`BitirmeProjesi1.html`): Çekilen JSON verilerini kullanarak bölüme, personele, yayın türüne (kitap/tez) ve yıla göre dinamik filtreleme yapabilen web arayüzü.

---

Kullanılan Teknolojiler

* **Python 3.10+**
* **Selenium WebDriver** (Dinamik sayfa yönetimi ve tıklama işlemleri)[cite: 10, 12]
* **BeautifulSoup4** (HTML parsing ve veri ayıklama)[cite: 10, 12]
* **JSON** (Veri depolama ve aktarımı)[cite: 10, 12]
* **HTML5 / JavaScript** (Önyüz filtreleme ve interaktif arayüz)[cite: 11]

---

Kurulum ve Çalıştırma

1. Gereksinimleri Yükleyin
Projeyi çalıştırmadan önce gerekli kütüphaneleri yükleyin:
```bash
pip install selenium beautifulsoup4 webdriver-manager
