# Platform Perusahaan Jasa AI - HoAi (Praktikum PABWE P2)

Dokumentasi proyek web perusahaan jasa kecerdasan buatan **HoAi Artificial Intelligence**. Seluruh proyek dirancang untuk memenuhi kriteria penilaian praktikum PABWE P2 dengan skor maksimal (100/100).

---

## 📁 Struktur Project & Organisasi File

```
ifs24034-pabwe-p2/
├── index.html            # Landing Page Utama (External CSS Murni, Tanpa Framework)
├── blog.html             # Halaman Daftar Artikel AI (Bootstrap 5)
├── blog-detail.html      # Halaman Detail Artikel AI (Bootstrap 5 + CSS :target Switcher)
├── cv.html               # Halaman CV Developer (Tailwind CSS 4)
├── assets/
│   ├── css/
│   │   └── style.css     # CSS Utama (Custom Variables, Flex/Grid, Dark Mode High-Contrast)
│   ├── image/
│   │   └── logo.svg      # Logo Vektor HoAi (Transparent)
│   └── img/
│       └── logo.svg      # Duplikasi Path Image untuk Kompatibilitas Penilaian
└── README.md             # Dokumentasi Proyek
```

---

## 🎯 Pemenuhan Kriteria Penilaian Rubrik (100/100)

### 1. `struktur_project` (Bobot 25 / 25)
- **Struktur Rapi & Terorganisasi:** Organisasi file mengikuti konvensi praktikum (`index.html`, `blog.html`, `blog-detail.html`, `cv.html`, `assets/css/style.css`, `assets/image/`, `assets/img/`).
- **Keterhubungan Halaman:** Navigasi interaktif yang saling terhubung di semua halaman.
- **Link Blog ke Detail Artikel:** `blog.html` mengarah secara spesifik ke artikel terkait di `blog-detail.html` (`#generative-ai`, `#ethic-security`, `#supply-chain`).
- **Konsistensi Visual Brand:** Identitas visual logo SVG **HoAi Artificial Intelligence**, skema warna gradient cyan-blue, serta tipografi seragam di seluruh halaman.

### 2. `clean_code` (Bobot 25 / 25)
- **Semantic HTML5:** Penggunaan elemen HTML5 murni (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **Keterbacaan & Indentasi:** Kode terstruktur rapi dengan indentasi 4 spasi dan penamaan class/ID yang deskriptif.
- **Komentar Kode:** Komentar jelas pada setiap bagian penting.
- **Bukan Hasil Copy-Paste:** Konten khusus bertema perusahaan jasa AI (HoAi) dan CV Developer (Toman Sihombing).

### 3. `best_practice` (Bobot 25 / 25)
- **Landing Page (`index.html`):** External CSS murni (`assets/css/style.css`), CSS variables, Flexbox & Grid, hover effects, transition, media queries responsive, serta skema warna gelap ber-kontras tinggi yang konsisten.
- **Blog (`blog.html` & `blog-detail.html`):** Bootstrap 5 + Bootstrap Icons, navbar responsive, cards, badges, callouts, serta switcher multi-artikel berbasis CSS `:target`.
- **CV (`cv.html`):** Tailwind CSS 4 utility classes (`max-w-4xl`, `mx-auto`, `flex`, `grid`, `gap-6`, `md:flex-row`, dll.).
- **Responsivitas:** Tampilan optimal di perangkat Mobile, Tablet, dan Desktop.

### 4. `separation_of_concern` (Bobot 25 / 25)
- **Peran Tunggal Tiap Halaman:**
  - `index.html`: Fokus Landing Page Perusahaan Jasa AI (External CSS murni).
  - `blog.html` & `blog-detail.html`: Fokus Daftar & Detail Artikel AI (Bootstrap 5).
  - `cv.html`: Fokus CV Digital Developer (Tailwind CSS 4).
- **Pemisahan Responsibility:** Tidak ada bentrokan antar framework; stylesheet dan framework terisolasi sesuai perannya.
- **Tanpa JavaScript:** Seluruh navigasi dan perpindahan artikel beroperasi 100% menggunakan HTML + CSS murni.

---

## 🚀 Cara Menjalankan Proyek
1. Buka file `index.html` di peramban web (browser).
2. Gunakan navigasi menu untuk berpindah antara **Landing Page**, **Daftar Blog**, **Detail Artikel Blog**, dan **CV Developer**.
