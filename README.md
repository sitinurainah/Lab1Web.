# Lab1Web.
Laporan Praktikum 1: HTML Dasar

Mata Kuliah: Pemrograman Web

Dosen Pengampu: Agung Nugroho (agung@pelitabangsa.ac.id)

Institusi: Universitas Pelita Bangsa, Bekasi

Repositori ini dibuat untuk mendokumentasikan seluruh rangkaian kegiatan Praktikum 1: HTML Dasar. Setiap tahapan dari persiapan awal hingga penggabungan seluruh elemen web dijelaskan secara rinci di bawah ini.

Daftar Isi

Persiapan Awal & Membuat File index.html

Langkah 1: Membuat Paragraf

Langkah 2: Menambahkan Judul (Heading)

Langkah 3: Memformat Teks

Langkah 4: Menyisipkan Gambar

Langkah 5: Mengatur Ukuran Gambar

Langkah 6: Menambahkan Hyperlink

Langkah 7: Menambahkan List (Daftar)

Langkah 8: Menambahkan Komentar

Langkah 9: Menggabungkan Semua Elemen (Profil Mahasiswa)

Persiapan Awal & Membuat File index.html

Sebelum memulai penulisan kode, pastikan teks editor seperti Visual Studio Code (VSCode) sudah terpasang. Buatlah folder kerja dengan nama praktikum-1-html-dasar, lalu buat file baru bernama index.html.

Tambahkan struktur dasar dokumen HTML5 berikut ke dalam file index.html:

<!DOCTYPE html>
<html>
<head>
    <title>Praktikum HTML Dasar</title>
</head>
<body>
</body>
</html>


Penjelasan: Deklarasi <!DOCTYPE html> memberitahu browser bahwa dokumen ini menggunakan standar HTML5. Elemen <head> memuat informasi meta seperti <title> (judul tab browser), sedangkan elemen <body> berisi konten yang akan dirender ke layar pengguna.

Screenshot Hasil Persiapan Awal:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 210457" src="https://github.com/user-attachments/assets/a7a0e300-07dc-4e22-a92e-4ca757c92e9e" />

[screenshot tampilan struktur dasar HTML pada browser]

Langkah 1: Membuat Paragraf

Pada tahap ini, kita menambahkan beberapa paragraf teks ke dalam elemen <body> menggunakan tag <p>. Paragraf secara otomatis akan memberikan jarak vertikal antar blok teks di browser.

Kode yang ditambahkan:

<!-- Ini adalah paragraf pertama -->
<p>
Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>
<!-- Ini adalah paragraf kedua -->
<p>
HTML digunakan untuk menyusun struktur dan konten halaman web.
Browser akan menampilkan hasil interpretasi dari dokumen HTML.
</p>


Screenshot Hasil Langkah 1:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 210657" src="https://github.com/user-attachments/assets/6378fa61-5c92-4626-a9fc-6bb2a9d96d46" />

[screenshot tampilan paragraf yang memiliki jarak antar paragraf di browser]

Langkah 2: Menambahkan Judul (Heading)

Judul atau heading digunakan untuk membuat hierarki informasi pada halaman web. HTML menyediakan tingkatan dari <h1> (paling utama) hingga <h6>.

Kode yang ditambahkan:

<!-- judul utama -->
<h1>Belajar Dasar HTML</h1>
<!-- subjudul -->
<h2>Paragraf pada HTML</h2>


Screenshot Hasil Langkah 2:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 210815" src="https://github.com/user-attachments/assets/a927e60f-bc3e-407c-bbaa-a7553a38a4e0" />

[screenshot tampilan heading h1 dan h2 di atas paragraf]

Langkah 3: Memformat Teks

HTML menyediakan berbagai tag untuk memformat tampilan teks, seperti membuat teks tebal, miring, garis bawah, teks coret, subscript, superscript, dan penanda (mark).

Kode yang ditambahkan:

<p>
Kami sedang belajar <b>HTML dasar</b> pada mata kuliah
<i>Pemrograman Web</i>.
</p>
<p>
HTML merupakan <strong>bahasa markup</strong> untuk menyusun
struktur halaman web.
</p>
<p>
Air ditulis sebagai H<sub>2</sub>O dan luas dapat ditulis
sebagai x<sup>2</sup>.
</p>


(Catatan: Anda juga bisa bereksperimen dengan tag seperti <em>, <mark>, <small>, <del>, dan <ins>).

Screenshot Hasil Langkah 3:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 211012" src="https://github.com/user-attachments/assets/a787b78c-d425-4aa6-9934-2cb4a95cba0e" />


[screenshot hasil format teks tebal, miring, subscript, dan superscript]

Langkah 4: Menyisipkan Gambar

U<img width="1474" height="792" alt="hasil 4" src="https://github.com/user-attachments/assets/b948117f-e512-4ec5-a67d-2a2a2e45d620" />
ntuk menampilkan gambar, kita perlu menyiapkan folder bernama images di dalam direktori project dan memasukkan file gambar (misal: profil.jpg). Tag <img> digunakan bersama atribut src dan alt.

Struktur Folder:

praktikum-1-html-dasar/
├── index.html
└── images/
    └── profil.jpg

Kode yang ditambahkan:

<h3>Menambahkan Gambar</h3>
<img src="images/profil.jpg"
     alt="Foto profil mahasiswa"
     title="Foto Profil Mahasiswa">


Screenshot Hasil Langkah 4:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 212924" src="https://github.com/user-attachments/assets/d0fe384c-4a33-4d58-975f-3d62a0260987" />

[screenshot gambar profil yang berhasil dimuat di browser]

Langkah 5: Mengatur Ukuran Gambar

Atribut width dan height digunakan untuk membatasi dimensi ukuran gambar agar sesuai dengan layout halaman web yang diinginkan.

Kode yang ditambahkan:

<img src="images/profil.jpg" width="200" alt="Foto profil mahasiswa">


Screenshot Hasil Langkah 5:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 223838" src="https://github.com/user-attachments/assets/837b703b-dc94-49d4-9da7-833777ebbf0c" />

[screenshot gambar setelah diatur ukurannya menjadi lebar 200px]

Langkah 6: Menambahkan Hyperlink

Hyperlink dibuat menggunakan tag <a> dengan atribut href. Kita dapat menghubungkan halaman lokal (halaman2.html) maupun situs web eksternal (seperti Google).

Pertama, buat file baru bernama halaman2.html dengan struktur dasar HTML bebas. Lalu tambahkan navigasi berikut di halaman utama:

Kode yang ditambahkan:

<!-- navigasi halaman -->
<nav>
    <a href="index.html">Dasar HTML</a>
    <a href="halaman2.html">Halaman 2</a>
    <a href="https://www.google.com">Website Eksternal</a>
</nav>
<hr>


Screenshot Hasil Langkah 6:

[screenshot tautan navigasi yang aktif di browser]

Langkah 7: Menambahkan List (Daftar)

List dibagi menjadi dua jenis utama: Unordered List (<ul>) untuk daftar tanpa nomor (bullet) dan Ordered List (<ol>) untuk daftar berurutan (angka).

Kode yang ditambahkan:

<h2>Keahlian</h2>
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

<h2>Urutan Belajar</h2>
<ol>
    <li>Mempelajari struktur HTML</li>
    <li>Mempelajari tag dan atribut</li>
    <li>Membuat halaman HTML</li>
    <li>Menguji halaman pada browser</li>
</ol>


Screenshot Hasil Langkah 7:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 224359" src="https://github.com/user-attachments/assets/0b04e53b-2321-4c69-aa9e-272df86d19ed" />

[screenshot tampilan list keahlian dan urutan belajar di browser]

Langkah 8: Menambahkan Komentar

Komentar ditulis menggunakan format <!-- isi komentar -->. Komentar ini berfungsi sebagai dokumentasi kode atau catatan pengembang dan tidak akan dieksekusi atau ditampilkan oleh browser.

Kode yang ditambahkan:

<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>
<!-- Bagian Keahlian -->
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>


Screenshot Hasil Langkah 8:
<img width="1920" height="1080" alt="Screenshot 2026-09-26 224221" src="https://github.com/user-attachments/assets/fce6b999-c3fb-4aa0-a334-bf4c93b9570d" />

[screenshot kode sumber (source code) yang menunjukkan penulisan komentar]

Langkah 9: Menggabungkan Semua Elemen (Profil Mahasiswa)

Pada tahap akhir, seluruh elemen yang telah dipelajari (navigasi, heading, gambar, paragraf data diri, list keahlian, dan target belajar) digabungkan menjadi satu halaman web yang utuh.

Kode Lengkap index.html:

<!DOCTYPE html>
<html>
<head>
    <title>Profil Mahasiswa</title>
</head>
<body>
    <nav>
        <a href="index.html">Beranda</a>
        <a href="halaman2.html">Halaman 2</a>
    </nav>
    <hr>
    
    <h1>Profil Mahasiswa</h1>
    <img src="images/profil.jpg" width="200" alt="Foto profil mahasiswa">
    
    <h2>Data Diri</h2>
    <p>Nama: Nama Mahasiswa</p>
    <p>Program Studi: Teknik Informatika</p>
    <p>Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan HTML.</p>
    
    <h2>Keahlian</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
    
    <h2>Target Belajar</h2>
    <ol>
        <li>Menguasai HTML</li>
        <li>Menguasai CSS</li>
        <li>Menguasai JavaScript</li>
    </ol>
</body>
</html>


Screenshot Hasil Akhir (Langkah 9):
<img width="1920" height="1080" alt="Screenshot 2026-09-26 224734" src="https://github.com/user-attachments/assets/7688f724-342e-4111-9d09-c98278013d46" />

[screenshot halaman penuh Profil Mahasiswa yang telah digabungkan]

Kesimpulan

Melalui praktikum pertama ini, saya telah mempelajari dan memahami dasar-dasar penggunaan HTML mulai dari struktur dokumen standar, penggunaan elemen heading, paragraf, pemformatan teks, penyisipan serta pengaturan gambar, pembuatan tautan navigasi (hyperlink), penggunaan list, hingga penulisan komentar kode yang baik.<img width="1413" 
                                                                                                                                                                                                                                                                                                                                    
Soal Pertanyaan Berikut:
1. Apa fungsi deklarasi <!DOCTYPE html> pada dokumen HTML?
2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
3. Apa perbedaan <p> dengan <br>? Jelaskan penggunaannya.
4. Apa fungsi atribut href pada tag <a>?
5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
6. Apa fungsi atribut src dan alt pada tag <img>?
7. Apa perbedaan penggunaan <ul> dan <ol>?
8. Apa yang terjadi jika path gambar pada atribut src salah?
9. Mengapa struktur heading h1 sampai h6 perlu digunakan secara terstruktur?
10. Apa fungsi komentar <!-- ... --> dalam kode HTML?

Jawaban :
1. Menyatakan kepada browser bahwa dokumen menggunakan standar HTML5.
2.Tag adalah penanda awalan dan akhiran elemen (<p>), elemen adalah komponen utuh dari tag beserta isinya, dan atribut adalah informasi tambahan di dalam tag pembuka (href, src).
3.<p> digunakan untuk membuat paragraf baru dengan jarak blok, sedangkan <br> digunakan untuk pindah ke baris baru tanpa membuat paragraf baru.
4.Menentukan URL atau alamat tujuan tautan yang akan dikunjungi.
5.Hyperlink internal menghubungkan ke halaman lain di dalam satu website yang sama, sedangkan hyperlink eksternal menghubungkan ke website di luar situs tersebut.
6.src menentukan lokasi/path file gambar, sedangkan alt memberikan teks deskripsi jika gambar gagal dimuat.
7.<ul> membuat daftar dengan simbol (bullet) tanpa nomor, sedangkan <ol> membuat daftar berurutan dengan angka atau huruf.
8.Gambar tidak akan tampil di browser (muncul ikon gambar rusak).
9.Agar hierarki informasi dokumen web tertata dengan jelas dan logis dari judul utama hingga sub-bagian terkecil.
10.Memberikan catatan atau penanda kode yang diabaikan oleh browser sehingga tidak tampil di halaman 
