# 📘 Project CodeIgniter 4 - CRUD Mahasiswa (Modul 1)

# NAMA : USWATUN HASANAH
# NIM : 312410163

## 📌 Deskripsi Project

Project ini adalah aplikasi sederhana berbasis **CodeIgniter 4** yang digunakan untuk mengelola data mahasiswa menggunakan fitur CRUD (Create, Read, Delete).

---

## ⚙️ Teknologi yang Digunakan

* PHP 8.2
* CodeIgniter 4
* MySQL / MariaDB (XAMPP)
* Apache (XAMPP)
* VS Code

---

## 🚀 Fitur Aplikasi

* Menampilkan data mahasiswa (READ)
* Menambah data mahasiswa (CREATE)
* Menghapus data mahasiswa (DELETE)
* Koneksi database MySQL

---

## 🗄️ Struktur Database

Database: `ci4_db`
Tabel: `mahasiswa`

```sql
CREATE TABLE mahasiswa (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nama VARCHAR(100),
    nim VARCHAR(20),
    jurusan VARCHAR(100)
);
```

---

## 📂 Struktur Folder Penting

```
app/
 ├── Controllers/
 │     └── Mahasiswa.php
 ├── Models/
 │     └── MahasiswaModel.php
 ├── Views/
 │     └── mahasiswa/
 │           ├── index.php
 │           └── create.php
```

---

## ⚡ Cara Menjalankan Project

1. Clone / extract project ke folder:

```
C:\xampp\htdocs\lab11_ci\ci4
```

2. Jalankan XAMPP:

* Apache ✔
* MySQL ✔

3. Start server CodeIgniter:

```bash
C:\xampp\php\php.exe spark serve
```

4. Buka browser:

```
http://localhost:8080/mahasiswa
```

---

## 🧠 Catatan

* Pastikan ekstensi `mysqli` aktif di php.ini
* Database sudah dibuat di phpMyAdmin atau MySQL
* CI_ENVIRONMENT = development

---

## 🎯 Output

Aplikasi akan menampilkan data mahasiswa dan bisa melakukan tambah serta hapus data.

---

## ✨ Status Project

✔ Selesai (Modul 1 CRUD dasar CI4)
