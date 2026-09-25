# 🏛️ Philosofun

> Ensiklopedia filsafat interaktif berbahasa Indonesia untuk menjelajahi sejarah gagasan, profil tokoh, analisis argumen, hingga uji logika.

---

## 🚀 Live Demo

Coba dan akses aplikasi secara langsung melalui GitHub Pages:

👉 **[Buka Aplikasi Philosofun](https://ravv-low.github.io/philosophy-encyclopedia/)**

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
| :--- | :--- |
| **📚 Ensiklopedia Filsafat** | Profil mendalam tokoh filsafat, era, latar belakang, genealogi gagasan, cabang pemikiran, karya utama, dan kutipan. |
| **⏳ Filter Era** | Menyaring tokoh berdasarkan periode sejarah (Kuno, Abad Pertengahan, Modern, Kontemporer, dll.). |
| **📖 Detail Dossier** | Tampilan antarmuka bacaan yang rapi dan fokus untuk mengeksplorasi pemikiran tiap filsuf. |
| **🔍 Penguji Kesesatan Berpikir** | Alat bantu otomatis untuk mendeteksi pola *logical fallacy* berbasis kata kunci. |
| **⚖️ Uji Silogisme Deduktif** | Modul pengujian hubungan antar-term dalam premis dan kesimpulan. |
| **📖 Katalog Fallacy** | Direktori kesesatan berpikir yang dapat dicari berdasarkan nama, definisi, atau contoh kasus. |
| **🌓 Dark & Light Mode** | Beralih tema tampilan terang/gelap dengan preferensi yang tersimpan di `localStorage`. |
| **🔗 Salin & Bagikan** | Fitur menyalin dan membagikan kutipan favorit via Clipboard API / Web Share API. |
| **🔐 Simulasi Auth** | Antarmuka Form Sign In & Sign Up untuk alur pengguna. |

---

## 🛠️ Teknologi

Aplikasi ini dibangun menggunakan teknologi web murni tanpa *framework*, *database*, atau proses *build*:

* **HTML5** – Struktur konten & kompartemen aplikasi
* **CSS3** – Layout responsif, variabel tema, dan styling kustom
* **JavaScript (ES Modules)** – Arsitektur modular client-side
* **Google Fonts** – Tipografi (*Cinzel* & *Inter*)
* **Font Awesome 6** – Ikon antarmuka

---

## 🏃 Menjalankan Secara Lokal

Karena aplikasi ini menggunakan **JavaScript ES Modules**, proyek harus dijalankan melalui server lokal (bukan membuka `index.html` langsung via `file://`).

### Opsi 1: Menggunakan Python
Jalankan perintah berikut di dalam folder proyek melalui terminal:
```bash
python -m http.server 8000
