# Secure EV Charging Station Simulation 🔐⚡

Bu proje, araç şarj istasyonlarında kullanılan iletişim protokollerinin güvenliğini artırmak amacıyla bir **şifreleme ve kimlik doğrulama simülasyonu** geliştirir.

## 🎯 Amaç
Elektrikli araç ile şarj istasyonu arasında gerçekleşen veri alışverişini (örneğin kimlik, ödeme, enerji akışı bilgileri) güvenli hâle getirmek ve olası saldırı senaryolarını test etmek.

## 🧩 Teknik Bileşenler
- **Python 3.13**
- `socket` ve `ssl` modülleri ile araç-istasyon iletişimi
- `cryptography` veya `pycryptodome` ile AES / RSA / ECC tabanlı şifreleme
- `logging` modülü ile olay kaydı
- MITM (Man-in-the-Middle) saldırısı simülasyonu
- JSON tabanlı rapor çıktısı

## 📁 Proje Yapısı
--------------------------
