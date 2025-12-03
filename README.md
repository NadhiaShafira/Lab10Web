# Lab10Web

**Nama         : Nadhia Shafira**

**Kelas        : TI.24.A.5**

**Matkul       : Pemograman Web 1**

# 📝 Praktikum 10 — Pemrograman Web (PHP OOP)

Laporan ini berisi hasil pengerjaan Praktikum 10 yang mencakup konsep **Object-Oriented Programming (OOP) di PHP**, penggunaan **Class**, **Object**, **Modularisasi**, hingga implementasi CRUD menggunakan **MySQL + PHP OOP** serta **layout template Bootstrap**.

---

# Program Class Mobil (OOP Dasar)

Pada tahap ini dibuat file `mobil.php` berisi class:

* Atribut: `warna`, `merk`, `harga`
* Method: `gantiWarna()`, `tampilWarna()`
* 2 objek mobil diciptakan dan dilakukan perubahan warna.

📸 **Screenshot:** 

![foto](https://github.com/NadhiaShafira/Lab10Web/blob/9e14bf88bdeb51b65df3e2377963aaab66aa1e8b/SS_Prak10/01-output-mobil..png) 

---

# Class Form (Modularisasi)

File `form.php` berisi class untuk membuat form secara dinamis dengan method:

* `addField()`
* `displayForm()`

📸 **Screenshot:**

![foto](https://github.com/NadhiaShafira/Lab10Web/blob/0041945d07b92401c634efcd342f1f508b1682e0/SS_Prak10/02-kode-form-php..png) 

---

# ⭐ 3. Implementasi Form (form_input.php)

File ini memanggil class Form dari `form.php` lalu menampilkan form input berisi:

* NIM
* Nama
* Alamat

📸 **Screenshot:** 

![foto](https://github.com/NadhiaShafira/Lab10Web/blob/5719825a28611b2899b7424e4ee8a167287ef448/README.md)

---

# ⭐ 4. Class Database (CRUD Modular)

File `database.php` berisi class Database lengkap dengan method:

* `query()`
* `get()`
* `insert()`
* `update()` (SUDAH diperbaiki)
* `delete()`

📸 **Screenshot:** 02-kode-database-php.png

---

# ⭐ 5. Template Layout (Bootstrap Pink Theme)

Aplikasi kini memakai tampilan konsisten melalui file `layout.php` (gabungan navbar, sidebar, footer).

📸 **Screenshot Layout:** 10-layout-via-dashboard.png

---

# ⭐ 6. Halaman Dashboard

Dashboard menampilkan jumlah total mahasiswa serta card informasi.

📸 **Screenshot:** 11-dashboard.png

---

# ⭐ 7. Menampilkan Semua Data Mahasiswa (Read)

Menggunakan file `list_mahasiswa.php` untuk menampilkan seluruh data dalam bentuk tabel.

📸 **Screenshot:** 12-list-mahasiswa.png

---

# ⭐ 8. Input Data (Create)

Form input mahasiswa → memproses ke `proses_input.php` → insert ke database.

📸 **Screenshot Form:** 13-form-input.png
📸 **Screenshot Proses:** 14-proses-input.png

---

# ⭐ 9. Edit Data (Update)

Halaman edit memanggil data berdasar NIM, kemudian disimpan melalui `proses_edit.php`.

📸 **Screenshot Edit:** 15-edit-mahasiswa.png
📸 **Screenshot Proses Edit:** 16-proses-edit.png

---

# ⭐ 10. Delete Data (Delete)

Menghapus data mahasiswa melalui `delete_mahasiswa.php`.

📸 **Screenshot:** 17-proses-delete.png

---

# ⭐ 11. Struktur Folder Proyek

```
lab10_php_oop/
│
├── mobil.php
├── form.php
├── form_input.php
├── database.php
├── layout.php
├── dashboard.php
├── list_mahasiswa.php
├── edit_mahasiswa.php
├── proses_input.php
├── proses_edit.php
├── delete_mahasiswa.php
└── config.php
```

---

# ⭐ 12. Database Structure

Tabel: **mahasiswa**

```
+--------+-----------+----------+
| nim    | nama      | alamat   |
+--------+-----------+----------+
| PK     | VARCHAR   | VARCHAR  |
```

---

# Kesimpulan

Pada praktikum ini berhasil dibuat:
✔ Penerapan OOP (Class + Object)
✔ Class Form (Modularisasi)
✔ Class Database dengan CRUD
✔ Implementasi CRUD (Create, Read, Update, Delete)
✔ Template layout Bootstrap yang konsisten (navbar, sidebar, footer)
✔ Tampilan dashboard dan halaman data mahasiswa yang rapi & modern (pink theme)

Semua fungsi bekerja dengan baik tanpa error.

---



💗 **Laporan selesai. Bila ingin diperbaiki gaya bahasanya atau versi PDF / Word, bilang saja!**

