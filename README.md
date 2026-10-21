# 🤖 ESP32-S3 AI & Otonom Companion Robot

Bu proje; **ESP32-S3** mikrokontrolcüsü tabanlı, gerçek zamanlı sensör verilerini işleyebilen, modüler C++ nesne yönelimli (OOP) mimariyle geliştirilmiş otonom bir robot sistemidir.

---

## 🏗️ Sistem Mimarisi & Donanım Bileşenleri
* **Ana Kontrolcü:** ESP32-S3-DevKitC (Çift çekirdekli işlemci, genişletilmiş GPIO)
* **Motor Sürücü:** L298N / TB6612FNG DC Motor Sürücü
* **Algılama Katmanı:** HC-SR04 Ultrasonik Mesafe Sensörü
* **Geri Bildirim:** WS2812B RGB LED & Aktif Buzzer

---

## 📂 Proje Yapısı
- `firmware/` -> Modüler C++ sürücü sınıfları ve ana mantık.
- `hardware/` -> Bağlantı şemaları ve pin dağılım tabloları.
- `docs/` -> Mimari akış şemaları.

---
