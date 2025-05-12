# Web Automation Framework

## 🚀 Deskripsi Proyek
Proyek Web Automation ini adalah kerangka pengujian otomatis yang dikembangkan menggunakan Selenium WebDriver dan TestNG. Framework ini dirancang untuk memudahkan pengujian fungsional pada aplikasi web secara sistematis dan scalable.

## ✨ Fitur Utama
- 🔍 Implementasi Page Object Model (POM)
- 🧪 Integrasi TestNG untuk manajemen test suite
- 🌐 Dukungan multi-browser
- 📦 Manajemen WebDriver otomatis
- 🛠️ Konfigurasi fleksibel
- 📊 Pelaporan terintegrasi

## 📋 Prasyarat
- Java Development Kit (JDK) 11 atau lebih baru
- Maven 3.6+
- Browser web (Chrome, Firefox, dll)

## 🛠️ Teknologi yang Digunakan
- **Automation Tools**: 
  - Selenium WebDriver
  - TestNG
- **Dependency Management**: Maven
- **WebDriver Management**: WebDriverManager
- **Reporting**: TestNG Built-in Reporting

## 🔧 Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/[username]/[repository-name].git
cd [repository-name]
```

### 2. Instal Dependencies
```bash
mvn clean install
```

## 🚦 Menjalankan Tests

### Menjalankan Seluruh Test Suite
```bash
mvn test
```

### Menjalankan Test Spesifik
```bash
mvn test -Dtest=NamaKelasTest
```

## 📂 Struktur Proyek
```
project-root/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/projectname/
│   │           ├── pages/         # Page Object Classes
│   │           └── utils/         # Utility Classes
│   │
│   └── test/
│       └── java/
│           └── com/projectname/
│               └── tests/         # Test Cases
│
├── resources/
│   ├── config.properties
│   └── testdata/
│
├── pom.xml
└── README.md
```

## 🔐 Konfigurasi
Konfigurasikan parameter pengujian di `resources/config.properties`:
- Browser
- URL Aplikasi
- Kredensial Uji

## 📝 Panduan Kontribusi
1. Fork repository
2. Buat branch fitur (`git checkout -b fitur/AturFitur`)
3. Commit perubahan (`git commit -m 'Tambah fitur baru'`)
4. Push ke branch (`git push origin fitur/AturFitur`)
5. Buat Pull Request

## 🐛 Menangani Masalah
- Periksa [Issues](https://github.com/[username]/[repository-name]/issues)
- Laporkan bug dengan detail yang jelas

## 📊 Laporan Test
- Laporan otomatis dihasilkan di direktori `target/surefire-reports/`
- Buka `index.html` untuk melihat detail lengkap

## ⚠️ Catatan Penting
- Selalu update WebDriver dan browser
- Gunakan wait eksplisit untuk elemen dinamis
- Pertahankan modularitas kode

## 👥 Kontributor
- [Nama Anda] - *Inisiator Proyek*

## 🔗 Referensi
- [Selenium Documentation](https://www.selenium.dev/documentation/)
- [TestNG Documentation](https://testng.org/)
- [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)

---

**Catatan**: Sesuaikan informasi yang ada dengan detail spesifik proyek Anda.
