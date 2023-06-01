﻿# FinalProject_Rental-Car-Management

Proyek Manajemen Persewaan Mobil adalah aplikasi CRUD sederhana yang dibangun menggunakan bahasa pemrograman Go (Golang) dengan menggunakan framework Gin dan GORM untuk mengelola data persewaan mobil. Aplikasi ini memungkinkan pengguna untuk melakukan operasi dasar seperti membuat, membaca, memperbarui, dan menghapus data pada berbagai entitas yang terkait dengan persewaan mobil.

## Fitur
- Pengelolaan riwayat pemeliharaan mobil
- Pengelolaan data pajak mobil
- Pengelolaan data pengguna
- Pengelolaan data mobil
- Pengelolaan data persewaan
- Pengelolaan data pembayaran

## Struktur Direktori

- `main.go`: File utama yang berisi inisialisasi aplikasi dan routing.
- `controller/`: Direktori yang berisi file-file controller untuk setiap entitas.
- `models/`: Direktori yang berisi file-file model untuk setiap entitas.
- `models/setup.go`: File yang berisi fungsi untuk menghubungkan ke database.
- `README.md`: File yang berisi dokumentasi proyek.

## Instalasi dan Penggunaan

1. Pastikan Anda memiliki Go (Golang) yang terinstal di komputer Anda.
2. Clone repositori ini ke direktori lokal Anda.
3. Buka terminal dan navigasikan ke direktori proyek.
4. Jalankan perintah `go mod tidy` untuk mengunduh dependensi yang diperlukan.
5. Konfigurasi koneksi database pada file `models/setup.go`.
6. Jalankan perintah `go run main.go` untuk menjalankan aplikasi.
7. Aplikasi akan berjalan di `http://localhost:8080`.

## API Endpoints

Berikut adalah daftar API endpoints yang tersedia:

### Riwayat Pemeliharaan Mobil
- `GET/maintenance`: Mengambil daftar riwayat pemeliharaan mobil.
- `GET/maintenance/:id`: Mengambil detail riwayat pemeliharaan mobil berdasarkan ID.
- `POST/maintenance`: Membuat riwayat pemeliharaan mobil baru.
- `PUT/maintenance/:id`: Memperbarui riwayat pemeliharaan mobil berdasarkan ID.
- `DELETE/maintenance/:id`: Menghapus riwayat pemeliharaan mobil berdasarkan ID.

### Data Pajak Mobil

- `GET/taxes`: Mengambil daftar data pajak mobil.
- `GET/taxes/:id`: Mengambil detail data pajak mobil berdasarkan ID.
- `POST/taxes`: Membuat data pajak mobil baru.
- `PUT/taxes/:id`: Memperbarui data pajak mobil berdasarkan ID.
- `DELETE/taxes/:id`: Menghapus data pajak mobil berdasarkan ID.

### Data Pengguna

- `GET/users`: Mengambil daftar data pengguna.
- `GET/users/:id`: Mengambil detail data pengguna berdasarkan ID.
- `POST/users`: Membuat data pengguna baru.
- `PUT/users/:id`: Memperbarui data pengguna berdasarkan ID.
- `DELETE/users/:id`: Menghapus data pengguna berdasarkan ID.

### Data Mobil

- `GET/cars`: Mengambil daftar data mobil.
- `GET/cars/:id`: Mengambil detail data mobil berdasarkan ID.
- `POST/cars`: Membuat data mobil baru.
- `PUT/cars/:id`: Memperbarui data mobil berdasarkan ID.
- `DELETE/cars/:id`: Menghapus data mobil berdasarkan ID.

### Data Persewaan

- `GET/rentals`: Mengambil daftar data persewaan.
- `GET/rentals/:id`: Mengambil detail data persewaan berdasarkan ID.
- `POST/rentals`: Membuat data persewaan baru.
- `PUT/rentals/:id`: Memperbarui data persewaan berdasarkan ID.
- `DELETE/rentals/:id`: Menghapus data persewaan berdasarkan ID.

### Data Pembayaran

- `GET/payments`: Mengambil daftar data pembayaran.
- `GET/payments/:id`: Mengambil detail data pembayaran berdasarkan ID.
- `POST/payments`: Membuat data pembayaran baru.
- `PUT/payments/:id`: Memperbarui data pembayaran berdasarkan ID.
- `DELETE/payments/:id`: Menghapus data pembayaran berdasarkan ID.
