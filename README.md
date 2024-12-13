# Lab8
Tugas Praktikum  Mata Kuliah Program Komputer dan Praktek
==========================================================================================================================

**Deskripsi**
Program ini merupakan aplikasi berbasis teks untuk mengelola data mahasiswa menggunakan pendekatan **Object-Oriented Programming (OOP)**. 

Program ini memiliki kemampuan untuk menambahkan, menampilkan, menghapus, dan mengubah data mahasiswa.

**Fitur Program**

Menambahkan Data Mahasiswa

> Pengguna dapat memasukkan nama dan nilai mahasiswa untuk disimpan.

Menampilkan Data Mahasiswa
    
> Program akan mencetak daftar semua mahasiswa beserta nilainya.

Menghapus Data Mahasiswa

> Pengguna dapat menghapus data mahasiswa berdasarkan nama.

Mengubah Data Mahasiswa

> Pengguna dapat memperbarui nilai mahasiswa berdasarkan nama.

Menu Interaktif

> Program menggunakan menu interaktif untuk memudahkan navigasi pengguna.

**Struktur Kelas**
Class Mahasiswa

Class ini bertanggung jawab untuk mengelola data mahasiswa.

Atribut:

**__data_mahasiswa**: List privat untuk menyimpan data mahasiswa.

Metode:
**tambah(nama, nilai)**: Menambahkan data mahasiswa baru.

**tampilkan()**: Menampilkan semua data mahasiswa.

**hapus(nama)**: Menghapus data mahasiswa berdasarkan nama.

**ubah(nama, nilai_baru)** : Mengubah nilai mahasiswa berdasarkan nama.

__find_by_name(nama): Metode privat untuk mencari data mahasiswa berdasarkan nama.

**Class Menu**

Class ini bertanggung jawab untuk menyediakan antarmuka pengguna.

Atribut:

mahasiswa: Objek dari kelas Mahasiswa.

Metode:

tampilkan_menu(): Menampilkan menu utama dan menangani input pengguna.

__menu_tambah(): Menangani input untuk menambahkan data mahasiswa.

__menu_hapus(): Menangani input untuk menghapus data mahasiswa.

__menu_ubah(): Menangani input untuk mengubah data mahasiswa.

Cara Menjalankan Program

Pastikan Python sudah terinstall pada sistem Anda.

Simpan kode dalam file Python (misalnya main.py).

Jalankan file menggunakan perintah:
Tugas Lab 8.py

Pilih opsi pada menu utama sesuai kebutuhan Anda:

1: Tambah Data

2: Tampilkan Data

3: Hapus Data

4: Ubah Data

5: Keluar

**Diagram Class**
![395343798-b39bd0c5-60c0-48a2-8a15-a622b7e0312b](https://github.com/user-attachments/assets/acdc2785-af96-48dd-9981-99f94e02e685)

**FlowChart**
![395340670-e9131640-a2e0-4870-bace-478b3bd37aae](https://github.com/user-attachments/assets/f1e882e8-0902-476a-915f-a73c0825df5c)

**Code Program**
![Cuplikan layar 2024-12-13 090431](https://github.com/user-attachments/assets/8d8e21f4-1348-4f8a-ba5e-f11313177a91)
![Cuplikan layar 2024-12-13 090502](https://github.com/user-attachments/assets/7476da38-8a22-46a9-b032-a8b1245e7338)
![Cuplikan layar 2024-12-13 090519](https://github.com/user-attachments/assets/1285ebc7-6a1a-4ea1-bf99-dbe70280d86a)

**Hasil Program**
![Cuplikan layar 2024-12-13 090332](https://github.com/user-attachments/assets/4736cfc8-d710-42ea-82f9-9554af5bc35f)
![Cuplikan layar 2024-12-13 090353](https://github.com/user-attachments/assets/5ae0099f-5539-4fc0-bf1f-ca9fcbc33ba2)




