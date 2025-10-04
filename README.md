# **A Front-End Learning Lab Final Project 2024**
(practice to deploy it at github)

### plan of scale-up the User Interface (UI)
**Fase 1: Peningkatan Interaktivitas & Penemuan Konten**
1. Fungsi Pencarian (Search Bar)✅
2. Sistem Filter dan Penyortiran (Filter & Sort): Di setiap kategori (Kuliner, Wisata, Event), tambahkan opsi filter.✅
   - Kuliner: Filter berdasarkan Harga (Murah, Menengah, Mahal),
   - Jenis Masakan (Jawa, Western, Chinese), Sertifikasi (Halal), atau Rating.
   - Wisata: Filter berdasarkan Harga Tiket (Gratis, Berbayar), Tipe (Alam, Sejarah, Keluarga), Fasilitas.
   - Event: Filter berdasarkan Tanggal atau Kategori (Musik, Budaya, Olahraga).
3. Tampilan Peta Interaktif (Interactive Map View): Using Google Maps API atau (**Leaflet.js**).✅
   Pengguna bisa mengklik pin (marked as plan when view at map) untuk melihat ringkasan info dan tautan ke halaman detailnya.

**Fase 2: Peningkatan Visual & Alur Pengguna yang Lebih Mendalam**
1. Implementasi Halaman Detail (Detail Page UI)
   Tampilan:
   - Hero Image: Saat halaman dibuka, tampilkan satu gambar besar dan berkualitas tinggi dari tempat tersebut di bagian atas.
   - Galeri Foto: Di bawah deskripsi, sediakan galeri berisi 5-10 foto yang bisa di-klik untuk diperbesar (menggunakan lightbox).
   - Tata Letak Informasi: Gunakan ikonografi yang jelas untuk menyajikan informasi kunci secara visual dan mudah dipindai. Contoh:
   - Jam Buka: 10:00 - 22:00
   - Estimasi Harga: Rp 25.000 - Rp 75.000
   - Kontak: 0812-3456-7890
2. Animasi & Transisi Halus (Micro-interactions)
   Tampilan:
   - Animasi Saat Scroll: Saat pengguna menggulir halaman, buat card-card muncul dengan efek fade-in atau slide-up yang lembut (menggunakan library seperti AOS - Animate on Scroll).
   - Efek Hover yang Ditingkatkan: Saat cursor diarahkan ke sebuah card, selain memperbesar, tambahkan efek bayangan yang lebih menonjol atau garis batas berwarna biru langit (sesuai tema) yang muncul perlahan.
   - Skeleton Loaders: Saat halaman pertama kali dimuat atau saat filter diterapkan, jangan tampilkan layar kosong. Tampilkan "kerangka" abu-abu dari card yang berdenyut pelan. Ini memberikan ilusi bahwa aplikasi berjalan cepat.
3. Navigasi Mobile yang Fungsional & Elegan
   Tampilan:
   - Saat tombol hamburger di-klik, menu navigasi muncul dari sisi kiri layar (off-canvas menu) dengan animasi geser yang mulus.
   - Sisa halaman di belakang menu menjadi sedikit lebih gelap (menggunakan overlay) untuk memberikan fokus pada menu yang sedang aktif.


