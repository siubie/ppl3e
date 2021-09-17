# Rangkuman

## BAB 9 – Test Plan

-	Dokumen test plan 
Merupakan dokumen yang mendefinisikan scope dan aktifitas yang dilakukan saat pengujian sistem. Yang berisi pendekatan atau strategi pengujian, tugas, jadwal dan kendala pengujian.

1.	Test Plan Identifier 	: pengenalan dari dokumen test plan yg dapat berupa kode unik maupun informasi penyusun dan tanggal disusunnya dokumen, revisi dll
2.	Introduction 		      : penjelasan secara narasi yang rinci dengan menambahkan subbab.
3.	Refrence 		          : dokumen penunjang untuk penyusunan test plan.
4.	Test Item 		        : daftar item yg akan diteskan.
5.	Software risk issue 	: mencakup hal hal yang tidak pasti dan memiliki potensi kerugian sehingga menghambat berjalannya pl.
6.	Features to be tested 	  : mencakup fitur fitur dan fungsi yang akan diuji
7.	Features not to be tested : berisi fitur yang tidak akan diujikan dengan mencantumkan alasan.
8.	Approach 		              : memberi penjelasan yang akan di ujikan.
9.	Item Pass/fail Criteria 	: menggambarkan proses dan standar keseluruhan untuk mengevaluasi hasil pengujian.
10.	Suspension Criteria and Resumption Requirement :  menentukan kriteria yang akan digunakan untuk dimulainya kembali kapan pengujian akan dilanjutkan setelah dihentikan.
11.	Test Deliverables 	      : Master test plan, Test design, Test procedure.
12.	Remaing Test Tasks 	      : tahapan yang harus dilakukan saat membuat apk, untuk mentrol pembuatan apk.
13.	Enviromental Needs 	      : persyaratan lingkungan pengujian dengan mengidentifikasi peralatan uji apa yang sudah ada dan apa yang perlu dibeli.
14.	Staffing and Training Need : Staffing mendeskripsikan pembagian tugas
15.	Responsibilites 		      : berisi penanggung jawab selama proses pengujian / testing sofware.
16.	Schedule 		              : untuk mengatur rentang waktu setiap bagian tugas.
17.	Planning Risks And Contingencies : memeriksa/ mengontrol risiko dari beberapa bagian. 
18.	Approvals 		            : mencatat sejarah revisi selama proses pengujian.
19.	Glossary 		              : daftar kata yang jarang ditemukan.

**Pertanyaan**

a.	Thalia Amira : Jelaskan secara singkat manfaat dan tujuan dari test plan ?

*Jawaban* : test plan dibuat dengan tujuan agar testing dilakukan secara terarah, baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. Dokumen ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji

b.	M. Yudha Erian: contoh dari glossary ?

*Jawaban* : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI, sehingga terdapat kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. contoh: requirement, software, hardware.



## BAB 2 - Klasifikasi Pengujian Perangkat Lunak

2 Pendekatan tipe pengujian

- Fungsional 		: pengujian yg melakukan validasi hasil implementasi perangkat lunak.

             Ex : fitur login, registras, dll.
  
      	Tujuan 	: menguji masing masing fungsi atau fitur pada perangkat lunak.

- Nonfungsional 	: pengujian yg memeriksa aspek non fungsional dari sistem perangkat lunak yg dibuat

			         Ex : performa sistem, manajemen memori.
        
        	tujuan 	: meningkatkan usability, efisiensi, portability dari perangkat lunak yang dihasilkan.

11 Indikator 

1.	Keamanan 		        : seberapa kuat pl melawan serangan dari dalam/luar.
2.	Reliabilitas 		    : seberapa mampu pl berfungsi secara baik dalam jangka waktu tanpa mengalami kendala/kegagalan.
3.	Survivabitlity 		  : seberapa kuat pl dapat terus berjalan.
4.	Availability 		    : seberapa banyak pengguna dapat menggunakan sistem dalam waktu bersamaan.
5.	Usability 		      : seberapa mudah pengguna dalam mempelajari menggunakan pl tersebut.
6.	Scalability 		    : seberapa mudah pl dinaikkan kapasitas processing untuk memenuhi kebutuhan yang meningkat.
7.	Interoperability 		: seberapa mudah pl dalam berinteraksi dg pl lainnya.
8.	Efficiency 		      : seberapa baik pl dalam menangani permintaan pengguna.
9.	Flexibility 		    : seberapa baik pl dalam kebutuhan hardware dan konfigurasi softwarenya.
10.	Portability 		    : seberapa baik pl dalam konteks pemindahan hardware / software.
11.	Reusability 		    : seberapa baik pl dalam konteks penggunaan kembali.


**Pertanyaan**

a.	Zalna : Apa persamaan pengujian fungsional dan non fungsional ?

*Jawaban* : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing.

b.	Devi Puspitasari : Apa kekurangan dari pengujian fungsional dan non fungsional ?

*Jawaban* : Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tsb.

## BAB  4 – Unit Testing dengan Jest

1.	Intalasi NodeJS : runtime environment untuk JavaScript yang bersifat open-source dan cross-platform.

Langkah-langkah instalasi Node.JS =

-	Buka web noteJs pada https://nodejs.org
-	Melakukan instalasi Node.js
-	Setelah selesai instalasi, melakukan pengecekkan versi node dan npm.

2.	Membuat proyek Node.JS
-	buat folder Bernama LatUnit1, lalu pada address bar folder yang kita buat ketik cmd lalu tekan enter.
-	Setelah cmd terbuka lalu ketik perintah npm init untuk membuat proyek, lalu tekan enter. Isian yang dapat di isi pertama adalah package name.
-	Version, disini adalah versi paket dari NodeJS.
-	Description, pengisian deskripsi disini bersifat opsional.
-	Jika semua isian telah dilengkapi, maka kita akan diminta untuk konfirmasi tekan enter untuk mengkonfirmasi.
-	File package.json berhasil dibuat.

3.	Instalasi Jest : Jest merupakan framework untuk menguji unit pada proyek dengan Bahasa pemrograman java script khususnya berbasis nodeJS
 

**Pertanyaan**

a.	Fransiska : Pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?

*Jawaban* : Penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test
dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.
