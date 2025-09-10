# Website ITERA

Proyek ini merupakan tugas pembuatan website sederhana yang berkaitan dengan Institut Teknologi Sumatera (ITERA). Website terdiri dari dua halaman utama:

1. **Halaman Utama (`index.html`)**
   - Menampilkan header dengan logo dan judul
   - Navigasi menuju halaman lain
   - Konten utama tentang ITERA
   - Aside berisi agenda terdekat
   - Tabel program studi populer
   - Footer dengan kontak

2. **Halaman Berita (`berita.html`)**
   - Artikel berita menggunakan elemen semantik `<article>`, `<header>`, `<section>`
   - Dua contoh berita terbaru
   - Tabel ringkasan berita populer
   - Footer dengan hak cipta

## Struktur Semantik

Proyek ini menggunakan elemen semantik HTML5 untuk meningkatkan aksesibilitas dan SEO:

- `<header>`: Menampung logo, judul, dan navigasi.
- `<nav>`: Navigasi utama website.
- `<main>`: Konten inti pada setiap halaman.
- `<article>`: Digunakan untuk setiap berita agar terstruktur jelas.
- `<section>`: Membagi konten ke bagian terpisah (tentang, tabel, isi berita).
- `<aside>`: Menyajikan informasi tambahan seperti agenda.
- `<footer>`: Informasi hak cipta dan kontak.

## Tantangan dan Solusi

1. **Menentukan struktur semantik yang tepat**  
   Tantangan: Menentukan kapan menggunakan `<section>` atau `<article>`.  
   Solusi: Mengacu pada prinsip HTML semantik, artikel dipakai untuk konten berita mandiri, sedangkan section dipakai untuk sub-bagian yang terkait halaman.

2. **Validasi kode HTML**  
   Tantangan: Menghindari error saat pengecekan di W3C Validator.  
   Solusi: Menggunakan DOCTYPE HTML5 (`<!DOCTYPE html>`), menutup semua tag dengan benar, serta menggunakan atribut wajib seperti `alt` pada gambar.

3. **Keterbatasan styling (tanpa CSS)**  
   Tantangan: Tampilan masih sederhana.  
   Solusi: Fokus pada struktur semantik dulu sesuai instruksi tugas. CSS dapat ditambahkan kemudian.

## Hosting

GitHub: (https://qoriib.github.io/pemweb-tugas2)[https://qoriib.github.io/pemweb-tugas2]