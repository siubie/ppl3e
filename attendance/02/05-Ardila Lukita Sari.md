# Rangkuman BAB 2
# ------     Klasifikasi Pengujian Perangkat Lunak    ------

### 
Dalam proses pengujian perangkat lunak, terdapat 2 pendekatan tipe pengujian diantaranya :
1. <b>Pengujian Fungsional</b>
   - <b>Pengertian</b> <br>
		Pengujian fungsional, pengujian yang melakukan validasi hasil implementasi perangkat lunak terhadap spesifikasi dari pengguna.
   - <b>Tujuan</b> <br>
	 - Melakukan pengujian terhadap fitur - fitur perangkat lunak yang telah dibuat oleh tim developer   apakah sudah sesuai dengan requirements yang ada atau belum. Untuk proses pengujian ini sendiri bisa dilakukan dengan 2 cara, yaitu :
   - <b>Cara Pengujian Fungsional</b> <br>
     - <b>Black box testing </b>, pengujian yang tidak memper.hatikan kode program, tetapi lebih kepada fungsionalitasnya, database, dan juga user interface. Contoh: <b>fitur login, CRUD.</b>
     - <b>White box testing</b>, pengujian yang berfokus pada pemeriksaan ketepatan hasil dari fungsi yang ada di dalam kode sistem. Contoh: <b>algoritma pada sebuah sistem.</b>
2. <b>Pengujian Non-Fungsional</b>
   - <b>Pengertian</b> <br> 
 		Pengujian Non-Fungsional, pengujian yang berfokus pada pemeriksaan aspek - aspek non-fungsional sistem, seperti <b>performa sistem, manajamen memori</b>.
	- <b>Tujuan</b> <br>
	  - Meningkatkan usability, efisiensi, maintainability, dan portability dari sistem yang sedang dikembangkan.
	- <b>Indikator Pengujian Non-Fungsional</b> <br>
	  - Security, kekuatan perangkat lunak dalam melawan serangan.            
	  - Reliability, kekonsistenan kinerja perangkat lunak.       
	  - Survivability, sebearapa kuat perangkat lunak dapat berjalan / berfungsi normal setelah terjadi error / bug.
	  - Availability, ketersediaan daya pakai perangkat lunak.
	  - Usability, mudah atau tidaknya user dalam mempelajari sistem.
	  - Scalability,  kemampuan suatu sistem, jaringan, atau proses untuk menangani penambahan beban yang diberikan.
	  - Interoperability, mengukur kemampuan perangkat lunak dalam berinteraksi dengan perangkat lunak yang lain.
	  - Efficiency, kualitas sistem dalam memenuhi requirement atau permintaan user.
	  - Flexibility, kemampuan perangkat lunak untuk menambahkan/memodifikasi/menghapus fungsi tanpa merusak sistem yang sedang berjalan. 
	  - Portability, mengukur mudah atau tidaknya sistem dalam memindahkan hardware / software yang tersedia.
	  - Reusability, kemampuan sebuah sistem yang nantinya dapat digunakan atau diimplementasikan kembali pada program lain.


#

# Rangkuman BAB 4
# ------    Unit Testing Dengan Jest    ------

### 
Untuk melakukan pengujian perangkat lunak dengan menggunakan Jest, ada beberapa langkah awal yang harus dilakukan sebelum proses pengcodingan, yaitu : <br>
1. Melakukan instalasi NodeJs(perangkat yang membantu memenajamen package berbasis NodeJs).
2. Setelah proses instalasi selesai dilakukan, langkah berikutnya ialah membuat folder bernama <b>LatUnit1</b>. 
3. Kemudian kita masuk ke cmd dan coba jalankan perintah <b>npm init</b> untuk membuat project. Untuk informasi - informasi data, seperti package name, versi, deskripsi, dan test command kita isikan sesuai dengan defaultnya.
4. Selanjutnya, kita bisa lanjutkan instalasi Jest dengan menjalankan perintah <b>npm install --save-dev jest</b> di dalam folder<b>LatUnit1</b>. Setelah proses ini selesai, kita bisa lakukan proses testing dengan Jest.

#

# Rangkuman BAB 9
# ------    Test Plan   ------

### 
Test plan adalah salah satu dokumen yang digunakan untuk mendefinisikan scope sekaligus aktifitas yang terjadi selama proses pengujian perangkat lunak. Adapun poin - poin yang menjadi dasar dalam penyusunan dokumen ini ialah :
1. Test plan identifier
2. References
3. Introduction
4. Test item dan software risk issue
5. Features to be tested
6. Features not to be tested
7. Approach
8. Item pass
9. Suspension criteria and resumption requirements
10. Test Deliverables
11. Remaining test tasks
12. Environmental needs
13. Staffing and training needs
14. Responsibilities
15. Schedule
16. Planning risk and contingencies
17. Approvals
18. Glossary 

Dengan adanya dokumen test plan ini, tentunya sistem pengujian perangkat lunak bisa berjalan lebih terstruktur dan terencana dengan baik, terlebih dalam memanajamen kinerja tim, waktu, sumber daya yang ada.


#

# Bagian Akhir
# ------    Pertanyaan dan Jawaban   ------

### 

- KELOMPOK 2 <br>
a. Zalna 
Pertanyaan: <br>
Apa persamaan pengujian fungsional dan non fungsional ?
Jawab: <br>
Keduanya sama - sama diuji, selain itu pengujian keduanya juga bisa sama - sama menggunakan manual testing dan automated testing.<br>
b. Devi 
Pertanyaan: <br>
Apa kekurangan dari pengujian fungsional dan non fungsional ?
Jawab: <br>
Mahal dibiaya pengujian, sebab harus membayar engineer dalam melakukan pengujian perangkat lunak tersebut.

- KELOMPOK 4 <br>
a. Fransiska
Pertanyaan: <br>
Apakah pada penamaan file tambah.test.js merupakan nama default atau nama tersebut bisa ditentukan dan juga apa nama function dapat diubah?
Jawab: <br>
Untuk penamaan file tambah.test.js sendiri pada dasaranya dapat diubah akan tetapi dengan syarat file .test harus mengacu pada file package.json yang mana disana ada sintak test dan kemudian untuk penamaan code function dapat diubah juga, asalkan pada kode berikutnya harus mengikuti nama functionnya.

- KELOMPOK 9 <br>
a. Thalia Amira : <br> 
Pertanyaan: <br>
Jelaskan secara singkat manfaat dan tujuan dari test plan! <br>
Jawab: <br>
Test plan pada dasarnya dibuat agar proses testing perangkat lunak dilakukan secara terarah, baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. Selain itu, dokumen ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji.<br>
b. M. Yudha Erian:  <br> 
Pertanyaan: <br>
Jelaskan dan sebutkan contoh dari glossary!
Jawab: <br>
-  Glossary ialah bagian yang memuat daftar sekumpulan kata atau istilah yang jarang diketahui oleh pembaca yang awam terhadap topik pengujian yang sedang diangkat. Contohnya saja dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI, sehingga terdapat kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. 
-  Contoh Glossary:
Requirement, software, hardware.