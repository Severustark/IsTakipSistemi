
# 📌 İş Takip Sistemi

Bu proje, **ASP.NET MVC** ve **MS SQL Server** kullanılarak geliştirilmiş bir iş takip sistemidir. Kullanıcıların görev oluşturmasını, görev atamasını ve iş süreçlerini takip etmesini sağlayan basit ve kullanışlı bir web uygulamasıdır.

## 🚀 Özellikler

- Kullanıcı yönetimi (kayıt, giriş)
- Görev oluşturma ve düzenleme
- Görev durumu takibi (Beklemede, Devam Ediyor, Tamamlandı)
- Görev atama ve son teslim tarihi belirleme
- Basit ve kullanıcı dostu arayüz (Razor View Engine)

## 🛠️ Kullanılan Teknolojiler

- ASP.NET MVC 5
- C#
- Entity Framework
- MS SQL Server
- Bootstrap (arayüz tasarımı için)
- LINQ

## 🗃️ Veritabanı

Proje MS SQL Server kullanmaktadır. Veritabanı bağlantısı `Web.config` dosyasında yer alan connection string ile yapılmaktadır.

**Örnek connection string:**
```xml
<connectionStrings>
  <add name="DbContext" connectionString="Data Source=.;Initial Catalog=IsTakipDb;Integrated Security=True" providerName="System.Data.SqlClient" />
</connectionStrings>
```

## ⚙️ Kurulum ve Çalıştırma

1. Bu repoyu indir veya klonla:
   ```bash
   git clone https://github.com/kullaniciadi/IsTakipSistemi.git
   ```

2. Visual Studio ile projeyi aç.

3. `App_Data` altındaki veritabanı dosyasını kontrol et veya kendi SQL Server'ında `IsTakipDb` adında bir veritabanı oluştur.

4. `Web.config` dosyasındaki connection string’i kendi sunucuna göre düzenle.

5. NuGet paketlerini yükle:
   ```
   Tools > NuGet Package Manager > Manage NuGet Packages for Solution
   ```

6. Uygulamayı çalıştır (`Ctrl + F5`).

## 👤 Geliştirici

- **Ad Soyad:** DAMLA ARPA
--2024--
