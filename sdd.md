

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

**BAB 2 Referensi**

IEEE P1016/D5.0; 12 December 2005, IEEE Draft Standard for Software Design
Descriptions

**BAB 3 Definisi**

	Diagram Konteks
	
![enter image description here](https://lh3.googleusercontent.com/-Ky-_cGCZCEE/WrEjE-yA5gI/AAAAAAAAAbg/WaghyDGsBAMdSTD-XA7uthOHPOGNOpj2gCL0BGAs/w530-d-h335-n/Diagram+konteks.jpg)
	

	
	Diagram level 0

![enter image description here](https://lh3.googleusercontent.com/-7L8hPlRtEcc/WrEfaaH63eI/AAAAAAAAAY0/MCwwSKzwnHAN1k6CPDNSxK_O7c-EIBP6ACL0BGAs/w530-d-h405-n/konteks.png)

	Diagram level 1

![enter image description here](https://lh3.googleusercontent.com/-exeKWSSev5w/WrEfhiQm4iI/AAAAAAAAAZI/Ltt9knISKSEJc-hAAZ9o4CCtggkUCHnuQCL0BGAs/w530-d-h316-n/lvl1.png)

	Diagram level 2

![enter image description here](https://lh3.googleusercontent.com/-YNi1-lBFId8/WrEfpQ28DfI/AAAAAAAAAZc/omRIc9KDIhEgKfSELnV0Uhd0NMjzgjibwCL0BGAs/w530-d-h410-n/lvl2.png)

	Diagram level 3

![enter image description here](https://lh3.googleusercontent.com/-9DQEePWu-ec/WrEfu6uQegI/AAAAAAAAAZw/giZG_15HcOAp4Fx2OFLRo2kQXdr9KQpZgCL0BGAs/w530-d-h342-n/lvl3.png)

	Diagram level 4

![enter image description here](https://lh3.googleusercontent.com/-TQZG1vhi7UU/WrEfz03YuQI/AAAAAAAAAaE/YaYeKVFg6XAG2YjRl6pytmsVD9_neMSAQCL0BGAs/w530-d-h448-n/lvl4.png)

