🌙 Deskripsi Produk

Umroh Ease adalah aplikasi panduan umroh berbasis web yang dirancang untuk membantu jamaah menjalani ibadah dengan lebih tenang, terarah, dan mudah. Aplikasi ini menghadirkan panduan manasik, kumpulan doa, paket umroh, Al-Qur’an digital, peta lokasi Sa’i & Masjidil Haram, kalender global, dan informasi kontak—all in one place.

Aplikasi bersifat mobile-first, ringan, dan dapat diakses langsung melalui browser tanpa instalasi.

🔗 Live Demo:
https://muhammadarthur21.github.io/umroh-ease/

🧩 Komponen Pembangun Produk
🖥 Frontend & Framework

Ionic Framework

Vite (bundler & dev server)

TypeScript sebagai bahasa utama

JavaScript ES6 untuk interaktivitas tambahan

HTML5 & CSS3 untuk struktur dan gaya tampilan

📚 Library & Dependencies

Leaflet.js → peta interaktif

OpenStreetMap → penyedia basemap global

Font Awesome → set ikon

Google Fonts – Poppins

📁 Struktur Proyek Utama
/src          -> halaman & komponen utama
/public       -> aset statis (ikon, gambar)
/resources    -> data JSON internal
/cypress      -> automation testing (template bawaan)
index.html    -> halaman utama aplikasi
package.json  -> dependency & script project
vite.config.ts -> konfigurasi Vite

💻 Bahasa yang Digunakan

TypeScript: 79%

JavaScript: 8%

HTML: 8%

CSS: 4%

🗂 Sumber Data
1. Peta & Lokasi Ibadah

Basemap: OpenStreetMap Contributors

Library: Leaflet.js

Koordinat titik Sa’i (Shafa–Marwah) disusun secara manual untuk akurasi visual.

2. Al-Qur’an Digital

Data berasal dari API Al-Qur’an atau JSON internal (tergantung implementasi final di repository).

Memuat daftar surah, jumlah ayat, dan nama terjemahan.

3. Panduan Manasik & Doa

Disusun manual dalam format JSON internal untuk memastikan konsistensi isi.

4. Paket Umroh

Data simulatif berupa JSON statis yang menampilkan durasi, fasilitas, dan harga.

5. Ikon

Font Awesome

SVG custom

Aset ringan dari folder /public

📸 Tangkapan Layar Komponen Penting
<img width="2245" height="1587" alt="Untitled design" src="https://github.com/user-attachments/assets/15251da3-e5d3-4b67-9e45-94a18ccf07d2" />
