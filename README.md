# Money Tracker Web

## Deskripsi

Money Tracker adalah aplikasi berbasis web sederhana yang digunakan untuk mencatat pemasukan dan pengeluaran. Aplikasi ini memungkinkan pengguna untuk mengelola transaksi keuangan, mengelompokkan berdasarkan kategori, serta melihat laporan keuangan secara real-time.

Aplikasi ini dibuat sebagai implementasi dari perancangan sistem pada Daily Project 6.

---

## Fitur Utama

* Menambahkan transaksi (pemasukan & pengeluaran)
* Menentukan kategori transaksi (Makanan, Transport, Gaji, Lainnya)
* Menampilkan daftar transaksi dalam bentuk tabel
* Menghapus transaksi
* Filter transaksi berdasarkan tipe (semua, pemasukan, pengeluaran)
* Menghitung saldo otomatis
* Menampilkan total pemasukan dan total pengeluaran
* Penyimpanan data menggunakan LocalStorage (data tetap tersimpan di browser)

---

## Kesesuaian dengan Use Case (DP6)

| Use Case            | Implementasi di Sistem             |
| ------------------- | ---------------------------------- |
| Tambah Transaksi    | Form input deskripsi, jumlah, tipe |
| Kelola Kategori     | Dropdown kategori                  |
| Lihat Laporan       | Tabel transaksi + saldo + total    |
| Monitoring Keuangan | Total pemasukan & pengeluaran      |
| Hapus Data          | Tombol hapus pada tabel            |

---

## Teknologi yang Digunakan

* HTML
* CSS
* JavaScript (Vanilla)
* LocalStorage (untuk penyimpanan data)

---

## Cara Menjalankan

1. Download atau clone repository ini
2. Buka file `index.html` di browser
3. Aplikasi langsung bisa digunakan tanpa instalasi tambahan

---

##  Pengujian Sistem

| No | Aspek       | Skenario                       | Hasil    |
| -- | ----------- | ------------------------------ | -------- |
| 1  | Fungsional  | Menambah transaksi             | Berhasil |
| 2  | Fungsional  | Menghapus transaksi            | Berhasil |
| 3  | Fungsional  | Filter transaksi               | Berhasil |
| 4  | Fungsional  | Perhitungan saldo              | Berhasil |
| 5  | Usability   | Tampilan mudah dipahami        | Baik     |
| 6  | Reliability | Data tersimpan di LocalStorage | Berhasil |
| 7  | Performance | Aplikasi berjalan lancar       | Baik     |

---

## Keterbatasan Sistem

* Belum mendukung login pengguna
* Belum tersedia grafik atau visualisasi data
* Data hanya tersimpan di browser (tidak berbasis cloud)
* Belum ada fitur manajemen anggaran

---

## Kesimpulan

Aplikasi Money Tracker berhasil diimplementasikan sesuai dengan kebutuhan utama yang telah dirancang pada tahap analisis. Sistem dapat digunakan untuk pencatatan keuangan sederhana dengan fitur utama seperti transaksi, kategori, dan laporan keuangan dasar.

---
