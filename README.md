# Panduan Menjalankan Website CRUD dengan XAMPP

## Deskripsi
Repo ini berisi proyek website CRUD yang dapat digunakan untuk mengelola data.

## Langkah-langkah

1. **Clone Repository**
   - Clone repository ini ke dalam direktori lokal menggunakan perintah berikut:
     ```
     git clone https://github.com/guns-joy/simple-crud.git
     ```

2. **Menghidupkan XAMPP**
   - Pastikan XAMPP telah diunduh, diinstal, dan dijalankan di komputer Anda.
   - Pastikan layanan Apache dan MySQL diaktifkan melalui kontrol panel XAMPP.

3. **Konfigurasi HTDOCS**
   - Pindahkan isi dari direktori proyek ke dalam direktori htdocs di dalam direktori instalasi XAMPP.

4. **Import Database**
   - Buka phpMyAdmin melalui panel XAMPP atau akses melalui browser.
     -impor file `db.sql` yang ada di dalam proyek lalu klik go.

5. **Konfigurasi Servername, Username,Password, dan Nama Database**
   - Buka file konfigurasi proyek (misalnya: `koneksi.php`) dan sesuaikan parameter servername, username, password,dan nama database dengan pengaturan server dan database Anda.

6. **Menjalankan Website**
   - Buka browser dan akses website menggunakan URL yang sesuai dengan pengaturan server Anda.

7. **Menggunakan Website CRUD**
   - Anda sekarang dapat menggunakan website CRUD untuk menambah, mengedit, menghapus, dan mengelola data sesuai kebutuhan Anda.

## Catatan Tambahan
- Pastikan Anda telah menginstal XAMPP dan semua dependensi yang dibutuhkan sebelum menjalankan website.
- Untuk bantuan lebih lanjut, silakan lihat dokumentasi XAMPP atau hubungi tim pengembang.

Selamat menggunakan 🫠🤩!
