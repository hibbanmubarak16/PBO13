# 🧩 Tugas Pertemuan 13 — Penerapan Login dengan Java Persistence API (JPA)

Proyek ini merupakan implementasi sistem **Login dan Manajemen Akun** menggunakan **Java Swing** dan **JPA (EclipseLink)** yang terhubung ke **database PostgreSQL**.  
Aplikasi ini dikembangkan sebagai tugas mata kuliah **Pemrograman Berorientasi Objek (PBO)**, dengan fokus pada penerapan **Java Persistence** dan **Entity Relationship** dalam aplikasi GUI.

---

## 🚀 Fitur Utama

### 🔐 1. Login User
- Validasi `username` dan `password` menggunakan data dari tabel `akun` di database.
- Jika login berhasil, pengguna diarahkan ke halaman utama (`GuiDatabase`) dengan sapaan “Selamat datang, *username*!”.
- Jika gagal, muncul notifikasi kesalahan.

### 🧾 2. Register (Buat Akun)
- Pengguna dapat membuat akun baru melalui form pendaftaran.
- Data tersimpan otomatis ke tabel `akun` dengan validasi agar tidak ada username duplikat.

### 🔁 3. Lupa/Ubah Password
- Pengguna dapat mencari username-nya.
- Jika username ditemukan, field untuk memasukkan password baru akan muncul.
- Password diperbarui langsung di database menggunakan `EntityManager` JPA.

### 💾 4. Integrasi Database
- Menggunakan **PostgreSQL** sebagai sistem manajemen basis data.
- Dikelola melalui `persistence.xml` dengan `EclipseLink (JPA 2.2)`.

---

## ⚙️ Teknologi yang Digunakan
- Java 17+
- NetBeans IDE
- PostgreSQL
- EclipseLink (JPA 2.2)
- Swing GUI

---
### ✍️ Penulis
Hibban

Mahasiswa Sistem Informasi

Semester 3

Universitas Islam Negeri Sunan Ampel Surabaya
