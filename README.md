# TabungSiswa

TabungSiswa adalah aplikasi berbasis web yang dirancang untuk memudahkan manajemen tabungan siswa. Aplikasi ini memungkinkan siswa, guru, dan staf sekolah untuk mencatat, memantau, dan mengelola aktivitas tabungan secara efisien. Dibuat menggunakan **PHP** dan **MySQL 5.7**, aplikasi ini menyediakan antarmuka yang sederhana namun fungsional untuk semua pengguna.

## Fitur

- **Manajemen Akun Pengguna:** Siswa dapat membuat akun dan mengelola saldo tabungan mereka.
- **Transaksi Simpanan dan Penarikan:** Memungkinkan siswa untuk mencatat simpanan dan penarikan uang secara mudah.
- **Laporan Keuangan:** Guru atau admin dapat memantau dan mencetak laporan tabungan siswa.
- **Keamanan Data:** Menggunakan PHP dan MySQL untuk pengelolaan data dengan aman.

## Prasyarat

Sebelum memulai, pastikan Anda memiliki persyaratan berikut:

- **PHP** (versi 7.x atau lebih baru)
- **MySQL** (versi 5.7)
- Web server seperti **Apache** atau **Nginx**

## Instalasi

1. Clone repositori ini:

    ```bash
    git clone https://github.com/sowhatinfosec/tabungsiswa.git
    ```

2. Buka folder project:

    ```bash
    cd tabungsiswa
    ```

3. Buat database MySQL baru dan impor file SQL yang terdapat di folder `db/`:

    ```bash
    mysql -u root -p < db/tabungsiswa.sql
    ```

4. Konfigurasi file `config.php` untuk menghubungkan aplikasi dengan database MySQL Anda:

    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'root');
    define('DB_PASSWORD', 'password');
    define('DB_NAME', 'tabungsiswa');
    ```

5. Jalankan aplikasi di web server lokal Anda.

## Penggunaan

- **Siswa:** Setelah mendaftar, siswa dapat melihat saldo tabungan, menyetor uang, dan mencatat penarikan.
- **Admin:** Admin memiliki akses untuk melihat semua akun siswa dan mengelola laporan keuangan.

## Kontribusi

Kontribusi sangat terbuka! Jika Anda ingin berkontribusi:

1. Fork repositori ini.
2. Buat branch fitur (`git checkout -b fitur-anda`).
3. Commit perubahan Anda (`git commit -am 'Tambahkan fitur baru'`).
4. Push ke branch tersebut (`git push origin fitur-anda`).
5. Buat Pull Request.

## Lisensi

Aplikasi ini dilisensikan di bawah [MIT License](LICENSE).

