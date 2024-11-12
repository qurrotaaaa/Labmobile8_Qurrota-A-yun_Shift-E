# CRUD Ionic - Data Mahasiswa
Aplikasi CRUD sederhana menggunakan Ionic untuk mengelola data mahasiswa.

Nama: Qurrota A'yun
Jurusan: Informatika


1. Tampil Data (Read)
![alt text](image-2.png)
Penjelasan:
- Halaman utama menampilkan daftar mahasiswa dalam bentuk card
- Setiap card menampilkan informasi nama dan jurusan mahasiswa
- Terdapat tombol "Tambah Mahasiswa" di bagian atas untuk menambah data baru
- Setiap card memiliki 2 tombol: Edit (biru) dan Hapus (merah)
- Data diambil dari database menggunakan API service
- List akan auto-refresh setiap ada perubahan data

2. Tambah Data (Create)
![alt text](image-1.png)
Penjelasan:
- Modal form untuk menambah data mahasiswa baru
- Terdapat 2 input field:
  * Nama Mahasiswa (wajib diisi)
  * Jurusan Mahasiswa (wajib diisi)
- Tombol "Batal" untuk menutup modal
- Tombol "Tambah Mahasiswa" untuk menyimpan data
- Validasi: semua field harus diisi
- Setelah berhasil tambah, modal tertutup dan list terupdate

3. Edit Data (Update)
![alt text](image-3.png)
Penjelasan:
- Modal form untuk mengubah data mahasiswa yang sudah ada
- Field nama dan jurusan otomatis terisi dengan data existing
- ID mahasiswa disimpan dalam hidden input
- Tombol "Batal" untuk membatalkan perubahan
- Tombol "Edit Mahasiswa" untuk menyimpan perubahan
- Setelah berhasil edit, modal tertutup dan list terupdate

4. Konfirmasi Hapus (Delete)
![alt text](image-4.png)
Penjelasan:
- Alert konfirmasi muncul sebelum menghapus data
- Menampilkan pesan "Apakah Anda yakin ingin menghapus data ini?"
- Terdapat 2 pilihan:
  * "Tidak" - membatalkan penghapusan
  * "Ya" - melanjutkan proses hapus
- Mencegah penghapusan data yang tidak disengaja

5. Hasil Setelah Hapus
![alt text](image-5.png)
Penjelasan:
- Tampilan list setelah data berhasil dihapus
- Data yang dihapus sudah tidak muncul di list
- List otomatis terupdate setelah penghapusan
- Tidak perlu refresh manual