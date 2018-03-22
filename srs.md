

<!DOCTYPE html>
<html>
<head>
</head>
<body><center>
	<h1 align="center">Software Requirements Specification</h1>
	<h2 align="center">Version 1.5<br>
	22 Maret 2018</h2><br><br>
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
</html>

**1. Pendahuluan**

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien menjadi tidak valid. Serta data stook obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat mempermudah petugas di tempat praktek Dr. Jamil dalam pendataan pasien. 

1.1 Tujuan 

Tujuan pembuatan SRS (Software Requirement Specifications) adalah untuk deskripsikan kebutuhan pada perangkat lunak yang dibuat, yaitu "Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil'.

1.2 Lingkup 

Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android ini adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat.

1.3 Definisi, Istilah dan Singkatan
	
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
	

1.4 Referensi

 1. IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. 
 2. https://openlibrary.telkomuniversity.ac.id/pustaka/files/97623/resume/sistem-informasi-pelayanan-pasien-pada-klinik-permata-raya-bandung.pdf 

1.5 Deskripsi Umum Dokumen (Ikhtisar)

pada Bab pertama yaitu menjelaskan tentang aplikasi atau project yang akan dibuat. Bab berikutnya, bagian Uraian Keseluruhan, dari dokumen ini memberikan gambaran umum tentang sistem yang akan dibuat dan alur dari sistemnya. dan bab yang ketiga yaitu menjelaskan gambaran umum fungsi fungsi dari setiap user diantaranya yaitu fungsi sebagai admin, dokter, dan apotek. 

**2. Gambaran Umum**

Aplikasi sistem informasi pasien dengan study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek.Aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil.

Aplikasi ini terdapat 3 user, yaitu:

1. admin    : Input data pasien.
2. Dokter	: Input data pasien dan insert resep dokter.
3. Apotek	: View data pasien,input resep obat dan input harga.

2.1 Perspektif produk (Perbandingan)

Aplikasi yang kita buat ini adalah sistem informasi pasien dengan study kasus Dr. Jamil. Untuk perbedaan antara aplikasi Sistem Informasi Pasien dengan Study Kasus Dr. Jamil yang kami buat dengan-Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan Layanan Web (https://www.researchgate.net/publication/320519219_Rancang_Bangun_Aplikasi_Rekam_Medis_untuk_Praktik_Pribadi_Dokter_Berbasis_Android_dan_Memanfaatkan_Layanan_Web).
Keunggulan dari aplikasi kami adalah terhubung dengan Apotek dan Kasir ditempat Praktek tersebut. Sedangkan Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan Layanan Web ini hanya diperuntukan untuk pasien yang berkonsultasi dengan Dokter, dan pada data Dokter, Dokter hanya bisa melihat dan menambahkan pasien tanpa bisa mengupdate data pasien.


		2.1.1 Antarmuka Sistem

| No | User |	Fungsi  |
|--|--|--|
| 1 |Admin| menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan|
|2|Dokter|view data pasien, input resep dokter, Pada Menu ini, terdapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan Pasien bisa dilihat pada Dokter. Tetapi disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari .|
|3|Apotek|input stok obat, view dan cetak data pasien yang sudah berobat|

Data Flow Diagram:

 ![enter image description here](https://lh3.googleusercontent.com/-H5XNofHT6II/WpGTJA65rJI/AAAAAAAAAiw/J2FCAQ47OJcvy5sJCQYuMCxhkDbCHb9pwCL0BGAs/w795-d-h653-n/Dfd.jpg)
PENJELASAN:
 1. ADMIN: admin ke sistem mempunyai fungsi input pasien, dan keluar yang dihasilkan berupa data laporan jumlah pasien yang berboat berupa grafik.
 2. DOKTER: mempunyai fungsi input resep obat ke sistem sesudah melihat data pasien yang masuk yang diinputkan oleh Admin. 
 3. APOTEK: Menginputkan stok obat, nama obat, jenis obat, jumlah obat, dan bisa melihat data pasien yang masuk.	
 
REFERENSI:
 http://www.academia.edu/11355568/Contoh_SKPL_SPESIFIKASI_KEBUTUHAN_PERANGKAT_LUNAK_

2.1.2 Atarmuka Pengguna

Berikut ini adalah Mockup (Rancangan Interface) dari Aplikasi yang akan dibuat, yaitu:

a. Dibawah ini adalah mockup Admin, untuk dashboard Admin menampilkan laporan berupa grafik peningkatan jumlah pasien tiap bulannya.
	
	Register Admin
![Register Admin](https://lh3.googleusercontent.com/-2VFO9kvwgXA/Wp_22e5JPyI/AAAAAAAAAMM/_3VH6SS1KB4sK2TDyc0W-c1azpBkg1JTACL0BGAs/w530-d-h398-n-rw/register.png)
	
	Log In Admin
![Log in Admin](https://lh3.googleusercontent.com/-8UAgXZK1MWM/Wp_27BObXtI/AAAAAAAAAMg/ChLGZO9VbVMckbbzLel0iOHowTfCknVmACL0BGAs/w530-d-h409-n-rw/masuk.png)
	
	Dashboard Admin
 ![Dashboard Admin](https://lh3.googleusercontent.com/-UsALNKxjXvo/WpGZNzS5sTI/AAAAAAAAAjs/7tiuojJ1go4Y3SLwcHT0hOfdOSINWUk5gCL0BGAs/w795-d-h612-n/dashboard+admin.png)

b. ini adalah menu input pada admin, yaitu fungsi utama admin menginputkan data pasien yang berobat 
			 ![enter image description here](https://lh3.googleusercontent.com/-M2NT_SUfy4w/WpGbN0Km1pI/AAAAAAAAAkc/73KuGZ4frYklKtC4BduCU2JoUNCjHvwYgCL0BGAs/w795-d-h612-n/input+data+pasien+%2528admin%2529.png)

c. Berikut ini adalah menu login pada dokter, dimana dokter bisa view data pasien yang mudah siakses dengan android, dimana pada pict user kita bisa klik yang kemudian akan menampilkan nama pasien yang disebelahnya ada button proses. setelah tombol proses diklik mana akan sinkron dan ngelink ke menu selanjutnya.

![enter image description here](https://lh3.googleusercontent.com/-0AfY-A7YgLo/WpGb27VJUvI/AAAAAAAAAk4/4pxAivgt-Hc1dPx67Hvpb9bdc2WqtroXgCL0BGAs/w795-d-h651-n/login+dokter+dan+view+pasien.PNG)

d. Selanjutnya tersedia daftar Menu yang menampilkan perintah proses yaitu tampilan view biodata pasien,yang kemudian ketikas dokter sudah view data pasien maka dokter akan input resep, nah didalam menu resep dokter ada 2 button yaitu button obat sama proses. dokter bisa dengan mudah input resep obat, yang selanjutnya akan menglink ke bagian apotek ketika resep sudah disimpan.

![enter image description here](https://lh3.googleusercontent.com/-trOICIsRZzA/WpGdG-7YYFI/AAAAAAAAAls/PFhAOVoe1N8_Diu86eMdSn6MdJ7BtFYggCL0BGAs/w572-d-h477-n/data+pasien+dan+resep+obat.PNG)

e. Berikut penjelasannya button **obat** yang akan menampilkan stok obat yang ada di apotek, sehingga dokter dengan mudah memantau stok obat yang tersedia. kemudian untuk button **proses** data akan tersimpan secara otomatis ke data apotek.
 
![enter image description here](https://lh3.googleusercontent.com/-FrORJLGulzg/WpGeTu1A4uI/AAAAAAAAAmk/OX70BtUlOyQ7Zq2yd6A1zfAbfV8EP_SigCL0BGAs/w795-d-h653-n/view+stok+obat+dan+data+pasien.PNG)

f. Dibawah ini adalah menu apotek, dimana fungsi utama apotek yaitu menginput stok obat yang terdapat pada apotek tersbut. Kemudian bisa view resep obat dan view data pasien, kemudian setelah menerima kiriman dari dokter, maka resep dokter itu akan secara default tercetak kemudian pasien tinggak registrasi kepada kasir. sehingga mempermudah dalam proses ttransaksi pembayaran dan pendataannya juga, khususnya pendataan pasien dan obat.

![enter image description here](https://lh3.googleusercontent.com/-V2kNv3gGh7Q/WpGf7svxW9I/AAAAAAAAAnQ/MEmtUcEqQ0IYRTZvTP1sQOA2C-IpT4pwwCL0BGAs/w795-d-h692-n/login+apotek+dan+input+stok+obat.PNG)

2.1.3 Antarmuka Perangkat Keras (Hardware)

Dibawah ini adalah  antar muka hardware:
Admin :menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan.

Dokter : view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.

Apotek :input stok obat, view dan cetak data pasien yang sudah berobat.

![enter image description here](https://lh3.googleusercontent.com/-Vm8DM0x7o0A/WpJ6cgU_uMI/AAAAAAAAARQ/FrchoGJ_Xo8kTTH0iRZfmX1OFu1-cbfYwCL0BGAs/w530-d-h275-n/usecase.png)

2.1.4 Antarmuka Perangkat Lunak

Tidak ada antarmuka perangkat lain yang dibutuhkan dalam pengembangan Aplikasi Sistem Informasi Pasien pada Study Kasus Dr. Jamil.

2.1.5 Antarmuka Komunikasi

Ada antarmuka komunikasi yang dibutuhkan dalam aplikasi ini yaitu antarmuka untuk melakukan koneksi dalam jaringan internet yaitu:

1.  Antarmuka komunikasi pada sisi Server

Sebuah aplikasi web berkomunikasi dengan perangkat lunak _client_ melalui HTTP. HTTP, sebagai protokol yang berbicara menggunakan _request_ dan _response_ menjadikan aplikasi web bergantung kepada siklus ini untuk menghasilkan dokumen yang ingin diakses oleh pengguna. Secara umum, aplikasi web yang akan kita kembangkan harus memiliki satu cara untuk membaca HTTP Request dan mengembalikan HTTP Response ke pengguna.

2.1.6 Batasan Memori

Penggunaan Ruang penyimpanan pada aplikasi ini (berbasis Android) yaitu tidak kurang dari 100 Mb.

	 
2.2 Fungsi-fungsi produk 
![enter image description here](https://lh3.googleusercontent.com/-EWCFjOFxbqk/WpdkCjxqzRI/AAAAAAAAArw/ym8TI0ZMviof1mN_TxermDDTBU1zj3uJQCL0BGAs/w795-d-h615-n/use+case+fungsi++project.jpeg)

	2.2.1  Tabel Kebutuhan Fungsional
| No | User |Fungsi  |
|--|--|--|
| 1 |Admin	  | menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan|
|2|Dokter|view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.|
|3|Apotek |input stok obat, view dan cetak data pasien yang sudah berobat|

**3. Kebutuhan lain yang spesifik**

3.1 Kebutuhan antarmuka eksternal

	3.1.1 Antarmuka pemakai

Dokter dan Apotek sebagai user yang dapat mengoperasikan aplikasi sistem informasi pasien pada study kasus Dr. Jamil dengan menggunakan smartphone yang berupa android.
	
	3.1.2 Antarmuka perangkat lunak
Aplikasi ini dapat diakses jika terhubung dengan internet dan memiliki OS android.

3.2 Kebutuhan Fungsional 

	3.2.1 Diagram Kebutuhan Fungsional

|Use Case Name|Dokter dan Apoteker|
|--|--|
|**Trigger**| halaman beranda user admin|
| **Pre condition**  | Web ditampilkan hanya untuk admin yang digunakan untuk input saat pendaftaran pasien |
|**Basic Path** | 1. admin input data pasien	
||2. Sistem mengirim data pasien, dan view data pasien .
||3. Dokter input resep obat, yang kemudian terhubung langsung ke bagian apoteker.|
|**Post condition**| user dokter mampu melihat daftar pasien yang dikirim dari admin, dan apotek bisa melihat resep obat dari dokter|
|**Exception push**| user dokter dapat melakukan pencarian obat, yang sebelumnya data obat tersebut sudah duimasukkan oleh user apotek.|
|**Other**| data stok barang dapat ditampilkan dan diview oleh user dokter|

	3.2.2 komunikasi
	
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

	3.2.3 tambahan

|Nama Use Case|Sistem|
|--|--|
|  **Trigger**| Admin, melakukan proses pendataan pasien  |
|**Precondition**|admin telah mengakses layar utama |
|**Basic Path**| 1\. Sistem menyajikan tabel kosong untuk memasukkan pendaftaran pasien 
||2\. admin memasukkan informasi dan mengirimkan biodata pasien 
||3\. Sistem memeriksa bahwa kolom nama biodata lainnya sudah terpenuhi|

3.3 Persyaratan Non Fungsional 

	3.3.1 Struktur tidak logis

Struktur logis data (ERD) yang akan disimpan dalam database Article Manager internal diberikan di bawah ini:
![enter image description here](https://lh3.googleusercontent.com/-b-psNrrlOk8/WqonLX7W3GI/AAAAAAAAA3Y/6n_qs5JVVm8efgapTqOS5IVgKpEIlZKuACL0BGAs/w530-d-h418-n-rw/ERD%2BFIX%2BBISMILLAH.jpg)


|Data item|Type|Description|Comment|
|--|--|--|--|
|nama|text|nama obat|menampilkan nama|
|ID|Integer|harga obat|ID harus Primary key|
|speciality|Text|mempunyai keahlian dalam bidangnya masing-masing|

3.3.2 Keamanan

Server tempat untuk admin dan apotek berada akan memiliki keamanan sendiri untuk mencegah akses write / delete yang tidak sah. Tidak ada batasan akses baca. 

PC tempat admin berada akan memiliki keamanan sendiri. Hanya admin yang memiliki akses fisik ke mesin dan program di dalamnya. Tidak ada perlindungan khusus yang ada di dalam sistem ini.

