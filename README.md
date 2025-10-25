# Catatan Anggaran Sederhana 💰

**Catatan Anggaran Sederhana** adalah aplikasi web sederhana untuk mencatat dan mengelola keuangan pribadi secara offline. Dibuat dengan HTML, CSS, dan JavaScript, aplikasi ini menggunakan `localStorage` untuk menyimpan data transaksi, mendukung input pemasukan/pengeluaran, ringkasan harian & bulanan, serta ekspor/impor data. Antarmuka mobile-friendly dirancang dalam bahasa Indonesia dengan desain yang bersih dan intuitif.

## 📋 Fitur Utama

- **Catatan Harian**:
  - Tambah transaksi (pemasukan/pengeluaran) dengan tanggal, jumlah, catatan, dan bukti foto (opsional).
  - Kompresi gambar otomatis (max 800x800px, JPEG quality 0.7).
  - Filter catatan berdasarkan tipe (masuk/keluar).
  - Ringkasan harian (total pemasukan, pengeluaran, dan saldo kumulatif).
  - Hapus catatan individu dengan animasi transisi.

- **Ringkasan Bulanan**:
  - Lihat ringkasan pemasukan, pengeluaran, dan saldo per bulan.
  - Ekspor ringkasan bulanan ke CSV.

- **Pengaturan Data**:
  - Ekspor semua data (termasuk gambar) ke JSON.
  - Impor data JSON (menimpa data lama).
  - Hapus semua data dengan konfirmasi.

- **Desain & UX**:
  - Antarmuka responsif dengan tab navigasi bawah (mobile-friendly).
  - Format Rupiah otomatis untuk input jumlah.
  - Peringatan saldo negatif (< -Rp 50.000) saat input pengeluaran.
  - Modal untuk melihat gambar bukti transaksi dalam ukuran penuh.

- **Teknologi**:
  - Offline-first: Semua data disimpan di `localStorage`.
  - Tidak memerlukan backend atau database.
  - Kompresi gambar menggunakan Canvas API.
  - Font Poppins dari Google Fonts untuk estetika modern.

 ## 📸 Tampilan Aplikasi

Berikut adalah beberapa tangkapan layar (screenshot) untuk melihat bagaimana aplikasi ini bekerja:

### Menu Catatan
![Tampilan Catatan Aplikasi](screenshots/Catatan.png)

### Menu Ringkasan
![Tampilan Ringkasan](screenshots/Ringkasan.png)

### Menu Atur
![Tampilan Atur](screenshots/Atur.png)

## ✨ Cara Pakai 

klik link ini :
[go go go](https://wicky14.github.io/budget/)

