# CSS Framework - Bootstrap - Tazkia

Folder ini merupakan task pertama dari materi CSS Framework. Pada task pertama, file dibuat menggunakan HTML5, CSS3, javascript, jQuery, dan bootstrap. Struktur dari folder ini adalah sebagai berikut :

```
btj-academy-fe-tazkia
|-- src/
|  |-- css/
|    |-- style.css
|  |-- html/
|    |-- AboutMe.html
|    |-- LandingPage.html
|  |-- script/
|    |-- index.js
|  |-- img/
|-- README.md
```

### Penggunaan :
1. Download atau clone repository ini :
```
git clone https://github.com/tazkiaathariza/btj-academy-fe-bs-tazkia.git
```
2. Buka file 'LandingPage.html' untuk melihat hasil (disarankan menggunakan chrome).
3. Pada navigation bar, tekan 'About' untuk melihat halaman 'AboutMe'.

## Penjelasan

Penjelasan kali ini berfokus tentang penggunaan framework bootstrap. Bootstrap CDN disertakan langsung pada file HTML :

    ```
        // pada tag head
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">

        // pada tag body
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    ```

#### Penggunaan Bootstrap pada Landing Page

Berikut adalah komponen dan fitur layout dari Bootstrap yang digunakan pada halaman landing (home) :

1. Menggunakan class `container`, `row`, dan `col` untuk layouting.
2. Menggunakan `class="navbar"` kemudian memodifikasi warnanya di file css.
3. Menggunakan `class="card"` untuk membuat card login dan menambahkan box-shadow melalui css.
4. Menggunakan komponen form kemudian memodifikasi input box ketika 'focus' agar warnanya sesuai dengan tema.
5. Menggunakan button `class="btn btn-primary"`. Warna dimodifikasi agar sesuai dengan tema.
6. Mengatur padding dan margin secara otomatis pada kelas, contoh : `class="pt-md-2 pb-md-3"`
7. Code selengkapnya dapat dilihat pada file html dan css.

#### Penggunaan Bootstrap pada About Me Page

Berikut adalah komponen dan fitur layout dari Bootstrap yang digunakan pada halaman About Me :

1. Menggunakan class `container`, `row`, dan `col` untuk layouting.
2. Menggunakan `class="navbar"` kemudian memodifikasi warnanya di file css.
3. Menggunakan `class="card"` untuk membuat card education.
4. Menambahkan modal `class="modal"` yang dapat terbuka ketika button pada card diklik.
4. Menggunakan table bawaan dari bootstrap dan memodifikasi warnanya.
5. Menggunakan accordion `class="accordion` pada bagian organisasi.
6. Menggunakan carousel `class="carousel slide carousel-dark"` untuk bagian projek.
5. Menggunakan button `class="btn btn-primary"`. Warna dimodifikasi agar sesuai dengan tema.
6. Mengatur padding dan margin secara otomatis pada kelas, contoh : `class="pt-md-2 pb-md-3"`
7. Code selengkapnya dapat dilihat pada file html dan css.
