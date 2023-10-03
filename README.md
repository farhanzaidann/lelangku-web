# Sistem Lelang Online :handbag:

> Projek ini merupakan _project open source_, Anda dapat download/fork/clone pada projek ini.
> Aplikasi Sistem Lelang berbasis website, dibuat dengan Bahasa Pemrograman **PHP Native versi 8.x dengan menggunakan pattern MVC (Model View Controller), MySQL dan Bootstrap 5**.

## 🤔 Latar Belakang dan Tujuan

Ditujukan untuk memenuhi program Uji Kompetensi Keahlian Rekayasa Perangkat Lunak (RPL) dan sebagai metode pembelajaran untuk memperdalam pengembangan _software_ menggunakan teknologi _frontend_ dan _backend_ serta berguna bagi masyarakat yang ingin membangun sebuah sistem lelang barang secara _online_.

## 💻 Tools & Software yang Digunakan

    XAMPP 8.1.2
    Code Editor

## 🔧 Konfigurasi

- Import file lelang.sql ke database
- Buka file app/config/config.php
- Ubah pada bagian

      const BASE_URL = 'http://localhost/php-lelang';
      const DB_NAME = 'lelang';

- Sesuaikan dengan yang kalian punya

## :man: Akun

    - Hak Akses Administrator
    	Username: admin
    	Password: batagorenak
    - Hak Akses Petugas
    	Username: petugas
    	Password: batagorenak
    - Hak Akses Masyarakat/User
    	Username: fikri
    	Password: batagorenak