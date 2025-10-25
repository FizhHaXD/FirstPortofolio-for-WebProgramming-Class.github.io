# Tugas Pemrograman Web - Portfolio Website

## Identitas
- **Nama:** Muhammad Hafizh Wijdan
- **NIM:** 202431005
- **Program Studi:** Teknik Informatika
- **Institusi:** Institut Teknologi PLN
- **Mata Kuliah:** Pemrograman Web
- **Deskripsi Tugas:** Membuat Website Portfolio Responsif

## Deskripsi Proyek
Website portfolio responsif yang menampilkan informasi personal, keahlian, dan proyek-proyek yang telah dikerjakan. Website ini dibuat menggunakan HTML dan CSS murni tanpa framework, menerapkan konsep desain responsif dan modern.

## Fitur Website
1. **Halaman Beranda (`index.html`)**
   - Header dengan navigasi responsif
   - Hero section dengan foto profil
   - Bagian "Tentang Saya"
   - Keahlian dalam bentuk grid box responsif
   - Footer dengan link ke IT PLN

2. **Halaman Portofolio (`portfolio.html`)**
   - Tabel responsif menampilkan data proyek
   - Minimal 5 proyek dengan detail:
     - Nama Proyek
     - Tahun Pembuatan
     - Teknologi yang Digunakan
     - Status
     - Link Demo (gambar/video)

3. **Halaman Kontak (`contact.html`)**
   - Form request project responsif
   - Input fields:
     - Nama
     - Email
     - Jenis Layanan (dropdown)
     - Deskripsi Proyek
     - Preferensi Kontak
     - Checkbox persetujuan

## Teknologi yang Digunakan
- HTML5 Semantic
- CSS3 dengan Fitur Modern:
  - CSS Variables (Custom Properties)
  - Flexbox & Grid Layout
  - Media Queries untuk Responsivitas
  - Gradients & Animations
- Google Fonts (Inter & Poppins)

## Struktur Proyek

```
.
├── index.html           # Halaman utama
├── portfolio.html       # Halaman portfolio/data proyek
├── contact.html         # Halaman kontak
├── style.css           # Stylesheet utama
└── src/                # Folder aset
    ├── video/          # Video demo proyek
    └── *.png, *.jpeg   # Gambar proyek
```

## Cara Deploy ke GitHub Pages

1. Buat repository baru di GitHub
2. Upload semua file ke repository
3. Di repository settings, aktifkan GitHub Pages:
   - Buka tab "Settings"
   - Pilih "Pages" di sidebar
   - Di "Source", pilih branch "main"
   - Klik "Save"

Struktur repository di GitHub harus seperti ini:
```
your-username.github.io/
├── index.html
├── portfolio.html
├── contact.html
├── style.css
└── src/
    └── [semua aset]
```

## Responsive Breakpoints
- Mobile: < 520px
- Tablet: 520px - 768px
- Desktop: > 768px

## Fitur Responsif
- Menu navigasi menyesuaikan ukuran layar
- Grid skills mengatur ulang jumlah kolom otomatis
- Tabel portofolio scroll horizontal di mobile
- Form kontak full-width di mobile
- Font size yang adaptif
- Spacing yang responsif

## Validasi & Testing
- HTML valid sesuai W3C standards
- CSS valid sesuai W3C standards
- Tested di Chrome, Firefox, dan Edge
- Responsive di berbagai ukuran layar

## Kredit
- Fonts: Google Fonts (Inter & Poppins)
- Color Scheme: Custom dark theme dengan gradien modern

## Author
**Muhammad Hafizh Wijdan**  
Teknik Informatika  
Institut Teknologi PLN  
2024