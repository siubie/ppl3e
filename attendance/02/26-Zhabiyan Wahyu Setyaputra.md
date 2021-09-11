# Rangkuman pertemuan 2

## Kelompok 9 Test Plan: Fransiska, Ardila, Azmi

Dokumen test plan adalah dokumen yang mendefinisikan scope dan aktifitas yang dilakukan saat pengujian software atau sistem

#### Overview : 
	Test plan identifier : pengenal dari dokumen test plan yang berupa kode unik
	Introduction : penjelasan secara narasi mengenai testing yang dilakukan terhadap objek testing
	Reference : referensi dokumen penunjang untuk menyusun test plan
	Test items : daftar item yang akan diteskan
	Software risk issue : mencakup kemungkinan yang terjadinya hal-hal yang tidak pasti
	Features to be tested : mencakup fitur-fitur dan fungsi yang akan diujikan
	Features not to be tested : mengenai lingkup fitur maupun fungsi yang tidak diujikan
	Approach : bagian yang digunakan untuk memberi deskripsi mengenai cara yang dilakukan untuk melaksanakan testing
	Item pass/faill criteria : berkaitan dengan menentukan kapan item telah lulus/gagal
	Suspension criteria and resumtion requirements : menentukan kriteria yg akan digunakan
	Test deliverables : dokumen-dokumen yang dihasilkan adalah  : Master Test Plan, Test Design, Test Procedure, Test Case, Test Summary.
	Remaining test task : tahapan yg harus dilakukan secara bertahap
	Environmental needs : persyaratan untuk lingkungan pengujian
	Staffing  and Training needs : pembagian tugas dan anggota tim mengikuti pelatihan
	Responsibilities : harus tanggung jawab pada setiap anggota tim
	Schedule : mengatur rentang waktu setiap pembagian tugas
	Planning risk and contingencies : mengontrol risiko dari beberapa bagian
	Approvals : mencatat sejarah revisi yang dilakukan selama proses pengujian perangkat lunak
	Glossary : berisi daftar kata yang jarang digunakan atau asing untuk sebagian orang
  
#### Pertanyaan :
1. Thalia Amira : Jelaskan secara singkat manfaat dan tujuan dari test plan!

    Jawaban : tujuannya agar testing dilakukan lebih  terarah dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing.
2. M. Yudha Erian: Berikan contoh dari glossary!

    Jawaban : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI, sehingga terdapat
    kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. Contoh : requirement, software, hardware.
    
## Kelompok 2 Klasifikasi Pengujian Perangkat Lunak: Thalia, Tyone

#### Ada beberapa indikator yang digunakan sebagai pengujian non fungsional :
1. Keamanan : seberapa kuat perangkat lunak melawan serangan dari dalam maupun luar, misalnya dari virus
2. Reliabilitas : seberapa mampu perangkat lunak berfungsi secara baik dalam jangka waktu tertentu tanpa mengalami kegagalan sistem
3. Survivability :seberapa kuat perangkat lunak berjalan normal jika terjadi kegagalan sistem
4. Availability : seberapa banyak pengguna dapat menggunakan sistem dalam waktu yang bersamaan sekaligus
5. Usability : seberapa mudah user dalam mempelajari menggunakan perangkat lunak tersebut
6. Scalability : seberapa mudah perangkat lunak dinaikkan kapasitas prosesnya untuk memenuhi kebutuhan yang semakin meningkat
7. Interoperability : seberapa mudah perangkat lunak dalam berinteraksi dengan perangkat lunak lainnya
8. Efficiency : seberapa baik perangkat lunak dalam menangani permintaan user
9. Flexibility : untuk mengetahui seberapa baik perangkat lunak dalam konteks kebutuhan hardware dan konfigurasi software
10. Portability : seberapa baik perangkat lunak dalam konteks pemindahan hardware atau software
11. Reusability : seberapa baik perangkat lunak dalam konteks penggunaan kembali bagian dari perangkat lunak tersebut ke perangkat lunak lainnya, bahasa lainnya daur ulang

#### Pertanyaan :
1. Zalna : Apa persamaan pengujian fungsional dan non fungsional?

   Jawaban : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing.
2. Devi : Apa kekurangan dari pengujian fungsional dan non fungsional?

   Jawaban : Mahal dibiaya pengujian. Harus membayar engineer dalam melakukan pengujian perangkat lunak tersebut.
   
## Kelompok 4 Unit Testing dengan Jest : Adi, Firman, Yudha

#### Instalasi Node.js
	Node.js : adalah runtime environment untuk JavaScript yang bersifat open-source dan cross-platform. 
	Node Package Manager (NPM) merupakan sebuah perangkat yang digunakan untuk memanajemen package (library) berbasis Node.js

#### Langkah-langkah instalasi Node.js :
1. Buka website Node.jS
2. Install Node.jS
3. Mengecek versi Node.js dan npm

#### Membuat proyek Node.js :
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

#### Instalasi Jest
Jest merupakan framework untuk menguji unit pada proyek dengan bahasa pemrograman javascript
Langkah-langkah instalasi Jest :
1. Membuka folder LatUnit1 lalu mengetik cmd pada address bar lalu tekan enter, pada cmd ketikkan npm install --save-dev jest lalu tekan enter. 
2. Tunggu instalasi selesai (tergantung kecepatan internet kalian)
3. Instalasi selesai

#### Membuat unit test sederhana 
1. Membuka visual studio code, kemudian membuat file dengan nama tambah.js pada direktori “LatUnit1”
2. Ketikkan code sederhana pada file "tambah.js"
3. Membuat file dengan nama “tambah.test.js” 
4. Merubah code pada package.json dng menulis jest pada “test”
5. Menggunakan flag –coverage

#### Pertanyaan :
1. Fransiska : pada penamaan file "tambah.test.js" apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?

   Jawaban : untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana
   ada sintak test, dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.
