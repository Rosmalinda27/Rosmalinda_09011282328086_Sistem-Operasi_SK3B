<h1> LAPORAN PRAKTIKUM 1 SISTEM OPERASI </h1>
<h2> PENDAHULUAN </h2>
<h3> LATAR BELAKANG </h3>
<P> Program yang digunakan sebagai jembatan atau penghubung antara pengguna dan perangkat keras adalah Sistem Operasi. Sistem operasi merupakan hal yang paling penting dari perangkat lunak dalam system Komputer. Oleh karena itu, Perangkat keras komputer dapat berfungsi dan memberikan akses bagi aplikasi untuk berjalan. Sistem Operasi mengelola sumber daya system seperti memori, prosesor, dan perangkat input/output. Fungsi dasar Sistem Operasi ialah manajemen proses, manajemen memori, sistem file, serta control perangkat. </P> 
<P> Salah satu sistem operasi yang paling banyak digunakan didunia saat ini adalah Linux. Linux merupakan sistem operasi open-source yang dikenal karena fleksibilitasnya, dan keamanan yang tinggi. Linux menyediakan berbagai distribusi, seperti Ubuntu, Fedora, dan CentOS. Pada praktikum ini distribusi yang digunakan ialah Ubuntu. Dengan praktikum ini, kita diharapkan dapat memahami dasar-dasar sistem operasi Linux termasuk cara instalasi nya dan menganalisis proses instalasi sistem operasi linux. </P>
<h3> TUJUAN </h3>
1.	Mengetahui prosedur instalasi pada sistem operasi Linux. <br/>
2.	Mampu menjalankan instalasi melalui Graphic User Interface (GUI) maupun Command Line Linux. <br/>
3.	Mampu menganalisis proses instalasi sistem operasi Linux. <br/>
<h3> ALAT DAN BAHAN </h3>
1. Laptop <br/>
2. Ubuntu 24.04 LTS <br/>
3. Virtual box <br/>
<h3> DASAR TEORI </h3>
<P> Sistem Operasi adalah program yang mengelola perangkat keras komputer dan menyediakan akses bagi program aplikasi di perangkat lunak. Perangkat keras tidak bisa digunakan secara efisien apabila tidak ada sistem operasi karena sistem operasi sendiri mengelola berbagai tugas dasar yang diperlukan oleh komputer dalam menjalankan program. Sistem Operasi berfungsi sebagai manajemen sumber daya komputer, mengatur sistem kerja perangkat, menghubungkan hardware dan pengguna, dan lain sebagainya. </P>
<p> Linux adalah Sistem operasi open-source yang berfungsi sebagai penghubung antara perangkat lunak dan perangkat keras. Linux dapat dikendalikan oleh satu atau lebih antarmuka perintah (Command Line Interface) berbasis teks, antarmuka pengguna grafis. Pengguna linux juga dapat memilih komponen inti, seperti sistem yang dapat menampilkan grafik, ataupun komponen antarmuka pengguna lainnya. </p>

<h2> PEMBAHASAN </h2>
<h3> Proses Instalasi Ubuntu </h3>
1.	Download Ubuntu 24.04 LTS di google lalu download rufus ( karena menggunakan flash disk sehingga membutuhkan rufus untuk memindahkan ubuntu ). Setelah itu atur penyimpanan yang ingin dipisahkan di Disk Management sebesar 50 GB untuk penyimpanan linux nya nanti. <br/>
2.	Atur di bios untuk pengaturan booting lalu untuk secure boot nya di disabled. <br/>
3.	Setelah booting selesai akan muncul pilihan seperti gambar dibawah, lalu Pilih Try or Install Ubuntu untuk menginstall ubuntunya. <br/>
<img src="https://github.com/user-attachments/assets/9ce81d3a-7b16-4678-9e6e-c72119d7fb23" width=500/>
<br/>
4. Lalu pilih English untuk pilihan bahasanya lalu kemudian next. <br/>
<img src="https://github.com/user-attachments/assets/b4cca571-5fe0-4542-8cf5-fd625f777895" width=500/>
<br/>
5.	Untuk tampilan ini langsung di next saja. <br/>
<img src="https://github.com/user-attachments/assets/2a0a0da3-56fe-4093-ad36-0d1a6e307d5a" width=500/>
<br/>
6. Untuk pilihan keyboard layout pilih English(US). <br/>
<img src="https://github.com/user-attachments/assets/318f9d55-b031-4453-a7ff-1563ef33d988" width=500/>
<br/>
7.	Untuk connect to internet boleh pilih use wired connection jika ingin langsung terhubung ke internet. <br/>
<img src="https://github.com/user-attachments/assets/a3e7eb05-6824-40b0-a945-5cb2128a50fe" width=500/>
<br/>
8.	Lalu pilih Install Ubuntu karena kita memang ingin menginstall ubuntu. <br/>
<img src="https://github.com/user-attachments/assets/89ab7e0a-6ae4-4a4d-af4e-7a1d2f73ca9c" width=500/>
<br/>
9.	Lalu pilih interactive Ubuntu, pilihan ini dipilih karena lebih aman dan mudah bagi para pengguna yang belum pernah melakukan instalasi sistem operasi. <br/>
<img src="https://github.com/user-attachments/assets/3726ea0a-82fa-4466-9a8d-8e6eca65dd8c" width=500/>
<br/>
10.	Lalu Pilih Default Selection ini bermaksud kita mengikuti cara install dari ubuntu nya dan tidak mensetting apapun. <br/>
<img src="https://github.com/user-attachments/assets/8cdb70ca-1103-4134-ae1b-f082541e2149" width=500/>
<br/>
11.	Lalu disini klik saja keduanya opsi ini untuk memastikan bahwa sistem operasi dapat berfungsi secara optimal. <br/>
<img src="https://github.com/user-attachments/assets/4cd88cbb-7e39-45a6-a152-a88abff4571a" width=500/>
<br/>
12.	Pilih Erase disk and Install Ubuntu, pilihan ini berarti kita menginstall ubuntu dengan menggunakan partisi hardisk sepenuhnya tanpa mengsetting secara manual. <br/>
<img src="https://github.com/user-attachments/assets/be0def6b-71fd-40f5-b2da-56e1f8b76870" width=500/>
<br/>
13)	Disini bisa diisi untuk nama dan password nya. <br/>
<img src="https://github.com/user-attachments/assets/730bc07c-10f6-49f8-b0ab-84017afad76d" width=500/>
<br/>
14.	Lalu untuk wilayah kita pilih Jakarta <br/>
<img src="https://github.com/user-attachments/assets/dbf49c94-70e1-4d17-b27d-f04ee4b27d64" width=500/>
<br/>
15.	Kemudian klik install dan tunggu hingga selesai menginstall. <br/>
<img src="https://github.com/user-attachments/assets/39be6b29-ee78-495e-84d1-050d6c231774" width=500/>
<br/>
<img src="https://github.com/user-attachments/assets/90d2919c-0b86-42ca-8344-eb27dcef09fe" width=500/>
<br/> 
16.	Sebelum ke desktop home nya pengguna akan diminta untuk memasukkan password yang sudah di buat pada saat proses instalasi Ubuntu. Ini tampilan home nya Ketika instalasi nya telah selesai. <br/>
<img src="https://github.com/user-attachments/assets/edcf8e7b-1983-4648-9de8-1f5ad7eb78d0" width=500/>
<br/>

<h3> Analisis Saat Instalasi Dipilih “/” Pada Opsi MountPoint </h3>
<p> Pada saat instalasi linux Ubuntu perlu memilih “/” (root) sebagai mount point karena direktori root adalah titik awal dari seluruh struktur file sistem di sistem operasi linux. Direktori root sendiri merupakan direktori tertinggi di sistem linux Dimana semua file dan direktori lain berada di bawah direktori ini. Seluruh sistem operasi, seperti kernel, binary, perpustakaan, dan aplikasi lainnya akan diinstal di bawah direktori root. Jika pada saat instalasi tidak memilih “/” (root) sebagai mount point maka sistem operasi tidak akan tahu dimana akan meletakkan file-file penting tersebut. Selain itu memilih “/” sebagai mount point bisa untuk partisi utama, Sehingga seluruh sistem dapat mengakses ke seluruh direktori penting seperti /home, /etc, /bin, dan lainnya. Ini juga penting agar sistem dapat berjalan dengan benar setelah instalasi. </p>

<h3>	Penjelasan Tentang Ext4, Ext3, Swap, Ntfs, Fat32, Btrfs </h3>
•	Ext4 (Fourth Extended Filesystem) : merupakan sistem file default di distribusi linux. Ext4 mendukung file dan partisi yang besar serta berbagai fitur yang akan meningkatkan kecepatan dan stabilitas. Ext4 lebih cepat dalam penulisan dan membaca data dibandingkan dengan ext3. Ext4 mendukung file hingga 16 Terabyte (TB) dan partisi 1 exabyte (EB). Selain itu ext4 juga memiliki fitur journaling yang dapat membantu dalam mencegah kerusakan data. Namun, fitur journaling ini tidak diperlukan jika untuk penggunaan sederhana. <br/>
•	Ext3 (Third Extended Filesystem) : merupakan sistem file yang cukup stabil dengan fitur journaling yang dapat melacak perubahan data sehingga lebih aman apabila terjadi crash. Namun ext3 tidak cepat dan seefisien jika dibandingkan dengan ext 4 dalam hal kecepatan dan pengelolaan ruang. <br/>
•	Swap : merupakan ruang pada hard disk yang berfungsi sebagai memori virtual pada sistem operasi apabila RAM penuh. Sehingga, sistem dapat menjalankan banyak aplikasi secara bersamaan atau aplikasi besar walaupun RAM nya terbatas. Namun swap jauh lebih lambat daripada RAM karena menggunakan disk yang dapat mengakibatkan performa sistem menurun jika swap digunakan terlalu banyak. <br/>
•	Ntfs (New Technology File System) : merupakan sistem file yang digunakan pada sistem operasi windows namun ntfs juga dapat diakses dari sistem operasi linux tetapi masih terbatas. Ntfs mendukung file besar yaitu lebih dari 4 GB dan memiliki fitur keamanan seperti enkripsi dan izin file. <br/>
•	Fat32 (File Allocation Table 32) : merupakan sistem file yang lebih tua tapi sangat kompatibel yang sering digunakan pada perangkat penyimpanan eksternal. Namun, Fat32 ini mendukung file hanya batas 4 GB dan tidak memiliki fitur keamanan. <br/>
•	Btrfs (B-tree File System) : merupakan system file linux yang mempunyai fitur-fitur canggih seperti, snapshot, dan manajemen ruang yang fleksibel. Namun btrfs sendiri masih baru sehingga masih belum secepat ext4 dalam beberapa kondisi. <br/>

<h2> PENUTUP </h2>
<h3> KESIMPULAN </h3>
<p> Sistem operasi berperan sangat penting yaitu sebagai penghubung antara perangkat lunak dan perangkat keras. Tanpa sistem operasi, perangkat keras tidak bisa bekerja secara optimal karena tidak ada yang mengatur interaksi antar komponen pada komputernya. Dengan adanya sistem operasi berbagai aplikasi dapat berjalan secara efisien dan meminimalisir gangguan. Sistem operasi yang sedang kita bahas dipraktikum ini ialah Linux. Linux sendiri memiliki banyak distribusi namun pada praktikum ini kita memakai Ubuntu. Melalui praktikum ini, Kita sudah mempelajari cara melakukan instalasi pada system operasi linux khususnya Ubuntu. Kemudian, menganalisis beberapa proses yang dilakukan pada saat instalasi.  </p>







