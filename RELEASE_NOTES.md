# Catatan Rilis (Release Notes)

Dokumen ini memuat rangkuman pembaruan, perbandingan fitur, serta catatan perubahan teknis untuk setiap rilis **Atheric Mobile**.

---

### Rilis Terbaru (v1.0.2)

Pembaruan rilis terbaru menghadirkan fitur **Rangkuman Analisis AI (AI Synthesis)**, penyempurnaan kartu **Sentimen Pasar multi-pilar**, standarisasi **warna semantik finansial**, perbaikan proses masuk Google, dan peningkatan performa serta stabilitas aplikasi.

#### Perbandingan Fitur: Versi Sebelumnya vs Rilis Terbaru

| Aspek & Fitur | Versi Sebelumnya | Rilis Terbaru |
| :--- | :--- | :--- |
| **Rangkuman Analisis AI** | Belum tersedia di aplikasi mobile | **Hadir resmi**: Kartu analisis prospek emiten, target resistensi, batas proteksi stop loss, dan sinyal AI |
| **Tampilan Sentimen Pasar** | Speedometer rawan terpotong & teks deskripsi panjang | **Disempurnakan**: Speedometer setengah lingkaran presisi & ringkasan pilar padat |
| **Palet Warna Indikator** | Warna campuran tanpa standarisasi | **Standar Finansial**: Hijau (Untung/BUY), Kuning (HOLD), Merah (Rugi/SELL/Proteksi) |
| **Iconografi AI** | Menggunakan icon sparkle generik | **Icon Robot Engineering** yang bersih dan profesional |
| **Masuk dengan Google** | Transisi autentikasi kadang terhambat | **Optimal**: Alur masuk OAuth langsung diarahkan ke halaman utama |
| **Pembaruan Aplikasi** | Memerlukan pencopotan manual aplikasi lama | **In-App Updater**: Deteksi dan pasang rilis baru langsung dari menu Pengaturan |

#### Rincian Pembaruan

- **Rangkuman Analisis AI (AI Synthesis Card):**
  - Implementasi kartu rangkuman prospek emiten pada halaman detail saham mobile dan web.
  - Memuat 3 metrik kuantitatif: **Target Resistensi** (dengan estimasi potensi kenaikan), **Batas Stop Loss Proteksi**, dan **Sinyal Rekomendasi Model AI**.
  - Poin analisis padat, terstruktur, dan langsung pada kesimpulan tanpa pengantar bertele-tele.
- **Penyempurnaan Sentimen Pasar Multi-Pilar:**
  - Desain speedometer setengah lingkaran yang presisi tanpa pemotongan visual pada berbagai ukuran layar.
  - Penataan 4 pilar analisis (Berita Media, Kuantitatif Teknikal, Pasar Makro, dan AI Engine) dengan ringkasan padat satu baris yang terbaca utuh.
  - Penggunaan icon robot AI engineer profesional menggantikan icon sparkle.
- **Penyelarasan Warna Semantik Finansial:**
  - Standar visual pasar modal: **Hijau** (Untung / Bullish / BUY), **Kuning** (HOLD / Netral), dan **Merah** (Rugi / Bearish / SELL / Proteksi Risiko) berpadu harmonis dengan tema utama Atheric Blue.
- **Penyelarasan Navigasi & Berita Mingguan:**
  - Akses ulasan sentimen mingguan IHSG dan berita pasar terkini lebih responsif.
- **Autentikasi & Pembaruan In-App:**
  - Peningkatan kehandalan alur masuk akun Google (OAuth).
  - Deteksi dan pemasangan rilis baru langsung via menu Pengaturan aplikasi.

---

### Riwayat Rilis Sebelumnya

Untuk melihat arsip rilis terdahulu dan mengunduh berkas biner versi sebelumnya, kunjungi halaman [GitHub Releases](https://github.com/mleGIBEItelyu/atheric_release/releases).
