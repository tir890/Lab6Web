## 🧾 **README.md – Praktikum 6: Twitter Bootstrap**

# Praktikum 6: Twitter Bootstrap

Nama: Tiara Hayatul Khoir
NIM : 312410474
Kelas : TI.24.A5

## 📚 Deskripsi
Praktikum ini bertujuan untuk memahami konsep **CSS Framework**, khususnya **Bootstrap**, serta mengimplementasikannya untuk membuat layout web yang responsif dan modern tanpa menulis banyak kode CSS manual.

Pada praktikum ini, dilakukan refactor dari layout web sebelumnya (Praktikum 4 dan 5) agar lebih rapi dan efisien menggunakan komponen-komponen yang disediakan oleh Bootstrap.

---

## 🎯 Tujuan
1. Mahasiswa mampu memahami konsep dasar **CSS Framework**.
2. Mahasiswa mampu menyertakan **Bootstrap library** ke dalam halaman web.
3. Mahasiswa mampu memahami dan mengimplementasikan **Bootstrap Grid System**.
4. Mahasiswa mampu menggunakan komponen dasar Bootstrap seperti **Navbar**, **Button**, **Card**, dan **Form**.
5. Mahasiswa mampu membuat layout web sederhana dengan cepat dan responsif menggunakan Bootstrap.

---

## 🧠 Dasar Teori

### Apa itu CSS Framework?
**CSS Framework** adalah kumpulan kode CSS siap pakai yang membantu mempercepat proses pembuatan tampilan web. Dengan framework, kita tidak perlu menulis seluruh styling dari nol.

### Apa itu Bootstrap?
**Bootstrap** adalah framework CSS open-source yang dikembangkan oleh Twitter.  
Framework ini menyediakan berbagai komponen siap pakai seperti grid system, tombol, form, navigasi, hingga card, yang sudah dioptimalkan untuk tampilan **responsif (mobile-first)**.

---

## 🧩 Langkah Praktikum

### 1. Setup Bootstrap (Menggunakan CDN)
Bootstrap dihubungkan ke file HTML melalui CDN dengan menambahkan link CSS dan JS di bagian `<head>` dan sebelum `</body>`.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
````

---

### 2. Container dan Grid System

Digunakan class `.container`, `.row`, dan `.col-md-*` untuk mengatur layout halaman agar responsif di berbagai ukuran layar.

Contoh:

```html
<div class="container">
  <div class="row">
    <div class="col-md-8">Main Content</div>
    <div class="col-md-4">Sidebar</div>
  </div>
</div>
```

---

### 3. Komponen Bootstrap

#### 🔹 Navbar

Digunakan untuk membuat navigasi halaman dengan class `.navbar` dan `.navbar-expand-lg`.

#### 🔹 Button

Tersedia berbagai style tombol seperti `.btn-primary`, `.btn-success`, `.btn-danger`, dll.

#### 🔹 Card

Komponen serbaguna untuk menampilkan konten dalam bentuk box rapi.

#### 🔹 Form

Bootstrap menyediakan class seperti `.form-label` dan `.form-control` untuk menata form agar lebih rapi dan seragam.

---

### 4. Refactor Layout Praktikum 4

Layout web dari Praktikum 4 yang awalnya menggunakan `float` dan `margin` diubah menggunakan sistem grid Bootstrap.
Elemen seperti navigasi, sidebar, dan widget diganti dengan **Navbar** dan **Card Bootstrap**.

---

### 5. Refactor Form Praktikum 5

Form input yang sebelumnya dibuat manual kini menggunakan class Bootstrap untuk tampilan yang lebih konsisten dan responsif.

---

### 6. Membuat Halaman Portfolio Sederhana

File baru `portfolio.html` dibuat dengan struktur:

* Navbar di bagian atas.
* Section **Tentang Saya** dengan 2 kolom (foto dan deskripsi diri).
* Section **Portfolio Saya** berisi 3 card proyek.
* Footer di bagian bawah.

Contoh struktur:

```html
<section class="container">
  <div class="row">
    <div class="col-md-4">Foto</div>
    <div class="col-md-8">Deskripsi</div>
  </div>
</section>
```

---

## 📸 Screenshot Hasil

**1. Halaman Index (Bootstrap Layout)**

> [Tambahkan screenshot di sini]

**2. Halaman Portfolio**

> [Tambahkan screenshot di sini]

---

## 🗂️ Struktur Folder

```
lab6_bootstrap/
├── index.html
├── portfolio.html
├── style.css
└── img/
    └── gambar.jpg
```

## 🧾 Kesimpulan

Dengan menggunakan **Bootstrap**, pembuatan layout web menjadi jauh lebih mudah dan cepat.
Bootstrap menyediakan berbagai komponen siap pakai yang membuat tampilan web otomatis **responsif**, rapi, dan konsisten di berbagai ukuran layar tanpa perlu menulis banyak kode CSS manual.
