
<!DOCTYPE html>
<html>
<head></head

<body><center>
	<h1 align="center">Software Design Description</h1>
	<h2 align="center">Version 1.1<br>
	10 Maret 2018</h2><br><br>
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

**BAB 1 Pendahuluan**

	1.1 Cakupan 

SDD adalah representasi dari perancangan perangkat lunak untuk digunakan untuk merekam informasi desain dan mengkomunikasikan informasi desain ke desain utama stakeholder. Software Design Description (SDD) ini berupa dokumen yang melengkapi kode program Sistem Informasi Pasien pada Study Kasus Dr. Jamil (Simpaty Adil). kegunaan dari penulisan dokumen adalah untuk memberikan penjelsan mengenai perangkat luak yang akan dibangun, baik secara umum maupun secara detail seperti definisi kebutuhan sistem dan spesifikasi kebutuhan fungsional. Dokumen ini digunakan sebagai acuan dan sebagai bahan evaluasi pada saat pengembangan perangkat lunak. Dengan dokumen ini diharapkan pengembangan perangkat lunak Sistem Informasi Pasien Pada Study Kasus Dr. Jamil ini akan lebih terarah dan tidak menimbulkan ambigius bagi pihak pengembang dan pengguna perangkat lunak.

	1.2 Tujuan

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Sistem Informasi Pasien Pada Stdy Kasus Dr. Jamil, dan juga memberi definisi kebutuhan untuk sistem dan spesifikasikebutuhan fungsional. Fungsi utama dari Sistem Informasi Pasien Pada Study Kasus Dr. Jamil ini adalah untuk mempermudah sistem pada praktek Dr. Jamil selain itu dapat efisiensi dalam waktu kerja.

Fungsi utama dari Sistem Informasi Pasien Pada Stdy Kasus Dr. Jamil adalah :
	
|No|User|Fungsi|
|--|--|--|
| 1 | Admin |Menginput data pasien, kemudian data itu akan muncul pada Dokter.|
| 2| Dokter |Melihat data pasien serta bisa memasukan resep obat yang kemudian akan dikirim ke bagian apoteker.|
| 3 | Apoteker |Melihat data kesuluruhan yang sudah dimasukan oleh Dokter, selain itu juga Apoteker bisa menginputkan stok obat yang ada di apotek sehingga data itu akan muncul ke bagian Dokter.|

	1.3 Audients yang dituju

Aplikasi ini dibuat berdasarkan study kasus pada Dr. Jamil yang ditujukan pada sistem prakter Dokter tersebut. Dimana aplikasi ini mempunyai fungsi untuk menjembatani dan mensinkronkan antara Admin-Dokter-Apoteker sehingga data pasien dapat tersimpan dengan rapi, selain itu juga data stok obat mampu dimonitoring oleh Dokter, dengan demikian aplikasi ini diharapkan mampu mengefisiensikan sistem yang ada pada praktek dokter tersebut.

	1.4 Kesesuaian

SDD ini mengacu pada **IEEE Draft Standard for Software Design
Descriptions** .

** BAB 2 Referensi**

IEEE P1016/D5.0; 12 December 2005, IEEE Draft Standard for Software Design
Descriptions

**BAB 3 Definisi**

	
![enter image description here](https://lh3.googleusercontent.com/HTjJ_xBgNNM513h6a_5g8kYmze-8dw9Ucw6mg9-u7ec2vC1c-FgJJb-cdrYxVsuV5KhZzec0DtXN=s700 )
	
	Diagram level 0

![enter image description here](https://lh3.googleusercontent.com/-NSwsuQrAnnQ/WqSW5Ne_1dI/AAAAAAAAA1M/x-UEPg9j6OEyXTi0JGi9YetnHjozxnPFQCL0BGAs/w795-d-h536-n/LEVEL+O.PNG)

	Diagram level 1

![enter image description here](https://lh3.googleusercontent.com/-XVs_QUHt6-k/WqSRsrwWwCI/AAAAAAAAAwc/uSHqcyGJ3hMWBer-3ql801v4v2Vzvq0rgCL0BGAs/w795-d-h813-n/Level+1.jpeg)

	Diagram level 2

![enter image description here](https://lh3.googleusercontent.com/-sjlQVVd_ZOo/WqSR41gTsqI/AAAAAAAAAw0/GFl5BDef6KAeM202TadT8RvkRFIyTwhswCL0BGAs/w795-d-h438-n/dfd+level+2.png)

	Diagram level 3

![enter image description here](https://lh3.googleusercontent.com/-lzav3YlomtM/WqSSPK41b1I/AAAAAAAAAxM/VZ8QimoDlG0GniPBf_P9l0QQkbq2YoOcACL0BGAs/w795-d-h423-n/dfd+level+3.png)

**BAB 4 Konsep Framework untuk SDD**

	4.1 Software Desain Konteks

https://lh3.googleusercontent.com/-Uh6lqSmsUEk/WqR2C2aX-tI/AAAAAAAAAA4/rJ6A-GxIcfMQAarY-7l6hdtK15Qo5r0BwCL0BGAs/w530-d-h335-n-rw/Diagram%2Bkonteks.png


