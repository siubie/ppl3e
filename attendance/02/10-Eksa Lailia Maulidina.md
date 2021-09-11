#BAB 9 
##TEST PLAN

Dokumen test plan : Test plan adalah dokumen yang mendefinisikan scope dan aktifitas yang dilakukan saat pengujian software atau sistem.
Overview
1.	Test plan identifier : Test plan identifier merupakan pengenal dari dokumen test plan yang dapat berupa kode unik maupun informasi penyusun dan tanggal disusunnya dokumen, tanggal revisi dan lain-lain
2.	References : Pada bagian ini dicantumkan referensi dokumen penunjang untuk penyusunan test plan
3.	Introduction : berisi tentang daftar item yang akan diteskan. Contoh : Batasan dari pengujian ini menyangkup Aplikasi Web SEO v.1.0 khususnya pada modul HRD.
4.	Test item
5.	Software risk issues : Mencakup kemungkinan terjadinya hal-hal yang tidak pasti dan memiliki potensi kerugian. Contoh : atas waktu yang sedikit, sumber daya tidak mencukupi,
6.	Features to be tested : pada bagian ini mencakup fitur-fitur dan fungsi yang akan diuji. Contoh : fitur-fitur yang diujikan antara lain:
- fitur tambah pegawai
- fitur edit pegawai
- fitur hapus pegawai
7.	Features not to be tested : bagian ini berisi mengenai lingkup fitur maupun fungsi yang tidak diujikan. Contoh : Fitur-fitur   yang   tidak   diuji   adalah   semua   fitur   yang   terdapat   pada   modul  Event, Keuangan, dan Marketing
8.	Approarch : approach adalah bagian yang digunakan untuk memberi deskirpsi mengenai cara/approach yang dilakukan untuk melaksanakan testing dan disertakan dengan penjelasan. Contoh : unit testing menggunakan black box testing dan white box testing beserta dengan penjelasan
9.	Item pass/fail criteria : bagian berkaitan dengan menentukan kapan item telah lulus atau gagal. Contoh : kriteria lolos untuk tiap fase harus terpenuhi sebelum pengujian beranjak menuju fase selanjutnya, dimana persetujuan akan dilakukan oleh project manager seo.
10.	Suspension criteria and resumption requirements : menentukan kriteria yang akan digunakan untuk dimulainya kembali semua atau sebagian kegiatan pengujian. Contoh : Pengujian akan dihentikan jika terjadi masalah pada  localhost, dan akan dilanjutkan kembali secepatnya setelah masalah diatasi
11.	Test deliverables : 
Dokumen-dokumen berikut akan dihasilkan setelah aktivitas pengujian dilakukan:
a. Master Test Plan
b. Test Design
c. Test Procedure
d. Test Case
e. Test Summary
12.	Remaining test tasks : tahapan yang harus dilakukan saat sebuah aplikasi dirilis secara bertahap. 
13.	Environmental needs : Bagian ini menjelaskan persyaratan untuk lingkungan pengujian. Rencana tersebut harus mengidentifikasi peralatan uji apa yang sudah ada dan apa yang perlu dibeli.
14.	Staffing and training needs : pembagian tugas terhadapmasing – masing anggota tim untuk melakukan testing sesuai dengan tugas yang diberikan. setiap anggota tim yang bertugas akan diberikan pelatihan hal ini berlaku juga untuk sistem yang sedang dikembangkan
15.	Responsibilities : bagian ini akan disampaikan tugas dan penanggung jawab selama proses pengujian / testing software.
pembagian tugasnya dibagi menjadi 4 poin, 
- Membuat test plan
- Membuat design test
- Melakukan testing / pengujian
- Membuat dokumen final
16.	Schedule : memuat time schedule yang berfungsi untuk mengatur rentang waktu setiap bagian tugas.
17.	Planning risks and contingencies : bertujuan memeriksa / mengontrol risiko dari beberapa bagian yang tidak masuk dalam control pengerjaan software namun keberadaannya dapat memberikan dampak langsung terhadap proses testing.
18.	Approvals : mencatat sejarah revisi yang dilakukan selama proses pengujian perangkat lunak memuat (tanggal revisi,penyusun, versi, dan juga ringkasan perubahan)
19.	Glossary : Glossary ini sendiri berisi daftar kata atau istilah yang jarang ditemukan atau asing bagi sebagian orang
Pertanyaan :
1.	Jelaskan secara singkat manfaat dan tujuan dari test plan?
Jawab : test plan dibuat dengan tujuan agar testing dilakukan secara terarah baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. Dokumen ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji
2.	Berikan contoh dari glossary!
Jawab : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI. Beberapa kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. contoh: requirement, software, hardware.


#BAB 2
##KLASIFIKASI PENGUJIAN PERANGKAT LUNAK

Ada 2 pendekatan tipe pengujian
1.	Pengujian fungsional : Jenis pengujian perangkat lunak yang melakukan validasi hasil implementasi perangkat lunak, terhadap kebutuhan / spesifikasi dari pengguna. Contoh : fitur login, registrasi dll
Tujuan : menguji masing-masing fungsi / fitur pada perangkat lunak yang dibuat dengan memberikan input dan memvalidasi output. 
Jenis pengujian :
a.	Black box testing : tidak memperhatikan kode program. Contoh : fitur login, CRUD
b.	White box testing : memeriksa kebenaran hasil dari fungsi-fungsi dalam kode system. Contoh : algoritma diskon pada system kasir.
2.	Pengujian non fungsional : memeriksa aspek-aspek non fungsional, dari sistem perangkat lunak yang dibuat. Contoh : performa sistem, manajemen memori
Tujuan : meningkatkan usability(kemudahan), efisiensi(ketepatan), maintainability(pemeliharaan), dan portability(keluwesan) dari produk perangkat lunak yang dihasilkan.
3.	11 indikator 
a.	Keamanan(Security) : Seberapa kuat pl melawan serangan dari dalam maupun dari luar
b.	Reliabilitas (Reliability) : Seberapa mampu pl berfungsi secara baik dalam jangka waktu tertentu tanpa mengalami kegagalan
c.	Survivability : Seberapa kuat pl dapat terus berjalan dan kembali fungsi normal jika terjadi kegagalan sistem
d.	Availability : Seberapa banyak pengguna dapat menggunakan sistem dalam waktu bersamaan
e.	Usability : Seberapa mudah pengguna dalam mempelajari menggunakan pl tsb
f.	Scalability : Seberapa mudah pl dinaikkan kapasitas processing untuk memenuhi kebutuhan yang meningkat
g.	Interoperability : Seberapa mudah pl dalam berinteraksi dengan pl lainnya
h.	Efficiency : Seberapa baik pl dalam menangani permintaan pengguna. Ex : response time
i.	Flexibility : Seberapa baik pl dalam konteks kebutuhan hardware dan konfigurasi softwarenya. Ex : minimum RAM yang dibutuhkan
j.	Portability : Seberapa baik pl dalam konteks pemindahan hardware atau software
k.	Reusability : Seberapa baik pl dalam konteks penggunaan kembali bagian dari pl tsb ke pl lainya.

Pertanyaan 
1.	Apa persamaan pengujian fungsional dan non fungsional ?
Jawab : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing
2.	Apa kekurangan dari pengujian fungsional dan non fungsional ?
Jawab : Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tersebut.




#BAB 6
##UNIT TESTING DENGAN JEST

1.	installasi node.js 
- buka website node.js pada https://nodejs.org  dan download
- menginstall dan mengecek versi dengan npm
2.	membuat proyek node js
- buat folder
- membuka cmd pada address bar folder yang kita buat
- ketik perintah npm init untuk membuat proyek, lalu tekan enter. 
 	 Isian yang dapat di isi pertama adalah package name.
- setelah itu ada Version, disini adalah versi paket dari NodeJS
- ada description, dimana pengisian deskripsi disini bersifat opsional.
- melakukan Entry Point, entry point adalah file utama/induk yang akan diakses pertama, 
 	 isian defaultnya adalah index.js
- Test command : script yang digunakan untuk menjalankan pengujian. 
- Git repository : berisi alamat repository pengisian alamat
- Keywords : berisi kata kunci yang berkaitan dengan proyek disini juga bersifat opsional kita dapat mengisinya atau tidak.
- Author : pemilik dari proyek, yang dapat diisi dengan nama kita.
- license:  Jenis lisensi default yang diberikan NodeJS adalah ISC.
- Jika semua isian telah dilengkapi, maka kita akan diminta untuk konfirmasi,
tekan enter untuk mengkonfirmasi.
3.	installasi jest
- membuka folder  lalu mengetik cmd pada address bar, 
- pada cmd ketikkan npm install --save-dev jest lalu tekan enter
- Tunggu sampai instalasi selesai.
- pada file package.json terdapat informasi mengenai dependency baru yang berisikan jest. 

Dependency tersebut disimpan dengan nama “devDependencies” yang menandakan package dalam daftar tersebut  merupakan package dependency yang hanya digunakan pada proses pengembangan.
- Pada folder, terdapat folder baru dengan nama folder node_modules yang berisi file instalasi   
   jest.
4.	Membuat Unit Test Sederhana
- Buka Visual Studio Kemudian buat file dengan nama tambah.js pada direktori folder
- Ketik kode sederhana pada file tambah.js 
- Lalu membuat file dengan nama “tambah.test.js” 
- rubah kode pada package.json dengan menuliskan jest pada “test”, kemudian ketikan perintah   
  $npm run test.
- Pada jest juga dapat menggunakan flag –coverage untuk informasi tentang code coverage, 
   branch coverage, function coverage, dan line coverage dengan dengan menambahkan 
   package.json

Pertanyaan
1.	Pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?
Jawab : untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.


