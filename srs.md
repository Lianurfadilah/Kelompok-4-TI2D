				Software Requirements Specification
							Version X.X
						  22 Februari 2018
						  
			[Gambar POLINDRA](/SEMESTER 4/POLINDRA.png)
			
		Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil
							(SIMPATY ADIL)
							
					   Nama Anggota TIM :
				   LIA NUR FADILAH 	(1603104)
				   LUVI HAERUNISAH 	(1603105)
				   MAULANA AHMAD Q.	(1603106)
				  
					  
				JURUSAN D3 TEKNIK INFORMATIKA
				 POLITEKNIK NEGERI INDRAMAYU
		
1. Pendahuluan
		Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi
	yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, 
	aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil.
	Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. 
	Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya 
	sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter 
	yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian 
	registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. 
	Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, 
	dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. 
	Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien 
	menjadi tidak valid. Serta data stook obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, 
	pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah 
	sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat 
	mempermudah petugas di tempat praktek Dr. Jamil dalam pendataan pasien. 

1.2 Lingkup Masalah

    Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi
    yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, 
    aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil.
	Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat.

1.3 Definisi, Istilah dan Singkatan
	
	Tabel 1. Daftar Definisi dan Akronm
	____________________________________________________________________________________
	|  Kata Kunci 	|  			Definisi atau akronim 							 		|
	------------------------------------------------------------------------------------
	| SRS		 	| Software Requirement Specification						 		|
	| SKPL		 	| Spesifikasi Kebutuhan Perangkat Lunak 					 		|
	|				| Dokumen hasil analis yang berisi spesifikasi kebutuhan user		|
    |RPL			| Rekayasa Perangkat Lunak, Kegiatan pengembangan perangkat lunak	|
	-------------------------------------------------------------------------------------
	
	tabel 2. Daftar Istilah
	______________________________________________________________________________________________________
	|  Kata Kunci 	|  			Definisi atau akronim 							 						 |
	-----------------------------------------------------------------------------------------------------
	| 	 Android	| sistem operasi berbasis Linux yang dirancang untuk perangkat bergerak layar sentuh |
    |              	|  seperti telepon pintar dan komputer tablet										 |
	| 	 web		|suatu ruang informasi yang dipakai oleh pengenal globalyang disebut Pengidentifikasi| 
	| 				|Sumber Seragam untuk mengenal pasti sumber daya berguna.							 |
	------------------------------------------------------------------------------------------------------
	

1.4 Aturan Penomoran


1.5 Referensi
     1. https://openlibrary.telkomuniversity.ac.id/pustaka/files/97623/resume/sistem-informasi-pelayanan-pasien-pada-klinik-permata-raya-bandung.pdf
	[PDF]sistem informasi pelayanan pasien pada klinik permata ... - Open Library
	

1.6 Deskripsi Umum Dokumen (Ikhtisar)



2. Gambaran Umum
	Aplikasi sistem informasi pasien dengan study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi
    yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, 
    aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil.
    Aplikasi ini terdapat 4 user, yaitu diantaranya :
	1. Admin	: Input data pasien
	2. Dokter	: Input data pasien dan insert resep dokter
	3. Apotek	: View data pasien,input resep obat dan input harga

  2.1 Perspektif produk (Perbandingan)
		Aplikasi yang kita buat ini adalah sistem informasi pasien dengan study kasus Dr. Jamil.
		Untuk perbedaan antara aplikasi Sistem Informasi Pasien dengan Study Kasus Dr. Jamilyang kami buat dengan-
		Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan Layanan Web 
		(https://www.researchgate.net/publication/320519219_Rancang_Bangun_Aplikasi_Rekam_Medis_untuk_Praktik_Pribadi_Dokter_Berbasis_Android_dan_Memanfaatkan_Layanan_Web).
		Keunggulan dari aplikasi kami adalah, aplikasi kami terhubung dengan Apotek dan Kasir ditempat Praktek tersebut.
		Sedangkan Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan 
		Layanan Web ini hanya diperuntukan untuk asien yang berkonsultasi dengan Dokter, 
		dan pada data Doter, Doter hanya bisa melihat dan menambahkan pasien tanpa bisa mengupdtae data pasien.
	 2.1.1 Antarmuka Sistem
		Admin	: -Bisa menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan
					
		Dokter	: -Bisa menambahkan, mengedit dan menghhapus data pasien.
				  -Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin.
					Dimana Data Pasien ini berisi Nama Pasien, NIK,
					Umur, No Telp dan Keluhan si Pasien.
					Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,
					Dokter bisa klik tombol search untuk mencari.
					
		Apotek	: -Bisa input data obat (nama dan harga obat)
				  -View data pasien
		
	 2.1.2 Atarmuka Pengguna
	 
		
	