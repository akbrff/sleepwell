# 🏨 Sleepwell - Sistem Reservasi Hotel

Sleepwell adalah aplikasi desktop berbasis **Java GUI** dan **MySQL** yang dirancang untuk mempermudah operasional penginapan atau hotel berskala kecil hingga menengah. Sistem ini mendigitalisasi alur kerja manual menjadi sistematis, aman, dan tersinkronisasi.

## ✨ Fitur Utama
* **Manajemen Kamar:** Menambah, mengedit, menghapus, dan melihat status ketersediaan kamar secara *real-time*.
* **Manajemen Tamu:** Pendataan informasi tamu yang menginap.
* **Sistem Transaksi:** Mengelola alur *Check-in* dan otomatisasi *Check-out* tamu beserta kalkulasi total biayanya.
* **Sinkronisasi Otomatis:** Status kamar akan otomatis berubah menjadi "Tersedia" kembali ketika tamu di-*checkout*.
* **Keamanan Admin:** Otorisasi menggunakan *password* untuk tindakan krusial seperti menghapus atau mengedit data transaksi.
* **Cetak Laporan:** Fitur *live search* dan ekspor data tabel menjadi laporan berformat HTML/PDF.
* **Cetak Invoice:** Fitur *generate* struk/invoice otomatis dalam format HTML yang responsif, terstruktur, dan siap cetak (terintegrasi langsung dengan *browser* bawaan).

## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Java (Visual GUI / Swing)
* **IDE:** Apache NetBeans
* **Database:** MySQL (XAMPP / phpMyAdmin)
* **Library Tambahan:** JDBC Driver (untuk koneksi database)

## 👥 Tim Pengembang

Aplikasi ini dibangun sebagai tugas mata kuliah Pemrograman 1 pada program studi Teknik Informatika, Universitas Pamulang.

| Nama Lengkap | NIM | Peran Utama | Deskripsi Tugas |
| :--- | :--- | :--- | :--- |
| **Muhamad Akbar Febiansyah** | 241011402265 | Team Leader & Lead Developer | Merancang sistem, *Full-Stack Coding*, desain UI/UX, dan Arsitek Database. |
| **Bagas Dwi Prasojo** | 241011402570 | Multimedia Specialist & GUI Programmer | Mengelola produksi video presentasi dan merancang implementasi grafis antarmuka. |
| **Melani Alisya Putri** | 241011401658 | Technical Writer & System Analyst | Menganalisis alur bisnis sistem, menyusun dokumentasi, dan membuat laporan akhir. |
| **Muhammad Asyhadullah** | 241011402474 | Database Administrator & UI/UX Researcher | Mengelola struktur *database* relasional dan menganalisis kenyamanan pengguna. |
| **Muhammad Azis** | 241011400392 | QA & Software Tester | Melakukan pengujian fitur aplikasi secara menyeluruh dan mencari *bug* (*debugging*). |

## 🚀 Cara Menjalankan Aplikasi

1. Clone repository ini ke komputer lokal Anda:
```bash
   git clone [https://github.com/akbrff/sleepwell.git](https://github.com/akbrff/sleepwell.git)
```
2. Pastikan XAMPP (Apache & MySQL) dalam keadaan menyala.

3. Import file database sleepwell.sql ke dalam phpMyAdmin lokal Anda.

4. Buka folder project menggunakan Apache NetBeans.

5. Sesuaikan konfigurasi username dan password pada package koneksi.java (jika diperlukan).

6. Jalankan (Run) aplikasi dimulai dari file FormLogin.java atau index.java.

Dibuat dengan ❤️ oleh Kelompok Kami 
