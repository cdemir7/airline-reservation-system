# ✈️ Airline Reservation System (Hava Yolu Rezervasyon Sistemi)

Bu proje, kullanıcıların uçuşları sorgulayabileceği, koltuk seçimi yapabileceği ve bilet rezervasyon işlemlerini gerçekleştirebileceği kapsamlı bir otomasyon sistemidir.

Proje, hem müşteri (yolcu) hem de yönetici (admin) panellerini içererek, bir hava yolu şirketinin temel operasyonel süreçlerini dijital ortamda simüle etmeyi amaçlar.



## 🚀 Özellikler

Sistem iki ana modülden oluşmaktadır:

### 1. Kullanıcı (Yolcu) Modülü
* **Uçuş Arama:** Kalkış ve varış noktasına, tarihe göre uçuş sorgulama.
* **Rezervasyon:** Seçilen uçuş için bilet alma ve koltuk seçimi.
* **Bilet Görüntüleme:** Mevcut rezervasyonları listeleme ve yazdırma (PNR sorgulama).
* **İptal:** Rezervasyonu iptal etme.

### 2. Yönetici (Admin) Modülü
* **Uçuş Yönetimi:** Yeni uçuş seferleri ekleme, düzenleme veya iptal etme.
* **Uçak Tanımlama:** Filoya yeni uçak ekleme ve kapasite belirleme.
* **Yolcu Listesi:** Belirli bir uçuşa kayıtlı yolcuları görüntüleme.

## 🛠️ Kullanılan Teknolojiler

* **Programlama Dili:** Java
* **Veritabanı:** MySQL
* **Arayüz (GUI):** Java Swing
* **Veri Bağlantısı:** JDBC

## 💾 Veritabanı Yapısı

Proje ilişkisel veritabanı yapısını kullanır. Temel tablolar şunlardır:

* `Flights` (Uçuşlar): Uçuş No, Kalkış, Varış, Tarih, Saat, Fiyat.
* `Passengers` (Yolcular): Ad, Soyad, TC/Pasaport No, İletişim.
* `Reservations` (Rezervasyonlar): PNR Kodu, Yolcu ID, Uçuş ID, Koltuk No.
* `Airplanes` (Uçaklar): Model, Kapasite.

---
*Geliştirici: [Cihan Demir](https://github.com/cdemir7)*
