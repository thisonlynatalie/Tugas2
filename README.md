# 🧩 Tugas 2: MySQL to JSON - JSON to PHP Array/Object

Repositori ini berisi pengerjaan **tugas praktikum Rekayasa Web** yang berfokus pada **pengambilan data dari MySQL**, konversi ke **format JSON**, serta **penampilan hasil decode JSON dalam bentuk tabel HTML** menggunakan PHP.

---

## ✒️ Deskripsi Tugas

Tugas ini memiliki satu bagian utama, yaitu:

### Soal: MySQL to JSON - JSON to PHP Array/Object
1. Membuat script PHP untuk mengambil data dari tabel `wisata` di database MySQL.
2. Mengonversi data tersebut menjadi format **JSON** menggunakan `json_encode()`.
3. Mengambil kembali data JSON menggunakan `json_decode()`.
4. Menampilkan hasil decode dalam bentuk **tabel HTML** di browser.

---

## 📂 Struktur Repositori

- **getWisata.php** → Mengambil data dari MySQL dan mengonversinya ke format JSON.  
- **tampilWisata.php** → Mengambil data JSON dan menampilkannya dalam bentuk tabel HTML.  
- **db_json.sql** → File database berisi tabel `wisata`.  
---

## 📸 Hasil Screenshot

Berikut adalah hasil output saat dijalankan di browser:

![Hasil Output](https://raw.githubusercontent.com/thisonlynatalie/Tugas2/main/images/Screenshot1.png)

## ⚙️ Teknologi yang Digunakan

- **PHP 8.1 (atau versi yang kompatibel)**  
- **MySQL Database**  
- **Web Server Lokal (XAMPP dengan Apache dan MySQL)**  
- **Browser (Chrome / Edge / Firefox)**

---

## 🚀 Cara Menjalankan

Untuk menjalankan script ini di lingkungan lokal, ikuti langkah-langkah berikut:

### 1️⃣ Clone Repositori
```bash
git clone https://github.com/thisonlynatalie/Tugas2.git
2️⃣ Pindahkan Folder

Pindahkan folder hasil clone ke dalam direktori htdocs di XAMPP Anda.
Contoh path:

C:\xampp\htdocs\Tugas2

3️⃣ Jalankan XAMPP

Buka XAMPP Control Panel, lalu aktifkan service Apache dan MySQL.

4️⃣ Import Database

Buka phpMyAdmin

Buat database baru bernama json

Import file db_json.sql yang tersedia di repositori ini

5️⃣ Jalankan di Browser

Akses URL berikut:

http://localhost/Tugas2-MySQL-JSON/tampilWisata.php

👨‍🎓 Informasi Mahasiswa

Nama: Natalie Gabriel I
NIM/NPM: G.231.23.0050
Kelas: Teknik Informatika A2
Dosen Pengampu: Dicky Yudha Pratama, M.Kom
