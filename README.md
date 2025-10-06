# MvcOnlineTicariOtomasyon

[TR]

**ASP.NET MVC Kullanılarak Geliştirilmiş Kapsamlı Online Ticari Otomasyon Sistemi**

[![ASP.NET MVC](https://img.shields.io/badge/Framework-ASP.NET_MVC-602C78.svg)](https://dotnet.microsoft.com/apps/aspnet/mvc)
[![C#](https://img.shields.io/badge/Language-C%23-blue.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Database](https://img.shields.io/badge/Database-SQL_Server-CC2927.svg)](https://www.microsoft.com/en-us/sql-server)
[![GitHub repo size](https://img.shields.io/github/repo-size/abdullahhaktan/MvcOnlineTicariOtomasyon)](https://github.com/abdullahhaktan/MvcOnlineTicariOtomasyon)

---

## 💻 Proje Hakkında

Bu proje, **ASP.NET MVC** mimarisi kullanılarak geliştirilmiş, **tam kapsamlı bir online ticari otomasyon sistemi** simülasyonudur. Proje, bir e-ticaret platformunun veya şirket içi envanter yönetim sisteminin temel işlevlerini kapsayarak, **gelişmiş veritabanı etkileşimleri** ve **kullanıcı yetkilendirme** pratiklerini göstermektedir.

---

## ✨ Temel Özellikler

### Mimari ve Teknik Uygulamalar
* **Model-View-Controller (MVC) Mimarisi:** İş mantığı, veri ve arayüz arasında net bir ayrım sağlayarak sürdürülebilir bir kod tabanı oluşturulmuştur.
* **Entity Framework (Code First/Database First):** Veritabanı ile Object-Relational Mapping (ORM) kullanılarak hızlı ve güvenilir veri işlemleri gerçekleştirilmiştir.
* **Repository/Unit of Work (Olası Kullanım):** Veri erişim katmanının test edilebilirliğini ve esnekliğini artırmak için tasarım desenleri kullanılmıştır.
* **C# ile Geliştirme:** Tüm arka uç mantığı ve veri işleme süreçleri C# dili ile yazılmıştır.

### Modül ve İşlevsellik
* **Ürün ve Stok Yönetimi:** Ürün ekleme, kategorilendirme, stok takibi ve envanter raporlaması.
* **Cari (Müşteri/Tedarikçi) Takibi:** Müşteri ve tedarikçi bilgilerinin kaydı, listelenmesi ve detaylı hareket takibi.
* **Satış ve İşlem Yönetimi:** Sipariş/satış kayıtlarının tutulması, faturalandırma ve gelir-gider takibi.
* **Kullanıcı ve Rol Yönetimi:** Farklı yetki seviyelerine sahip kullanıcılar için **kimlik doğrulama (Authentication)** ve **yetkilendirme (Authorization)** sistemi.
* **Raporlama:** Görsel raporlar ve istatistikler sunarak ticari verilerin analiz edilmesini sağlar (Örn: En çok satan ürünler, aylık gelir grafikleri).

---

## 🚀 Nasıl Çalıştırılır?

Bu proje, bir **SQL Server** veritabanı ve **Visual Studio** ortamını gerektirir.

1.  **Projeyi Klonlama:**
    ```bash
    git clone [https://github.com/abdullahhaktan/MvcOnlineTicariOtomasyon](https://github.com/abdullahhaktan/MvcOnlineTicariOtomasyon)
    cd MvcOnlineTicariOtomasyon
    ```

2.  **Veritabanı Kurulumu:**
    * **SQL Server Management Studio'yu** açın ve yeni bir veritabanı oluşturun.
    * Veritabanı şemasını (tablolar ve ilişkiler) oluşturmak için projenin ilgili veri erişim katmanındaki (genellikle `Web.config` veya `App.config` içinde belirtilir) **Entity Framework Migration** komutlarını çalıştırın veya manuel SQL scriptlerini uygulayın.

3.  **Bağlantı Dizesini Ayarlama:**
    * Projenin ana yapılandırma dosyasındaki (`Web.config` veya modern projelerde `appsettings.json`) **SQL Server bağlantı dizesini** kendi yerel sunucu adınıza ve veritabanı adınıza göre güncelleyin.

4.  **Projeyi Başlatma:**
    * **Visual Studio** ile `.sln` dosyasını açın.
    * Gerekliyse **NuGet** paketlerini geri yükleyin.
    * Uygulamayı çalıştırın (F5). Uygulama, belirtilen yerel adreste tarayıcınızda açılacaktır.

---
---

[EN]

# MvcOnlineTicariOtomasyon

**Comprehensive Online Commercial Automation System Developed Using ASP.NET MVC**

---

## 💻 About the Project

This project is a **comprehensive online commercial automation system** simulation developed using the **ASP.NET MVC** architecture. It covers the core functionalities of an e-commerce platform or an internal inventory management system, demonstrating **advanced database interactions** and **user authorization** practices.

---

## ✨ Core Features

### Architecture and Technical Implementation
* **Model-View-Controller (MVC) Architecture:** Ensures code maintainability by providing a clear separation between business logic, data, and the user interface.
* **Entity Framework (Code First/Database First):** Utilizes Object-Relational Mapping (ORM) for fast and reliable database operations.
* **Repository/Unit of Work (Potential Use):** Design patterns used to enhance the testability and flexibility of the data access layer.
* **C# Development:** All backend logic and data processing are written in the C# language.

### Modules and Functionality
* **Product and Stock Management:** Includes adding products, categorization, inventory tracking, and stock reporting.
* **Customer/Supplier (Account) Tracking:** Recording and listing of customer and supplier information, along with detailed transaction tracking.
* **Sales and Transaction Management:** Recording orders/sales, invoicing, and tracking income/expenses.
* **User and Role Management:** **Authentication** and **Authorization** system for users with different access levels.
* **Reporting:** Provides visual reports and statistics for commercial data analysis (e.g., top-selling products, monthly revenue charts).

---

## 🚀 How to Run

This project requires a **SQL Server** database and a **Visual Studio** environment.

1.  **Cloning the Project:**
    ```bash
    git clone [https://github.com/abdullahhaktan/MvcOnlineTicariOtomasyon](https://github.com/abdullahhaktan/MvcOnlineTicariOtomasyon)
    cd MvcOnlineTicariOtomasyon
    ```

2.  **Database Setup:**
    * Open **SQL Server Management Studio** and create a new database.
    * Apply the **Entity Framework Migration** commands or manual SQL scripts found in the project's data access layer (usually specified in `Web.config` or `App.config`) to build the database schema (tables and relationships).

3.  **Configuring the Connection String:**
    * Update the **SQL Server connection string** in the project's main configuration file (`Web.config` or `appsettings.json` in modern versions) to match your local server name and database name.

4.  **Starting the Project:**
    * Open the `.sln` file with **Visual Studio**.
    * Restore all **NuGet** packages if necessary.
    * Run the application (F5). The application will open in your browser at the specified local address.

---
---

![ticari1](https://github.com/user-attachments/assets/a96b1ec2-4b44-426b-ab50-38c52a081741)

---

![2](https://github.com/user-attachments/assets/1e45f0e3-f247-40b4-b72f-ccfdaa1865e9)

---

![3](https://github.com/user-attachments/assets/6a0509ad-5097-4d97-a23a-b83b1324b7ac)

---
![4](https://github.com/user-attachments/assets/0ced139e-dbc4-4f4a-ae7b-65257ac7b98a)

---

![5](https://github.com/user-attachments/assets/a9ec9439-dae3-4c4e-89e6-52b2b5d653a7)
