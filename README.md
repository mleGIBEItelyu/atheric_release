<div align="center">

  <img src="./assets/atheric-logo-white.png" alt="Atheric AI" width="260" />

  <h3>Terminal Riset, Peramalan Harga & Analitik Pasar Saham IDX Berbasis Kecerdasan Buatan</h3>

  <p>
    <a href="https://github.com/mleGIBEItelyu/atheric_release/releases/latest">
      <img src="https://img.shields.io/badge/Release-Terbaru-3b82f6?style=for-the-badge&logo=github" alt="Release" />
    </a>
    <img src="https://img.shields.io/badge/Platform-Android%2011%2B%20%7C%20Web-2563eb?style=for-the-badge&logo=android" alt="Platform" />
    <img src="https://img.shields.io/badge/Status-Production%20Ready-10b981?style=for-the-badge" alt="Status" />
    <a href="./LICENSE">
      <img src="https://img.shields.io/badge/License-Proprietary-f59e0b?style=for-the-badge" alt="License" />
    </a>
  </p>

</div>

---

## Distribusi Resmi Aplikasi

Repositori ini merupakan portal distribusi publik, publikasi berkas instalasi biner (_installer_), dan pencatatan riwayat rilis resmi (**Changelog**) untuk ekosistem **Atheric**. Kode sumber aplikasi dikembangkan dan dikelola secara privat pada repositori internal guna menjamin integritas infrastruktur peramalan kuantitatif, keamanan kunci otentikasi, serta kepatuhan perlindungan data.

Seluruh berkas biner yang dipublikasikan di kanal ini telah melalui proses kompilasi rilis terverifikasi, optimasi byte code, *tree-shaking*, dan penandatanganan digital (*digital signature*).

---

## Unduh Versi Terbaru

Paket instalasi resmi dapat diunduh langsung melalui rilis GitHub terbaru:

| Platform | Format | Status | Arsitektur | Tautan Unduhan |
| :--- | :--- | :--- | :--- | :--- |
| **Android** | `.apk` | Rilis Terbaru | `arm64-v8a`, `armeabi-v7a`, `x86_64` | [Unduh atheric_release.apk](../../releases/latest/download/atheric_release.apk) |
| **Web Platform** | Web App | Live | Modern Browsers | [Kunjungi Platform Web (atheric.id)](https://atheric.id) |

Riwayat seluruh versi dan catatan pembaruan terdahulu dapat ditinjau pada halaman **[Daftar Rilis](../../releases)**.

---

## Perbandingan Umum: Versi Sebelumnya vs Versi Terbaru

Secara umum, berikut peningkatan dan perbedaan utama versi terbaru dibandingkan versi sebelumnya:

| Aspek & Fitur | Versi Sebelumnya | Versi Terbaru |
| :--- | :--- | :--- |
| **Rangkuman Analisis AI** | Belum tersedia di aplikasi mobile | **Hadir resmi**: Kartu analisis prospek emiten, target harga, batas stop loss, dan sinyal AI |
| **Tampilan Sentimen Pasar** | Speedometer rawan terpotong & teks deskripsi panjang | **Disempurnakan**: Speedometer setengah lingkaran presisi & ringkasan pilar padat |
| **Palet Warna Indikator** | Warna campuran tanpa standarisasi | **Standar Finansial**: Hijau (Untung/BUY), Kuning (HOLD), Merah (Rugi/SELL/Proteksi) |
| **Iconografi AI** | Menggunakan icon sparkle generik | **Icon Robot Engineering** yang bersih dan profesional |
| **Masuk dengan Google** | Transisi autentikasi kadang terhambat | **Optimal**: Alur masuk OAuth langsung diarahkan ke halaman utama |
| **Pembaruan Aplikasi** | Memerlukan pencopotan manual aplikasi lama | **In-App Updater**: Deteksi dan pasang versi baru langsung dari menu Pengaturan |

---

## Rincian Pembaruan Versi Terbaru

- **Rangkuman Analisis AI (AI Synthesis Card):**
  - Implementasi kartu rangkuman prospek emiten pada halaman detail saham mobile dan web.
  - Memuat metrik kuantitatif: **Target Resistensi** (dengan kalkulasi potensi kenaikan), **Batas Stop Loss Proteksi**, dan **Sinyal Rekomendasi Model AI**.
  - Poin analisis padat, terstruktur, dan langsung pada kesimpulan tanpa pengantar bertele-tele.
- **Penyempurnaan Sentimen Pasar Multi-Pilar:**
  - Desain speedometer setengah lingkaran yang presisi tanpa pemotongan visual.
  - Penataan 4 pilar analisis (Berita Media, Kuantitatif Teknikal, Pasar Makro, dan AI Engine) dengan deskripsi ringkas yang terbaca utuh di semua resolusi layar.
  - Penggunaan icon robot AI engineer profesional menggantikan icon sparkle.
- **Penyelarasan Warna Semantik Finansial:**
  - Standar visual navigasi pasar: **Hijau** (Untung / Bullish / BUY), **Kuning** (HOLD / Netral), dan **Merah** (Rugi / Bearish / SELL / Proteksi Risiko) berpadu dengan tema utama Atheric Blue.
- **Penyelarasan Navigasi & Berita Mingguan:**
  - Akses ulasan sentimen mingguan IHSG dan berita pasar terkini lebih responsif.
- **Autentikasi & Pembaruan In-App:**
  - Peningkatan kehandalan masuk dengan akun Google (OAuth) dan deteksi pembaruan otomatis via menu Pengaturan.

---

## Spesifikasi Teknis & Integritas Berkas

Untuk memastikan berkas instalasi yang Anda unduh asli dan belum dimodifikasi oleh pihak ketiga, verifikasi integritas berkas rilis berikut:

| Parameter | Spesifikasi |
| :--- | :--- |
| **Nama Berkas** | `atheric_release.apk` |
| **Kanal Distribusi** | Rilis Publik Terbaru |
| **Ukuran Berkas** | ~61 MB |
| **Target SDK** | Android 14 (API Level 34) |
| **Minimum SDK** | Android 11 (API Level 30) |
| **Algoritma Hash** | `SHA-256` |
| **Nilai Checksum** | `0B9DC2B001F827603DB85BB61A2DB78A8A37AE26571E4085E4F5D222C3FF8CE7` |

### Verifikasi Checksum Mandiri

**Windows (PowerShell):**
```powershell
Get-FileHash .\atheric_release.apk -Algorithm SHA256
```

**macOS / Linux:**
```bash
sha256sum atheric_release.apk
```

Pastikan nilai hash yang dihasilkan identik dengan tabel di atas.

---

## Panduan Pemasangan (Android Sideload)

1. Unduh berkas **`atheric_release.apk`** melalui tautan rilis di atas.
2. Buka berkas APK yang telah selesai diunduh dari bilah notifikasi atau melalui aplikasi **Pengelola Berkas (File Manager)**.
3. Apabila sistem Android meminta konfirmasi keamanan untuk memasang aplikasi dari sumber tidak dikenal:
   - Ketuk **Setelan / Pengaturan**.
   - Aktifkan toggle **Izinkan dari sumber ini** (*Allow from this source*).
4. Ketuk **Pasang / Install** dan tunggu hingga proses selesai.
5. Jalankan aplikasi **Atheric**, kemudian masuk menggunakan akun Anda atau akun Google.

---

## Pembaruan Otomatis

Aplikasi Atheric Mobile telah dilengkapi mekanisme deteksi pembaruan terintegrasi. Anda dapat memeriksa ketersediaan versi baru kapan saja melalui:
> **Menu Navigasi > Pengaturan > Cek Pembaruan**

Sistem akan memvalidasi versi terpasang dengan server rilis dan menyediakan opsi unduh langsung tanpa perlu mencopot aplikasi sebelumnya.

---

## Lisensi & Hak Cipta

Distribusi biner aplikasi ini dilindungi di bawah ketentuan lisensi hak cipta proprietary **Atheric AI**. Rincian lisensi penggunaan dapat dibaca pada berkas [LICENSE](./LICENSE).

Seluruh hak cipta atas algoritma peramalan, model kecerdasan buatan, arsitektur data kuantitatif, dan identitas visual merupakan milik sah Atheric AI.

---

## Pernyataan Penyangkalan (Financial Disclaimer)

> **PERINGATAN RISIKO:**
> Seluruh informasi, data statistik, analisis sentimen, peramalan harga, dan rangkuman kecerdasan buatan yang disajikan dalam aplikasi Atheric merupakan **alat bantu analisis riset dan edukasi keputusan investasi**. Konten yang dihasilkan **bukan merupakan anjuran, ajakan, rekomendasi pasti, atau jaminan keuntungan** untuk melakukan transaksi jual atau beli pada instrumen pasar modal manapun. Keputusan investasi sepenuhnya merupakan tanggung jawab dan hak prerogatif masing-masing investor.

---

<div align="center">
  <sub>Hak Cipta © 2026 Atheric AI. Seluruh hak cipta dilindungi undang-undang.</sub>
</div>
