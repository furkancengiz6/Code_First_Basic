# Code First Basic - Entity Framework Core Web API

Bu proje, **Entity Framework Core** kullanarak **Code First** yaklaşımını öğrenmek ve uygulamak amacıyla geliştirilmiştir. Proje, bir Web API kullanarak, iki tabloyu (`Movie` ve `Game`) veritabanına eklemeyi amaçlamaktadır. Proje, **Visual Studio 2022** ve **SQL Server** kullanılarak oluşturulmuştur.

## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Teknolojiler](#teknolojiler)
- [Kurulum ve Çalıştırma](#kurulum-ve-çalıştırma)
- [Veritabanı Yapısı](#veritabanı-yapısı)
- [Özellikler](#özellikler)
- [Veritabanı Migrasyonu](#veritabanı-migrasyonu)
- [Swagger API Dokümantasyonu](#swagger-api-dokümantasyonu)

## Proje Hakkında

Bu proje, **Code First** yaklaşımını kullanarak veritabanı oluşturmayı, migrasyon işlemlerini yapmayı ve SQL Server veritabanına bağlantıyı sağlamayı amaçlamaktadır. `Movies` ve `Games` adında iki bağımsız tablonun bulunduğu bir veritabanı yapısı oluşturulmuştur.

- **Movies Tablosu:**
  - Id: int (otomatik artan, birincil anahtar)
  - Title: string (film başlığı)
  - Genre: string (film türü: Action, Comedy, Drama, vb.)
  - ReleaseYear: int (film çıkış yılı)

- **Games Tablosu:**
  - Id: int (otomatik artan, birincil anahtar)
  - Name: string (oyun adı)
  - Platform: string (oyunun oynandığı platform: PC, PlayStation, Xbox, vb.)
  - Rating: decimal (0 ile 10 arasında, oyun puanı)

## Teknolojiler

- **.NET 8**
- **Entity Framework Core**
- **SQL Server**
- **Swagger (API Dokümantasyonu)**
- **Visual Studio 2022**

## Kurulum ve Çalıştırma

Proje yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **Repository'i Klonlayın:**

   ```bash
   git clone https://github.com/furkancengiz6/Code_First_Basic.git
