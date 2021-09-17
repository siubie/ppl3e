# BAB 2
# KLASIFIKASI PENGUJIAN PERANGKAT LUNAK

Pengujian fungsional : Jenis pengujian perangkat lunak yang melakukan validasi hasil implementasi perangkat lunak, terhadap kebutuhan / spesifikasi dari pengguna. Contoh : fitur login, registrasi dll

Tujuan : menguji masing-masing fungsi / fitur pada perangkat lunak yang dibuat dengan memberikan input dan memvalidasi output. 
Jenis pengujian :

Pengujian non fungsional : memeriksa aspek-aspek non fungsional, dari sistem perangkat lunak yang dibuat. Contoh : performa sistem, manajemen memori

Tujuan : meningkatkan usability(kemudahan), efisiensi(ketepatan), maintainability(pemeliharaan), dan portability(keluwesan) dari produk perangkat lunak yang dihasilkan.

# PERTANYAAN

Apa persamaan pengujian fungsional dan non fungsional ?

Jawab : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing

Apa kekurangan dari pengujian fungsional dan non fungsional ?

Jawab : Mahal dibiaya pengujian. harus membayar engineer dalam melakukan pengujian perangkat lunak tersebut.

# BAB 6
# SKENARIO PENGUJIAN DAN KASUS UJI

1. Instalasi Node.js
- buka website node.js pada https://nodejs.org  dan download
- menginstall dan mengecek versi dengan npm

2. membuat proyek node js
- buat folder
- membuka cmd pada address bar folder yang kita buat
- ketik perintah npm init untuk membuat proyek, lalu tekan enter. 

Isian yang dapat di isi pertama adalah package name.
- setelah itu ada Version, disini adalah versi paket dari NodeJS
- ada description, dimana pengisian deskripsi disini bersifat opsional.
- melakukan Entry Point, entry point adalah file utama/induk yang akan diakses pertama, 

Isian defaultnya adalah index.js
- Test command : script yang digunakan untuk menjalankan pengujian. 
- Git repository : berisi alamat repository pengisian alamat
- Keywords : berisi kata kunci yang berkaitan dengan proyek disini juga bersifat opsional kita dapat mengisinya atau tidak.
- Author : pemilik dari proyek, yang dapat diisi dengan nama kita.
- license:  Jenis lisensi default yang diberikan NodeJS adalah ISC.
- Jika semua isian telah dilengkapi, maka kita akan diminta untuk konfirmasi, tekan enter untuk mengkonfirmasi.
3. installasi jest
- membuka folder  lalu mengetik cmd pada address bar, 
- pada cmd ketikkan npm install --save-dev jest lalu tekan enter
- Tunggu sampai instalasi selesai.
- pada file package.json terdapat informasi mengenai dependency baru yang berisikan jest.
4. Membuat Unit Test Sederhana
- Buka Visual Studio Kemudian buat file dengan nama tambah.js pada direktori folder
- Ketik kode sederhana pada file tambah.js 
- Lalu membuat file dengan nama “tambah.test.js” 
- rubah kode pada package.json dengan menuliskan jest pada “test”, kemudian ketikan perintah $npm run test.
- Pada jest juga dapat menggunakan flag 
- coverage untuk informasi tentang code coverage, 
   branch coverage, function coverage, dan line coverage dengan dengan menambahkan 
   package.json
   
# PERTANYAAN

Pada penamaan file tambah.test.js apakah default nama test atau bisa ditentukan dan juga apa nama function dapat diubah?

Jawab : untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus mengacu pada file package.json yang dimana disana ada sintak test dan kemudian pada penamaan code function dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.

# BAB 9
# TEST PLAN

Dokumen test plan : Test plan adalah dokumen yang mendefinisikan scope dan aktifitas yang dilakukan saat pengujian software atau sistem.

OVERVIEW

1. Test plan identifier : Test plan identifier merupakan pengenal dari dokumen test plan yang dapat berupa kode unik maupun informasi penyusun dan tanggal disusunnya dokumen, tanggal revisi dan lain-lain
2. References : Pada bagian ini dicantumkan referensi dokumen penunjang untuk penyusunan test plan
3. Introduction : berisi tentang daftar item yang akan diteskan. Contoh : Batasan dari pengujian ini menyangkup Aplikasi Web SEO v.1.0 khususnya pada modul HRD.
4. Test item
5. Software risk issues : Mencakup kemungkinan terjadinya hal-hal yang tidak pasti dan memiliki potensi kerugian. Contoh : atas waktu yang sedikit, sumber daya tidak mencukupi,
6. Features to be tested : pada bagian ini mencakup fitur-fitur dan fungsi yang akan diuji. Contoh : fitur-fitur yang diujikan antara lain:
- fitur tambah pegawai
- fitur edit pegawai
- fitur hapus pegawai
7. Features not to be tested : bagian ini berisi mengenai lingkup fitur maupun fungsi yang tidak diujikan. Contoh : Fitur-fitur   yang   tidak   diuji   adalah   semua   fitur   yang   terdapat   pada   modul  Event, Keuangan, dan Marketing
8. Approarch : approach adalah bagian yang digunakan untuk memberi deskirpsi mengenai cara/approach yang dilakukan untuk melaksanakan testing dan disertakan dengan penjelasan. Contoh : unit testing menggunakan black box testing dan white box testing beserta dengan penjelasan
9. Item pass/fail criteria : bagian berkaitan dengan menentukan kapan item telah lulus atau gagal. Contoh : kriteria lolos untuk tiap fase harus terpenuhi sebelum pengujian beranjak menuju fase selanjutnya, dimana persetujuan akan dilakukan oleh project manager seo.
10. Suspension criteria and resumption requirements : menentukan kriteria yang akan digunakan untuk dimulainya kembali semua atau sebagian kegiatan pengujian. Contoh : Pengujian akan dihentikan jika terjadi masalah pada  localhost, dan akan dilanjutkan kembali secepatnya setelah masalah diatasi

# PERTANYAAN

Jelaskan secara singkat manfaat dan tujuan dari test plan?

Jawab : test plan dibuat dengan tujuan agar testing dilakukan secara terarah baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. Dokumen ini juga merupakan bentuk kesepakatan antara developer dengan pihak penguji

Berikan contoh dari glossary!

Jawab : dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI. Beberapa kemungkinan orang yang non-TI tidak memahami beberapa kalimat yang ada didalam dokumen. contoh: requirement, software, hardware.

