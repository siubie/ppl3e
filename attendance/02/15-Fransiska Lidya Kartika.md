# Rangkuman Pertemuan kedua
## 1. BAB 9 - Test Plan
pertanyaan presentasi :
- Thalia Amira : 
Jelaskan secara singkat manfaat dan tujuan dari test plan
**jawaban** : test plan dibuat dengan tujuan agar testing dilakukan secara terarah,
baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. dokumen
ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji

- M. Yudha Erian:
contoh dari glossary
**jawaban** : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI,
sehingga terdapat kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. contoh:
requirement, software, hardware.

## 2. BAB 2 - Klasifikasi Pengujian Perangkat Lunak
### terdapat 2 pendekatan klasifikasi pengujian perangkat lunak: 
- fungsional = menguji masing-masing fitur utama dengan memberikan input dan memvalidasi output apakah berdasarkan kebutuhan fungsional
- non-fungsional = jenis pengujian yang memeriksa aspek non-fungsional 

### metode testing:
- black box testing : pengujiannya tidak memperhatikan kode program, memeriksa UI, database dan fungsionalitasnya
contoh. fitur login, CRUD

- white box testing : pengujian dengan memeriksa kebenaran hasil dari fungsi dalam kode sebuah sistem
contoh. algoritma diskon pada kasir

### Tujuan pengujian Non-fungsional
Meningkatkan usability(kemudahan), efisiensi(ketepatan),maintainability (pemeliharaan), portability (keluwesan) dari produk perangkat lunak yang dihasilkan

### 11 indikator klasifikasi pengujian perangkat lunak
- keamanan : kekuatan melawan serangan dari dalam maupun luar
- reliabilitas : kemampuan berfungsi dalam jangka waktu tertentu tanpa kegagalan
- survivability : kekuatan berjalan dan kembali fungsi normal jika terjadi kegagalan sistem
- availability : banyak pengguna dapat menggunakan sistem dalam satu waktu
- usability : kemudahan pengguna mempelajari penggunaan
- scability : kemudahan kenaikan kapasitas processing untuk memenuhi peningkatan kebutuhan
- Interoperability : kemudahan dalam berinteraksi
- Efficiency :Seberapa baik pl dalam menangani permintaan pengguna. 
- Flexibility : Seberapa baik pl dalam konteks kebutuhan hardware dan konfigurasi softwarenya. 
- Portability : kemudahan dalam pemindahan hardware atau software
- Reusability : kemudahan penggunaan kembali

### pertanyaan :
- Zalna :
Apa persamaan pengujian fungsional dan non fungsional ?
**jawaban** : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing
- Devi :
Apa kekurangan dari pengujian fungsional dan non fungsional ?
**jawaban** : Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tsb.

## 3. BAB 4 - unit testing dengan jest
- melakukan pengecekan node.js dengan cmd
- instal node.js 
- melakukan pengecekan npm
membuat folder
- `npm init` untuk membuat project
 jest adalah framework untuk menguji unit proyek dalam bahasa javascript. berikut step untuk installasi jest:
- membuka cmd pada folder project dan mengetikan `npm install --save-dev jest`
- tunggu hingga selesai

### pertanyaan :
- fransiska:
pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?
**jawaban** : untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test yang juga harus disesuaikan perubahannya, begitu juga dengan penamaan code function. perubahan penamaan harus diikuti dengan perubahan pada parameter pada file lain yang terhubung secara langsung
