# Praktikum 6: Twitter Bootstrap

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
