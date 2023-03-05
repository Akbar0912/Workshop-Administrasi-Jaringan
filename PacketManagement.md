# Package-Management 
## Evolusi OS
### Ubuntu
Ubuntu pertama kali dirilis pada tanggal 20 Oktober 2004 oleh Canonical Ltd., sebuah perusahaan yang didirikan oleh entrepreneur Mark Shuttleworth. Ubuntu awalnya didasarkan pada distribusi Debian Linux, tetapi seiring waktu telah mengembangkan identitasnya sendiri dan memperkenalkan fitur-fitur baru.
Nama 'Ubuntu' berasal dari filosofi Afrika Selatan yang mengajarkan tentang kesatuan dan persatuan antara manusia. Ubuntu didasarkan pada prinsip-prinsip ini, dan bertujuan untuk memberikan pengalaman pengguna yang lebih manusiawi dan terhubung dengan komunitas luas.
Ubuntu telah menjadi salah satu distribusi Linux yang paling populer di dunia, dan digunakan oleh jutaan pengguna di seluruh dunia. Canonical Ltd. terus mengembangkan Ubuntu dengan pembaruan berkala dan meningkatkan kinerja serta keamanannya.
### Versi Ubuntu
Versi terbaru dari Ubuntu saat ini adalah versi 20.04 LTS (Long-Term Support), yang dirilis pada bulan April 2020. Ubuntu 20.04 LTS menawarkan berbagai fitur baru, termasuk dukungan untuk teknologi terbaru dan pembaruan keamanan yang lebih baik.
### Debian
Debian adalah sistem operasi open-source yang populer berbasis pada kernel Linux. Pertama kali dirilis pada tahun 1993, Debian telah menjadi salah satu distribusi Linux yang paling stabil dan aman. Debian dirancang untuk memenuhi kebutuhan berbagai pengguna, dari pengguna rumahan hingga perusahaan besar.
Salah satu fitur utama dari Debian adalah manajemen paket yang canggih, yang memungkinkan pengguna untuk dengan mudah menginstal, menghapus, dan memperbarui perangkat lunak pada sistem mereka. Debian juga dikenal karena stabilitasnya yang tinggi dan dukungan jangka panjang untuk setiap versi.
Ubuntu sendiri didasarkan pada distribusi Debian Linux. Oleh karena itu, Ubuntu memiliki banyak kesamaan dengan Debian dalam hal manajemen paket dan stabilitas. Namun, Ubuntu menawarkan pendekatan yang lebih ramah pengguna dan lebih banyak fitur bawaan, sehingga lebih cocok untuk pengguna pemula.
Secara keseluruhan, evolusi Debian dan Ubuntu menunjukkan perkembangan yang positif untuk sistem operasi open-source berbasis Linux, dan keduanya terus berkembang dengan pembaruan berkala dan peningkatan kinerja serta keamanan.
### Versi Debian
The newest version of Debian is Debian 11 "Bullseye", which was released on August 14, 2021
## SU | SUDO | Sudo SU
### Perbedaan SU, SUDO, dan SUDO SU
Perintah su (kependekan dari substitute atau switch user) adalah perintah yang memungkinkan Anda untuk menjalankan perintah dengan hak istimewa pengguna lain, secara default sebagai root.Menggunakan su adalah cara paling sederhana untuk beralih ke akun administratif dalam sesi login saat ini.
SUDO adalah singkatan dari "superuser do". Perintah ini memungkinkan pengguna biasa untuk menjalankan perintah sebagai superuser atau root dengan memasukkan kata sandi. Dengan menggunakan SUDO, pengguna dapat menjalankan perintah yang memerlukan hak akses penuh tanpa harus keluar dari akun pengguna biasa.
SUDO SU sebenarnya tidak ada. Namun, pengguna dapat menggunakan perintah sudo su untuk masuk ke dalam akun root dengan hak akses penuh. Hal ini dapat berguna dalam situasi di mana pengguna ingin menjalankan beberapa perintah sebagai root tanpa harus keluar dari akun pengguna biasa dan masuk ke dalam akun root dengan perintah su.
Secara keseluruhan, SU, SUDO, dan SUDO SU adalah perintah yang berguna dalam mengelola dan memodifikasi sistem operasi Linux. Namun, pengguna harus menggunakannya dengan hati-hati dan hanya ketika diperlukan.
## Cara mensetting repository linux
Untuk mensetting repository pada Linux, ikuti langkah-langkah berikut:
1.	Buka terminal pada sistem Linux Anda.
2.	Jalankan perintah *sudo nano /etc/apt/sources.list* untuk membuka file sources.list.
3.	Cari baris yang berisi informasi repository yang ingin Anda tambahkan atau ubah. Baris tersebut akan terlihat seperti <deb <http://example.com/ubuntu> bionic main>.
4.	Jika ingin menambahkan repository baru, tambahkan baris baru dengan format <deb <http://example.com/ubuntu> bionic main>. Ganti http://example.com/ubuntu dengan URL repository yang ingin Anda tambahkan, dan ganti bionic dengan nama versi distribusi Linux yang Anda gunakan.
5.	Jika ingin mengubah repository yang sudah ada, ubah baris yang sudah ada dengan URL repository yang baru.
6.	Setelah selesai mengedit file sources.list, tekan Ctrl + X, lalu tekan Y untuk menyimpan perubahannya.
7.	Jalankan perintah sudo apt-get update untuk memperbarui daftar paket dan repository pada sistem Linux Anda.
Setelah selesai melakukan langkah-langkah di atas, repository yang baru ditambahkan atau diubah akan tersedia pada sistem Linux Anda.
