# 🏗️ Monolithic App (Spring Boot)

Aplikasi ini adalah contoh implementasi arsitektur monolitik menggunakan Spring Boot. Semua fitur (user & produk) digabung dalam satu codebase dan satu proses deployment.

## 🧱 Teknologi
- Spring Boot
- Spring Data JPA
- MySQL
- Java 17+

## 📦 Fitur
- CRUD User
- CRUD Product
- REST API berbasis Spring MVC

## ▶️ Cara Menjalankan
1. Buat database: `monolithic_db` di MySQL
2. Sesuaikan `application.properties` dengan username/password MySQL kamu
3. Jalankan `MonolithicAppApplication.java`
4. Tes API via Postman di port `8080`

## 📌 Arsitektur Monolitik
Semua modul berada dalam satu aplikasi. Cocok untuk aplikasi kecil hingga menengah. Namun, kurang fleksibel untuk scaling besar.

