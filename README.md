Umroh Ease

Umroh Ease adalah aplikasi panduan umroh berbasis web yang dirancang untuk membantu jamaah menjalani ibadah dengan lebih tenang, terstruktur, dan mudah. Aplikasi ini menyediakan panduan manasik, kumpulan doa, paket umroh, Al-Qur’an digital, peta lokasi Sa’i & Masjidil Haram, kalender global, serta informasi kontak.
Aplikasi dibangun secara mobile-first dan dapat diakses langsung melalui browser tanpa instalasi.

Deskripsi Produk

Umroh Ease berfungsi sebagai one-stop guide untuk jamaah umroh. Setiap fitur disusun dalam bentuk modul interaktif: mulai dari penjelasan manasik tahap demi tahap, doa-doa sesuai lokasi dan aktivitas, daftar paket umroh simulatif, akses cepat ke surah-surah Al-Qur’an, visualisasi lokasi ibadah menggunakan peta Leaflet, hingga kalender waktu global yang relevan untuk perjalanan.
Semua komponen dirancang responsif, sederhana, dan mudah digunakan.

Komponen Pembangun Produk
1. Framework & Tools

Ionic Framework

Vite (bundler)

TypeScript (kode utama)

JavaScript ES6

HTML5 & CSS3

2. Libraries & Dependencies

Leaflet.js → peta interaktif

OpenStreetMap → penyedia basemap

Font Awesome → ikon

Google Fonts (Poppins)

3. Struktur Proyek

Folder penting dalam repository:

/src – halaman, komponen, logika aplikasi

/public – gambar dan aset statis

/resources – data JSON pendukung

/cypress – testing bawaan template

index.html – halaman utama

vite.config.ts, tsconfig.json – konfigurasi proyek

4. Bahasa dalam Project

TypeScript: 79%

JavaScript: 8%

HTML: 8%

CSS: 4%

Sumber Data
1. Peta & Lokasi

Basemap: OpenStreetMap Contributors

Library: Leaflet.js

Lokasi Sa’i (Shafa – Marwah) dan area Masjidil Haram dibuat secara manual menggunakan koordinat GPS.

2. Al-Qur’an

Sumber: API Al-Qur’an / JSON internal (menyesuaikan implementasi repository)

Jika menggunakan file JSON: seluruh data surah dan ayat disimpan dalam folder resources.

3. Doa dan Panduan Manasik

Data disusun sendiri dalam format JSON dan dimuat melalui modul-modul di folder /src.

4. Paket Umroh

Dataset dibuat secara manual sebagai data statis untuk simulasi tampilan paket.

5. Ikon

Font Awesome & SVG custom.
<img width="2245" height="1587" alt="Untitled design" src="https://github.com/user-attachments/assets/15251da3-e5d3-4b67-9e45-94a18ccf07d2" />
