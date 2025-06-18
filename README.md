# IoCatering-Web-PHP-Bootsrap

## Sistem Iocatering Pemesanan Makanan & Minuman untuk Acara 
Sistem ini merupakan aplikasi iocatering pemesanan catering berbasis web yang dikembangkan menggunakan **PHP Native** dan **Database SQL**. Sistem dirancang untuk melayani proses pemesanan catering makanan dan minuman untuk acara tertentu secara efisien 

## 📦 Teknologi yang Digunakan

- **Bahasa Pemrograman:** PHP dengan Framework Boostrap
- **Database:** SQL (MySQL / MariaDB)

## 🔐 Login Admin

Untuk kebutuhan pengujian atau penggunaan awal, sistem menyediakan akun admin default dengan kredensial berikut:

- **Username:** `admin`
- **Password:** `admin`

> Catatan: Username dan password ini disimpan secara hardcoded dalam sistem. Setelah deploy ke produksi, disarankan untuk mengubah metode autentikasi agar lebih aman.

Akun karyawan dapat dibuat melalui dashboard admin setelah login.

---

## 👥 Jenis Pengguna dan Fungsionalitas

### 1. Pelanggan
Pengguna yang ingin melakukan pemesanan makanan dan minuman. Fitur yang tersedia untuk pembeli meliputi:

- Menampilkan daftar menu
- Menambahkan item ke keranjang
- Checkout pesanan


### 2. Karyawan
Bertugas menangani proses pemesanan yang masuk. Fitur utama untuk karyawan antara lain:

- Melihat daftar pesanan masuk
- Mengonfirmasi pembayaran dan invoice
- Memproses dan menyelesaikan pesanan
- Mengelola daftar menu (tambah/edit/hapus item)

### 3. Admin
Memiliki hak akses penuh terhadap sistem. Fitur yang dapat diakses oleh admin meliputi:

- Pengaturan harga dan daftar menu
- Pencatatan arus kas harian
- Pembuatan akun karyawan
- Melihat dan menyusun laporan penjualan

---
[Manual_Book WEB IOCatering.pdf](https://github.com/miftahnur21/IOCatering-Web-PHP-Native/blob/main/SDD%20%26%20Manual%20Book/Manual_Book%20WEB%20IOCatering.pdf)
