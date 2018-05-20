

<!DOCTYPE html>
<html>
<head>
</head>
<body><center>
	<h1 align="center">Software Requirements Specification</h1>
	<h2 align="center">Version 1.5<br>
	15 April 2018</h2><br><br>
	<p align="center"> <img src="https://lh3.googleusercontent.com/Mk2_cB7YlTjA6BhAtenwi-6nfONxdU_Mnew1OaieHO2UTlc0SDEL8wFkT94CIst1T-uykihG561B=s200"></p>
	<br>
	<h2 align="center">Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil</h2>
	<align="center" br>
	<div align="center">
	<h4>Nama Anggota TIM</h4><br>
	LIA NUR FADILAH (1603104)<br>
	JENIA ADELLIA P.(1603102)<br>
	LUVI HAERUNISAH	(1603105)<br>
	MAULANA AHMAD Q.(1603106)<br>
	</div>
	<br>
	<h2 align="center">JURUSAN D3 TEKNIK INFORMATIKA<br>
		POLITEKNIK NEGERI INDRAMAYU<br>
		2018</h2>
</center>
</body>
</html>
	
**1. Pendahuluan**

Aplikasi Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil Berbasis Website adalah sebuah aplikasi yang ditunjukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien menjadi tidak valid. Serta data stok obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat mempermudah petugas pada rekam medis Dr. Jamil.
	
**1.1 Tujuan**

Tujuan pembuatan SRS (Software Requirement Specifications) adalah untuk pendeskripsian kebutuhan pada perangkat lunak yang dibuat yaitu Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil.

**1.2 Lingkup**

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android ini adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat.

**1.3 Definisi, Istilah dan Singkatan**

Tabel 1. Daftar Definisi dan Akronim
	
|Kata Kunci | Definisi atau Akronim  |
|--|--|
| SRS | Software Requirement Specification. |
| SKPL| Spesifikasi Kebutuhan Perangkat Lunak, Merupakan Dokumen hasil analis yang berisi spesifikasi kebutuhan user. |
| RPL | Rekayasa Perangkat Lunak, Kegiatan pengembangan perangkat lunak. |
| Valid | perbuatan / tindakan ataupun sesuatu yang dilakukan secara sahih atau sesuai dengan aturan yang semestinya. |
| IEEE | Institute of Electrical and Electronics Engineers | 

tabel 2. Daftar Istilah
	
| Kata Kunci  | Definisi atau Akronim |
|--|--|
| 	 Web		|suatu ruang informasi yang dipakai oleh pengenal global yang disebut Pengidentifikasi Sumber Seragam untuk mengenal pasti sumber daya berguna.|
|	Rekam Medis	|informasi yang diperoleh dokter dengan cara menanyakan pertanyaan tertentu, dan pasien dapat memberikan jawaban yang sesuai.|
	

**1.4 Referensi**

 1. IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 
 2. Teamleader, Joan. Adams, Paul. Baker, Bobbie. Charlie, Charles. 15 April 2004. Web Publishing System
 "SRSExample-webapp.pdf".

**1.5 Deskripsi Umum Dokumen (Ikhtisar)**
 
Pada bab selanjutnya yaitu menjelaskan Menjelaskan gambaran umum aplikasi,interface pada tiap bagian dan alur. pada bab terakhir menjelaskan tentang fungsi-fungsi yang di implentasi.

**2. Gambaran Umum**

Rancang Bangun Aplikasi Pasien pada Study kasus Dr. Jamil merupakan kegiatan menerjemahkan hasil analisa kedalam bentuk paket perangkat lunak atau software kemudian menciptakan sistem tersebut ataupun memperbaiki sistem yang sudah ada. permasalahan yang ada pada Dr.Jamil ini yaitu pengelolaan data pasien yang kurang efektif dan efisien. tujuan dibuatnya aplikasi ini yaitu supaya pengelolaan data pasien dapat berjalan dengan cepat dan tepat. Metode pengembangan sistem ini menggunakan SDLC dengan membuat diagram-diagram UML seperi use case diagram, class diagram, activity diagram, entity relationship diagram sebagai tahapan perancangan sistem. Aplikasi ini dibuat dengan berbasis WEB menggunakan bahasa pemrograman PHP yang didukung basis data MySQL. Hasil rancang bangun sistem ini diharapkan dapat menjadi salah satu solusi dari permasalahan yang terjadi selama ini. 

Dengan demikian kelompok kami mempunyai gagasan dan ide yang dpat meminimalisir dari ketidakefisienan dan ketidakefektifan pada sistem yang ada di Dr. Jamil. pada sistem ini ada 3 user, yaitu diantaranya :

Dari sistem admin yaitu mempunyai fungsi untuk menginputkan data pasien yang regiter, dan melaporkan hasil laporan jumlah pasien perbulannya, 
Sedangkan untuk sistem dokter yaitu mampu melihat data pasien dan kemudian menginput resep obat yang sesuai dengan keluhan data pasien, selain itu dokter juga mampu memonitoring jumlah stok obat yang ada diapotek.
kemudian untuk sistem apotek yaitu mampu menginputkan data stok obat, selain itu juga bagian apotek mampu melihat resep obat yang sudah diinput oleh dokter, yang kemudian melakukan proses pencetakan pada resep obat.

**2.1 Perspektif Produk**

| No | User |	Fungsi  |
| -- | -- | -- |
| 1 | Admin| Login, menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan, dan menampilkan laporan pendaftaran pasien tiap bulan berupa grafik|
|2|Dokter|view data pasien, dan input resep obat. Pada Menu ini terdapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan Pasien bisa dilihat pada Dokter. agar lebih efisien disini Dokter bisa klik tombol search untuk mencari data pasien.|
|3|Apotek|input stok obat, lihat dan cetak data pasien yang sudah berobat|

**2.1.1 Antarmuka Sistem**

![enter image description here](https://lh3.googleusercontent.com/-4f9m-y1iEdI/Ws20d9qoLyI/AAAAAAAAAMk/HMN9HUevz28_Ny0l8Nmt553IQI6RfGLFACJoC/w530-h410-n/antarmuka+sistem.jpeg)

**2.1.2 Atarmuka Pengguna**

|||
|--|--|
|![enter image description here](https://lh3.googleusercontent.com/-4ig80hC8VYs/WtNYNnU28II/AAAAAAAABFc/F8YepuGwta88hXiSU3rX2DQiRTKlBa_AwCL0BGAs/w795-d-h462-n/create+new+account.png)
halaman daftar akun, akses sebagai dokter atau apoteker.|![enter image description here](https://lh3.googleusercontent.com/-TjaLOIEm8Hs/WtNX_L9hYfI/AAAAAAAABFI/qVoyeNcovWsR40ckIRnwaP77o496VCPFQCL0BGAs/w795-d-h549-n/login.png)halaman login setelah mendaftar akun.|
| ![enter image description here](https://lh3.googleusercontent.com/-pyzuZnY6WTo/WtNYtp62BrI/AAAAAAAABGE/srYNT-o_iOssMwEsJnkUYxKO6PZ-a34OgCL0BGAs/w795-d-h446-n/admin.png) halaman dashboard admin, dimana ada menu data pasien dan laporan. pada data pasien menampilkan tabel yang  berupa inputan untuk pasien yang register, dan pada laporan, akan menampilkan grafik jumlah pasien tiap bulannya.| ![enter image description here](https://lh3.googleusercontent.com/-stI1u4C_5OI/WtNZDg6CVAI/AAAAAAAABGg/RdjJHDj9GW0dWNSwX6WMM961BxQ5vor2QCL0BGAs/w795-d-h549-n/dashboard.png) |
| ![enter image description here](https://lh3.googleusercontent.com/-vXg_0sDhZQ0/WtNZbUxHLaI/AAAAAAAABHA/fd2D-z1l7lQWgoZiKk7ItrubneIDIGV5gCL0BGAs/w795-d-h438-n/dokter.png)halaman dokter, dimana ada dua menu yaitu data pasien dan data stok obat. pada data pasien, dokter bisa melihat data pasien, dan menginputkan resep pasien. dan pada menu stok obat, dokter bisa melihat dan memonitoring stok obat ada diapotek.|  ![enter image description here](https://lh3.googleusercontent.com/-hqu2LhBM7KE/WtNZt516-kI/AAAAAAAABHc/a8tz1Tkk7tYu1phPFt9405FSmGkf8B2QgCL0BGAs/w795-d-h572-n/resep.png)halaman inputan resep obat untuk dokter.|
|![enter image description here](https://lh3.googleusercontent.com/-4myjz4P8Geg/WtNfjjd5ZBI/AAAAAAAABKk/dqzcWHLkmnIQgFoAe_27AMVl3nNrB4nhACL0BGAs/w795-d-h446-n/Apotek.png)halaman apotek ada dropdown berupa menu resep obat dan stok obat. pada resep obat, bagian apoteker akan mencetak resep yang sudah diinputkan dokter. pada menu stok obat apoteker menginputkan stok obat.|![enter image description here](https://lh3.googleusercontent.com/-X2dnNGpUSYQ/WtNaaC8G-_I/AAAAAAAABIY/IJFF1HiP-koV4i1OwclImfwXJJfly-8lACL0BGAs/w795-d-h572-n/New+Mockup+7.png)halaman resep obat yang akan dicetak pada apoteker.|

**2.1.3 Antarmuka Perangkat Keras**

![enter image description here](https://lh3.googleusercontent.com/-RtCAMqcDuq0/WtH0yUs-zJI/AAAAAAAAAPE/yHgn2IChBHcCcxhqYtt5IxLb_BuD171SgCJoC/w530-h168-n/antarmuka%2Bperangkat%2Bkeras%2B%25281%2529.jpg)

**2.1.4 Antarmuka Perangkat Lunak**

Aplikasi Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil digunakan pada semua browser (all support).

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang dibutuhkan dalam aplikasi ini yaitu antarmuka untuk melakukan koneksi dalam jaringan internet yaitu:

1.  Antarmuka komunikasi pada sisi Server

Sebuah aplikasi web berkomunikasi dengan perangkat lunak _client_ melalui HTTP. HTTP, sebagai protokol yang berbicara menggunakan _request_ dan _response_ menjadikan aplikasi web bergantung kepada siklus ini untuk menghasilkan dokumen yang ingin diakses oleh pengguna. Secara umum, aplikasi web yang akan kita kembangkan harus memiliki satu cara untuk membaca HTTP Request dan mengembalikan HTTP Response ke pengguna.

**2.1.6 Batasan Memori**

Pada memori yang di butuhkan tidak ada karena Aplikasi ini berbasis website.

**2.1.7 Operasi-operasi**
	
|No| Operasi |Fungsi|
|--|--|--|
| 1 | Login |Untuk masuk sebagai user dan dapat mengakses aplikasi|
|  2| Input Data |Untuk Memasukkan data-data yang terkait|
| 3 | Delete Data |Untuk menghapus data|
| 4 | Edit Data |Untuk mengubah data|
| 5 | Save Data |Untuk menyimpan data|
| 6 | View Data |Untuk menampilkan data|
| 7 |Back |Untuk kembali kehalaman sebelumnya|
| 8 | Print |Untuk mencetak sebuah data atau laporan|

**2.2 Spesifikasi Kebutuhan fungsional**

![use case all](https://lh3.googleusercontent.com/-zCFPWKrvUbc/WwERNQz1MgI/AAAAAAAAAUA/IOGQ5NjAKjcoIo15RfhY0fWDzoE3ARu5QCL0BGAs/w530-d-h461-n-rw/use%2Bcase.jpg)

**2.2.1 use case Register**

![register](https://lh3.googleusercontent.com/-Q8IB18qfKbo/WwEXIHrQcgI/AAAAAAAAAUk/sO66cfaZly4-M5hGhUR9S8LWLNCWUXLpgCL0BGAs/w530-d-h252-n-rw/use%2Bcase%2B%25281%2529.jpg)

1. User memasukan data diri untuk register akun.
2. Sistem mevalidasi data yang di inputkan.

**2.2.1 use case Login**

![login](https://lh3.googleusercontent.com/-vNrC8QMfD5g/WwEXaNbizuI/AAAAAAAAAVA/jX6Z4B8RabwodOFFsvv_pan2MwbrsZg6ACL0BGAs/w530-d-h224-n-rw/use%2Bcase%2B%25281%2529.jpg)

1. Masukan username dan password.
2. Sistem meverifikasi kesalahan data yang di masukan.
3. jika berhasil login maka akan sesuai dengan tipe nya yaitu; Admin, Dokter, atau Apoteker (berdasarkan username dan password).

**2.2.2 use case Verivikasi password**

![login](https://lh3.googleusercontent.com/-vNrC8QMfD5g/WwEXaNbizuI/AAAAAAAAAVA/jX6Z4B8RabwodOFFsvv_pan2MwbrsZg6ACL0BGAs/w530-d-h224-n-rw/use%2Bcase%2B%25281%2529.jpg)

1. User memasukan username dan password dengan benar.
2. Sistem memverifikasi data yang di masukan.
3. Jika username benar dan password salah maka gagal.
4. Jika username salah dan password benar maka gagal.

**2.2.3 use case Display Login Error**

![login](https://lh3.googleusercontent.com/-vNrC8QMfD5g/WwEXaNbizuI/AAAAAAAAAVA/jX6Z4B8RabwodOFFsvv_pan2MwbrsZg6ACL0BGAs/w530-d-h224-n-rw/use%2Bcase%2B%25281%2529.jpg)

1. Jika username benar dan password salah maka gagal. maka sistem akan memunculkan kesalahan data login tidak berhasil.
2. Jika username benar dan password salah maka gagal. maka sistem akan memunculkan kesalahan data login tidak berhasil.

**2.2.4 use case Input Data Pasien**

![input data pasien](https://lh3.googleusercontent.com/-TbF_6TQ5mUw/WwEYCs2Q_0I/AAAAAAAAAVg/1Rg_lvfQkA8XwZtNmnKc4wjux_zuHVDaACL0BGAs/w530-d-h79-n-rw/use%2Bcase%2B%25282%2529.jpg)

1. user menginputkan data pasien 
input data pasien dengan cara:
1. Masukan Data NIK Pasien.
2. Masukan Nama Pasien.
3. Masukan Alamat Pasien.
4. Masukan Keluhan Pasien.
5. Masukan Umur Pasien.
6. Masukan No.telp Pasien.

2. sistem menampilkan data pasien.


**2.2.5 use case Laporan berupa Grafik Jumlah Pasien**

![grafik data pasien](https://lh3.googleusercontent.com/-TbF_6TQ5mUw/WwEYCs2Q_0I/AAAAAAAAAVg/1Rg_lvfQkA8XwZtNmnKc4wjux_zuHVDaACL0BGAs/w530-d-h79-n-rw/use%2Bcase%2B%25282%2529.jpg)

Admin dapat melihat laporan berupa grafik yaitu jumlah pasien perbulan melalui:

1. Halaman Laporan berada pada Dashboard Admin.
2. Apabila Admin input data pasien (perbulan dengan jumlah banyak) maka Sistem akan menampilkan grafik laporan.

**2.2.6 use case Lihat Data Pasien**

![lihat data pasien](https://lh3.googleusercontent.com/-bZyZHFXMjOg/WwEYtyrqxHI/AAAAAAAAAWE/txuQydYD7qMKrPargafEE6MM7HRWyNMPQCL0BGAs/w530-d-h161-n-rw/use%2Bcase%2B%25283%2529.jpg)

1. user dapat melihat data pasien

- Data Pasien bisa dilihat dengan data pasien yang berhasil di inputkan
- Data Pasien bisa di cari dengan NIK.

2. Sistem menampilkan data pasien 

**2.2.7 use case Input Resep Obat**

![input resep obat](https://lh3.googleusercontent.com/-DkFn45NQjy4/WwEaGp6v-JI/AAAAAAAAAXk/OY8MzlZakHkJ5oZlfhNbP_b39nIOvmnIgCL0BGAs/w530-d-h137-n-rw/use%2Bcase%2B%25284%2529.jpg)

1. User menginputkan resep obat
2. Sistem menampilkan resep obat


**2.2.8 use case Lihat Stok Obat**

![view stok obat](https://lh3.googleusercontent.com/-3FcEPOpnWf4/WwEcdXrtNYI/AAAAAAAAAZQ/bO23fpmQ0ScahFHMHi6Tg6ziceW318ChQCL0BGAs/w530-d-h79-n-rw/use%2Bcase%2B%25285%2529.jpg)

User dapat Lihat stok obat dengan cara:

1. lihat stok obat (sesuai dengan nama obat yang telah di input oleh Apoteker).

**2.2.9 use case Lihat Resep Obat**

![input resep obat](https://lh3.googleusercontent.com/-DkFn45NQjy4/WwEaGp6v-JI/AAAAAAAAAXk/OY8MzlZakHkJ5oZlfhNbP_b39nIOvmnIgCL0BGAs/w530-d-h137-n-rw/use%2Bcase%2B%25284%2529.jpg)

User dapat Lihat resep obat dengan cara:

1.lihat resep obat (sesuai dengan nama pasien yang telah di input oleh Dokter)


**2.2.10 use case Input Stok Obat**


![view stok obat](https://lh3.googleusercontent.com/-3FcEPOpnWf4/WwEcdXrtNYI/AAAAAAAAAZQ/bO23fpmQ0ScahFHMHi6Tg6ziceW318ChQCL0BGAs/w530-d-h79-n-rw/use%2Bcase%2B%25285%2529.jpg)

User dapat input resep obat dengan cara:

1. Masukan Stok Obat:
- nama obat
- harga obat
- jumlah obat

2. Sistem akan menampilkan data stok obat.

**2.3 Spesifikasi Kebutuhan non-fungsional**

Usability
kebutuhan yang digunakan dalam usability sebagai menjadi user-friendly. contoh nya penggunaan boostrap pada aplikasi agar kelihatan rapih dan lebih menarik.  

Security
Kebutuhan yang digunakan dalam security yaitu harus registrasi pada sistem terlebih dahulu (user;Apoteker, dan Dokter). dan kebutuhan lainnya yaitu proses verifikasi akun berupa pengguna captcha.

Reability
Kebutuhan yang digunakan dalam Reability yaitu proses pada pencetakan resep obat.

**2.4 karakteristik pengguna**

| Tipe Pengguna | Operasi | Keterangan |
| -- | -- | --|
| Admin | 1\. Laporan Pasien(grafik)| menampilkan jumlah pasien perbulan dalam bentuk tabel grafik |
||2\. Input data pasien. |memasukan data pasien pada sistem.
Dokter|1\.Input resep|memasukan resep pasien pada sistem.|
||2\.Lihat stok obat| menampilkan nama obat, jumlah obat ,harga obat dan status.
||3\.Lihat data pasien |menampilkan data pasien yang masuk.
|Apoteker|1\.Input Stok obat|memasukan data obat pada sistem.
||2\.Lihat resep|menampilkan data resep pasien yang di telah input oleh dokter.
||3\.Lihat data pasien|menampilkan data pasien yang telah di input oleh Admin.|
**2.5 Batasan-batasan**

Keterbatasan waktu yang singkat memungkinkan implementasi fungsi-fungsi yang ada di rencanakan belum bisa berfungsi dengan sesuai.

**3. Persyaratan Kebutuhan**

**3.1 Persyaratan Antarmuka Eksternal**

Salah satu syarat untuk mengakses aplikasi ini yaitu harus mendapatkan hak akses terlebih dahulu yang diberikan oleh bagian admin. kemudian melakukan login yang diwajibkan untuk mengisi username dan password yang sesuai. Setelah login berhasil, dokter dapat melihat data pasien, stok obat, dan menginput resep pasien. Dan untuk apotek dapat menginput data stok obat dan mencetak resep obat.

**3.2 Persyaratan Fungsional**

Logika Struktur Data terdapat pada bagian 3.3.1

**3.2.1 Registrasi Dokter**

| Nama Fungsi | Registrasi Dokter |
|--|--|
| **Ref** | Registrasi Dokter |
| **Trigger** | user login,insert resep. |
| **Pre condition**  |halaman dashboard , dan halaman insert resep, dan kolom view stok obat.|
| **Basic Path** | 1. user memilih kolom registrasi pada dashboard.
|| 2. user mengisi kolom registrasi. 
|| 3. user mengirim data registrasi.
|| 4. user mempunyai akses untuk login. 
| **Alternative Path** |tidak ada.
| **Post condition** |User dapat Registrasi dan dapat mengakses untuk login.
| **Exception push** | Tidak ada Koneksi 

**3.2.2 Registrasi Apoteker**

| Nama Fungsi | Registrasi Apoteker |
|--|--|
| **Ref** | Registrasi Apoteker 
| **Trigger** | user login,insert stok obat, obat.|
| **Pre condition**  |halaman dashboard dan halaman input obat, stok obat, dan view resep.|
| **Basic Path** | 1\. user memilih kolom registrasi pada dashboard.	
|| 2\. user mengisi kolom registrasi.
|| 3\. user mengirim data registrasi.
|| 4\. user mempunyai akses untuk login.|
| **Alternative Path** |tidak ada.|
| **Post condition** |User dapat Registrasi dan dapat mengakses untuk login.|
| **Exception push** | Tidak ada Koneksi|

**3.2.3 Halaman menu Dashboard**

| Nama Fungsi | Dashboard Admin |
|--|--|
| **Ref** |laporan data pasien perbulan dalam bentuk grafik.|
| **Triger** |menginput data pasien maka akan menampilkan laporan berupa grafik.|
| **Precondition** |halaman login|
| **Basic Path** | 1\. Admin menginput data pasien.	
|| 2\.Sistem mengirim data terebut ke dalam sistem user dokternya, sehingga ketika dokter membuka menu daftar pasien, maka data sudah muncul secara otomatis.   
|| 3\. Dokter menginputkan resep obat, yang kemudian terhubung langsung ke bagian apoteker.|
| **Alternative** |Tidak ada. |
| **Postcondition** | user apotek bisa melihat data obat yang sudah diinputkan. |
| **Exception Paths** | bisa dilihat kapan saja,dikhususkan untuk pelaporan data jumlah pasien perbulannya. |

**3.2.4 tambahan**

| Nama Fungsi | Sistem |
|--|--|
| **Trigger** | Admin, melakukan proses pendataan pasien. |
| **Precondition** |admin telah mengakses layar utama. |
| **Basic Path** | 1\. Sistem menyajikan tabel kosong untuk memasukkan pendaftaran pasien. 
||2\. admin memasukkan informasi dan mengirimkan biodata pasien.
||3\. Sistem memeriksa bahwa kolom nama biodata lainnya sudah terpenuhi. |

**3.3 Persyaratan Non Fungsional**

**3.3.1 Logika Struktur Data**

Struktur logis data (ERD) yang akan disimpan dalam database Article Manager internal diberikan sebagai berikut:

![enter image description here](https://lh3.googleusercontent.com/-b-psNrrlOk8/WqonLX7W3GI/AAAAAAAAA3Y/6n_qs5JVVm8efgapTqOS5IVgKpEIlZKuACL0BGAs/w530-d-h418-n-rw/ERD%2BFIX%2BBISMILLAH.jpg)

Dokter

| Data item | Type | Description |
|--|--|--|
|Id_dokter|Integer|Primary key|
|Id_login|Integer|foreign key|
|Id_obat|Integer|golongan obat|
|nama_dokter|varchar|nama dokter|

Data Pasien

| Data item | Type | Description |
|--|--|--|
|Id_pasien|Integer|Primary Key|
|nik|Integer|nomor induk kependudukan|
|nama_pasien|varchar|nama pasien|
|umur|integer|umur|
|alamat_pasien|varchar|alamat|
|no_telp|integer|nomor telepon|
|keluhan|varchar|keluhan pasien|


Resep

| Data item | Type | Description |
|--|--|--|
|Id_resep_obat|integer| Primary key|
|nama_obat|varchar| nama obat |
|aturan_pakai|varchar|aturan minum obat|
|Id_stok_obat|integer|foreign key|

Obat

| Data item | Type | Description |
|--|--|--|
|Id_obat|integer|primary key|
|Id_stok_obat|integer|foreign key|
|Id_resep_obat|integer||

Stok Obat

| Data item | Type | Description |
|--|--|--|
|Id_stok_obat|integer|primary key|
|nama_obat|varchar|nama obat|
|harga_obat|varchar|harga obat|
|jumlah_obat|varchar|jumlah obat|

Apoteker

| Data item | Type | Description |
|--|--|--|
|Id_apoteker|integer|primary key|
|Id_login|integer|foreign key|
|Id_stok_obat|integer||
|nama_apoteker|varchar|nama apoteker|

Login

| Data item | Type | Description |
|--|--|--|
|Id_login|integer|primary key|
|username|varchar|username|
|password|varchar|password|
|type|varchar|type user|


**3.3.2 Keamanan** 

Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil akan memiliki keamanannya sendiri untuk mencegah kesalahan dalam masuk ke sistem. Tidak ada batasan akses baca. menggunakan validasi login dan keamanan eksternal tambahn untuk sistem.









