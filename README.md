# Manajemen_Jadwal_Latihan_Olahraga

# Deskripsi Program
Program manajemen jadwal latihan olahraga adalah program berbasis Java yang digunakan user untuk mengatur jadwal latihan olahraga mingguan.
Fitur program ini terdiri dari beberapa package:
1. Model: Berisi atribut, constructor, dan getter & setter
2. Service: Menangani logika bisnis dan logika CRUD yang terdiri dari
- Tambah jadwal -> Menambahkan jenis latihan serta hari latihan tersebut
- Lihat jadwal -> Melihat jadwal latihan yang telah ditambahkan
- Update jadwal -> Mengganti jenis latihan dan hari latihan sesuai nomor jadwal
- Hapus jadwal -> Menghapus jadwal latihan yang ada sesuai nomor jadwal
- Cari berdasarkan hari -> Mencari jadwal latihan berdasarkan hari
- Keluar dari program -> Program berhenti
3. Main: Berfungsi sebagai entry poin program

# Alur Program
1. Pilih Menu
<img width="631" height="196" alt="image" src="https://github.com/user-attachments/assets/2e381a8e-61a4-4cab-8ec7-f0d066ee1648" />

Pada opsi 1, user dapat menambahkan jadwal latihan dengan menginput jenis latihan serta hari latihan itu dilakukan. Jadwal akan disimpan ke dalam ArrayList dengan format "Hari - Jenis Latihan". Setelah user menambah jadwal, program akan menampilkan pesan "Jadwal berhasil ditambahkan" sebagai konfirmasi.

2. Pilih menu == 2
  Pada opsi 2, program akan memeriksa apakah ada data di dalam ArrayList. Pertama, program akan cek apakah jadwalLatihan kosong dengan size() == 0.Jika ada, jadwal akan ditampilkan dalam bentuk list.
4. Pilih menu == 3
  Pada opsi 3, user dapat memilih salah satu jadwal yang ingin diperbarui dengan menginput sesuai dengan nomor jadwal. Jika nomor valid, user diminta memasukkan jenis latihan dan hari latihan. Setelah user memperbarui jadwal, program akan menampilkan pesan "Jadwal berhasil diperbarui" sebagai konfirmasi.

6. Pilih menu == 4
Pada opsi 4, user dapat menghapus salah satu jadwal sesuai dengan nomor jadwal yang ditampilkan. Setelah user mwnghapus jadwal, program akan menampilkan pesan "Jadwal berhasil dihapus" sebagai konfirmasi.

8. Pilih menu == 5
ada opsi 5, user dapat mencari jadwal latihan berdasarkan hari latihan.

10. Pilih menu == 6
Pada opsi 5, user dapat menghapus salah satu jadwal sesuai dengan nomor jadwal yang ditampilkan. Setelah user mwnghapus jadwal, program akan menampilkan pesan "Jadwal berhasil dihapus" sebagai konfirmasi.

