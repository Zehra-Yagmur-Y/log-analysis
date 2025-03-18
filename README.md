# Log Analyzer - Log Analiz Uygulaması

Log Analyzer is a web application developed for analyzing system logs, categorizing errors, and providing detailed log reports. 

 Features
 Group logs by level (INFO, DEBUG, ERROR)
 Filter and search logs by date
 View log summaries
 Identify error categories (Database errors, Connection issues, Unauthorized access, etc.)
 Send email notifications for errors (SMTP)
 AI-powered error analysis (Coming soon)

 Installation & Running
 Backend (Spring Boot)
 Requirements:

Java 17+
Maven
PostgreSQL (If using a database)
Steps:
sh
Kopyala
Düzenle
# Clone the project
git clone https://github.com/username/log-analyzer.git

# Navigate to backend
cd log-analyzer-backend

# Install dependencies and start the application
mvn clean install
mvn spring-boot:run



Log Analyzer, sistem loglarını analiz etmek, hata kategorileri oluşturmak ve detaylı log raporları sunmak için geliştirilmiş bir web uygulamasıdır. 

##  Özellikler
 Logları seviyelerine göre gruplama (**INFO, DEBUG, ERROR**)  
 Logları tarih bazlı filtreleme ve arama  
 Log özetlerini görüntüleme  
 Hata kategorilerini belirleme (**Veritabanı hataları, Bağlantı sorunları, Yetkisiz erişim vb.**)  
 Hata bildirimleri için **E-Posta** gönderme (SMTP)  
 AI destekli hata analizi (Gelecekte eklenecek)  

---

## Kurulum & Çalıştırma

###  Backend (Spring Boot)**
**Gereksinimler:**  
- **Java 17+**  
- **Maven**  
- **PostgreSQL** (Eğer veritabanı kullanıyorsan)  

#### **Adımlar:**
```sh
# Projeyi klonla
git clone https://github.com/kullaniciadi/log-analyzer.git

# Backend dizinine gir
cd log-analyzer-backend

# Maven bağımlılıklarını yükle ve uygulamayı başlat
mvn clean install
mvn spring-boot:run
