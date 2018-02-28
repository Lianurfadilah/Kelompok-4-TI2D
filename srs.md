


				Software Requirements Specification
							Version 1.1
						  22 Februari 2018
						  
![enter image description here](https://lh3.googleusercontent.com/Mk2_cB7YlTjA6BhAtenwi-6nfONxdU_Mnew1OaieHO2UTlc0SDEL8wFkT94CIst1T-uykihG561B=s200)
			
		Aplikasi Sistem Informasi Pasien pada Study Kasus Dr.Jamil
							(SIMPATY ADIL)
							
					   Nama Anggota TIM :
				   LIA NUR FADILAH 	(1603104)
				   LUVI HAERUNISAH 	(1603105)
				   MAULANA AHMAD Q.	(1603106)
				  
					  
				JURUSAN D3 TEKNIK INFORMATIKA
				 POLITEKNIK NEGERI INDRAMAYU
1. Pendahuluan
		Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Perkembangan teknologi informasi saat ini semakin pesat. Informasi dapat diperoleh secara manual maupun secara komputerisasi. Saat ini komputerisasi memegang peranan penting dalam menyelesaikan langkah kerja yang besar dan rumit. Dengan berkembangnya sistem komputer efisiensi dan optimasi kerja dapat tercapai. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat. Saat ini Praktek Dr. Jamil memiliki 4 jenis pegawai yaitu dokter, admin, apotek, bagian registrasi (kasir). Sejauh ini, kondisi tempat praktek dokter masih menggunakan sebuah sistem pendataan yang manual. Hal ini membuat data pasien dalam skala besar seringkali hilang. Setiap ada pasien yang datang periksa, dokter atau petugas registrasi harus mendata satu per satu dengan mengacu pada kartu periksa pasien. Kegiatan operasional sehari-hari mereka sering mengalami kesulitan dalam mendata riwayat periksa pasien dan data pasien menjadi tidak valid. Serta data stook obat yang ada di apotek tidak terpantau dengan baik. Dengan adanya permasalahan tersebut, pelayanan terhadap pasien menjadi kurang berjalan dengan maksimal. Sehubungan dengan hal ini perlu dikembangkan sebuah sistem informasi berbasis web dan android untuk menangani masalah pendataan pasien, serta pendataan obat. Sistem ini dapat mempermudah petugas di tempat praktek Dr. Jamil dalam pendataan pasien. 
1.1 Tujuan 
		tujuan pembuatan SRS yaitu sebagai pendokumentasian file-file atau berkas-berkas terkait project yang dibuat, yang nantinya akan dijadikan sebagai suatu acuan.
1.2 Lingkup 
		Aplikasi Sistem Informasi pasien pada study kasus Dr. Jamil Berbasis Android ini adalah sebuah aplikasi yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil. Praktek Dr. Jamil merupakan salah satu layanan praktek dokter yang ada di Indramayu, Jawa Barat.
1.3 Definisi, Istilah dan Singkatan
	


	Tabel 1. Daftar Definisi dan Akronm
	
|Kata Kunci |Definisi atau Akronim  |
|--|--|
| SRS | Software Requirement Specification		 |
| SKPL		 	| Spesifikasi Kebutuhan Perangkat Lunak, Merupakan Dokumen hasil analis yang berisi spesifikasi kebutuhan user				 		|
 |RPL			| Rekayasa Perangkat Lunak, Kegiatan pengembangan perangkat lunak	|


	tabel 2. Daftar Istilah
	
| Kata Kunci  | Definisi atau Akronim |
|--|--|
| 	 Android	| sistem operasi berbasis Linux yang dirancang untuk perangkat bergerak layar sentuh seperti telepon pintar dan komputer tablet |
| 	 web		|suatu ruang informasi yang dipakai oleh pengenal globalyang disebut Pengidentifikasi Sumber Seragam untuk mengenal pasti sumber daya berguna |
	

1.4 Referensi
IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998. dan  https://openlibrary.telkomuniversity.ac.id/pustaka/files/97623/resume/sistem-informasi-pelayanan-pasien-pada-klinik-permata-raya-bandung.pdf [PDF]sistem informasi pelayanan pasien pada klinik permata ... - Open Library  yang akan dijadikan sebagai acuan untuk pembuatan project
	

1.5 Deskripsi Umum Dokumen (Ikhtisar)
		pada Bab pertama yaitu menjelaskan tentang aplikasi atau project yang akan dibuat. Bab berikutnya, bagian Uraian Keseluruhan, dari dokumen ini memberikan gambaran umum tentang sistem yang akan dibuat dan alur dari sistemnya. dan bab yang ketiga yaitu menjelaskan gambaran umum fungsi fungsi dari setiap user diantaranya yaitu fungsi sebagai admin, dokter, dan apotek. 
2. Gambaran Umum
	Aplikasi sistem informasi pasien dengan study kasus Dr. Jamil Berbasis Android adalah sebuah aplikasi
    yang ditujukan untuk mempermudah dalam proses pendataan pasien dan pendataan obat yang terdapat pada apotek, 
    aplikasi ini lebih dikhususkan untuk sistem yang terdapat pada Praktek Dr. Jamil.
    Aplikasi ini terdapat 4 user, yaitu diantaranya :
	1. Admin	 	: Input data pasien
	2. Dokter	: Input data pasien dan insert resep dokter
	3. Apotek	: View data pasien,input resep obat dan input harga

  2.1 Perspektif produk (Perbandingan)
		Aplikasi yang kita buat ini adalah sistem informasi pasien dengan study kasus Dr. Jamil. Untuk perbedaan antara aplikasi Sistem Informasi Pasien dengan Study Kasus Dr. Jamilyang kami buat dengan-Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan Layanan Web (https://www.researchgate.net/publication/320519219_Rancang_Bangun_Aplikasi_Rekam_Medis_untuk_Praktik_Pribadi_Dokter_Berbasis_Android_dan_Memanfaatkan_Layanan_Web). Keunggulan dari aplikasi kami adalah, aplikasi kami terhubung dengan Apotek dan Kasir ditempat Praktek tersebut. Sedangkan Rancang Bangun Aplikasi Rekam Medis untuk Praktik Pribadi Dokter Berbasis Android dan Memanfaatkan Layanan Web ini hanya diperuntukan untuk asien yang berkonsultasi dengan Dokter, dan pada data Dokter, Dokter hanya bisa melihat dan menambahkan pasien tanpa bisa mengupdtae data pasien.
	 2.1.1 Antarmuka Sistem

| No | User |Fungsi  |
|--|--|--|
| 1 |Admin	  | menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan|
|2|Dokter|view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.|
|3|Apotek |input stok obat, view dan cetak data pasien yang sudah berobat|
		
 ![enter image description here](https://lh3.googleusercontent.com/-H5XNofHT6II/WpGTJA65rJI/AAAAAAAAAiw/J2FCAQ47OJcvy5sJCQYuMCxhkDbCHb9pwCL0BGAs/w795-d-h653-n/Dfd.jpg)
		
	 2.1.2 Atarmuka Pengguna
			 berikut ini adalah mockup dari aplikasi yang akan dibuat, yaitu diantaranya :
a. dibawah ini adalah mockup admin, untuk dashboard admin menampilkan laporan berupa grafik peningkatan jumlah pasien tiap bulannya
 ![Dashboard Admin](https://lh3.googleusercontent.com/-UsALNKxjXvo/WpGZNzS5sTI/AAAAAAAAAjs/7tiuojJ1go4Y3SLwcHT0hOfdOSINWUk5gCL0BGAs/w795-d-h612-n/dashboard+admin.png)

b. ini adalah menu input pada admin, yaitu fungsi utama admin menginputkan data pasien yang berobat 
			 ![enter image description here](https://lh3.googleusercontent.com/-M2NT_SUfy4w/WpGbN0Km1pI/AAAAAAAAAkc/73KuGZ4frYklKtC4BduCU2JoUNCjHvwYgCL0BGAs/w795-d-h612-n/input+data+pasien+%2528admin%2529.png)

c. berikut ini adalah menu login pada dokter, dimana dokter bisa view data pasien yang mudah siakses dengan android, dimana pada pict user kita bisa klik yang kemudian akan menampilkan nama pasien yang disebelahnya ada button proses. setelah tombol proses diklik mana akan sinkron dan ngelink ke menu selanjutnya.
 ![enter image description here](https://lh3.googleusercontent.com/-0AfY-A7YgLo/WpGb27VJUvI/AAAAAAAAAk4/4pxAivgt-Hc1dPx67Hvpb9bdc2WqtroXgCL0BGAs/w795-d-h651-n/login+dokter+dan+view+pasien.PNG)

d. selanjutnya ada menu yang ,enampilkan perintah proses yaitu tampilan view biodata pasien,yang kemudian ketikas dokter sudah view data pasien maka dokter akan input resep, nah didalam menu resep dokter ada 2 button yaitu button obat sama proses. dokter bisa dengan mudah input resep obat, yang selanjutnya akan menglink ke bagian apotek ketika resep sudah disimpan. 
 ![enter image description here](https://lh3.googleusercontent.com/-trOICIsRZzA/WpGdG-7YYFI/AAAAAAAAAls/PFhAOVoe1N8_Diu86eMdSn6MdJ7BtFYggCL0BGAs/w572-d-h477-n/data+pasien+dan+resep+obat.PNG)
e. berikut penjelasannya button **obat** akan menampilkan stok obat yang ada di apotek, sehingga dokter dengan mudah memantau stok obat yang tersedia. kemudian untuk button **proses** data akan tersimpan secara otomatis ke data apotek 
 ![enter image description here](https://lh3.googleusercontent.com/-FrORJLGulzg/WpGeTu1A4uI/AAAAAAAAAmk/OX70BtUlOyQ7Zq2yd6A1zfAbfV8EP_SigCL0BGAs/w795-d-h653-n/view+stok+obat+dan+data+pasien.PNG)

f. dibawah ini adalah menu buat apotek, dimana fungsi utama apotek yaitu menginput stok obat yang terdapat pada apotek tersbut, kemudian bisa view resep obat dan view data pasien, kemudian setelah menerima kiriman dari dokter, maka resep dokter itu akan secara default tercetak kemudian pasien tinggak registrasi kepada kasir. sehingga mempermudah dalam proses ttransaksi pembayaran dan pendataannya juga, khususnya pendataan pasien dan obat 
 ![enter image description here](https://lh3.googleusercontent.com/-V2kNv3gGh7Q/WpGf7svxW9I/AAAAAAAAAnQ/MEmtUcEqQ0IYRTZvTP1sQOA2C-IpT4pwwCL0BGAs/w795-d-h692-n/login+apotek+dan+input+stok+obat.PNG)
	 2.1.3 Antarmuka Perangkat Keras (Hardware)
	 Dibawah ini adalah  antar muka hardware.
	 Admin :menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan.
	 Dokter : view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.
	 Apotek :input stok obat, view dan cetak data pasien yang sudah berobat
	 ![enter image description here](https://lh3.googleusercontent.com/-Vm8DM0x7o0A/WpJ6cgU_uMI/AAAAAAAAARQ/FrchoGJ_Xo8kTTH0iRZfmX1OFu1-cbfYwCL0BGAs/w530-d-h275-n/usecase.png)
	 
2.2 Fungsi-fungsi produk 
![enter image description here](https://lh3.googleusercontent.com/-pr6PIJurEGg/WpJqtSlhMfI/AAAAAAAAAp0/mIqkzS9s8pQZY_Ab17ZwJvQJSdZhbEnDwCJoC/w795-h627-n/use+case.jpg)

| No | User |Fungsi  |
|--|--|--|
| 1 |Admin	  | menginput Data pasien yang terdiri dari Nama Pasien, NIK, Alamat, No Telp, Umur dan Keluhan|
|2|Dokter|view data pasien, input resep dokter, Pada Menu ini, tedapat Data Pasien yang sudah terhubung dengan Admin. Dimana Data Pasien ini berisi Nama Pasien, NIK,Umur, No Telp dan Keluhan si Pasien. Disini Dokter hanya bisa melihat saja dan untuk megefisiensikan waktu,Dokter bisa klik tombol search untuk mencari.|
|3|Apotek |input stok obat, view dan cetak data pasien yang sudah berobat|
3. Kebutuhan lain yang spesifik 
	3.1 Kebutuhan antarmuka eksternal
		3.1.1 Antarmuka pemakai 
					 dokter dan apotek sebagai user yang dapat mengoperasikan  	aplikasi sistem informasi pasien pada study kasus Dr. Jamil dengan menggunakan smartphone yang berupa android.
		3.1.2 Antarmuka perangkat lunak
	Aplikasi dapat diakses jika terhubung dengan internet dan memiliki OS android
	3.2 Kebutuhan Fungsional 
		3.2.1 Aliran informasi 
			3.2.1.1 DFD
	![enter image description here](https://lh3.googleusercontent.com/-H5XNofHT6II/WpGTJA65rJI/AAAAAAAAAiw/J2FCAQ47OJcvy5sJCQYuMCxhkDbCHb9pwCL0BGAs/w795-d-h653-n/Dfd.jpg)
	
			3.2.1.2 Flowchart 
	![enter image description here](https://lh3.googleusercontent.com/FbMisA8lRJADXeOnisOfOBfsdTMChc0GyclLf7_GSXtGnRTzzLIGN-Il63nDR84i6zfuq5VhnMHp=s600 "flowchart")
	3.3 Pemodelan data 
![enter image description here](https://lh3.googleusercontent.com/vMNrVRPLzCFx4mPb5LV3yTdk26-hHYnKfXb7wwUjVnr188lNZwwdfthI3Bj4xcv5hHyzfuD4wXDg=s600)

