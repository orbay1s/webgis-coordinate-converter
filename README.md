# 🌍 OpenGIS-TR | Coordinate Converter

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Maintained](https://img.shields.io/badge/Maintained-Yes-blue.svg)
![Language](https://img.shields.io/badge/Language-HTML%20%7C%20JS-orange.svg)

![App Screenshot](https://via.placeholder.com/800x400?text=Uygulama+Goruntusu+Buraya+Gelecek)

> **🚀 Live Demo / Canlı Uygulama:** [https://orbay1s.github.io/webgis-coordinate-converter](https://orbay1s.github.io/webgis-coordinate-converter)

---

## 🇬🇧 English
**OpenGIS-TR Coordinate Converter** is a browser-based, client-side coordinate conversion and analysis tool. It is specifically designed to solve the **ED50 <-> ITRF96** datum transformation issues frequently encountered in Turkey's geospatial projects.

### 🌟 Key Features
* **Multi-System Support:** Instant conversion between WGS84, ITRF96 (TM27-45), and ED50 (TM27-45) systems.
* **Visual Validation:** Dynamically displays the valid bounding box of the selected coordinate system on the map.
* **Zone Control:** Mathematically validates whether the converted coordinate falls within the target system's boundaries.
* **Address Search:** Integrated OpenStreetMap infrastructure for address/place search.
* **Client-Side Architecture:** Zero server dependency. Runs entirely in your browser using HTML5/JS.

### 🧩 Development Approach
This tool was conceptualized by an **Urban Planner** and built using **AI-Assisted Development** workflows. It aims to bridge the gap between complex geodetic problems and practical field needs without requiring deep software engineering knowledge.

### 🛠 Built With
* **Leaflet.js:** Interactive map engine.
* **Proj4js:** Coordinate projection library.
* **Bootstrap 5:** Responsive UI.

### 📦 Installation
Since this is a static web app, no backend installation is required.

```bash
git clone [https://github.com/orbay1s/webgis-coordinate-converter.git](https://github.com/orbay1s/webgis-coordinate-converter.git)
cd webgis-coordinate-converter
# Simply open index.html in your browser

---

## 🇹🇷 Türkçe
**Coordinate Converter**, tarayıcı tabanlı ve istemci taraflı çalışan bir koordinat dönüşüm ve analiz aracıdır. Özellikle Türkiye'deki mekansal projelerde sıklıkla karşılaşılan **ED50 <-> ITRF96** datum dönüşüm sorunlarını çözmek için özel olarak tasarlanmıştır.

### 🌟 Temel Özellikler
* **Çoklu Sistem Desteği:** WGS84, ITRF96 (TM27-45) ve ED50 (TM27-45) sistemleri arasında anlık dönüşüm.
* **Görsel Doğrulama:** Seçilen koordinat sisteminin geçerli sınır kutusunu (bounding box) harita üzerinde dinamik olarak gösterir.
* **Zone (Dilim) Kontrolü:** Dönüştürülen koordinatın hedef sistem sınırları içinde kalıp kalmadığını matematiksel olarak doğrular.
* **Adres Arama:** Adres/yer arama işlemleri için entegre OpenStreetMap altyapısı.
* **İstemci Taraflı Mimari:** Sıfır sunucu bağımlılığı. Tamamen HTML5/JS kullanarak tarayıcınızda çalışır.

### 🧩 Geliştirme Yaklaşımı
Bu araç bir **Şehir Plancısı** tarafından kurgulanmış ve **Yapay Zeka Destekli Geliştirme** iş akışları kullanılarak oluşturulmuştur. Derin yazılım mühendisliği bilgisine ihtiyaç duymadan, karmaşık jeodezik problemler ile pratik saha ihtiyaçları arasındaki boşluğu doldurmayı amaçlamaktadır.

### 🛠 Kullanılan Teknolojiler
* **Leaflet.js:** Etkileşimli harita motoru.
* **Proj4js:** Koordinat projeksiyon kütüphanesi.
* **Bootstrap 5:** Duyarlı (Responsive) kullanıcı arayüzü.

### 📦 Kurulum
Bu statik bir web uygulaması olduğu için herhangi bir backend kurulumu gerekmez.

```bash
git clone https://github.com/orbay1s/webgis-coordinate-converter.git
cd webgis-coordinate-converter
# Sadece index.html dosyasını tarayıcınızda açın
