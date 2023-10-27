
<html>
<body>
<div align="center"><h1> Software Requirements Spesification </h1></div>

<p align="center"><b>Version 1.7 </b><br>
<p align="center">23 Oktober 2023 </b>
<p align="center">

</p>

<p align="center"><b> Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II <br>
</b>
<p align="center">Kelompok 3 <br>
Denisa Ruthdiani Siagian    (2257301031)<br>
Daud Markhesywan    (2257301030)<br>
Desfian Zahta Gunawan   (2257301032)<br><br><br>

<p align="center"><b>Jurusan Teknik Informasi</b><br>
<p align="center"><b>Politeknik Caltex Riau</b>
<p align="center"><b>2023</b>
</p>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Informasi Penerimaaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II". Dokumen ini dibangun untuk mempermudah bagi calon siswa yang akan mendaftar di SMP Al-Azhar Syifa Budi Pekanbaru II yang mengubah sistem lama secara konvensional dalam melakukan pendaftaran siswa baru tersebut menjadi secara terstruktur yaitu pendaftaran secara online. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II".

1.2   Lingkup
----------
Sistem Informasi Penerimaan Mahasiswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II merupakan aplikasi yang kami bangun untuk mempermudah proses pendaftaran calon siswa dan untuk meningkatkan efisiensi dari waktu para guru atau panitia dan calon siswa itu sendiri.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | Perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | Situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4 Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah:
-
-
-

1.5 Overview
---------
Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi dibidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari-hari.
Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah didaerah Pekanbaru. Kasus yang kami peroleh pembuatan laporan penerimaan siswa baru. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah dengan menerapkan sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II . Sehingga memudahkan dalam menginputkan data-data calon siswa. Software yang kami buat ini berbasis website dimana website sebagai admin, panitia PSB dan calon siswa. Sistem yang kami buat di dalamnya terdapat berikut adalah sistem penerimaan Al-Azhar:
1. Pendaftaran Online
2. Proses seleksi
3. Pengumuman Hasil
4. Proses Registrasi
5. Orientasi Siswa Baru
6. Pemantauan Akademik
7. Bimbingan dan Konseling
8. Pembaruan Informasi
9. Keamanan Data

Berikut ini fungsi user dalam bentuk grafik :

1. Isi biodata
2. 
3. 
4. 

2.1 Perspektif Produk
----------
Sistem Informasi Penerimaan Siswa Baru adalah sebuah sistem administrasi data yang diaplikasikan pada website. Terdapat 2 jenis yaitu panitia PSB dan calon siswa. Pengolahan data di kelola oleh panitia PSB pada website dan calon siswa hanya bisa melakukan pendaftaran dan registrasi pembayaran.
Pada sistem informasi penerimaan siswa baru ini akan menampilkan grafik penerimaan siswa yang sudah diinputkan oleh calon siswa.

**2.1.1 Antarmuka Sistem**
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/UseCaseSistemInformasiPenerimaanSiswaBaru.jpg)
Sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II memiliki 2 user yaitu panitia PSB dan calon siswa. Panitia PSB mempunyai fungsi yaitu melakukan view grafik, bisa view laporan, mengelola data. Calon siswa untuk melakukan pendaftaran dan registrasi.

**2.1.2 Antarmuka Pengguna**

**2.1.3 Antarmuka Perangkat Keras**
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/antarmukaperangkatkeras.drawio.png)
Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. Wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi atau website|
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak bukti pendaftaran |

**2.1.8 Kebutuhan adaptasi**

Tidak ada

2.2 Spesifikasi Kebutuhan fungsional
------------
  
**2.2.1 Kepala Desa Login**

**2.2.2 Kepala desa melihat laporan kependudukan**

**2.2.3 Admin login**

**2.2.4 Admin input data kependudukan**

**2.2.5 Admin melihat data kependudukan**

**2.2.6 Generate Laporan**

**2.2.7 Admin mengelola user**

2.3   Spesifikasi Kebutuhan non-fungsional
--------------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platform OS 
  
2.4   Karakteristik pengguna
--------------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem dan bisa juga dengan secara langsung tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.
  
2.6   Asumsi-asumsi
----------
2.7   Kebutuhan Penyeimbang
----------
Tidak ada

BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan hak akses yang di berikan oleh panitia PSB, login melalui website ini dengan membuat akun dengan informasi pribadi dan mengisi formulir pendaftaran. Setelah login berhasil, calon siswa dapat melihat status pendaftaran mereka setelah pendaftaran.
   
3.2 Functional Requirement
----------
**3.2.1 Kepala desa Login**

**3.2.2 Kepala desa melihat laporan kependudukan**

**3.2.3 Admin login**

**3.2.4 Admin input data kependudukan**

**3.2.5 Admin melihat data kependudukan**

**3.2.6 Cetak Laporan**

**3.2.7  Admin mengelola user**

3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**





