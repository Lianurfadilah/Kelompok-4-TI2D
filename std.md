

<!DOCTYPE html>
<html>
<head></head

<body><center>
	<h1 align="center">Software Testing Document</h1>
	<h2 align="center">Version 1.1<br>
	09 Mei 2018</h2><br><br>
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
<td>Referensi</td>
</tr>
<tr>
<td>1</td>
<td>IEEE P1016/D5.0; 12 December 2005, IEEE Draft Standard for Software Design</td>
</tr>
<tr>
<td>2</td>
<td> Software Design Description (SDD) / Deskripsi Perancangan Perangkat Lunak (DPPL)- Software Design Description.pdf</td>
</tr>
</table>



**2 Lingkungan Pengujian Perangkat Lunak**

**2.1 Perangkat Lunak Pengujian**

Perangkat lunak ini (SPEK) diujikan dengan beberapa perangkat lunak lain.
Pendukung dalam pembuatan aplikasi antara lain:

<table>
<tr>
<td>No</td>
<td>Pendukung</td>
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
</table>


**2.2 Perangkat Keras Pengujian**

 Perangkat keras yang diperlukan untuk menguji aplikasi SPEK ini adalah satu set komputer dengan spesifikasi:
 • Processor: Intel® Pentium Dual Core
 • Memory: 4 GB DDR3
 • Harddisk 100 GB

**2.3 Material Pengujian**

Pada program “Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr. Jamil” Aplikasi Rancang Bangun Aplikasi Pasien Pada Study Kasus Dr.Jamil Berbasis Website adalah sebuah aplikasi yang ditunjukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. 

**2.4 Sumber Daya Manusia**
Persyaratan sumber daya manusia yang akan terlibat dalam proses
pengujian perangkat lunak ini adalah:

<table>
<tr>
<td>No</td>
<td>Sumber Daya Manusia</td>
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
• Processor: Intel® Pentium Dual Core
• Memory: 4 GB DDR3
• Harddisk 100 GB

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
</body>
</html>

