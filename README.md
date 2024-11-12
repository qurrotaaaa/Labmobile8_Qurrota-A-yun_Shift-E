# CRUD Ionic - Data Mahasiswa
Aplikasi CRUD sederhana menggunakan Ionic untuk mengelola data mahasiswa.

Nama: Qurrota A'yun
Jurusan: Informatika

1. Tambah Data (Create)
![image](https://github.com/user-attachments/assets/73445a91-3b60-4a5f-af6e-253cebcee2d0)

Penjelasan:
- Modal form untuk menambah data mahasiswa baru
- Terdapat 2 input field:
  * Nama Mahasiswa (wajib diisi)
  * Jurusan Mahasiswa (wajib diisi)
- Tombol "Batal" untuk menutup modal
- Tombol "Tambah Mahasiswa" untuk menyimpan data
- Validasi: semua field harus diisi
- Setelah berhasil tambah, modal tertutup dan list terupdate

2. Tampil Data (Read)
   ![image](https://github.com/user-attachments/assets/405fa51b-7fbc-40a0-8f11-11b0fe7c4920)
   
Penjelasan:
- Halaman utama menampilkan daftar mahasiswa dalam bentuk card
- Setiap card menampilkan informasi nama dan jurusan mahasiswa
- Terdapat tombol "Tambah Mahasiswa" di bagian atas untuk menambah data baru
- Setiap card memiliki 2 tombol: Edit (biru) dan Hapus (merah)
- Data diambil dari database menggunakan API service
- List akan auto-refresh setiap ada perubahan data

3. Edit Data (Update)
![image](https://github.com/user-attachments/assets/3c0b2c14-3b68-41b9-a957-232cd6c2a0b0)

Penjelasan:
- Modal form untuk mengubah data mahasiswa yang sudah ada
- Field nama dan jurusan otomatis terisi dengan data existing
- ID mahasiswa disimpan dalam hidden input
- Tombol "Batal" untuk membatalkan perubahan
- Tombol "Edit Mahasiswa" untuk menyimpan perubahan
- Setelah berhasil edit, modal tertutup dan list terupdate

4. Konfirmasi Hapus (Delete)
![image](https://github.com/user-attachments/assets/cba0e8dc-75e9-40ce-aed5-6d57c390184c)

Penjelasan:
- Alert konfirmasi muncul sebelum menghapus data
- Menampilkan pesan "Apakah Anda yakin ingin menghapus data ini?"
- Terdapat 2 pilihan:
  * "Tidak" - membatalkan penghapusan
  * "Ya" - melanjutkan proses hapus
- Mencegah penghapusan data yang tidak disengaja

5. Hasil Setelah Hapus
![image](https://github.com/user-attachments/assets/8783fa60-759d-4dd4-be45-4dee889cbc25)

Penjelasan:
- Tampilan list setelah data berhasil dihapus
- Data yang dihapus sudah tidak muncul di list
- List otomatis terupdate setelah penghapusan
- Tidak perlu refresh manual
