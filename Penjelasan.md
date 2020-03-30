![Gambar 1](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/1.png)
![Gambar 2](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/2.png)
![Gambar 3](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/3.png)
![Gambar 4](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/4.png)
![Gambar 6](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/6.png)
![Gambar 7](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/7.png)
![Gambar 8](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/8.png)
![Gambar 9](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/9.png)
![Gambar 10](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/10.png)
![Gambar 11](https://github.com/Myayanwahyudi/UTS_TCC/blob/master/11.png)

)PENJELASAN

CATATAN :
	Pada pengistalan docker aplikasi ini,di sini saya menggunkan peralatan yaitu laptop yang sama dengan teman saya yang bernama Berliando dikarenakan laptop yang saya gunakan untuk mengistal aplikasi docker tidak komputen, dengan kapasitas laptop saya,jadi pada bagian terminal (editor text) masih tercantum nama penggunanya berliando.Tetapi tahapan dan car acara yang saya gunakan untuk menjalankan docker hub,sepenuh nya dikerjakan oleh saya sendiri.

Gambar 1
Penjelelasan :
	Pada gambar 1 adalah salah satu contoh aplikasi docker yang sudah saya istall pada laptop dan siap untuk dijalankan

Gambar 2 
Penjelasan : 
	Ini adalah akun yang sudah saya buat di dalam aplikasi docker hub

Gambar 3
Penjelasan :
	 Dapat dilihat pada gambar ke 3 ini dibagian menu eksplor(ini adalah merupakan tempat tersedianya docker images)
	Docker images yang saya gunakan yaitu Ubuntu yaitu Versi 18.04








Gambar 4
Penjelasan : 
	Jadi gambar ke 4 ini menunjukan apakah docker images yang teristall akan tertampilkan
	Dan disini hanya cukup mengetik scrip docker images maka ouput akan menampilkan dokcker images yang pernah terpasang sebelum nya.

Gambar 5
Penjelasan : 
	Jadi pada bagian nomor 5 ini Docker images yang sudah saya pilih yaitu Ubuntu Versi 18.04 
	Dan disini saya mendownload Ubuntu versi 18.04 dengan mengetik scrip: docker pull Ubuntu:18.04
	Pada proses yang dilalui ini akan memakan waktu cukup lama karena tergantung kapasitas yang akan di download .
	Dan kesetabilan jaringan sangat berpenggaruh untuk proses pendownloadan

Gambar 6
Penjelasan : 
	Jadi pada bagian ini bisa dilihat pada gambar 6 downloadan sudah terpasang di local computer.
	Dengan mengetik scrip “Docker Images” di sini akan menampilkan output memastikan docker images sudah terpasang atau belum.

Gambar 7
Penjelasan : 
	pada tampilan gambar ke 7 disini mencoba menampilkan apakah docker container sudah terpasang atau belum
	Dengan mengetik script “docker container ls”








Gambar 8
Penjelasan : 
	Pada tampilan gambar ke 8 ini mencoba untuk menampilkan semua docker container yang pernah terpasang di locak computer “Docker Container ls”
	Dan dapat di lihat outpuy nya hanya berupa Container Id, image,Command,Created,Status,Ports,Names.

Gambar 9
Penjelasan :
	Pada tampilan gambar ke 9 ini mencoba untuk membuat docker container dengan mengetik “Docker container create –name ubuntuserver1 ubuntu:18.04”
	Dan dapat di lihat pada output menghasilkan keluaran seperti ada di gambar,Itu merupakan docker container sudah terbuat .
	Dan ketika  kita ingin mengakses maka nama file digunakan adalah nama yang ada pada keluaran output tersebut.
	Dan nama file juga bisa menggunakan “ubuntuserver1 ubuntu:18.04”
	Diantara ke 2 anam file tersebut semuanya bisa di gunakan .

Gambar 10
Penjelasan :
	Pada penjelasan gambar ke 10 ini disini sya mencoba untuk melihat apakah docker container sudah terpasang apa belum.
	Dengan mengetik “docker container ls”, Dapat di lihat docker container masih kosong kerena masih dalam proses running.

Gambar 11
Penjelasan :
	Pada penjelasan gambar ke 11 ini disini saya mencoba untuk memastikan lagi docker container yang saya buat.
	 Dengan mengetik script “docker container ls –all”,Maksud dari script ini adalah untuk mencoba menampilkan docker file yang sudah selsai running.
	Dan dapat dilihat pada outputnya docker container sudah selesai terpasang  dengan nama Ubuntu versi 18.04 (ini adalah docker images yang saya gunakan).

