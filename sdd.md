
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

	
![diagram konteks](https://lh3.googleusercontent.com/-ch93xPulygU/WqqLLAI6YnI/AAAAAAAAAEI/A6o0LzPEp8AWpMTqkZkNBPRDnOvEjeg_wCL0BGAs/w530-d-h335-n-rw/Diagram%2Bkonteks.jpg)
	
	Diagram level 0

![enter image description here](https://lh3.googleusercontent.com/-OzWpIrh7tJ4/WqqLSSrcujI/AAAAAAAAAEc/b7Sf4lVFwEYB1yoUezaMLLeMePujwXJIgCL0BGAs/w530-d-h377-n-rw/diagram%2Blev0.jpg)

	Diagram level 1

![enter image description here](https://lh3.googleusercontent.com/-6ZexaTP2iBQ/WqqLdaa3YYI/AAAAAAAAAEw/ik7OXQdDY24UuOLcElHObaD80OBY7RIqwCL0BGAs/w530-d-h286-n-rw/diagramlev1.jpg)

	Diagram level 2

![enter image description here](https://lh3.googleusercontent.com/-6qkWp7i7HRY/WqqLngilSZI/AAAAAAAAAFE/6zfpih4N98Mn8WdcRFosag7SZ9C0qNkngCL0BGAs/w530-d-h379-n-rw/diagramlev2.jpg)

	Diagram level 3

![enter image description here](https://lh3.googleusercontent.com/-MsfJjknmVIo/WqqLuvFm9oI/AAAAAAAAAFY/4_LFE3QAecwBeibT8F-rQCP1AM_hKgjBACL0BGAs/w530-d-h342-n-rw/diagramlev3.jpg)

	Diagram level 4

![enter image description here](https://lh3.googleusercontent.com/-iE04LtcBTHY/WqqL3gb_rgI/AAAAAAAAAFs/WV5nPoxpM9kClEk-mtO1GOzbnMCAy3RywCL0BGAs/w530-d-h463-n-rw/diagramlev4.jpg)



