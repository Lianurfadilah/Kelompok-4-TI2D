

<!DOCTYPE html>
<html>
<head></head

<body><center>
	<h1 align="center">Software Design Description</h1>
	<h2 align="center">Version 1.5<br>
	25 Maret 2018</h2><br><br>
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

**BAB 1 Pendahuluan**

**1.1 Tujuan**

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Sistem Informasi Pasien Pada Stdy Kasus Dr. Jamil, dan juga memberi definisi kebutuhan untuk sistem dan spesifikasikebutuhan fungsional. Fungsi utama dari Sistem Informasi Pasien Pada Study Kasus Dr. Jamil ini adalah untuk mempermudah sistem pada praktek Dr. Jamil selain itu dapat efisiensi dalam waktu kerja.

**1.2 Cakupan**

SDD adalah representasi dari perancangan perangkat lunak untuk digunakan untuk merekam informasi desain dan mengkomunikasikan informasi desain ke desain utama stakeholder. Software Design Description (SDD) ini berupa dokumen yang melengkapi kode program Sistem Informasi Pasien pada Study Kasus Dr. Jamil (Simpaty Adil). kegunaan dari penulisan dokumen adalah untuk memberikan penjelasan mengenai perangkat luak yang akan dibangun, baik secara umum maupun secara detail seperti definisi kebutuhan sistem dan spesifikasi kebutuhan fungsional. Dokumen ini digunakan sebagai acuan dan sebagai bahan evaluasi pada saat pengembangan perangkat lunak. Dengan dokumen ini diharapkan pengembangan perangkat lunak Sistem Informasi Pasien Pada Study Kasus Dr. Jamil ini akan lebih terarah dan tidak menimbulkan ambigius bagi pihak pengembang dan pengguna perangkat lunak.
Fungsi utama dari Sistem Informasi Pasien Pada Stdy Kasus Dr. Jamil adalah :
	
|No|User|Fungsi|
|--|--|--|
| 1 | Admin |Menginput data pasien, kemudian data itu akan muncul pada Dokter.|
| 2| Dokter |Melihat data pasien serta bisa memasukan resep obat yang kemudian akan dikirim ke bagian apoteker.|
| 3 | Apoteker |Melihat data kesuluruhan yang sudah dimasukan oleh Dokter, selain itu juga Apoteker bisa menginputkan stok obat yang ada di apotek sehingga data itu akan muncul ke bagian Dokter.|

**1.3 Definisi, Akronim, dan Singkatan**

|No.|Singkatan|Definisi|
|--|--|--|
|1.|SDD|Software Design Description|
|2.|IEEE|Institute of Electrical and Electronics Engineers|
|3.|Dr.|Dokter (seseorang yang karena keilmuannya berusaha menyembuhkan orang-orang yang sakit.)|

**1.4 Referensi**

1. IEEE P1016/D5.0; 12 December 2005, IEEE Draft Standard for Software Design
2. Software Design Description (SDD) / Deskripsi Perancangan Perangkat Lunak (DPPL)- Software Design Description.pdf

**1.5 Ikhtisar dokumen**

Pada bab selanjutnya yaitu menjelaskan gambaran Deskripsi perancangan Global, Rancangan Lingkungan Implementasi. pada bab terakhir menjelaskan tentang Deskripsi perancangan secara rinci.

**2. Deskripsi Perancangan Global**

Pendukung dalam pembuatan aplikasi antara lain:

a. Sistem Operasi
Microsoft Windows 7 s/d Windows 10

b. DBMS

DBMS yang digunakan adalah Mysqli

c. Development Tools

- Sublime text 3

- XAMPP Control Panel v.3.2.2

d. Bahasa Pemrograman

Bahasa pemrograman yang digunakan yaitu PHP, HTML, Bootstrap dan CSS.

**2.2 Deskripsi Data**
**2.2.1 Definisi Domain / Type **

tabel database yang digunakan pada Rancang Bangun aplikasi pasien pada study kasus Dr.Jamil adalah:

Dokter

| Domain | Type | Description |
|--|--|--|
|Id_dokter|Integer|Primary key|
|Id_login|Integer|foreign key|
|Id_obat|Integer|golongan obat|
|nama_dokter|varchar|nama dokter|

Data Pasien

| Domain | Type | Description |
|--|--|--|
|Id_pasien|Integer|Primary Key|
|nik|Integer|nomor induk kependudukan|
|nama_pasien|varchar|nama pasien|
|umur|integer|umur|
|alamat_pasien|varchar|alamat|
|no_telp|integer|nomor telepon|
|keluhan|varchar|keluhan pasien|


Resep

| Domain | Type | Description |
|--|--|--|
|Id_resep_obat|integer| Primary key|
|nama_obat|varchar| nama obat |
|aturan_pakai|varchar|aturan minum obat|
|Id_stok_obat|integer|foreign key|

Obat

| Domain | Type | Description |
|--|--|--|
|Id_obat|integer|primary key|
|Id_stok_obat|integer|foreign key|
|Id_resep_obat|integer||

Stok Obat

| Domain | Type | Description |
|--|--|--|
|Id_stok_obat|integer|primary key|
|nama_obat|varchar|nama obat|
|harga_obat|varchar|harga obat|
|jumlah_obat|varchar|jumlah obat|

Apoteker

| Domain | Type | Description |
|--|--|--|
|Id_apoteker|integer|primary key|
|Id_login|integer|foreign key|
|Id_stok_obat|integer||
|nama_apoteker|varchar|nama apoteker|

Login

| Domain | Type | Description |
|--|--|--|
|Id_login|integer|primary key|
|username|varchar|username|
|password|varchar|password|
|type|varchar|type user|

**2.2.2 Conceptual Data Model**

![konsep](https://lh3.googleusercontent.com/-Inm9n7_Ba78/WtNkW3sWiSI/AAAAAAAAAQo/7A0GnBWddlUnQKKPepWQLEB0k8NVrWkJQCL0BGAs/w530-d-h337-n-rw/konsep.jpg)

**2.2.3 Physical Data Model**

![relasi tabel](https://lh3.googleusercontent.com/-GNArDOoIRhI/WtNiTOglZyI/AAAAAAAAAQE/wnQxioNuCRwDhtdJzbs9xNTUgWtsQ3yvwCL0BGAs/w530-d-h262-n-rw/relasi%2Btabel.PNG)

**2.2.4 Daftar Tabel Aplikasi**

**2.3 Deskripsi Modul**


**BAB 3 Deskripsi Perancangan Rinci**

**3.1 Diagram Konteks**
	
![enter image description here](https://lh3.googleusercontent.com/-Ky-_cGCZCEE/WrEjE-yA5gI/AAAAAAAAAbg/WaghyDGsBAMdSTD-XA7uthOHPOGNOpj2gCL0BGAs/w530-d-h335-n/Diagram+konteks.jpg)
	
**3.1.1 Diagram level 0**

![enter image description here](https://lh3.googleusercontent.com/-lkVF6lTqdm8/WrfIZQdv-7I/AAAAAAAAA7U/4pKvCB8HyowLnai8SsQmSbmlLvklI7xvQCJoC/w795-h467-n/level+0.png)


**3.1.1.1 Diagram level 1**

![enter image description here](https://lh3.googleusercontent.com/-fj63jHKyGic/WrfIcBgE0YI/AAAAAAAAA7U/SwSwjdx6sxI7SWaxj_jIi-m8KNGm-OwZwCJoC/w795-h567-n/level+1.png)

**3.1.1.2 Diagram level 2**

![enter image description here](https://lh3.googleusercontent.com/-y1rpbOKuoc4/WrfIfBtYzWI/AAAAAAAAA7U/EdyApJKkmCEOa4fTpYd5nvBucoK9C54KgCJoC/w795-h437-n/level+2.png)

**3.1.1.3 Diagram level 3**

![enter image description here](https://lh3.googleusercontent.com/-M_yW1nWhR5s/WrfIioYJAJI/AAAAAAAAA7U/6nAKxU_wbsEUcK960J3zweAXpb1t0e72QCJoC/w795-h482-n/level+3.png)

**3.1.1.4 Diagram level 4**

![enter image description here](https://lh3.googleusercontent.com/-xxH9r27lXpY/WrfImpro_II/AAAAAAAAA7U/w8yLjyJ7zAI8sfUPTlRAtCJhhaZGg29pQCJoC/w795-h473-n/level+4.png)

**3.1.1.5 Diagram level 5**

![enter image description here](https://lh3.googleusercontent.com/-8RxouDRwMbM/WrfIpijV_rI/AAAAAAAAA7U/_hI4_VrF6aUx2QgfsKYBQdQtQl7edfiIgCJoC/w795-h572-n/level+5.png)
	
**3.1.1.6 Diagram level 6**

![enter image description here](https://lh3.googleusercontent.com/-3co6lNE5knM/WrfIsR8VsTI/AAAAAAAAA7U/zB33lXMnZMUrDrN-YQ261Rqhp3fVH0o9gCJoC/w795-h483-n/level+6.png)

** 3.1.1.7 Diagram level 7**

![enter image description here](https://lh3.googleusercontent.com/-d7tObjgAxZE/WrfIvna1xVI/AAAAAAAAA7U/eYoT7mTLLtUidwxaL5eJpZ83i36TgbXdQCJoC/w795-h695-n/level+7.png)

**3.1.1.8 Diagram level 8**

![enter image description here](https://lh3.googleusercontent.com/-NwF0OOZ5LEU/WrfIy0uNwgI/AAAAAAAAA7U/BFnAW-Lov_I4mR58zG_-o3Jy4w9lL8bfQCJoC/w795-h695-n/level+8.png)
