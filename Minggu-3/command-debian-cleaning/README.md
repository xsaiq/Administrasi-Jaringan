# 8.6 Cleaning the system 🔍

    Nama		: Yasir Maarif
    NRP		: 3122600013
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Konsep Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

#

### 8.6.1 Disk space information

#### Command `$ df -h`

Command ini digunakan untuk **mengetahui penggunaan kapasitas disk** pada setiap _mount point_ (drive dan partisi) pada siste. <br>

<div align="center">
    <img src="assets/1.png" width="70%">
</div>

#### Command `$ du` dan `$ sort`

Digunakan untuk **mengecek seberapa _bulky_ direktori** yang terdapat pada sistem dalam satuan megabyte. <br>

<div align="center">
    <img src="assets/2.png" width="70%">
</div>

#### NCDU

Merupakan software _disk analyzer_ dalam mode konsol. Sebelum dapat menggunakan software ini harus menginstall terlebih dahulu dengan command `$ sudo apt update && sudo apt install ncdu` lalu ketikkan command `$ ncdu` untuk membukanya. <br>

<div align="center">
    <img src="assets/3.png" width="70%">
</div>

#### Baobab

Sama seperti NCDU, bedanya Baobab merupakan GUI dan terintegrasi dengan GNOME. Instalasinya sama seperti NCDU dengan mengetikkan command `$ sudo apt update && sudo apt install baobab` lalu command `$ baobab` digunakan untuk menjalankan software tersebut. <br>

<div align="center">
    <img src="assets/4.png" width="70%">
</div>

### 8.6.2 Cleaning the packages

#### Command `$ apt clean`

Command yang berfungsi untuk **membersihkan cache** dari package yang terinstall pada sistem.<br>

<div align="center">
    <img src="assets/5.png" width="70%">
</div>

#### Command `$ apt autoremove --purge`

Berfungsi untuk **menghapus package beserta file confignya** dari sistem. <br>

<div align="center">
    <img src="assets/6.png" width="70%">
</div>

#### Command `$ apt list ` dan `$ apt remove`

Berfungsi untuk **menghapus package obsolete** dari sistem. <br>

<div align="center">
    <img src="assets/7.png" width="70%">
</div>

#### Deborphan

Selain `$ apt remove`, kita juga bisa menginstall Deborphan yang berfungsi untuk **menghapus _orphaned_ package** dari sistem. <br>

<div align="center">
    <img src="assets/8.png" width="70%">
</div>
<div align="center">
    <img src="assets/9.png" width="70%">
</div>

### 8.6.3 Emptying the trash bins

#### The User Wastebasket

Berikut command untuk membersihkan trash bin milik user. <br>

<div align="center">
    <img src="assets/10.png" width="70%">
</div>

#### The Root Wastebasket

Berikut command untuk membersihkan trash bin milik user root. <br>

<div align="center">
    <img src="assets/11.png" width="70%">
</div>

### 8.6.4 Purging application caches

Beberapa aplikasi menggunakan direktori cache untuk menyimpan file grafis dan beberapa informasi lainnya supaya bisa berjalan lebih cepat. Biasanya cache tidak memakan banyak ruang disk, tetapi jika direktori cache tersebut menjadi terlalu besar maka bisa dihapus untuk menyisakan ruang disk.<br>

#### Command

Berikut adalah command untuk menghapus file cache.<br>

<div align="center">
    <img src="assets/12.png" width="70%">
</div>

### 8.6.5 Purging the thumbnails

Thumbnails merupakan representasi dari file grafis seperti gambar atau video yang disimpan pada suatu direktori untuk digunakan ulang. Hal ini dapat menimbulkan masalah ketika user menghapus suatu file grafis, dikarenakan file thumbnailsnya yang masih tersimpan dan dapat memakan ruang disk hanya untuk menyimpan file obsolete.<br>

#### Command

Berikut adalah command untuk menghapus file thumbnails.<br>

<div align="center">
    <img src="assets/13.png" width="70%">
</div>
