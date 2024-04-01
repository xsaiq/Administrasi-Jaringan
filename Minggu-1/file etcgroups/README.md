# File /etc/groups

    Nama		: Yasir Maarif
    NRP		: 3122600013
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Konsep Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

#

Di sistem Debian (dan distribusi Linux lainnya), berkas /etc/group menyimpan informasi tentang grup yang ada di sistem. Setiap baris dalam berkas ini mewakili satu entri grup dan memiliki format yang ditentukan. Berikut adalah penjelasan singkat tentang fungsi dan format dari berkas /etc/group:

### Fungsi /etc/group:

Menyimpan Informasi Grup: Berkas ini digunakan untuk menyimpan daftar grup yang ada di sistem beserta informasi terkait, seperti ID grup, anggota grup, dan informasi tambahan.

### Format /etc/group di Debian:

Setiap baris dalam berkas /etc/group mengikuti format yang terdiri dari empat kolom, yang dipisahkan oleh titik dua (:):

Nama Grup: Nama unik dari grup.\
Kata Sandi: Biasanya diisi dengan tanda x. Sebelumnya, kata sandi grup disimpan di sini, tetapi sekarang umumnya disimpan dalam berkas /etc/gshadow.\
ID Grup: Nomor identifikasi unik untuk grup.\
Anggota Grup: Daftar nama pengguna yang merupakan anggota grup, dipisahkan oleh koma.
