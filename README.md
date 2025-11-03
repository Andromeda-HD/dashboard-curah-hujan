# Dashboard Curah Hujan Kaltim 2024

Dashboard ini menampilkan data curah hujan di Provinsi Kalimantan Timur tahun 2024 secara interaktif. Dibangun menggunakan **HTML**, **TailwindCSS**, dan **Chart.js**, serta terhubung dengan data JSON hasil pengamatan stasiun BMKG.

## Fitur Utama
- **Peta Interaktif**  
  Menampilkan lokasi stasiun hujan di Kalimantan Timur melalui iframe dari GitHub Pages.  
  Pengguna dapat melihat data per wilayah tanpa mengubah halaman utama.
- **Statistik Utama**  
  - Total curah hujan provinsi  
  - Rata-rata curah hujan per bulan  
  - Stasiun dengan curah hujan tertinggi
- **Filter dan Kontrol Cepat**  
  - Pilih hingga 3 stasiun untuk perbandingan grafik  
  - Tombol “Pilih 3 Teratas” untuk menampilkan stasiun dengan curah hujan tertinggi  
  - Tombol “Bersihkan” untuk reset tampilan grafik
- **Visualisasi Data Dinamis**  
  - **Line Chart:** menampilkan tren curah hujan bulanan antarstasiun  
  - **Bar Chart:** menampilkan total curah hujan per stasiun  
  - **Doughnut Chart:** menampilkan proporsi rata-rata curah hujan antarstasiun
- **Insight Otomatis**  
  Menampilkan informasi seperti:
  - Bulan dengan curah hujan tertinggi  
  - Stasiun dengan intensitas hujan paling rendah
- **Fitur Ekspor**  
  - Unduh data dalam format **CSV**  
  - Simpan grafik sebagai **PNG**  
  - Ekspor tampilan ke **PDF** (opsional)

## Struktur Folder
/dashboard-curah-hujan-kaltim/

│

├── index.html # Halaman utama dashboard

├── curah_hujan_kaltim.json # Data curah hujan format JSON

├── /assets/ # (opsional) ikon, logo, dan stylesheet tambahan

└── README.md # Dokumentasi proyek

## Teknologi yang Digunakan
- **Frontend:** HTML5, JavaScript (ES6)  
- **Framework CSS:** TailwindCSS (via CDN)  
- **Visualisasi Data:** Chart.js v4  
- **Sumber Data:** BMKG (data curah hujan per stasiun Kalimantan Timur)

## Cara Menjalankan
1. Pastikan file `index.html` dan `curah_hujan_kaltim.json` berada dalam folder yang sama.  
2. Buka file `index.html` di browser modern (Chrome, Edge, atau Firefox).  
3. Dashboard akan otomatis menampilkan peta, statistik, dan grafik interaktif.

## Penggunaan
- Pilih maksimal 3 stasiun untuk dibandingkan.  
- Klik “Pilih 3 Teratas” untuk melihat stasiun dengan curah hujan tertinggi.  
- Gunakan tombol ekspor untuk menyimpan data atau grafik.  
- Scroll ke bawah untuk melihat insight otomatis dan tren keseluruhan.

## Lisensi
© 2025 Universitas Mulawarman  
Dikembangkan untuk keperluan pembelajaran mata kuliah Sistem Informasi Geografis.  
Data bersumber dari BMKG dan diolah secara terbuka untuk visualisasi publik.
