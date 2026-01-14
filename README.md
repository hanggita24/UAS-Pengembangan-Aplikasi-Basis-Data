Nama  : Hanggita Noupris Sabrina  
NIM   : 20240100054  
Prodi : Informatika
Universitas Siber Muhammadiyah

# Sistem Informasi Perpustakaan Berbasis Web

Aplikasi ini merupakan sistem informasi perpustakaan berbasis PHP dan MySQL yang digunakan untuk mengelola data mahasiswa, buku, transaksi peminjaman, dan pengembalian buku secara terintegrasi.

## Fitur
- CRUD Data Mahasiswa
- CRUD Data Buku
- Transaksi Peminjaman Buku
- Pengembalian Buku (stok otomatis kembali)
- Dashboard terintegrasi

## Teknologi
- PHP Native
- MySQL
- Bootstrap 5
- XAMPP

## Cara Menjalankan Aplikasi

1. Download file app.rar lalu extract
2. Buka XAMPP
3. Jalankan Apache dan MySQL
4. Import database:
   - Buka http://localhost/phpmyadmin
   - Buat database baru dengan nama: `perpustakaan`
   - Import file `database.sql`
5. Salin folder `app` ke: C:\xampp\htdocs\
6. Rename folder `app` menjadi: `perpustakaan`
7. Buka browser dan akses: http://localhost/perpustakaan

## Struktur Aplikasi

perpustakaan/
├── index.php
├── koneksi.php
├── pinjam.php
├── simpan_pinjam.php
├── daftar_peminjaman.php
├── kembalikan.php
├── mahasiswa.php
├── buku.php
└── dst

## Catatan

Aplikasi ini dibuat untuk memenuhi tugas akhir mata kuliah **Pengembangan Aplikasi Basis Data**.
