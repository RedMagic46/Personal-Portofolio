# Portofolio Personal & Resume Digital

**Mata Kuliah:** Pemrograman Web (Semester 5)  
**Program Studi:** S1 Teknik Informatika — Universitas Muhammadiyah Malang (UMM)  
**Nama Pengembang:** Naufal Muammar  
**Profil GitHub:** [@RedMagic46 (Naufal Muammar)](https://github.com/RedMagic46)  

---

## 📌 Deskripsi Proyek

Proyek ini merupakan implementasi halaman **Portofolio Personal / Resume Digital** yang informatif, terstruktur secara semantik, dan memiliki estetika visual kelas atas (modern dark mode, glassmorphism, glowing accents, typography elegan, serta micro-interactions). Halaman ini dibangun **100% murni menggunakan HTML5 dan Vanilla CSS3** tanpa bantuan framework CSS eksternal apa pun (seperti Bootstrap, TailwindCSS, atau sejenisnya).

Seluruh data yang disajikan merefleksikan identitas dan rekam jejak nyata dari akun GitHub [RedMagic46](https://github.com/RedMagic46), mencakup profil pengembang, keahlian teknis (tech stack), riwayat pendidikan di Universitas Muhammadiyah Malang, serta proyek-proyek unggulan yang telah dipublikasikan dan di-deploy.

---

## 🎯 Pemenuhan Indikator Penilaian

### 1. Struktur & Semantik HTML
- **Tag Semantik HTML5 Lengkap:** Menggunakan tag semantik sesuai fungsinya:
  - `<header>`: Navigasi utama, logo monogram, theme toggle, tombol GitHub, dan hamburger drawer.
  - `<nav>`: Pengelompokan tautan navigasi yang dapat diakses pembaca layar (`aria-label`).
  - `<main>`: Membungkus seluruh konten inti dokumen.
  - `<section>`: Membagi blok topik utama (`#hero`, `#tentang`, `#keahlian`, `#proyek`, `#pendidikan`, `#kontak`) dengan atribut `aria-labelledby`.
  - `<article>`: Membungkus unit konten mandiri seperti setiap kartu proyek GitHub, kartu kategori keahlian, dan item riwayat pendidikan.
  - `<aside>`: Menampung kartu informasi ringkas dan statistik personal.
  - `<figure>` & `<img>`: Menyajikan foto profil avatar pengembang dengan atribut aksesibilitas `alt`, `loading`, dan penanganan error gambar.
  - `<address>`: Menampung kontak dan tautan sosial media resmi pengembang.
  - `<time>`: Menandai periode waktu perkuliahan dengan atribut `datetime`.
  - `<dl>`, `<dt>`, `<dd>`: Menyajikan metadata profil diri secara terstruktur.
- **Hirarki Tag Berjenjang:**
  - `<h1>`: Tepat 1 judul utama pada Hero section.
  - `<h2>`: Judul setiap seksi (section).
  - `<h3>`: Judul kartu proyek, kategori skill, dan institusi pendidikan.
  - `<h4>`: Judul sub-komponen.
- **Validasi Dokumen HTML:** Memenuhi standar W3C (`<!DOCTYPE html>`, atribut `lang="id"`, `<meta charset="UTF-8">`, `<meta name="viewport">`, meta deskripsi SEO, dan penutupan tag yang presisi).

### 2. Penerapan CSS & Layouting
- **Kejelasan Struktur Berkas CSS (`css/style.css`):**
  - Menggunakan **CSS Custom Properties (Design Tokens / `:root`)** untuk manajemen warna palette, gradien, bayangan (`box-shadow`), radius sudut, dan font.
  - Reset & normalize terstandarisasi (`box-sizing: border-box`, typography resets).
  - Terbagi menjadi 13 bagian modular yang terdokumentasi dengan rapi.
- **Konsistensi Warna & Estetika Visual:**
  - Tema default *Sleek Obsidian & Slate Dark Mode* (`#0a0e17`) berpadu dengan aksen harmonis *Indigo* (`#6366f1`) dan *Cyan* (`#06b6d4`).
  - Efek kartu *Glassmorphism* (`backdrop-filter: blur(12px)`) dengan garis tepi transparan (`rgba(255, 255, 255, 0.08)`).
  - Animasi halus (*micro-interactions*): transisi hover angkat (*lift*), indikator status berdenyut (*pulsing green dot*), dan tombol bertingkat (*gradient glow*).
  - Dilengkapi fitur pengubah tema (*Theme Switcher*) Dark & Light Mode yang konsisten.
- **Layouting Modern Murni (Tanpa Framework):**
  - Memanfaatkan **CSS Grid** (`grid-template-columns`, `repeat(auto-fit, minmax(...))`) dan **Flexbox** murni.
  - Penataan kontainer tengah dinamis dengan batas lebar maksimum teratur (`max-width: 1200px`).

### 3. Responsivitas Halaman (Desktop vs Mobile)
- **Desain Fluid & Media Queries:**
  - Breakpoints terstruktur: Desktop (`> 1024px`), Tablet (`<= 768px`), dan Smartphone (`<= 480px`).
  - Hero section bertransformasi dari tata letak 2-kolom di desktop menjadi 1-kolom terpusat di layar kecil.
  - Grid proyek dan keahlian melipat (*collapse*) secara otomatis menyesuaikan lebar layar perangkat tanpa horizontal scroll overflow.
  - Navigasi mobile memiliki menu hamburger interaktif dengan transisi drawer halus dan penutupan otomatis saat tautan diklik.

### 4. Integrasi Data Riil GitHub [RedMagic46](https://github.com/RedMagic46)
- **Data Profil:**
  - Foto avatar riil pengembang dari GitHub tersimpan di `assets/images/avatar.jpg` (dengan fallback CDN otomatis).
  - Bio asli: *"Building software and occasionally breaking things."*
  - Data institusi: Mahasiswa S1 Teknik Informatika, Universitas Muhammadiyah Malang (Semester 5).
  - Tautan profil LinkedIn dan Instagram asli Naufal Muammar.
- **Daftar 8 Proyek Nyata GitHub:**
  1. **Verikost**: Platform verifikasi kos terpadu ([Source Code](https://github.com/RedMagic46/Verikost) • [Live Demo](https://verikost-fy7m.vercel.app))
  2. **MindCare (Mental Health Detection)**: Aplikasi deteksi kesehatan mental ([Source Code](https://github.com/RedMagic46/mental-health-detection) • [Website](https://mindcare.my.id))
  3. **Lapak Jas Merah**: Katalog digital UMKM atribut kampus UMM ([Source Code](https://github.com/RedMagic46/lapak-jas-merah) • [Live Demo](https://lapak-jas-merah-8hyu.vercel.app/))
  4. **Jadwal Kuliah Pintar (IMKB)**: Sistem manajemen jadwal kuliah interaktif ([Source Code](https://github.com/RedMagic46/IMKB_Tugas8_Kelompok-02) • [Live Demo](https://jadwal-kuliah-self.vercel.app))
  5. **Visualisasi Algoritma & Pemrograman**: Proyek UAS Alpro ([Source Code](https://github.com/RedMagic46/Project-UAS-Algoritma-Pemrograman) • [Live Demo](https://project-uas-algoritma-pemrograman.vercel.app))
  6. **Praktikum Pemrograman Mobile**: Proyek modul aplikasi mobile semester 5 ([Source Code](https://github.com/RedMagic46/Praktikum-Pemrograman-Mobile))
  7. **Final Project Grafika Komputer 3D**: Simulasi rendering grafika 3D C++ / OpenGL ([Source Code](https://github.com/RedMagic46/Final-Project-Grafkom))
  8. **Presensi Cihuy**: Skrip otomasi pencatatan kehadiran perkuliahan dengan Python ([Source Code](https://github.com/RedMagic46/presensi-cihuy))

---

## 📁 Struktur Berkas Direktori

```text
Personal Portfolio/
├── index.html              # Dokumen utama (Struktur Semantik HTML5)
├── css/
│   └── style.css           # Penataan gaya & layouting murni (Vanilla CSS3)
├── js/
│   └── main.js            # Interaksi navigasi, filter proyek & theme switcher
├── assets/
│   └── images/
│       └── avatar.jpg      # Foto profil asli GitHub Naufal Muammar (RedMagic46)
└── README.md               # Dokumentasi lengkap
```

---

## 🚀 Petunjuk Menjalankan Proyek

Halaman ini tidak membutuhkan kompilasi (*zero build step*) dan dapat dibuka langsung:

### Opsi 1: Membuka Langsung di Browser
Klik dua kali berkas `index.html` atau buka melalui browser pilihan Anda (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

### Opsi 2: Menggunakan Local Web Server (Direkomendasikan)
Jika ingin menjalankan melalui local server:
```bash
# Melalui Python (bawaan terminal)
python -m http.server 3000

# Atau melalui Node.js npx
npx serve .
```
Lalu buka alamat `http://localhost:3000` pada peramban web Anda.
