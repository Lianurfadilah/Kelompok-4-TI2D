

<!DOCTYPE html>
<html>
<head></head

<body><center>
	<h1 align="center">Software Testing Document</h1>
	<h2 align="center">Version 1.3<br>
	20 Mei 2018</h2><br><br>
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

**1 Pendahuluan**

**1.1 Tujuan Pembuatan Dokumen**

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap Rancang Bangun Aplikasi Pasien pada Study Kasus Dr.Jamil
(SIMPATY ADIL). Dokumen ini digunakan untuk menguji coba kemampuan dari proyek yang kami buat agar sesuai dengan rancangan.
Pembuatan dokumen ini ditujukan untuk acuan dalam permbuatan aplikasi yang kami buat.

**1.2 Deskripsi Umum Sistem**

Perangkat lunak yang akan diuji adalah “Rancang Bangun Aplikasi Pasien pada Study Kasus Dr.Jamil (SIMPATY ADIL)”. Perangkat lunak ini adalah perangkat lunak yang digunakan untuk mempermudah transaksi pada praktek Dr. Jamil. Sistem ini diimplementasikan melalui komunikasi di media antara sesama pengguna dengan sistem.

**1.3 Deskripsi Dokumen (Ikhtisar)**

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

**1.4 Definisi dan Singkatan**<br>
Untuk merepresentasikan struktur data statis pada perangkat lunak.</br>
<table>
<tr>
<td>No</td>
<td>Singkatan</td>
<td>Definisi</td>
</tr>
<tr>
<td>1</td>
<td>SKPL</td>
<td>Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa Inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan (requirement)</td>
</tr>
<tr>
<td>2</td>
<td>DFD</td>
<td>Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak. Jurusan Teknik Komputer Diploma IPB PDHUPL-SPEK Halaman 7 dari 14 Template Dokumen ini dan informasi yang dimilikinya adalah milik Jurusan Teknik Komputer-Diploma IPB dan bersifat rahasia. Dilarang mereproduksi dokumen ini tanpa diketahui oleh Jurusan Teknik Komputer Diploma IPB</td>
</tr>
<tr>
<td>3</td>
<td>ERD</td>
<td>Entity Relationship Diagram, diagram dan notasi yang digunakan</td>
</tr>
</table>




	
**1.5 Dokumen Referensi**
<table>
<tr>
<td>No</td>
<td><center>Referensi</center></td>
</tr>
<tr>
<td>1</td>
<td>Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor.</td>
</tr>
<tr>
<td>2</td>
<td>Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor</td>
</tr>
<tr>
<td>3</td>
<td>Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.</td>
</tr>
</table>



**2 Lingkungan Pengujian Perangkat Lunak**

**2.1 Perangkat Lunak Pengujian**

Perangkat lunak ini (SPEK) diujikan dengan beberapa perangkat lunak lain.
Pendukung dalam pembuatan aplikasi antara lain:

<table>
<tr>
<td>No</td>
<td><center>Pendukung</center></td>
</tr>
<tr>
<td>1</td>
<td> Sistem Operasi Microsoft Windows 7 s/d Windows 10 </td>
</tr>
<tr>
<td>2</td>
<td>DBMS yang digunakan adalah Mysqli.</td>
</tr>
<tr>
<td>3</td>
<td>Development Tools Sublime text, 3XAMPP, Control Panel v.3.2.2</td>
</tr>
<tr>
<td>4</td>
<td>Bahasa pemrograman yang digunakan PHP, HTML, Bootstrap dan CSS.</td>
<tr>
<td>5</td>
<td>Framework menggunakan CI</td>
</table>


**2.2 Perangkat Keras Pengujian**

 Perangkat keras yang diperlukan untuk menguji aplikasi SPEK ini adalah satu set komputer dengan spesifikasi:
 <br>• Processor: Intel® Pentium Dual </br>
 <br>• Memory: 4 GB DDR3</br>
 <br>• Harddisk 100 GB</br>

**2.3 Material Pengujian**

Pada program “Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil” Aplikasi Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr.Jamil Berbasis Website adalah sebuah aplikasi yang ditunjukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. 

**2.4 Sumber Daya Manusia**
Persyaratan sumber daya manusia yang akan terlibat dalam proses
pengujian perangkat lunak ini adalah:

<table>
<tr>
<td>No</td>
<td><center>Sumber Daya Manusia</center></td>
</tr>
<tr>
<td>1</td>
<td>Memahami konsep pemrograman berorientasi objek dalam bahasa PHP</td>
</tr>
<tr>
<td>2</td>
<td>Memahami proses pengujian perangkat lunak berorientasi objek.</td>
</tr>
<tr>
<td>3</td>
<td>Memahami konsep pemrograman database XAMPP</td>
</tr>
</table>


**2.5 Prosedur Umum Pengujian**

**2.5.1 Pengenalan dan Latihan**

Penguji aplikasi ini hanya diberikan latihan kembali tentang SQL, dan pengenalan lebih lanjut mengenai database Mysqli, PHP, HTML, Bootstrap dan CSS.

**2.5.2 Persiapan Awal**

**2.5.2.1 Persiapan Prosedural**

Pengujian ini bisa dilakukan didalam lingkungan kampus, ditempat praktek Dr. Jamil dan bisa juga dilakukan ditempat lain yang berada diluar kampus. Dimana pengujian ini dilakukan oleh tim pembuat aplikasi / tim proyek yang sudah ditentukan oleh Dosen pengampu. Alat yang digunakan 1 buah komputer/laptop dengan software yang telah dipersiapkan.

**2.5.2.2 Persiapan Perangkat Keras**

Perangkat keras yang perlu dipesiapkan adalah:

Sebuah perangkat laptop yang dilengkapi dengan;
<br>• Processor: Intel® Pentium Dual Core</br>
<br>• Memory: 4 GB DDR3</br>
<br>• Harddisk 100 GB</br>

**2.5.2.3 Persiapan Perangkat Lunak**

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows (all support)
adalah sebagai berikut :

1. Persiapkan sistem operasi Microsoft Windows.

2. Perangkat lunak yang akan di uji di copykan ke sebuah direktori penyimpanan pada komputer/laptop, contohnya seperti C:\XAMPP\htdocs.

3. Browser Google Chrome.

4. Database diimportkan ke phpMyAdmin pada database.

5. Sublime untuk proses memasukan dan melihat source code.

**2.5.3 Pelaksanaan**

Pengujian dilaksanakan dengan mengikuti waktu yang sudah kami tentukan saat awal perancangan membuat aplikasi. Pelaksanaan pengujian dilakukan dengan mengeksekusi aplikasi yang sudah kami buat.

**2.5.4 Pelaporan Hasil**

Dokumen hasil uji dari aplikasi ini akan diberikan kepada Dosen Pembimbing dan dievaluasi oleh Dosen Pengampu dalam tindakan yang sudah selesai lalu Aplikasi akan diberikan ke mitra dan aplikasi yang telah dibuat di harapkan membuahkan hasil yang maksimal sebagai progress akhir.

**3. Identifikasi Rencana Pengujian**

Tabel 1 Identifikasi dan Rencana Pengujian

| Kelas Uji               | Butir Uji                                   | Identifikasi       |         | Jenis Pengujian | Jenis Pengujian | Penguji  |
|-------------------------|---------------------------------------------|--------------------|---------|-----------------|------------|----------|
| -----------             | ------------                                | **SRS/SDD**        | **STD** | -----------       | ----------  | -------- ||
|Pengujian Register User    | Mengisi data register user dengan benar|        SRS - 2.2.1            |    STD - 1.1    |        Sistem            |  Black Box                 |     Jenia Adellia     |
|                    |    Tidak semua mengisi Kolom input data register user    | SRS - 2.2.1 |          STD - 1.2        |    Sistem      | Black Box| Jenia Adellia
|                    |    Kesalahan Pengisian data register user    | SRS - 2.2.1 |          STD - 1.3         |    Sistem      | Black Box| Jenia Adellia
| Login | Username dan Password dimasukan sesuai data                 | SRS - 2.2.2|STD - 2.1|        Sistem          |           Black Box      | Jenia  Adellia |
|                         | Username dan Password yang dimasukan tidak sesuai dengan data|        SRS - 2.2.2            |    STD - 2.2     |        Sistem            |  Black Box                 |     Jenia Adellia     |
|                    |    Tidak mengisi Username dan Password    | SRS - 2.2.2 |          STD - 2.3         |    Sistem      | Black Box| Jenia Adellia
|Verifikasi Password | Password yang dimasukan sesuai  | SRS - 2.2.3|STD - 3.1|        Sistem          |           Black Box      | Jenia  Adellia |
|                         | Password yang dimasukan tidak sesuai |        SRS - 2.2.3           |    STD - 3.2     |        Sistem            |  Black Box                 |     Jenia Adellia     |
|                    |    Tidak memasukan password  | SRS - 2.2.3 |          STD - 3.3         |    Sistem      | Black Box| Jenia Adellia
|Display Login Error | Menampilkan Gagal login  | SRS - 2.2.4|STD - 4.1|        Sistem          |           Black Box      | Lia Nur Fadilah |
|                         | tidak memasukan Email dan Password|        SRS - 2.2.4            |    STD - 4.2     |        Sistem            |  Black Box                 |    Lia Nur Fadilah   |
|                    |    Tidak ada koneksi internet  | SRS - 2.2.4 |          STD - 4.3         |    Sistem      | Black Box| Lia Nur Fadilah
|Input Data Pasien | Mengisi data Pasien dengan benar | SRS - 2.2.5|STD - 5.1|        Sistem          |           Black Box      | Lia Nur Fadilah |
|                         | kesalahan mengisi data pasien (misal;antara NIK dan nama)|        SRS - 2.2.5           |    STD - 5.2     |        Sistem            |  Black Box                 |    Lia Nur Fadilah   |
|                    |    Tidak mengisi semua kolom input data pasien  | SRS - 2.2.5 |          STD - 5.3         |    Sistem      | Black Box| Lia Nur Fadilah
|Laporan berupa Grafik Jumlah Pasien | Menambah Pasien  | SRS - 2.2.6|STD - 6.1|        Sistem          |           Black Box      | Luvi Haerunisah |
|                         | Tidak menambah pasien|        SRS - 2.2.6            |    STD - 6.2     |        Sistem            |  Black Box                 |    Luvi Haerunisah   |
|                    |     Tidak ada koneksi Internet | SRS - 2.2.6 |          STD - 6.3         |    Sistem      | Black Box| Luvi Haerunisah
|Lihat Data Pasien | Menambah Pasien  | SRS - 2.2.7|STD - 7.1|        Sistem          |           Black Box      |Maulana Ahmad Qusyaeri |
|                         | Tidak menambah pasien|        SRS - 2.2.7            |    STD - 7.2     |        Sistem            |  Black Box                 |    Maulana Ahmad Qusyaeri   |
|                    |     Kesalahan mengisi tambah pasien| SRS - 2.2.7 |          STD - 7.3        |    Sistem      | Black Box| Maulana Ahmad Qusyaeri
|Input Resep Obat | Menginput resep obat dengan benar | SRS - 2.2.8|STD - 8.1|        Sistem          |           Black Box      |Jenia Adellia |
|                         | Kesalahan menginput resep obat|        SRS - 2.2.8            |    STD - 8.2     |        Sistem            |  Black Box                 |    Jenia Adellia   |
|                    |     Tidak input resep obat| SRS - 2.2.8 |          STD - 8.3        |    Sistem      | Black Box| Jenia Adellia

**Deskripsi dan Hasil Uji**

Tabel 2 Deskripsi dan Hasil Uji


<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-1.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Mengisi data register user dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui data register yang dimasukan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. masukan  data user di kolom register dengan benar
					  </ul><ul>2. Pilih tipe User untuk Register</ul><ul>3. Klik tombol Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> 
					Username:  Jenia<br>
					password :123<br>
					Nama	: Jenia Adellia <br>
					NIK : 1234567890 <br>
					Alamat : Bekasi  <br>
					Umur : 19
					tipe: Dokter <br>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data yang dimasukkan untuk register user berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>
				    Data yang dimasukan benar dan sesuai. misal NIK dengan angka.
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-1.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak semua mengisi Kolom input data register user</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah data yang tidak terisi semua akan berhasil register</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. masukan  data user di kolom register dengan benar
					  </ul><ul>2. Pilih tipe User untuk Register</ul><ul>3. Klik tombol Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> 
					Username:  Jenia<br>
					password :123<br>
					Nama	: Jenia Adellia <br>
					NIK : 1234567890 <br>
					 <br>
					Umur : 19
					tipe: Dokter <br>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data yang dimasukkan tidak berhasil register
				</ul>
			</td>
			<td rowspan="1">
				<ul>Data yang dimasukan salah karena ada kolom data input yang tidak di isi.
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-1.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Kesalahan Pengisian data register user</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Memeriksa apakah data yang salah bisa register atau tidak</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. masukan  data user di kolom register dengan benar
					  </ul><ul>2. Pilih tipe User untuk Register</ul><ul>3. Klik tombol Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> 
					Username:  Jenia<br>
					password :123<br>
					Nama	: Jenia Adellia <br>
					NIK : hahaha <br>
					Alamat : Bekasi  <br>
					Umur : 19
					tipe: Dokter <br>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data yang dimasukkan tidak berhasil register
				</ul>
			</td>
			<td rowspan="1">
				<ul>Data yang dimasukan salah karena ada kolom data input yang bukan tipe data nya.
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-2.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Email dan Password dimasukan sesuai data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui email dan password yang dimasukan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. masukan  username dan password sesuai dengan register user yang telah berhasil
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> 
					Username:  Jenia<br>
					password :123<br>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Username dan password yang dimasukan benar
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-2.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Email dan Password yang dimasukan tidak sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui email dan password yang dimasukan salah</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. masukan  username, dan password yang tidak sesuai dengan register user yang telah berhasil
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> 
					Username:  Jenia<br>
					password : sayangkamu<br>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login tidak Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Username yang dimasukan benar, namun password yang dimasukan salah
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-2.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak mengisi Username dan Password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui email dan password yang dimasukan salah</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Tidak memasukan username dan password
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> Tidak ada
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login tidak Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom username dan password
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-3.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Password yang dimasukan sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui password yang dimasukan sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login/Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan password yang sesuai dengan tipe data nya(varchar dengan nilai 10)
					  </ul><ul>2. Klik tombol Login/Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> password:123
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login/Register Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom password
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-3.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Password yang dimasukan tidak sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui password yang dimasukan tidak sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login/Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan password yang tidak sesuai dengan tipe data nya(varchar dengan nilai 10)
					  </ul><ul>2. Klik tombol Login/Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> password: sayangkamuselamanya
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login/Register tidak berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>password yang di isi tidak sesuai
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-3.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak memasukan password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Tidak mengisi kolom password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login/Register<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jenia Adellia</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Tidak memasukan password yang tidak sesuai dengan tipe data nya(varchar dengan nilai 10)
					  </ul><ul>2. Klik tombol Login/Register</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> tidak ada
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login/Register tidak berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom password
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-4.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menampilkan Gagal login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui gagal login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan username dan password tidak sesuai
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> username:jenia
				password:1234haha
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login tidak Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom username dan password dengan benar
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-4.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">tidak memasukan Email dan Password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui gagal login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan username dan password sesuai
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> username:jenia
				password:123
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom username dan password dengan benar
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-4.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak ada koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui gagal login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan username dan password sesuai
					  </ul><ul>2. Klik tombol Login</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul> username:jenia
				password:123
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Login Berhasil
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom username dan password dengan benar
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-5.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Mengisi data Pasien dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui data pasien yang berhasil di input</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman tambah pasien<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan NIK, Nama pasien, Umur, No.Telp, Alamat, dan Keluhan
					  </ul><ul>2. Klik tombol Simpan</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>NIK: 1234567890
				Nama: Lia
				Umur: 20
				No.tlp: 085774412565
				Alamat: Lohbener
				Keluhan: Pusing, Batuk Pilek
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data Berhasil tersimpan
				</ul>
			</td>
			<td rowspan="1">
				<ul>Harus mengisi kolom data pasien yang benar dan sesuai
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-5.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">kesalahan mengisi data pasien (misal;antara NIK dan nama)</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui data pasien yang salah di inputkan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman tambah pasien<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan NIK, Nama pasien, Umur, No.Telp, Alamat, dan Keluhan
					  </ul><ul>2. Klik tombol Simpan</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>NIK: hahahehe
				Nama: Lia
				Umur: 20
				No.tlp: 085774412565
				Alamat: Lohbener
				Keluhan: Pusing, Batuk Pilek
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data tidak Berhasil tersimpan
				</ul>
			</td>
			<td rowspan="1">
				<ul>tidak mengisi kolom data pasien yang benar dan sesuai
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-5.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak mengisi semua kolom input data pasien</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengetahui input data pasien ada kolom yang belum di isi </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman tambah pasien<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20-05-2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Lia Nur Fadilah</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>1. Memasukan NIK, Nama pasien, Umur, No.Telp, Alamat, dan Keluhan
					  </ul><ul>2. Klik tombol Simpan</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>NIK: hahahehe
				Umur: 20
				No.tlp: 085774412565
				Alamat: Lohbener
				Keluhan: Pusing, Batuk Pilek
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 Data tidak Berhasil tersimpan
				</ul>
			</td>
			<td rowspan="1">
				<ul>belum lengkap mengisi kolom data pasien yang benar dan sesuai
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					 OK
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>					
				</ul>
			</td>
		</tr>
	</thead>
</table>


</body>
</html>


