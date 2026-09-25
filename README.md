# Philosofun

Philosofun adalah ensiklopedia filsafat interaktif berbahasa Indonesia. Aplikasi ini mengajak pengguna menjelajahi sejarah gagasan melalui profil filsuf, analisis argumen, pengujian silogisme, dan katalog kesesatan berpikir.

## Fitur

- **Ensiklopedia filsafat** dengan profil tokoh, era, latar belakang, genealogi gagasan, cabang pemikiran, karya, dan kutipan.
- **Filter era** untuk menyaring tokoh berdasarkan periode sejarah.
- **Halaman detail filsuf** dengan tampilan bacaan yang lebih lengkap.
- **Penguji kesesatan berpikir** yang mendeteksi beberapa pola fallacy berdasarkan kata kunci.
- **Uji silogisme deduktif** untuk memeriksa hubungan dasar antar-term dalam premis dan kesimpulan.
- **Katalog fallacy** yang dapat dicari berdasarkan nama, definisi, atau contoh.
- **Mode terang dan gelap** yang disimpan di `localStorage` browser.
- **Salin dan bagikan kutipan** melalui Clipboard API atau Web Share API jika tersedia.
- **Form Sign In / Sign Up** sebagai simulasi antarmuka autentikasi.

## Teknologi

- HTML5
- CSS3
- JavaScript ES Modules
- Google Fonts: Cinzel dan Inter
- Font Awesome 6

Tidak ada framework, database, atau proses build yang diperlukan.

## Menjalankan Secara Lokal

Karena aplikasi menggunakan JavaScript ES Modules, jalankan melalui web server lokal dan bukan dengan membuka `index.html` langsung menggunakan protokol `file://`.

### Menggunakan Python

Pastikan Python sudah terpasang, lalu jalankan perintah berikut dari folder proyek:

```bash
python -m http.server 8000
```

Buka [http://localhost:8000](http://localhost:8000) di browser.

### Menggunakan Visual Studio Code

1. Buka folder proyek di Visual Studio Code.
2. Pasang ekstensi **Live Server**.
3. Klik kanan file `index.html`.
4. Pilih **Open with Live Server**.

## Struktur Folder

```text
Philosofun/
├── index.html              # Struktur halaman dan komponen antarmuka
├── css/
│   └── style.css           # Gaya, layout, tema, dan responsive design
└── js/
    ├── app.js              # Logika aplikasi dan interaksi pengguna
    └── data/
        ├── index.js        # Ekspor kumpulan data filsuf
        ├── alfarabi.js
        ├── aristotle.js
        ├── kant.js
        ├── foucault.js
        ├── expanded.js
        └── expanded2.js
```

## Catatan Implementasi

- Data filsuf dan fallacy disimpan secara statis di dalam berkas JavaScript.
- Fitur autentikasi saat ini hanya simulasi antarmuka; tidak ada akun, validasi server, atau penyimpanan password.
- Analisis fallacy dan silogisme merupakan pemeriksaan awal berbasis heuristik, bukan pengganti analisis logika atau verifikasi akademik.
- Font dan ikon dimuat dari CDN, sehingga koneksi internet diperlukan agar tampilan eksternal tersebut tampil sempurna.

## Pengembangan

Untuk menambahkan filsuf, tambahkan objek dengan struktur yang sesuai pada salah satu berkas di `js/data/`, kemudian ekspor dan gabungkan datanya melalui `js/data/index.js`. Perubahan pada perilaku antarmuka dapat dilakukan di `js/app.js`, sedangkan tampilan diatur melalui `css/style.css`.

## Lisensi

Belum ada lisensi open-source yang ditentukan untuk proyek ini.
