# 🌍 OpenGIS-TR | Coordinate Converter V18

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Maintained](https://img.shields.io/badge/Maintained-Yes-blue.svg)
![Version](https://img.shields.io/badge/Version-18.0-purple.svg)

![App Screenshot](ekran.png)

> **🚀 Live Demo / Canlı Uygulama:** [https://orbay1s.github.io/webgis-coordinate-converter](https://orbay1s.github.io/webgis-coordinate-converter)


---

## 🇬🇧 English
**OpenGIS-TR V18** is an advanced, browser-based coordinate conversion and analysis tool designed for **Survey Engineers, Urban Planners, and GIS Specialists**. It runs entirely on the client-side and supports Turkish National Datums (ED50 & ITRF96) along with batch processing capabilities.

### 🔥 New in V18
* **Batch Processing:** Bulk convert points from `.txt`, `.csv`, `.kml`, `.kmz`.
* **Expert Mode:** Customize projection parameters (Proj4 strings & datum shifts) on the fly.
* **Export:** Download results as Excel-compatible `CSV` or Google Earth `KML`.

### 🌟 Key Features
* **Multi-System Support:** Instant conversion between WGS84, ITRF96 (TM27-45), and ED50 (TM27-45) systems.
* **Visual Validation:** Dynamically displays the valid bounding box and zone boundaries on the map.
* **Smart Search:** Integrated OpenStreetMap (Nominatim) search to find locations.
* **Privacy Focused:** Zero server dependency. All data is processed locally in your browser.

### 🛠 Built With
* **Leaflet.js:** Interactive map engine.
* **Proj4js:** Coordinate projection library.
* **JSZip:** For handling KMZ and NCZ files.
* **Bootstrap 5:** Responsive UI.

### 📦 Installation
```bash
git clone [https://github.com/orbay1s/webgis-coordinate-converter.git](https://github.com/orbay1s/webgis-coordinate-converter.git)
cd webgis-coordinate-converter
# Open index.html in your browser
```

---

## 🇹🇷 Türkçe
**OpenGIS-TR V18**, Harita Mühendisleri ve Şehir Plancıları için geliştirilmiş; tarayıcı tabanlı, kurulum gerektirmeyen gelişmiş bir koordinat dönüşüm aracıdır. Özellikle Türkiye'deki ED50 - ITRF96 dönüşüm sorunlarını çözmek ve toplu veri işlemek için tasarlanmıştır.

### 🔥 V18 Sürümü Yenilikleri
* **Toplu İşlem (Batch):** `.txt`, `.csv`, `.kml`, `.kmz` dosyalarını yükleyerek binlerce noktayı aynı anda dönüştürün.
* **Uzman Modu:** Projeksiyon parametrelerine (Proj4 String) müdahale edebilir, yerel datum farkları için `+towgs84` değerlerini düzenleyebilirsiniz.
* **Dışa Aktarım:** Sonuçları Excel uyumlu `CSV` veya Google Earth `KML` formatında indirebilirsiniz.

### 🌟 Temel Özellikler
* **Çoklu Sistem Desteği:** WGS84, ITRF96 (TM27-45) ve ED50 (TM27-45) sistemleri arasında anlık dönüşüm.
* **Görsel Doğrulama:** Seçilen projeksiyonun geçerli olduğu zonu (Örn: ED50-30) haritada dinamik olarak gösterir.
* **Akıllı Arama:** Entegre OpenStreetMap (Nominatim) ile "Taksim Meydanı" gibi aramalarla konuma gidip koordinat alabilirsiniz.
* **Gizlilik Odaklı:** Sunucuya ihtiyaç duymaz, tüm veriler tarayıcınızda işlenir (Local Processing).

### 🛠 Kullanılan Teknolojiler
* **Leaflet.js:** İnteraktif harita motoru.
* **Proj4js:** Koordinat projeksiyon kütüphanesi.
* **JSZip:** KMZ ve NCZ dosyalarını işlemek için.
* **Bootstrap 5:** Responsive (Duyarlı) arayüz.

### 📦 Kurulum
```bash
git clone [https://github.com/orbay1s/webgis-coordinate-converter.git](https://github.com/orbay1s/webgis-coordinate-converter.git)
cd webgis-coordinate-converter
# index.html dosyasını tarayıcınızda açın
```
