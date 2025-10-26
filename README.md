# 📚 Library Management System (Java OOP)

Bu proje, bir üniversite kütüphanesinin temel işlevlerini yöneten **Java tabanlı nesne yönelimli (OOP)** bir uygulamadır.  
Soyut sınıflar (**abstract class**), arayüzler (**interface**) ve sınıflar arası ilişkiler (**inheritance**, **composition**) kullanılarak geliştirilmiştir.

---

## 🚀 Özellikler
- Kitap ekleme, silme ve listeleme  
- Üye ekleme ve listeleme  
- Kitap ödünç alma ve iade etme  
- Tüm işlem geçmişini görüntüleme  
- Arayüz (`IManageable`) ile yönetim fonksiyonlarının standartlaştırılması  

---

## 🧩 Sınıf Yapısı

| Sınıf | Açıklama |
|--------|-----------|
| `IManageable` | Kütüphane yönetim işlemleri için arayüz |
| `LibraryItem` | Kitapların ortak özelliklerini tanımlayan soyut sınıf |
| `Book` | `LibraryItem` sınıfından türeyen, ödünç alma/iade işlemleri bulunan sınıf |
| `Person` | Ortak kişi bilgilerini tutan soyut sınıf |
| `LibraryMember` | `Person` sınıfından türeyen, üyeleri temsil eden sınıf |
| `BorrowTransaction` | Kitap ödünç alma ve iade işlemlerini temsil eden sınıf |
| `LibrarySystem` | Kitap, üye ve işlem yönetimini gerçekleştiren sınıf |
| `Main` | Uygulamayı çalıştıran ana sınıf |

---

## 🧠 Kullanılan Kavramlar
- **Inheritance (Kalıtım)**
- **Abstract Class**
- **Interface**
- **Polymorphism**
- **Composition**
- **Encapsulation**

---

## ⚙️ Kurulum ve Çalıştırma
1. Projeyi klonla:
   ```bash
   git clone https://github.com/<kullaniciadi>/LibraryManagementSystem-JavaOOP.git

## 📷 Örnek Konsol Çıktısı
Suç ve Ceza kütüphaneye eklendi.
1984 kütüphaneye eklendi.
Simyacı kütüphaneye eklendi.

Ahmet Yılmaz kütüphaneye üye olarak eklendi.
Elif Demir kütüphaneye üye olarak eklendi.

=== KİTAP ÖDÜNÇ VERME ===
1984 kitabı Ahmet Yılmaz adlı üyeye ödünç verildi.
Simyacı kitabı Elif Demir adlı üyeye ödünç verildi.

=== KİTAP İADE ===
1984 kitabı iade edildi.

=== TÜM İŞLEM GEÇMİŞİ ===
------ ÖDÜNÇ İŞLEMİ ------
Kitap Bilgisi:
Kitap: 1984 | Yazar: George Orwell | Yıl: 1949 | Durum: Kütüphanede mevcut
Üye Bilgisi:
Üye Adı: Ahmet Yılmaz | Üye ID: LM001
Ödünç Alınma Tarihi: 2025-10-26
İade Tarihi: 2025-10-26
--------------------------
---

## 👨‍💻 Geliştirici
**Çetin [GitHub kullanıcı adın]**  
📍 Java Developer | OOP & Yazılım Temelleri  
📅 Ekim 2025  

---

## 🏷️ Lisans
Bu proje eğitim amaçlı hazırlanmıştır. İsteyen herkes kaynak göstererek kullanabilir.

