# Laporan Portofolio Website
## Naufal Inas Dzaki

---

## Identitas Pembuat

| Keterangan | Detail |
|---|---|
| **Nama** | Naufal Inas Dzaki |
| **Jenis Dokumen** | Laporan Proyek Web Portofolio |
| **Tahun** | 2025 |

---

## 1. Deskripsi Proyek

Proyek ini adalah sebuah **website portofolio pribadi** yang dibuat untuk menampilkan identitas, pengalaman, dan keahlian milik **Naufal Inas Dzaki**. Website dirancang dengan tampilan modern bertema gelap (*dark theme*) dan dibangun menggunakan teknologi web dasar: HTML, CSS, dan JavaScript murni (tanpa framework).

---

## 2. Struktur File Proyek

Proyek ini terdiri dari **5 file** yang saling terhubung:

```
portofolio-naufal/
├── index.html          → Halaman Beranda
├── pengalaman.html     → Halaman Pengalaman
├── kontak.html       → Halaman Kontak
├── style.css           → File CSS bersama (shared stylesheet)
└── laporan.md          → Laporan proyek ini
```

### Penjelasan Setiap File

#### `style.css` — Stylesheet Bersama
File CSS utama yang digunakan oleh ketiga halaman HTML. Berisi:
- Variabel warna (*CSS custom properties*)
- Reset dan base styling
- Komponen navigasi, footer, kartu, tombol, badge, dan tag
- Sistem animasi scroll reveal
- Layout page hero bersama
- Responsivitas untuk perangkat mobile

#### `index.html` — Halaman Beranda
Halaman pertama yang dilihat pengunjung. Berisi:
- Hero section dengan nama besar dan animasi teks latar
- Strip tentang diri (*About*) dengan statistik pencapaian
- Dua kartu navigasi cepat menuju halaman Pengalaman dan Kontak

#### `pengalaman.html` — Halaman Pengalaman
Menampilkan semua riwayat kegiatan secara lengkap. Berisi:
- 5 kartu pengalaman dengan ikon, deskripsi, dan pelajaran yang dipetik
- Timeline kronologi perjalanan kegiatan

#### `kontak.html` — Halaman Kontak
Menampilkan kemampuan dan minat secara visual. Berisi:
- Skill bars (progress bar) per kategori: Olahraga, Teknologi, Esports, Soft Skills
- Tag cloud semua minat
- 6 kotak statistik pencapaian dalam angka
- CTA (*Call to Action*) menuju halaman lain

---

## 3. Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| **HTML5** | Struktur dan konten halaman |
| **CSS3** | Tampilan, animasi, dan layout |
| **JavaScript (Vanilla)** | Animasi scroll reveal & skill bar |
| **Google Fonts** | Font *Bebas Neue*, *DM Sans*, *Playfair Display* |
| **CSS Custom Properties** | Sistem warna yang konsisten antar halaman |
| **IntersectionObserver API** | Animasi elemen saat masuk area tampilan |

---

## 4. Fitur dan Komponen

### Navigasi
- Navbar fixed di atas dengan efek *backdrop blur*
- Link aktif ditandai warna aksen dan garis bawah
- Responsif untuk layar mobile

### Animasi
- **Scroll Reveal** — elemen muncul dengan efek *fade up* saat discroll
- **Skill Bar** — progress bar terisi secara animasi saat masuk tampilan
- **Hero Background Text** — teks besar bergerak perlahan (*parallax drift*)
- **Card Hover** — garis aksen muncul dari atas saat kartu dihover
- **Button Hover** — tombol naik sedikit dengan bayangan warna aksen

### Desain
- Tema gelap (*dark mode*) konsisten di semua halaman
- Palet warna: hitam pekat `#0a0a0a` + aksen kuning-hijau `#d4f04a`
- *Noise texture overlay* untuk kedalaman visual
- Grid layout asimetris untuk tampilan yang tidak generik

---

## 5. Isi Pengalaman yang Ditampilkan

Terdapat **5 pengalaman** yang didokumentasikan dalam website ini:

1. **Turnamen Futsal** — Kompetisi tim olahraga futsal; mengasah kerja tim dan strategi.
2. **Turnamen Mobile Legends** — Kompetisi esports; melatih koordinasi dan keputusan cepat.
3. **Turnamen Sepak Takraw** — Olahraga tradisional akrobatik; melatih fisik dan konsentrasi.
4. **Membuat Game di Alice** — Proyek teknologi menggunakan platform Alice 3D; mengenalkan pemrograman visual.
5. **Organisasi Badminton SMA** — Organisasi ekstrakurikuler di sekolah; membangun jiwa kepemimpinan.

---

## 6. Cara Menggunakan

1. Letakkan semua file (`index.html`, `pengalaman.html`, `kontak.html`, `style.css`) dalam **satu folder yang sama**.
2. Buka file `index.html` menggunakan browser (Chrome, Firefox, Edge, dll.).
3. Navigasi antar halaman menggunakan menu di bagian atas (*navbar*).
4. Website tidak membutuhkan koneksi internet untuk fungsi utama, **kecuali** untuk memuat font dari Google Fonts.

---

## 7. Catatan Tambahan

- Website bersifat **statis** — tidak membutuhkan server atau database.
- Seluruh animasi menggunakan CSS dan JavaScript native, **tanpa library eksternal**.
- Desain sudah **responsif** dan dapat dilihat di perangkat mobile maupun desktop.
- File `style.css` dirancang sebagai *single source of truth* untuk seluruh gaya visual, sehingga perubahan warna atau font cukup dilakukan di satu tempat.

---

*Laporan ini dibuat sebagai dokumentasi proyek portofolio web milik Naufal Inas Dzaki.*
