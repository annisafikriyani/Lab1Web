Langkah-Langkah Praktikum
1. Membuat Struktur Dasar & Paragraf
Membuat dokumen HTML5 dengan struktur utama (<!DOCTYPE html>, <html>, <head>, <body>) serta menambahkan paragraf menggunakan tag <p>.

2. Menambahkan Heading & Pemformatan Teks
Menggunakan tag heading <h1> dan <h2>, serta menerapkan pemformatan teks tebal <b>/<strong>, miring <i>, <sub> (subscript), dan <sup> (superscript).

3. Menyisipkan & Mengatur Gambar
Menampilkan gambar profil mahasiswa menggunakan tag <img> dengan mengatur atribut src, width, alt, dan title.

4. Menambahkan Hyperlink (Internal & Eksternal)
Membuat tautan navigasi menggunakan tag <a> untuk menghubungkan index.html dengan halaman2.html (internal) dan tautan ke situs luar seperti Universitas Pelita Bangsa (eksternal).

5. Membuat List (Daftar)
Membuat daftar keahlian menggunakan <ul> (unordered list) dan daftar urutan/target belajar menggunakan <ol> (ordered list).



---

## Jawaban Pertanyaan Modul

1. **Fungsi deklarasi `<!DOCTYPE html>`:**
   Untuk memberitahu browser bahwa dokumen yang sedang dibuka menggunakan standar HTML5.

2. **Perbedaan Tag, Elemen, dan Atribut:**
   - **Tag**: Penanda awal (`<p>`) dan akhir (`</p>`) dari suatu komponen HTML.
   - **Elemen**: Komponen utuh yang terdiri dari tag pembuka, isi/konten, dan tag penutup.
   - **Atribut**: Informasi tambahan yang dimasukkan di dalam tag pembuka (misal: `src=""`, `href=""`).

3. **Perbedaan `<p>` dan `<br>`:**
   - **`<p>` (Paragraph)**: Digunakan untuk membuat blok paragraf baru dan otomatis memberikan spasi/jarak di atas dan bawahnya.
   - **`<br>` (Break)**: Digunakan untuk berpindah ke baris baru di dalam blok yang sama tanpa memberikan spasi paragraf.

4. **Fungsi atribut `href` pada tag `<a>`:**
   Untuk menentukan alamat URL atau tujuan halaman web yang akan dibuka ketika link diklik.

5. **Perbedaan Hyperlink Internal dan Eksternal:**
   - **Internal**: Menghubungkan ke file halaman lain yang ada di dalam proyek/folder yang sama (contoh: `halaman2.html`).
   - **Eksternal**: Menghubungkan ke halaman web di luar proyek melalui alamat URL lengkap (contoh: `https://www.google.com`).

6. **Fungsi atribut `src` dan `alt` pada tag `<img>`:**
   - **`src`**: Menentukan lokasi/path file gambar yang akan ditampilkan.
   - **`alt`**: Teks alternatif yang akan muncul jika gambar gagal dimuat atau dibaca oleh *screen reader*.

7. **Perbedaan `<ul>` dan `<ol>`:**
   - **`<ul>` (Unordered List)**: Membuat daftar tanpa urutan angka (menggunakan simbol *bullet*).
   - **`<ol>` (Ordered List)**: Membuat daftar berurutan (menggunakan angka atau huruf).

8. **Jika path gambar pada atribut `src` salah:**
   Gambar tidak akan tampil di browser dan akan menampilkan ikon gambar rusak beserta teks alternatif dari atribut `alt`.

9. **Alasan struktur Heading (`<h1>` sampai `<h6>`) harus terstruktur:**
   Untuk memberikan hierarki konten yang jelas bagi pengguna dan membantu mesin pencari (*SEO*) serta *screen reader* dalam memahami struktur utama halaman.

10. **Fungsi komentar `<!-- ... -->`:**
    Untuk memberikan catatan atau penanda pada kode yang tidak akan ditampilkan oleh browser.