

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
</html>

**1. Pendahuluan**

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Website adalah sebuah aplikasi yang ditunjukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien menjadi tidak valid. Serta data stok obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat mempermudah petugas di tempat praktek Dr. Jamil dalam pendataan pasien. 

**1.1 Tujuan**

Tujuan pembuatan SRS (Software Requirement Specifications) adalah untuk deskripsikan kebutuhan pada perangkat lunak yang dibuat, yaitu "Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil".

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
| IEEE | 

tabel 2. Daftar Istilah
	
| Kata Kunci  | Definisi atau Akronim |
|--|--|
| 	 Android	| sistem operasi berbasis Linux / Windows yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet |
| 	 Web		|suatu ruang informasi yang dipakai oleh pengenal global yang disebut Pengidentifikasi Sumber Seragam untuk mengenal pasti sumber daya berguna |
	

**1.4 Referensi**

 1. IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 
 2. Teamleader, Joan. Adams, Paul. Baker, Bobbie. Charlie, Charles. 15 April 2004. Web Publishing System
 "SRSExample-webapp.pdf".

**1.5 Deskripsi Umum Dokumen (Ikhtisar)**
 
sistem informasi pada pasien Dokter Jamil adalah

**2. Gambaran Umum**
**2.1 Perspektif Produk**

| No | User |	Fungsi  |
| -- | -- | -- |
| 1 | Admi n| Login, menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan, dan menampilkan laporan pendaftaran pasien tiap bulan berupa grafik|
|2|Dokter|view data pasien, dan input resep obat. Pada Menu ini terdapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan Pasien bisa dilihat pada Dokter. agar lebih efisien disini Dokter bisa klik tombol search untuk mencari data pasien.|
|3|Apotek|input stok obat, lihat dan cetak data pasien yang sudah berobat|

**2.1.1 Antarmuka Sistem**
![enter image description here](https://lh3.googleusercontent.com/-4f9m-y1iEdI/Ws20d9qoLyI/AAAAAAAAAMk/HMN9HUevz28_Ny0l8Nmt553IQI6RfGLFACJoC/w530-h410-n/antarmuka+sistem.jpeg)

**2.1.2 Atarmuka Pengguna**
**2.1.3 Antarmuka Perangkat Keras**

Admin :menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan.

Dokter : view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.

Apoteker :input stok obat, view dan cetak data pasien yang sudah berobat.

![enter image description here](https://lh3.googleusercontent.com/-RtCAMqcDuq0/WtH0yUs-zJI/AAAAAAAAAO0/RAc2UTDr_U8pbZWcr8h0zVk70_UG2vVzACL0BGAs/w530-d-h168-n-rw/antarmuka%2Bperangkat%2Bkeras%2B%25281%2529.jpg)

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada antarmuka perangkat lain yang dibutuhkan dalam pengembangan Aplikasi Sistem Informasi Pasien pada Study Kasus Dr. Jamil.

**2.1.5 Antarmuka Komunikasi**

Ada antarmuka komunikasi yang dibutuhkan dalam aplikasi ini yaitu antarmuka untuk melakukan koneksi dalam jaringan internet yaitu:

1.  Antarmuka komunikasi pada sisi Server

Sebuah aplikasi web berkomunikasi dengan perangkat lunak _client_ melalui HTTP. HTTP, sebagai protokol yang berbicara menggunakan _request_ dan _response_ menjadikan aplikasi web bergantung kepada siklus ini untuk menghasilkan dokumen yang ingin diakses oleh pengguna. Secara umum, aplikasi web yang akan kita kembangkan harus memiliki satu cara untuk membaca HTTP Request dan mengembalikan HTTP Response ke pengguna.

**2.1.6 Batasan Memori**

Penggunaan Ruang penyimpanan pada aplikasi ini (berbasis Android) yaitu tidak kurang dari 100 Mb.

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
![enter image description here](https://lh3.googleusercontent.com/-14ARNace9NU/WrQ6zwjNyXI/AAAAAAAAAIA/AHvQLduu7BQRP5o6S1JaKQXmCfIf2DhCQCL0BGAs/w530-d-h410-n-rw/use%2Bcase%2Bfungsit.jpg)

| No | User |Fungsi  |
|--|--|--|
| 1 | Admin | menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan.|
| 2 | Dokter |view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.|
| 3 | Apotek |input stok obat, view dan cetak data pasien yang sudah berobat.|

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
||2\.Lihat resep|menampilkan data resep pasien yang di telah input oleh dokter.||3\.Lihat data pasien|menampilkan data pasien yang telah di input oleh Admin.|

**2.5 Batasan-batasan**

Keterbatasan waktu yang singkat memungkinkan fungsi fungsi yang ada di web belum bisa berfungsi sesuai dengan fungsinya.
**2.6 Asumsi-asumsi keterkaitan**


**3. Persyaratan Kebutuhan**

**3.1 Persyaratan Antarmuka Eksternal**

Salah satu syarat untuk mengakses aplikasi ini yaitu harus mendapatkan hak akses terlebih dahulu yang diberikan oleh bagian admin. kemudian melakukan login yang diwajibkan untuk mengisi username dan password yang sesuai. Setelah login berhasil, dokter dapat melihat data pasien, stok obat, dan menginput resep pasien. Dan untuk apotek dapat menginput data stok obat dan mencetak resep obat.

**3.2 Persyaratan Fungsional**

Logika Struktur terdapat pada bagian 3.3.1

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

% Please add the following required packages to your document preamble:
% \usepackage[normalem]{ulem}
% \useunder{\uline}{\ul}{}
\begin{table}[]
\centering
\caption{My caption}
\label{my-label}
\begin{tabular}{ll}
Nama Fungsi         & Dashboard Admin                                                                                                                                            \\
**Ref**             & laporan data pasien perbulan dalam bentuk grafik.                                                                                                          \\
**Triger**          & menginput data pasien maka akan menampilkan laporan berupa grafik.                                                                                         \\
**Precondition**    & halaman login                                                                                                                                              \\
**Basic Path**      & 1\. Admin menginput data pasien.                                                                                                                           \\
                    & 2\.Sistem mengirim data terebut ke dalam sistem user dokternya, sehingga ketika dokter membuka menu daftar pasien, maka data sudah muncul secara otomatis. \\
                    & 3\. Dokter menginputkan resep obat, yang kemudian terhubung langsung ke bagian apoteker.                                                                   \\
**Alternative**     & Tidak ada.                                                                                                                                                 \\
**Postcondition**   & user apotek bisa melihat data obat yang sudah diinputkan.                                                                                                  \\
**Exception Paths** & bisa dilihat kapan saja,dikhususkan untuk pelaporan data jumlah pasien perbulannya.                                                                       
\end{tabular}
\end{table}

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

Struktur logis data (ERD) yang akan disimpan dalam database Article Manager internal diberikan di bawah ini:

![enter image description here](https://lh3.googleusercontent.com/-b-psNrrlOk8/WqonLX7W3GI/AAAAAAAAA3Y/6n_qs5JVVm8efgapTqOS5IVgKpEIlZKuACL0BGAs/w530-d-h418-n-rw/ERD%2BFIX%2BBISMILLAH.jpg)

| Data item | Type | Description | Comment |
|--|--|--|--|
| nama | text | nama obat | menampilkan nama |
|ID|Integer|harga obat|ID harus Primary key|
|speciality|Text|mempunyai keahlian dalam bidangnya masing-masing|-|


