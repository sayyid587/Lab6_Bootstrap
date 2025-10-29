# Lab6_Bootstrap

<p>Nama  : Sayyid Sulthan Abyan</p>
<p>NIM   : 312410496</p>
<p>Kelas : TI.24.A.5</p>

## Langkah-langkah Latihan Praktikum

---

##  Penjelasan Langkah Latihan Praktikum 6

### 1. Setup Bootstrap
Pada langkah ini, saya menambahkan Bootstrap ke dalam halaman HTML menggunakan CDN. File CSS Bootstrap disisipkan di dalam `<head>`, dan file JavaScript Bootstrap di akhir `<body>`. Ini memungkinkan saya menggunakan semua komponen dan sistem grid Bootstrap tanpa mengunduh file secara lokal.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

### 2. Container
Saya mencoba dua jenis container:
- `.container` untuk lebar tetap yang responsif
- `.container-fluid` untuk lebar penuh 100%

Tujuannya adalah memahami bagaimana Bootstrap mengatur perataan dan lebar konten secara otomatis.

---

### 3. Grid System
Saya menggunakan sistem grid 12 kolom Bootstrap untuk menggantikan layout manual dengan float. Saya membuat layout dengan:
- `.row` sebagai pembungkus kolom
- `.col-md-8` untuk konten utama
- `.col-md-4` untuk sidebar

Grid ini membuat layout responsif dan mudah diatur di berbagai ukuran layar.

---

### 4. Komponen: Button
Saya mencoba berbagai jenis tombol Bootstrap dengan class:
- `.btn-primary`
- `.btn-secondary`
- `.btn-success`
- `.btn-danger`

Setiap tombol memiliki warna dan gaya yang berbeda sesuai fungsinya.

---

### 5. Komponen: Navbar
Saya membuat navigasi horizontal menggunakan komponen `<nav>` Bootstrap. Navigasi ini berisi link: Home, Artikel, About, dan Kontak. Saya menggunakan class:
- `.navbar`
- `.nav`
- `.nav-link`
- `.bg-primary` untuk warna latar

Tampilannya mirip dengan layout Praktikum 4.

---

### 6. Komponen: Card
Saya mengganti struktur `.box` dan `.widget-box` dari Praktikum 4 dengan komponen `.card`. Setiap card berisi gambar, judul, deskripsi, dan tombol "View detail". Saya juga menggunakan class `.rounded-circle` untuk membuat gambar berbentuk lingkaran.

---

### 7. Komponen: Form
Saya refactor form dari Praktikum 5 menggunakan class Bootstrap:
- `.form-control` untuk input dan output
- `.form-label` untuk label
- `.btn` untuk tombol

Form ini digunakan untuk mengecek apakah bilangan yang dimasukkan adalah genap atau ganjil, dan tampilannya jauh lebih rapi dibanding versi manual.

---

### 8. Refactor Layout Praktikum 4
Saya mengganti seluruh layout manual dari Praktikum 4 dengan versi Bootstrap:
- Navigasi menggunakan `<nav>` Bootstrap
- Konten dan sidebar menggunakan `.row` dan `.col-md-*`
- Widget dan box diganti dengan `.card`
- Hero section menggunakan warna latar mirip dengan Praktikum 4 (`#e4e4e5`)

---

### 9. Tugas: Halaman Portfolio
Saya membuat file baru `portfolio.html` yang berisi:
- Navbar di atas
- Section "Tentang Saya" dengan dua kolom: foto dan deskripsi
- Section "Portfolio Saya" dengan tiga card proyek

Setiap card berisi gambar dummy dan deskripsi singkat proyek.

---

Kalau kamu mau, aku bisa bantu buatkan versi README lengkap dengan screenshot placeholder atau bantu lanjut ke bagian dokumentasi tugas dan commit. Mau lanjut ke bagian laporan atau upload ke GitHub?
