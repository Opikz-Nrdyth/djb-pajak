# Sistem Informasi Pajak Bangunan - Admin Dashboard (Frontend Prototype)

## Deskripsi Singkat

Proyek ini merupakan implementasi desain frontend untuk sebuah sistem admin dashboard yang ditujukan untuk pengelolaan data pajak bangunan. Dibuat untuk mendemonstrasikan kemampuan dalam merancang dan mengembangkan antarmuka pengguna (UI/UX) yang modern dan fungsional. Dashboard ini mencakup berbagai modul penting yang umum ditemukan dalam sistem informasi manajemen.

Seluruh desain dan interaksi dirancang agar responsif di berbagai perangkat, mulai dari desktop, tablet, hingga tampilan mobile, dengan memperhatikan pengalaman pengguna yang optimal.

## Fitur Utama yang Telah Dikembangkan

Berikut adalah daftar halaman dan fungsionalitas utama yang telah diimplementasikan dalam prototipe frontend ini:

- **Halaman Login:** Antarmuka masuk yang aman dan menarik dengan latar belakang gambar.
- **Dashboard Utama:**
  - Tampilan ringkasan data penting melalui kartu metrik.
  - Daftar aktivitas terbaru dalam format tabel.
  - Penjelasan mengenai pajak dan DJP.
- **Manajemen Wajib Pajak:**
  - Tampilan tabel data Wajib Pajak dengan pagination.
  - Fitur pencarian dan filter.
  - Tombol aksi untuk setiap baris data (Lihat Detail, Edit, Hapus).
  - Opsi untuk aksi massal (contoh: hapus terpilih).
- **Form Tambah Wajib Pajak Baru:** Formulir komprehensif dengan validasi input untuk pendaftaran Wajib Pajak baru, mencakup data pribadi, kontak, alamat, NPWP, dan informasi akun login.
- **Form Input Data Tagihan dan Perhitungan Pajak:** Antarmuka untuk memasukkan data terkait tagihan dan dasar perhitungan pajak bangunan, menampilkan data pemilik dan detail perhitungan.
- **Laporan Harian:**
  - Filter berdasarkan tanggal.
  - Kartu ringkasan metrik harian.
  - Tabel detail transaksi/aktivitas harian.
  - Opsi ekspor data (CSV/PDF).
- **Laporan Bulanan:**
  - Filter berdasarkan bulan dan tahun.
  - Kartu ringkasan metrik bulanan.
  - Placeholder untuk visualisasi data dengan grafik (misalnya tren harian dalam sebulan).
  - Tabel detail transaksi/aktivitas bulanan.
  - Opsi ekspor data.
- **Rekapitulasi Laporan Pajak:**
  - Filter fleksibel berdasarkan jenis rekapitulasi dan rentang tanggal.
  - Kartu ringkasan metrik agregat.
  - Tabel dan grafik dinamis yang menyesuaikan dengan jenis rekapitulasi terpilih.
  - Opsi ekspor data.
- **Pencarian Detail Laporan Pajak:**
  - Form pencarian berdasarkan NIK, Nama WP, No. Referensi, atau Periode.
  - Indikator loading saat pencarian.
  - Tampilan detail komprehensif untuk satu laporan pajak spesifik, mencakup informasi WP dan rincian tagihan.
- **Halaman Pengaturan:**
  - Antarmuka dengan sistem Tab (Profil Saya, Aplikasi, Notifikasi, Keamanan).
  - Form untuk mengubah profil pengguna (termasuk foto dan password).
  - Pengaturan umum aplikasi (zona waktu, format tanggal).
  - Preferensi notifikasi.
  - Informasi keamanan dasar dan placeholder untuk fitur lanjutan.
- **Layout Admin yang "Paten":**
  - Sidebar navigasi yang dinamis: dapat di-minimize di desktop/tablet, dan berubah menjadi menu off-canvas (hamburger) di mobile.
  - Header utama dengan judul halaman dinamis, pencarian global, notifikasi, dan profil pengguna.
  - Struktur konten modular dimana halaman baru dimuat ke dalam area konten utama (`<section class="content-body">`).
- **Desain Responsif:** Semua halaman dirancang untuk beradaptasi dengan baik pada ukuran layar desktop, tablet, dan mobile.
- **Animasi & Transisi:** Penggunaan animasi dan transisi CSS `ease-out` untuk meningkatkan pengalaman pengguna.

## Teknologi yang Digunakan

- **HTML5:** Untuk struktur dasar halaman web.
- **CSS3:** Untuk styling, layouting (Flexbox, Grid), animasi, dan desain responsif.
- **JavaScript (Vanilla JS):** Untuk interaktivitas dinamis pada antarmuka pengguna, seperti:
  - Toggle sidebar (minimize/maximize, mobile off-canvas).
  - Manajemen Tab pada halaman Pengaturan.
  - Interaksi form dasar dan logika tampilan kondisional.
  - (Dalam pengembangan riil, JS akan digunakan untuk AJAX, validasi kompleks, dan manipulasi data).
- **Font Awesome:** Untuk ikonografi di seluruh aplikasi.

## Struktur Layout "Paten"

Proyek ini dikembangkan dengan konsep layout dasar yang tetap (paten), terdiri dari:

- **Sidebar (`<aside class="sidebar">`):** Navigasi utama aplikasi.
- **Header Konten (`<header class="content-header">`):** Bagian atas area konten utama, berisi judul halaman, search bar, notifikasi, dan profil pengguna.
- **Area Konten Utama (`<section class="content-body">`):** Wadah dinamis dimana konten spesifik setiap halaman akan dimuat.

Pendekatan ini memudahkan pengembangan halaman baru dengan menjaga konsistensi tampilan dan fungsionalitas inti dari tata letak admin.

## Cara Menjalankan Prototipe

Karena ini adalah prototipe frontend murni (HTML, CSS, JavaScript klien):

1.  Clone repositori ini: `git clone https://github.com/username/repository-name.git`
2.  Navigasi ke direktori proyek: `cd repository-name`
3.  Buka file HTML utama (misalnya `login.html` atau salah satu file halaman dashboard seperti `dashboard_manajemen_wp.html`) langsung di browser web modern Anda.

Tidak ada proses build atau dependensi backend yang diperlukan untuk menjalankan prototipe antarmuka ini.

## Screenshot Halaman (Saran)

Untuk visualisasi yang lebih baik, Anda dapat menambahkan screenshot dari setiap halaman utama di sini.
Contoh:

- `[Screenshot Halaman Login]`
- `[Screenshot Dashboard Utama]`
- `[Screenshot Manajemen Wajib Pajak]`
- `[Screenshot Laporan Harian]`
- `[Screenshot Halaman Pengaturan]`

## Dikembangkan Oleh

<p>
  <a href="https://opikstudio.my.id/" target="_blank">
    <img src="https://opikstudio.my.id/images/logo_White.png" alt="Opik Studio Logo" width="150" style="margin-bottom:10px;">
  </a>
  <br>
  <strong>Opik Studio</strong>
</p>

Website Portfolio: [https://opikstudio.my.id/](https://opikstudio.my.id/) <br>
Mari berdiskusi lebih lanjut untuk pengembangan proyek Anda!

---

**Catatan:** Prototipe ini adalah representasi visual dan fungsional dari antarmuka pengguna (frontend). Untuk menjadi aplikasi yang berfungsi penuh, diperlukan integrasi dengan backend untuk manajemen data, otentikasi, dan logika bisnis.

---

## Lisensi (Saran)

Proyek ini dapat dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT) atau lisensi lain pilihan Anda.
