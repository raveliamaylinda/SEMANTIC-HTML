# SEMANTIC-HTML
Latihan Praktikum Semantic HTML


## Semantic HTML Project index.html ##
Project ini ada beberapa kesalahan dalam kode HTML. Hal ini dapat diperbaiki untuk menjaga struktur HTML 

1. Tag <h1> di Dalam <head>:
Di dalam <head>, terdapat tag <h1>. Ini tidak sesuai standar HTML karena <head> hanya digunakan untuk metadata, seperti judul, pengaturan viewport, dan referensi ke stylesheet atau skrip. Tag <h1> seharusnya berada di dalam <body>.
Perbaikan: Pindahkan <h1> ke dalam <body> jika ingin menampilkannya di halaman.

2. Kesalahan Penulisan Tag <meta>:
Di tag <meta name="viewport" content="width=device-width", initial-scale="1.0" />, ada koma (,) yang seharusnya adalah titik koma (;) antara width=device-width dan initial-scale=1.0.
Perbaikan: Ubah koma menjadi titik koma.

3. Tag <section> Ganda yang Tidak Ditutup:

Ada dua <section> tetapi hanya satu yang ditutup. Tag <section> pertama berisi "Konten" tapi tidak diakhiri dengan </section>. Ini menyebabkan struktur HTML menjadi tidak valid.
Perbaikan: Hapus <section> yang kedua atau tambahkan </section> di tempat yang sesuai.

BERIKUT KODE YANG TELAH DIPERBAIKI
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width; initial-scale=1.0" />
    <title>HTML5 Semantic</title>
    <link rel="stylesheet" href="./styles.css">
</head>
<body>
    <header>
        <h1>HTML5 Semantic</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#pengertian">Pengertian</a></li>
            <li><a href="#kesimpulan">Kesimpulan</a></li>
        </ul>
    </nav>
    <section>Konten</section>
    <footer>Copyright</footer>
</body>
</html>



## Semantic HTML Project Style.css ##
