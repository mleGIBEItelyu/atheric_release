<div align="center">

  <img src="./assets/atheric-logo-white.png" alt="Atheric AI" width="240" />

  <p><strong>Terminal Riset, Peramalan Harga & Analitik Pasar Saham Indonesia Berbasis Kecerdasan Buatan</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Platform-Android%20%7C%20Web-4F7DFF?style=for-the-badge" alt="Platform" />
    <img src="https://img.shields.io/badge/Status-Production%20Ready-2EC27A?style=for-the-badge" alt="Status" />
    <img src="https://img.shields.io/badge/Release-v1.0.0-gold?style=for-the-badge" alt="Version" />
  </p>

</div>

---

## Distribusi Resmi Aplikasi

Repositori ini dikhususkan sebagai kanal rilis publik, distribusi paket instalasi (*installer*), dan dokumentasi versi aplikasi **Atheric**. Source code utama dikembangkan dan dikelola secara terpusat di repositori internal privat untuk menjaga integritas sistem dan keamanan layanan.

Setiap berkas instalasi yang dipublikasikan di sini dibangun secara otomatis melalui pipeline CI/CD GitHub Actions terverifikasi langsung dari kode sumber resmi.

---

## Unduh Versi Terbaru

Berkas rilis resmi dapat diunduh melalui tabel berikut atau melalui halaman rilis publik:

| Platform | Format | Status | Tautan Unduhan |
| :--- | :--- | :--- | :--- |
| Android | APK | Stabil | [Unduh Paket APK Terbaru](../../releases/latest) |
| Web Application | Browser | Live | [Kunjungi Platform Web](https://atheric.id) |

Seluruh arsip versi terdahulu dan catatan pembaruan (*changelog*) dapat diakses pada halaman **[Daftar Rilis](../../releases)**.

---

## Panduan Instalasi Android

1. Unduh berkas `app-release.apk` dari tautan rilis terbaru di atas.
2. Buka berkas yang telah selesai diunduh melalui notifikasi unduhan atau pengelola berkas (*File Manager*) perangkat Anda.
3. Apabila sistem menampilkan konfirmasi izin keamanan instalasi aplikasi luar:
   - Pilih **Pengaturan** pada dialog yang muncul.
   - Aktifkan opsi **Izinkan dari sumber ini** (*Allow from this source*).
4. Lanjutkan proses pemasangan hingga selesai.
5. Jalankan aplikasi Atheric, lalu masuk dengan akun terdaftar atau buat akun baru.

---

## Pembaruan Aplikasi

Aplikasi mobile dilengkapi dengan fitur pembaruan terintegrasi pada menu **Pengaturan > Pembaruan Aplikasi**. Saat versi baru tersedia, sistem akan mendeteksi dan memandu pengunduhan berkas pembaruan secara langsung.

---

## Verifikasi & Keamanan

Setiap berkas rilis melewati tahapan validasi otomatis sebelum dipublikasikan:
- Pemindaian integritas kode dan ketergantungan paket.
- Kompilasi biner langsung di lingkungan *runner* GitHub Actions yang terisolasi.
- Tanda tangan digital (*release signature*) untuk memastikan aplikasi terbebas dari modifikasi tidak resmi.

---

<div align="center">
  <sub>Hak Cipta © 2026 Atheric AI. Seluruh hak cipta dilindungi undang-undang.</sub>
</div>
