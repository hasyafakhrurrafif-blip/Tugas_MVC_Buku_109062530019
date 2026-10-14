# MVC PHP Native - Data Buku

Aplikasi CRUD sederhana untuk mempelajari pola Model-View-Controller pada PHP Native[cite: 3].

## Kebutuhan
- PHP 8.0 atau lebih baru[cite: 3]
- MySQL/MariaDB[cite: 3]
- Web server lokal seperti XAMPP atau Laragon[cite: 3]
- Git[cite: 3]

## Instalasi
1. Clone atau salin project ke folder web server[cite: 3].
2. Import `database/buku.sql`[cite: 3].
3. Sesuaikan koneksi pada `config/database.php`[cite: 3].
4. Buka `http://localhost/mvc-native/public/index.php`[cite: 3].

## Struktur MVC
- `app/models/` : akses dan operasi data[cite: 3].
- `app/controllers/` : alur request dan pemanggilan Model/View[cite: 3].
- `app/views/` : tampilan HTML[cite: 3].
- `config/` : konfigurasi koneksi database[cite: 3].
- `database/` : skema dan data awal SQL[cite: 3].
- `public/` : entry point aplikasi[cite: 3].

## Fitur
- Menampilkan data buku
- Menambah data buku
- Mengubah data buku
- Menghapus data buku

## Histori Git
Gunakan `git log --oneline --graph --decorate` untuk melihat tahapan pengembangan[cite: 3].