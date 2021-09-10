# Attendance 2 – Rangkuman Pertemuan 2
# BAB 9 – TEST PLAN
Test plan adalah dok yang mendefinisikan scope dan aktifitas saat pengujian system
Test plan identifier
Adl pengenal dari dokumen berupa kode unik maupun informasi.
Introduction
Adalah penjelasan secara narasi mengenai testing yang akan dilakukan terhadap objek testing. 
Reference
Referensi saat penyusunan test plan.
Test Item
Berisi tentang daftar item yang akan di teskan
Features to be tested 
Bagian ini mencakup fitur2 dan fungsi yang akan di uji
Features not to be tested
Bagian ini mencakup fitur2 dan fungsi yang tidak akan di ujikan.
Approach
Adalah bagian yang digunakan untuk memberi dekskripsi cara melaksanakan testing.
Item Pas/Fail Creteria
Berkaitan dengan menentukan kapan item telah lulus/gagal.
Test Deliverables
Dokumen yang dihasilkan setelah proses testing selesai.
Staffing 
Adalah pembagian tugas terhadap masing2 anggota uuntuk melakukan tsting sesuai dengan tugas yang diberikan
Schedule
Adalah jadwal untuk mengatur rentang waktu setiap tugas.
Approvals
Adalah mencatat bagian revisi
Glossary
Aadalah daftar kata / istilah selama testing. 

PERTANYAAN BAB 9
a. Thalia Amira : 
Jelaskan secara singkat manfaat dan tujuan dari test plan
*jawaban* : test plan dibuat dengan tujuan agar testing dilakukan secara terarah,
baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. dokumen
ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji

b. M. Yudha Erian:
contoh dari glossary
*jawaban* : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI,
sehingga terdapat kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. contoh:
requirement, software, hardware.
 
# BAB 2 – KLAFIKASI PENGUJIAN PERANGKAT LUNAK

Pengujian Fungsional.
Jenis pengujian yang melakukan validasi
Tujuannya untuk menguji dengan memberikan input , dan memvalidasi output.
Contoh : Blackbox testing dan Whitebox Testing
Pengujian Non Fungsional
Jenis pengujian yang memeriksa aspek2 non fungsional
Contoh performa system, manajemen memory.
Tujuan : Untuk meningkatkan usability kemudahan.
11 indikator
1.	Keamanan
Agar mengetahui seberapa kuat perangkat lunak apabila mendapat serangan dari dalam maupun luar
2.	Reliabilitas
Agar mengetahui seberapa mampu pl berfungsi secara baik dalam jangka waktu tertentu.
3.	Survivability
Adalah seberapa kuat pl berjalan Kembali setelah terjadi kegagalan system
4.	Availability
Seberapa banyak pengguna dapat menggunakan system dalam waktu bersamaan.
5.	Usability
Seberapa mudah pengguna dalam mempelajari menggunakan pl tersebut.
6.	Scalability
7.	Interoparability
Seberapa mudah pl dalam berinteraksi dengan pl lainnya.
8.	Efficiency
Seberapa baik pl dalam menangani permintaan pengguna.
9.	Flexibility
Seberapa baik pl dalam konteks konfigurasi hardware dan konfigurasi softwarenya.
10.	Seberapa baik pl dalam konteks pemindahan hardware dan software.

PERTANYAAN BAB 2
Zalna :
-Apa persamaan pengujian fungsional dan non fungsional ?
--> Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing

Devi :
-Apa kekurangan dari pengujian fungsional dan non fungsional ?
--> Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tsb.

 
# BAB 4 – UNIT TESTING DENGAN JET
1.	Melakukan Instalasi Node JS.
2.	Membuat Proyek NodeJS.

1.	Setelah Cmd terbuka ketik perintah npm init.
2.	Varsion, disini versi adalah versi paket dari NodeJS.
3.	Description
4.	Entry Point
5.	Test Command
6.	Git Repository
Bersifat opsional berisi alamat repo pengisian alamat git repository.
7.	Keyword
8.	Author
9.	Licensi
Adalah jenis lisensi yang diberikan node js

INSTALASI JEST.
Membuat unit test sederhana
1.	Buka Visual studio
2.	Ketikan Coding sederhana
3.	Membuat file dengan nama “ tambah.test.js
Penamaan file test.js diatas sebagai prefix yang berfungsi untuk memanggil unit.
4.	Merubah kodingan pada package.json
5.	Pada jest juga dapat menggunakan flag -convergae untuk informasi tentang code converage.
 
PERTANYAAN BAB 4
-fransiska
pertanyaan
pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?
jawaban
untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test
dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.
