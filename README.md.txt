BiGoTalent

Aplikasi desktop berbasis Java untuk membantu proses pendaftaran siswa ke berbagai lomba. Project ini dibuat menggunakan Java Swing di NetBeans dan MySQL sebagai database.

Fitur

- Login pengguna.
- Pemisahan peran admin dan siswa sesuai rancangan database.
- Menampilkan pilihan lomba dari database.
- Pendaftaran siswa ke lomba yang dipilih.
- Menampilkan status pendaftaran siswa.
- Penyimpanan data menggunakan MySQL.

Teknologi

- Java
- Java Swing
- NetBeans IDE
- MySQL
- phpMyAdmin
- JDBC MySQL Connector

Struktur Project

```text
BiGoTalent/
├── src/
├── nbproject/
├── test/
├── database/
│   └── db_bigottalent.sql
├── .gitignore
└── README.md
```

Persyaratan

- Java Development Kit (JDK) yang sesuai dengan konfigurasi project.
- NetBeans IDE.
- MySQL Server.
- MySQL Connector/J.

## Cara Menjalankan

1. Pastikan MySQL Server sudah berjalan.
2. Buka phpMyAdmin melalui `http://localhost/phpmyadmin`.
3. Buat database bernama `db_bigottalent`.
4. Impor file `database/db_bigottalent.sql`.
5. Buka project BiGoTalent melalui NetBeans.
6. Pastikan konfigurasi koneksi database di `Koneksi.java` sesuai dengan MySQL lokal.
7. Pastikan MySQL Connector/J tersedia pada konfigurasi project.
8. Jalankan project dari NetBeans.

Database

Nama database: `db_bigottalent`

Database digunakan untuk menyimpan data pengguna, daftar lomba, dan pendaftaran siswa.

Catatan

Konfigurasi database pada setiap komputer mungkin perlu disesuaikan. Jangan menyertakan password asli atau informasi sensitif dalam repository publik.

Pengembang

BiGoTalent — Project aplikasi desktop Java.
