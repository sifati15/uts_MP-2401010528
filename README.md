Runaway QQ App
Deskripsi Aplikasi

Runaway QQ merupakan aplikasi mobile sederhana berbasis Flutter yang dikembangkan sebagai bagian dari praktikum Mobile Programming. Aplikasi ini dirancang untuk mengimplementasikan sistem autentikasi dasar yang terdiri dari halaman Login, Lupa Password, dan Dashboard.

Pengembangan aplikasi ini berfokus pada penerapan konsep dasar Flutter, seperti validasi form pada sisi klien, pengelolaan state sederhana, navigasi antar halaman, serta perancangan antarmuka pengguna dengan tema gelap (dark theme).

Fitur Utama
1. Halaman Login
Form input Email dan Password
Validasi data:
Email wajib diisi dan sesuai format
Password minimal 8 karakter dan mengandung huruf serta angka
Fitur show/hide password
Indikator loading saat proses login
Menampilkan pesan menggunakan Snackbar
Navigasi ke halaman Dashboard jika login berhasil
Navigasi ke halaman Lupa Password
2. Halaman Lupa Password
Form input email dengan validasi format
Tombol kirim link reset password
Indikator loading saat proses berlangsung
Menampilkan pesan menggunakan Snackbar
Navigasi kembali ke halaman Login
3. Halaman Dashboard
AppBar dengan judul dan tombol logout
Menampilkan informasi pengguna yang login
Navigasi menggunakan Drawer
Menampilkan daftar data menggunakan ListView.builder
Penggunaan Card dengan desain yang rapi
Fitur logout kembali ke halaman login
Teknologi yang Digunakan
Flutter (versi stable)
Dart (dengan null safety)
Material Design
Komponen dan Widget
Basic Widgets

Scaffold, Text, Container, Icon, ElevatedButton

Layout Widgets

Column, Row, Padding, SizedBox, SafeArea, Expanded

Advanced Widgets

TextFormField, ListView.builder, Card, Snackbar

State Management

Aplikasi ini menggunakan pendekatan setState() untuk mengelola beberapa state utama, yaitu:

isLoading: digunakan untuk menampilkan indikator loading
errorMessage: menyimpan pesan kesalahan
isPasswordVisible: mengatur visibilitas password
Data pengguna: dikirim ke halaman dashboard setelah login berhasil
Cara Menjalankan Aplikasi

Langkah-langkah untuk menjalankan aplikasi:

flutter pub get
flutter run

