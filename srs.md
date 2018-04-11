

<!DOCTYPE html>
<html>
<head>
</head>
<body><center>
	<h1 align="center">Software Requirements Specification</h1>
	<h2 align="center">Version 1.5<br>
	05 April 2018</h2><br><br>
	<p align="center"> <img src="https://lh3.googleusercontent.com/Mk2_cB7YlTjA6BhAtenwi-6nfONxdU_Mnew1OaieHO2UTlc0SDEL8wFkT94CIst1T-uykihG561B=s200"></p>
	<br>
	<h2 align="center">Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil<br>
	(SIMPATY ADIL)</h2>
	<align="center" br>
	<ol align="center">Nama Anggota TIM</ol><align="center">
	<div align="center">
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


**1. Pendahuluan**

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Website adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien menjadi tidak valid. Serta data stook obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat mempermudah petugas di tempat praktek Dr. Jamil dalam pendataan pasien. 

**1.1 Tujuan**

Tujuan pembuatan SRS (Software Requirement Specifications) adalah untuk deskripsikan kebutuhan pada perangkat lunak yang dibuat, yaitu "Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil".

**1.2 Lingkup**

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android ini adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat.

**1.3 Definisi, Istilah dan Singkatan**

Tabel 1. Daftar Definisi dan Akronim
	
|Kata Kunci | Definisi atau Akronim  |
|--|--|
| SRS | Software Requirement Specification|
| SKPL| Spesifikasi Kebutuhan Perangkat Lunak, Merupakan Dokumen hasil analis yang berisi spesifikasi kebutuhan user				 		|
|RPL| Rekayasa Perangkat Lunak, Kegiatan pengembangan perangkat lunak|


tabel 2. Daftar Istilah
	
| Kata Kunci  | Definisi atau Akronim |
|--|--|
| 	 Android	| sistem operasi berbasis Linux / Windows yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet |
| 	 Web		|suatu ruang informasi yang dipakai oleh pengenal global yang disebut Pengidentifikasi Sumber Seragam untuk mengenal pasti sumber daya berguna |
	

**1.4 Referensi**

 1. IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 
 //belum //

**1.5 Deskripsi Umum Dokumen (Ikhtisar)**
 
sistem informasi pada pasien a

**2. Gambaran Umum**
**2.1 Lingkungan Sistem**

![Antarmuka Sistem](https://lh3.googleusercontent.com/-4f9m-y1iEdI/Ws20d9qoLyI/AAAAAAAAAMQ/qGIDjE4c5-Y-sZALmAQ-XO2fkSKsxJLVgCL0BGAs/w530-d-h410-n-rw/antarmuka%2Bsistem.jpeg)

| No | User |	Fungsi  |
|--|--|--|
| 1 |Admin| Login, menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan, dan menampilkan laporan pendaftaran pasien tiap bulan berupa grafik|
|2|Dokter|view data pasien, dan input resep obat. Pada Menu ini terdapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan Pasien bisa dilihat pada Dokter. agar lebih efisien disini Dokter bisa klik tombol search untuk mencari data pasien.|
|3|Apotek|input stok obat, lihat dan cetak data pasien yang sudah berobat|

**2.2 Spesifikasi Persyaratan Fungsional**


**2.2.1 Antarmuka Sistem**
![Antarmuka sistem](https://lh3.googleusercontent.com/-9P0BW2SUZOc/Ws3AoZOaVHI/AAAAAAAAANA/RXeQDyvSD14hmRVv3S2UdkUQ-Hw0AoYfQCL0BGAs/w530-d-h410-n-rw/use%2Bcase%2Bfungsi%2B%2Bproject.jpeg)



**2.2.2 Atarmuka Pengguna**

**~~~belommmmm~~~**

**2.1.3 Antarmuka Perangkat Keras (Hardware)**

Admin :menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan.

Dokter : view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.

Apotek :input stok obat, view dan cetak data pasien yang sudah berobat.

![enter image description here](https://lh3.googleusercontent.com/-Vm8DM0x7o0A/WpJ6cgU_uMI/AAAAAAAAARQ/FrchoGJ_Xo8kTTH0iRZfmX1OFu1-cbfYwCL0BGAs/w530-d-h275-n/usecase.png)

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada antarmuka perangkat lain yang dibutuhkan dalam pengembangan Aplikasi Sistem Informasi Pasien pada Study Kasus Dr. Jamil.

**2.1.5 Antarmuka Komunikasi**

Ada antarmuka komunikasi yang dibutuhkan dalam aplikasi ini yaitu antarmuka untuk melakukan koneksi dalam jaringan internet yaitu:

1.  Antarmuka komunikasi pada sisi Server

Sebuah aplikasi web berkomunikasi dengan perangkat lunak _client_ melalui HTTP. HTTP, sebagai protokol yang berbicara menggunakan _request_ dan _response_ menjadikan aplikasi web bergantung kepada siklus ini untuk menghasilkan dokumen yang ingin diakses oleh pengguna. Secara umum, aplikasi web yang akan kita kembangkan harus memiliki satu cara untuk membaca HTTP Request dan mengembalikan HTTP Response ke pengguna.

**2.1.6 Batasan Memori**

Penggunaan Ruang penyimpanan pada aplikasi ini (berbasis Android) yaitu tidak kurang dari 100 Mb.

	 
**2.2 Fungsi-fungsi produk**
![enter image description here](https://lh3.googleusercontent.com/-14ARNace9NU/WrQ6zwjNyXI/AAAAAAAAAIA/AHvQLduu7BQRP5o6S1JaKQXmCfIf2DhCQCL0BGAs/w530-d-h410-n-rw/use%2Bcase%2Bfungsit.jpg)

**2.2.1  Tabel Kebutuhan Fungsional**
| No | User |Fungsi  |
|--|--|--|
| 1 |Admin	  | menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan|
|2|Dokter|view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.|
|3|Apotek |input stok obat, view dan cetak data pasien yang sudah berobat|

**3. Kebutuhan lain yang spesifik**

**3.1 Kebutuhan antarmuka eksternal**

**3.1.1 Antarmuka pemakai**

Dokter dan Apotek sebagai user yang dapat mengoperasikan aplikasi sistem informasi pasien pada study kasus Dr. Jamil dengan menggunakan smartphone yang berupa android.
	
**3.1.2 Antarmuka perangkat lunak**

Aplikasi ini dapat diakses jika terhubung dengan internet dan memiliki OS android.

**3.2 Kebutuhan Fungsional**

**3.2.1 Diagram Kebutuhan Fungsional**

|Use Case Name|Dokter dan Apoteker|
|--|--|
|**Trigger**| halaman awal aplikasi|
| **Pre condition**  | Web ditampilkan hanya untuk admin yang digunakan untuk input saat pendaftaran pasien |
|**Basic Path** | 1. admin input data pasien	
||2. Sistem mengirim data pasien, dan view data pasien .
||3. Dokter input resep obat, yang kemudian terhubung langsung ke bagian apoteker.|
|**Post condition**| user dokter mampu melihat daftar pasien yang dikirim dari admin, dan apotek bisa melihat resep obat dari dokter|
|**Exception push**| user dokter dapat melakukan pencarian obat, yang sebelumnya data obat tersebut sudah duimasukkan oleh user apotek.|
|**Other**| data stok barang dapat ditampilkan dan diview oleh user dokter|

**3.2.2 komunikasi**
	
| nama Use Case Komunikasi|  Admin|
|--|--|
| **Triger** | user login  |
|**Precondition**|halaman dashboard dan halaman input data pasien berupa web|
|**Basic Path** | 1. admin menginput data pasien	
||2. kemudian sistem mengirim data terebut ke dalam sistem user dokternya, sehingga ketika dokter membuka menu daftar pasien, maka data sudah muncul secara otomatis   
||3. Dokter menginputkan resep obat, yang kemudian terhubung langsung ke bagian apoteker|
|**Alternative**|Tidak ada |
|**Postcondition**|user apotek bisa melihat data obat yang sudah diinputkan|
|**Exception Paths**| bisa dilihat kapan saja,dikhususkan untuk pelaporan data jumlah pasien perbulannya|

**3.2.3 tambahan**

|Nama Use Case|Sistem|
|--|--|
|  **Trigger**| Admin, melakukan proses pendataan pasien  |
|**Precondition**|admin telah mengakses layar utama |
|**Basic Path**| 1\. Sistem menyajikan tabel kosong untuk memasukkan pendaftaran pasien 
||2\. admin memasukkan informasi dan mengirimkan biodata pasien 
||3\. Sistem memeriksa bahwa kolom nama biodata lainnya sudah terpenuhi|

**3.3 Persyaratan Non Fungsional**

**3.3.1 Struktur tidak logis**

Struktur logis data (ERD) yang akan disimpan dalam database Article Manager internal diberikan di bawah ini:
![enter image description here](https://lh3.googleusercontent.com/-b-psNrrlOk8/WqonLX7W3GI/AAAAAAAAA3Y/6n_qs5JVVm8efgapTqOS5IVgKpEIlZKuACL0BGAs/w530-d-h418-n-rw/ERD%2BFIX%2BBISMILLAH.jpg)

|Data item|Type|Description|Comment|
|--|--|--|--|
|nama|text|nama obat|menampilkan nama|
|ID|Integer|harga obat|ID harus Primary key|
|speciality|Text|mempunyai keahlian dalam bidangnya masing-masing|

**3.3.2 Keamanan**

Server tempat untuk admin dan apotek berada akan memiliki keamanan sendiri untuk mencegah akses write / delete yang tidak sah. Tidak ada batasan akses baca. 

PC tempat admin berada akan memiliki keamanan sendiri. Hanya admin yang memiliki akses fisik ke mesin dan program di dalamnya. Tidak ada perlindungan khusus yang ada di dalam sistem ini.


</html>