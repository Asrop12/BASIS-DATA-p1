Setup Database MySQL & Create Table

Dokumentasi ini menjelaskan cara masuk ke MySQL dan membuat database serta tabel.

---

1. Masuk ke MySQL

Buka terminal / CMD, lalu jalankan:

mysql -u root -p

Lalu masukkan password MySQL kamu.

---

2. Membuat Database

CREATE DATABASE nama_database;

Contoh:

CREATE DATABASE db_login;

---

3. Menggunakan Database

USE nama_database;

Contoh:

USE db_login;

---

4. Membuat Tabel

Contoh tabel user:

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(100),
    email VARCHAR(100)
);

---

5. Melihat Tabel

SHOW TABLES;

---

6. Melihat Struktur Tabel

DESCRIBE users;

---

7. Menambahkan Data (Opsional)

INSERT INTO users (username, password, email)
VALUES ('admin', '12345', 'admin@gmail.com');

---

8. Melihat Data

SELECT * FROM users;

---

Catatan

- Pastikan MySQL sudah terinstall
- Gunakan password yang aman
- Jangan gunakan data asli untuk testing

---

Author

- Asyroful Awlya Al Maysiry
