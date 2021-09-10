# Rangkuman pertemuan 2

## Kelompok 9 : Fransiska, Ardila, Azmi (Test Plan)

### Dokumen test plan 
adalah dokumen yang mendefinisikan scope dan aktifitas yang dilakukan saat pengujian software atau sistem

### Overview : 
•	test plan identifier : pengenal dari dokumen test plan yg dapat berupa kode unik
•	Introduction : penjelasan secar narasi mengenai testing yang akan dilakukan terhadap object testing.
•	Reference : referensi dokumen penunjang untuk menyusun test plan.
•	Test items : berisi daftar item yang akan diteskan
•	Software risk issue : mencakup kemungkinan yang terjadinya hal-hal yang tidak pasti
•	Features to be tested : mencakup fitur2 dan fungsi yang akan diujikan
•	Features not to be tested : berisi fitur maupun fungsi yang tidak diujikan
•	Approach : bagian yg digunakan untuk memberi deskripsi mengenai cara yang dilakukan untuk melaksanakan testing
•	Item pass/faill criteria : berkaitan dengan menentukan kapan item telah lulus/gagal
•	Suspension criteria and resumtion requirements : menentukan kriteria yg akan digunakan untuk dimulainya kembali semua atau sebagian kegiatan pengujian
•	Test deliverables : dokumen-dokumen yang dihasilkan adalah  : Master Test Plan, Test Design, Test Procedure, Test Case, Test Summary.
•	Remaining test task : tahapan yg harus dilakukan saat sebuah aplikasi dirilis secara bertahap
•	Environmental needs : menjelaskan persyaratan untuk lingkungan pengujian
•	Staffing  yaitu mendeskripsikan pembagian tugas terhadap masing-masing anggota. Training needs yaitu pelatihan untuk anggota yang bertugas dan juga sisitem yang sedang dikembangkan.
•	Responsibilities : akan disampaikan tugas dan penanggung jawab selama proses pengujian
•	Schedule : akan membuat time schedule yang berfungsi untuk mengatur rentang waktu setiap bagian tugas
•	Planning risk and contingencies : dengan tujuan memeriksa/mengontroli resiko dari beberapa bagian
•	Approvals : mencatat sejarah revisi yang dilakukan selama proses pengujian perangkat lunak
•	Glossary : beris daftar kata yang jarang digunakan /ditemukan untuk sebagian orang

### Pertanyaan :
1. Thalia Amira : Jelaskan secara singkat manfaat dan tujuan dari test plan !
Jawaban : tujuannya agar testing dilakukan lebih  terarah dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing.
2. M. Yudha Erian: Berikan contoh dari glossary!
Jawaban : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI, sehingga terdapat kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. Contoh : requirement, software, hardware.

## Kelompok 2 : Thalia, tyo (Klasifikasi Pengujian Perangkat Lunak)

### 2 pendekatan tipe pengujian :
•	Fungsional : pengujian dengan melakukan validasi hasil implementasi perangkat lunak. Tujuannya dari pengujian fungsional adalah menguji masing-masing fungsi/fitur pada perangkat lunak.
Black box testing : pengujiannnya tidak memerlukan kode program
White boc testing : dengan memeriksa fungsi-fungsi dalam kode sebuah sistem
•	Non-fungsional : jenis pengujian perangkat lunak yang memeriksa aspek-aspek non fungsional dari system perangkat lunak yang dibuat
Tujuan  dari pengujian non-fungsional meningkatkan, kemudahan, ketepatan, pemeliharaan, dan keluwesan dari produk perangkat lunak yang dihasilkan.

### 11	indikator /pedoman :
1. Keamanan : seberapa kuat perangkat lunak melawan serangan dari dalam maupun luar
2. Reliabilitas : seberapa mampu perangkat lunak berfungsi secara baik dalam jangka waktu tertentu tanpa mengalami kegagalan
3. Survivability :seberapa kuat perangkat lunak berjalan normal jika terjadi kegagalan system
4. Availability : seberapa banyak pengguna dapat menggunakan sistem dlm waktu bersamaan
5. Usability : seberapa mudah pengguna dalam mempelajari menggunakan perangkat lunak tersebut
6. Scalability : seberapa mudah perangkat lunak dinaikkan kapasitas processing untuk memenuhi kebutuhan yang meningkat
7. Interoperability : seberapa mudah perangkat lunak dalam berinteraksi dengan perangkat lunak lainnya
8. Efficiency : seberapa baik perangkat lunak dalam menangani permintaan pengguna
9. Flexibility : untuk mengetahui seberapa baik perangkat lunak dalam konteks kebutuhan hardware dan konfigurasi software
10. Portability : seberapa baik perangkat lunak dalam konteks pemindahan hardware /software
11. Reusability : seberapa baik perangkat lunak dalam konteks penggunaan kembali bagian dari perangkat lunak tersebut ke perangkat lunak lainnya

### Pertanyaan :
1. Zalna : Apa persamaan pengujian fungsional dan non fungsional ?
Jawaban : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing
2. Devi : Apa kekurangan dari pengujian fungsional dan non fungsional ?
Jawaban : Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tsb.

## Kelompok 4 : Yudha Erian, Agung Adi, Firman (Unit Testing dengan Jest)

### Instalasi note js
•	Note.js : adalah runtime environment untuk JavaScript yang bersifat open-source dan cross-platform. 
•	Node Package Manager (NPM) merupakan sebuah perangkat yang digunakan untuk memanajemen package (library) berbasis NodeJS. 

### Langkah-langkah instalasi nodeJS :
1. Buka website NodeJS
2. Installasi NodeJS
3. Mengecek versi node dan npm

### Membuat proyek nodeJS :
1. Buat folder bernama LatUnit1, lalu pada address bar folder yang kita buat ketik cmd lalu tekan enter.
2. Setelah cmd terbuka ketik perintah npm init untuk membuat proyek baru
3. Version
4. Description
5. Entry point
6. Test command
7. Git repository
8. Keyword berisi kata kuncidengan proyek (opsional)
9. Author
10. Lisensi default
11. Konfirmasi
12. File package .json berhasil dibuat

### Instalasi Jest
Jest merupakan framework untuk menguji unit pada proyek dengan Bahasa pemrograman java script
Langkah-langkah instalasi Jest :
1. Membuka folder LatUnit1 lalu mengetik cmd pada address bar lalu tekan enter, pada cmd ketikkan npm install --save-dev jest lalu tekan enter. 
2. Tunggu instalasi selesai (tergantung kecepatan internet)
3. Instalasi selesai

### Membuat unit test sederhana 
1. Membuka visual studio, kemudian membuat file dengan nama tambah.js pada direktori “LatUnit1”
2. Ketikkan coding sederhana pada file tambah.js
3. Membuat file dengan nama “tambah.test.js” 
4. Merubah kodingan pada package.json dng menulis jest pada “test”
5. Menggunakan flag –converage

### Pertanyaan :
1. Fransiska : pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?
Jawaban : untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test, dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.
