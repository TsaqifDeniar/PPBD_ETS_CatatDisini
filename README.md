# Catat Disini

**Catat Disini** adalah aplikasi pencatatan keuangan pribadi yang dirancang untuk membantu pengguna mengelola pemasukan dan pengeluaran secara efisien. Aplikasi ini menyediakan fitur untuk mencatat setiap transaksi, melihat total saldo, serta memantau laporan keuangan berdasarkan kategori dan waktu.

## Informasi Pengembang

- **Nama**: Tsaqif Deniar B.
- **NRP**: 5025211151
- **Kelas**: Pemrograman Perangkat Bergerak D
- **Mata Kuliah**: Evaluasi Tengah Semester
- **Proyek**: Front End Aplikasi Mobile

## Deskripsi Aplikasi

Dengan antarmuka yang sederhana dan intuitif, pengguna dapat dengan mudah menambahkan, mengelompokkan, dan melacak transaksi harian mereka. Fitur penyimpanan lokal memastikan data tetap aman di perangkat, sehingga pengguna dapat mengaksesnya kapan saja tanpa memerlukan koneksi internet.

## Fitur Utama

### 📊 Halaman Dashboard
Menampilkan ringkasan keuangan pengguna, termasuk:
- Total Saldo
- Total Pemasukan
- Total Pengeluaran (misalnya bulanan)

Memberikan gambaran umum tentang kondisi keuangan secara sekilas.

### ➕ Form Tambah Transaksi
Memungkinkan pengguna menambahkan transaksi baru dengan mengisi detail seperti:
- Tanggal
- Jenis transaksi (pemasukan atau pengeluaran)
- Jumlah uang
- Kategori transaksi

Data yang dimasukkan akan disimpan di penyimpanan lokal menggunakan Room Database.

### 📋 Daftar Transaksi
Menampilkan semua transaksi dalam format daftar. Setiap item mencakup:
- Tanggal
- Jenis transaksi
- Kategori
- Jumlah

Pengguna dapat melihat riwayat transaksi mereka dengan mudah.

### 💾 Penyimpanan Lokal
Menggunakan **Room Database** untuk menyimpan data transaksi secara lokal di perangkat pengguna. Data tetap tersimpan meskipun aplikasi ditutup atau perangkat dimatikan.

### 🔁 Navigasi Antar Halaman
Navigasi intuitif antar halaman utama aplikasi:
- Dashboard → Daftar Transaksi
- Dashboard → Form Tambah Transaksi

Dirancang agar mudah digunakan oleh pengguna.

### 📈 Grafik Sederhana
Visualisasi data keuangan dalam bentuk grafik:
- Pie Chart
- Bar Chart

Grafik membantu pengguna memahami distribusi pemasukan dan pengeluaran berdasarkan kategori atau waktu.

### 🏷️ Kategori Transaksi
Transaksi dapat dikelompokkan ke dalam kategori seperti:
- Makanan
- Transportasi
- Hiburan
- Tagihan
- Gaji
- Dan lain-lain

Fitur ini membantu pengguna menganalisis pola pengeluaran mereka.

---

## Teknologi yang Digunakan
- Android Studio
- Bahasa Pemrograman: Kotlin *(atau Java sesuaikan)*
- Room Persistence Library
- MPAndroidChart *(opsional, jika digunakan untuk grafik)*

---
