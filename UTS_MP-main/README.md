# 🚀 Runaway QQ App

## 📱 Deskripsi Aplikasi
Runaway QQ adalah aplikasi mobile sederhana berbasis Flutter yang dikembangkan sebagai bagian dari praktikum Mobile Programming.  
Aplikasi ini mengimplementasikan sistem autentikasi dasar yang terdiri dari halaman Login, Lupa Password, dan Dashboard.

Fokus utama aplikasi ini adalah penerapan:
- Form validation (client-side)
- State management sederhana
- Navigasi antar halaman
- UI modern dengan tema dark

---

## ✨ Fitur Utama

### 🔐 Login Screen
- Input Email & Password
- Validasi:
  - Email wajib & format valid
  - Password minimal 8 karakter (huruf & angka)
- Toggle show/hide password
- Loading indicator saat login
- Snackbar untuk feedback (success / error)
- Navigasi ke:
  - Dashboard (jika login berhasil)
  - Lupa Password

### 🔑 Lupa Password Screen
- Input email dengan validasi format
- Tombol kirim link reset
- Loading indicator
- Feedback menggunakan Snackbar
- Navigasi kembali ke halaman login

### 📊 Dashboard Screen
- AppBar dengan tombol logout
- Menampilkan data user login
- Sidebar / Drawer navigation
- List data menggunakan `ListView.builder`
- Card UI dengan styling modern
- Logout kembali ke login screen

---

## 🧱 Teknologi & Konsep yang Digunakan

- Flutter (Stable Version)
- Dart (Null Safety Enabled)
- Material Design

### Widget yang Digunakan:
- Basic: `Scaffold`, `Text`, `Container`, `Icon`, `ElevatedButton`
- Layout: `Column`, `Row`, `Padding`, `SizedBox`, `SafeArea`, `Expanded`
- Advanced:
  - `TextFormField`
  - `ListView.builder`
  - `Card`
  - `Snackbar`

---

## 🧠 State Management
Aplikasi ini menggunakan **setState()** untuk mengelola state berikut:
- `isLoading` → indikator loading saat proses login/reset
- `errorMessage` → pesan error
- `isPasswordVisible` → toggle visibility password
- Data user login → ditampilkan di dashboard

---


Update: login screen added
git add .
git commit -m "add form validation login"
git push
git add .
git commit -m "add forgot password feature"
git push
git add .
git commit -m "add dashboard UI"
git push