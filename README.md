# Mekanbul API Projesi

Bu proje, SDU Full Stack Bootcamp kapsamında geliştirilen mekan bulma uygulaması backend servisidir. RESTful API mimarisi kullanılarak geliştirilmiş, MongoDB veritabanı ile entegre edilmiştir.

## 🔗 Canlı Bağlantı (Vercel)
Proje şu adreste canlı olarak çalışmaktadır (API Base URL):
> **[https://backend-main-kappa.vercel.app/api](https://backend-main-kappa.vercel.app/api)**

---

## 🚀 Kullanılan Teknolojiler
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB Cloud (Atlas)
* **Deployment:** Vercel
* **Test:** Postman

---

## 🧪 Postman Test Sonuçları

Aşağıda API uç noktalarının (endpoints) başarılı çalıştığını gösteren test sonuçları yer almaktadır.

### 1. Mekan İşlemleri (Venues)

**Tüm Mekanları Listeleme (GET)**
![List Venue](test/listvenue.png)

**Yeni Mekan Ekleme (POST)**
![Add Venue](test/addvenue.png)

**Mekan Detayı Getirme (GET)**
![Get Venue](test/getvenue.png)

**Mekan Güncelleme (PUT)**
![Update Venue](test/updatevenue.png)

**Mekan Silme (DELETE)**
![Delete Venue](test/deletevenue.png)

---

### 2. Yorum İşlemleri (Comments)

**Mekana Yorum Ekleme (POST)**
![Add Comment](test/addcomment.png)

**Yorum Getirme (GET)**
![Get Comment](test/getcomment.png)

**Yorum Güncelleme (PUT)**
![Update Comment](test/updatecomment.png)

**Yorum Silme (DELETE)**
![Delete Comment](test/deletecomment.png)

---

## 📂 Postman Koleksiyonu
API testlerini kendi bilgisayarınızda çalıştırmak için proje dosyasında bulunan `.json` uzantılı Postman koleksiyonunu import edebilirsiniz.