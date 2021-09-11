BAB 9 - TEST PLAN

dokumen test plan : dokumen yg mendefinisikan scope dan aktifitas yg dilakukan 
saat pengujian software.

test plan identifier : pengenal dari dokumen test plan yg berupa kode unik
maupun informasi penyusun dan tanggal disusunnya dokumen, tanggal revisi, dll
introduction : penjelasan secara narasi mengenai testing yang akan dilakukan
terhadap objek testing. dibuat lebih rinci dengan menambahkan sub bab (tujuan, 
ruanglingkup, sasaran,dll)

reference : referensi dokumen peninjau untuk menyusun test plan

test item : daftar item yg akan di test kan. satu atau lebih modul proyek yg ada
software risk issue : kemungkinan terjadinya hal hal tidak pasti

features to be test: fitur yg akan diuji. memuat rincian fitur.
features not to be test : lingkup fitur yang tidak diujikan, dapat ditambahkan
alasan mengapa tidak diujikan.

approach : bagian untuk memberi deskripsi mengenai cara yang dilakukan untuk melaksanakan testing
dan disertai alasan mengenai approach digunakan.
item pass/fail criteria : menentukan kapan item telah lulus atau gagal. menggambarkan
proses dan standar keseluruhan untuk mengevaluasi hasil.

suspension criteria and resumption requirement : menentukan kriteria yang akan digunakan.
test deliverables : dokumen yang sudah hasil pengujiannya
remaining test task : tahapan yang harus dilakukan saat sebuah software mengalami cacat
enviromental needs : persyaratan untuk lingkungan pengujian. mengidentifikasi 
peralatan pengujian.

staffing dan training needs: staafing mendeskripsikan pembagian tugas masing anggota tim
training dimaksudkan anggota yg bertugas melakukan training untuk meningkatkan 
kualitas bekerjanya

responsibilities : tugas dan penanggung jawab selama proses pengujian.

schedule : untuk mengatur rentang waktu setiap bagian tugas.

planning risk and contingencies : memeriksa/mengontrol resiko dari beberapa bagian yang tidak masuk dalam
control.

approvals : mencatat sejarah revisi selama proses pengujian software. data berupa tanggal, penyusun versi,bagian yg direvisi

glossary : daftar kata atau istilah yang jarang ditemukan.

pertanyaan 1 : ringkasan test plan. 
jawab : untuk mempermudah proses testing.

pertanyaan 2 : contoh dari kata yang asing dan jarang ditemukan.
jawab : kata serapan dari bahasa asing.

ada yg menguji pakai manual, ada yg pakai augmented testing. biasanya kalau di dunia kerja, 
menggunakan pengujian manual untuk mengetahui harga, entah pendekatannya 
bagaimana, yang nanti sehingga menemukan harga yang cocok untuk test.

pertanyaan 3 : apakah hanya ada beberapa features yang akan di test.
jawab : nanti di dunia kerja, features berdasarkan kontrak kerja sesuai apa yang diinginkan
klien.



BAB 2 - KLASIFIKASI PENGUJIAN PERANGKAT LUNAK

pengujian fungsional : pengujian yang melakukan validasi hasil implementasi software, 
tujuan : menguji masing masing fitur pada software.
black box testing : tidak memperhatikan kode program
white box testing : memeriksa kebenaran hasil dari fungsi yang ada dalam kode program.


pengujian non fungsional : pengujian yang memeriksa aspek aspek non-fungsional
 dari sistem yang dibuat.
tujuan : meningkatkan usability, efisiensi, maintainability, dan portability
dari software yang dihasilkan.

11 indikator pengujian perangkat lunak : 
- keamanan
- realibilitas
- survivability
- availability
- usability
- scalability
- interoperability
- efficiency
- flexibility
- portability
- reusability

- pertanyaan 1: persamaan pengujian fungsional dan non fungsional
jawab : Sama sama diuji dan pengujian dapat menggunakan Manual Testing dan Automated Testing

- pertanyaan 2 : kekurangan dari pengujian fungsional dan non fungsional.
jawab : Mahal dibiaya pengujian. harus membayar engineer 
dalam melakukan pengujian perangkat lunak tsb.

BAB 4 : UNIT TESTING DENGAN JEST

1. installasi node.js 
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
  isian defaultnya adalah index.js
- Test command : script yang digunakan untuk menjalankan pengujian. 
- Git repository : berisi alamat repository pengisian alamat
- Keywords : berisi kata kunci yang berkaitan dengan proyek disini juga bersifat opsional kita dapat mengisinya atau tidak.
- Author : pemilik dari proyek, yang dapat diisi dengan nama kita.
- license:  Jenis lisensi default yang diberikan NodeJS adalah ISC.
- Jika semua isian telah dilengkapi, maka kita akan diminta untuk konfirmasi,
tekan enter untuk mengkonfirmasi.


3. installasi jest
- membuka folder  lalu mengetik cmd pada address bar, 
- pada cmd ketikkan npm install --save-dev jest lalu tekan enter
- Tunggu sampai instalasi selesai.
- pada file package.json terdapat informasi mengenai dependency baru yang berisikan jest. 
Dependency tersebut disimpan dengan nama “devDependencies” yang menandakan package dalam daftar tersebut 
merupakan package dependency yang hanya digunakan pada proses pengembangan.
 - Pada folder, terdapat folder baru dengan nama folder node_modules yang berisi file instalasi jest.


4. Membuat Unit Test Sederhana
- Buka Visual Studio Kemudian buat file dengan nama tambah.js pada direktori folder
- Ketik kode sederhana pada file tambah.js 
- Lalu membuat file dengan nama “tambah.test.js” 
- rubah kode pada package.json dengan menuliskan jest pada “test”, 
kemudian ketikan perintah $npm run test.
- Pada jest juga dapat menggunakan flag –coverage untuk informasi tentang code coverage, 
branch coverage, function coverage, dan line coverage dengan dengan menambahkan package.json


pertanyaan 1 : pada penamaan file tambah.test.js apakah default nama test atau 
bisa ditentukan dan juga apa nama function dapat diubah?

jawab : untuk penamaan file tambah.test.js dapat diubah, akan tetapi pada .test harus mengacu 
pada file package.json yang mana disana ada sintak test. kemudian pada penamaan kode function 
dapat diubah asalkan pada kode berkutnya harus mengikuti nama function nya.
