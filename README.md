
🕊️ PETUNJUK INSTALASI WEB — SIMANTAB CBT v1.0.8

Aplikasi CBT Mandiri Ramah Madrasah & Sekolah
Wakaf Pendidikan dari Kang Ndofar (MA Nahdlatuth Thalabah, Kesilir - Jember)


Terima kasih telah menggunakan SIMANTAB CBT!
Aplikasi ini telah dilengkapi dengan Web Installer Wizard otomatis 5 langkah
sehingga Anda tidak perlu melakukan konfigurasi kode yang rumit.

----------------------------------------------------------------------------
A. CARA MEMASANG DI XAMPP / LARAGON (WINDOWS):
----------------------------------------------------------------------------
1. Ekstrak seluruh isi file ZIP ini ke dalam folder:
   - XAMPP  : C:\xampp\htdocs\cbt
   - Laragon: C:\laragon\www\cbt

2. Pastikan Apache dan MySQL sudah dijalankan (Start) di control panel XAMPP/Laragon.

3. Buka peramban (Google Chrome/Edge/Firefox) lalu kunjungi alamat:
   http://localhost/cbt
   atau
   http://localhost/cbt/install

4. Ikuti panduan wizard 5 langkah di layar:
   - Langkah 1: Pemeriksaan Kesiapan Server & Ekstensi PHP
   - Langkah 2: Konfigurasi Database (Host: 127.0.0.1, Port: 3306, User: root)
   - Langkah 3: Inisialisasi Skema & Master Data Wilayah Indonesia (Otomatis)
   - Langkah 4: Pengisian Profil Lembaga, Akun Superadmin, & Opsi Demo Pack
   - Langkah 5: Selesai & Aplikasi Siap Digunakan!

----------------------------------------------------------------------------
B. CARA MEMASANG DI WEB SERVER / CPANEL / VPS (LINUX):
----------------------------------------------------------------------------
1. Unggah dan ekstrak file ZIP ini ke direktori web server (misal: /var/www/html/cbt
   atau public_html/cbt).

2. Pastikan direktori berikut memiliki izin tulis (writable):
   - storage/
   - bootstrap/cache/

   (Pada Linux: chmod -R 775 storage bootstrap/cache && chown -R www-data:www-data storage bootstrap/cache)

3. Buat database baru di MySQL/MariaDB (misal: cbt_db) dan pengguna basis datanya.

4. Buka URL domain/subdomain Anda di peramban (misal: https://cbt.sekolahanda.sch.id).
   Sistem akan otomatis mengarahkan ke halaman instalasi (/install).

5. Masukkan rincian database, lalu ikuti langkah berikutnya sampai selesai!

----------------------------------------------------------------------------
C. BANTUAN & KONTRIBUSI:
----------------------------------------------------------------------------
- Playlist Panduan YouTube: https://www.youtube.com/playlist?list=PLbCxEFbLpJQs
- Dukungan & Komunitas: MA Nahdlatuth Thalabah Kesilir - Wuluhan - Jember
============================================================================
