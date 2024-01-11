![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/cover.png)

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
1. https://www.researchgate.net/publication/350967595_Sistem_Informasi_Penerimaan_Peserta_Didik_Baru_Berbasis_Web
2. https://media.neliti.com/media/publications/293445-sistem-informasi-penerimaan-peserta-didi-edf62154.pdf
3. https://github.com/jakariaaa27/RPL-D-1/blob/master/SRS.md?plain=1

1.5 Overview
---------
Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi dibidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari-hari.
Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah didaerah Pekanbaru. Kasus yang kami peroleh pembuatan laporan penerimaan siswa baru. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah dengan menerapkan sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II . Sehingga memudahkan dalam menginputkan data-data calon siswa. Software yang kami buat ini berbasis website dimana panitia PSB sebagai admin dan calon siswa. Berikut akan kami jelaskan sistem software kami, panitia PSB fungsi utama yaitu : 
1. Verifikasi biodata dan dokumen calon siswa
2. Seleksi Siswa
3. Pengumuman hasil seleksi
4. Pendaftaran siswa yang diterima
5. Pengelolaan data siswa
6. Komunikasi dengan calon siswa

Berikut ini fungsi calon siswa dalam bentuk grafik :

1. Mengisi biodata calon siswa
2. Melengkapi dokumen
3. Mengikuti seleksi
4. Melihat hasil seleksi
5. Pendaftaran siswa yang diterima
6. Memperbarui informasi pribadi
7. Menghubungi panitia PSB

2.1 Perspektif Produk
----------
Sistem Informasi Penerimaan Siswa Baru adalah sebuah sistem administrasi data yang diaplikasikan pada website. Terdapat 2 jenis yaitu panitia PSB dan calon siswa. Pengolahan data di kelola oleh panitia PSB pada website dan calon siswa hanya bisa melakukan pendaftaran dan registrasi pembayaran.
Pada sistem informasi penerimaan siswa baru ini akan menampilkan grafik penerimaan siswa yang sudah diinputkan oleh calon siswa.

**2.1.1 Antarmuka Sistem**
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Antarmukasistem.drawio.png)

Sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II memiliki 2 user yaitu panitia PSB dan calon siswa. Panitia PSB mempunyai fungsi yaitu melakukan view grafik, bisa view laporan, mengelola data. Calon siswa untuk melakukan pendaftaran dan mengikuti seleksi

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
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/UseCaseSistemInformasiPenerimaanSiswaBaru.jpg)

**2.2.1 Panitia PSB Login**

Use Case : Login

Diagram :
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Untitled%20Diagram.drawio%20(1).png)

Deskripsi Singkat
Panitia PSB memerlukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses atau gagal, Panitia PSB dapat mencoba lagi atau mengatur ulang kata sandi jika perlu.

Deskripsi langkah-langkah
1. Panitia PSB membuka halaman login sistem.
2. Panitia PSB memasukkan username dan password mereka.
3. Sistem memeriksa kecocokan informasi login yang dimasukkan dengan data yang ada di basis data.
4. Jika informasi login benar, sistem memberikan akses penuh ke fitur dan fungsi khusus yang hanya dapat diakses oleh panitia PSB.

Xref: Bagian 3.2.1, Login Panitia PSB

**2.2.2 Panitia PSB mengelola verifikasi dokumen**

Use Case : Mengelola verifikasi dokumen

Diagram :
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-2%20(1).jpg)

Deskripsi Singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola verifikasi dokumen yang diajukan oleh calon siswa sebagai bagian dari proses pendaftaran. Tujuannya adalah untuk memeriksa dan memvalidasi dokumen-dokumen yang diterima dari calon siswa.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Verifikasi Dokumen" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah mengajukan dokumen pendaftaran.
3. Panitia PSB memilih calon siswa yang akan diperiksa dokumennya.
4. Panitia PSB memeriksa dokumen yang diajukan oleh calon siswa, seperti akte kelahiran, rapor sekolah, dan dokumen lainnya.
5. Panitia PSB memutuskan apakah dokumen tersebut lengkap, valid, dan memenuhi persyaratan penerimaan.
6. Sistem mencatat hasil verifikasi dokumen dan status calon siswa yang bersangkutan.

Xref: Bagian 3.2.2, Mengelola Verifikasi Dokumen

**2.2.3 Panitia PSB Seleksi Siswa**

Use Case : Seleksi Siswa

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-3.jpg)

Deskripsi Singkat
Seleksi siswa yang dilakukan oleh panitia Penerimaan Siswa Baru (PSB) untuk menentukan apakah calon siswa memenuhi kriteria yang diperlukan untuk diterima dalam sekolah. Tujuannya adalah untuk menilai kemampuan dan kelayakan calon siswa.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Seleksi Siswa" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah melewati tahap verifikasi dokumen.
3. Panitia PSB meninjau data pendaftaran calon siswa, termasuk hasil tes atau kriteria seleksi yang telah diterapkan.
4. Panitia PSB menilai calon siswa berdasarkan tes, wawancara, atau kriteria seleksi lainnya.
5. Panitia PSB memutuskan apakah calon siswa diterima atau ditolak berdasarkan hasil seleksi.

Xref: Bagian 3.2.3, Seleksi Siswa

**2.2.4 Panitia PSB Mengelola Pengumuman Hasil Seleksi**

Use Case : Mengelola Pengumuman Hasil Seleksi

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-4.jpg)

Deskripsi singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola dan mempublikasikan hasil seleksi calon siswa kepada calon siswa dan orang tua/wali. Tujuannya adalah untuk memberikan transparansi dan memberitahu calon siswa tentang status seleksi mereka.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Hasil Pengumuman Seleksi" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah melewati tahap seleksi.
3. Panitia PSB memasukkan hasil seleksi untuk masing-masing calon siswa, menunjukkan apakah mereka diterima atau ditolak.
4. Sistem menghasilkan pengumuman hasil seleksi dan mempublikasikannya melalui website atau media lainnya yang dapat diakses oleh calon siswa dan orang tua/wali.

Xref: Bagian 3.2.4, Mengelola Pengumuman Hasil Seleksi

**2.2.5 Panitia PSB Mengelola Data Siswa**

Use Case: Mengelola Data Siswa

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-6.jpg)

Deskripsi singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola data siswa yang mendaftar untuk penerimaan siswa baru. Tujuannya adalah untuk mengumpulkan, menyimpan, dan mengelola informasi pribadi dan akademik calon siswa. 

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Data Siswa" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah mendaftar untuk penerimaan siswa baru.
3. Panitia PSB dapat menambahkan data siswa baru, termasuk informasi pribadi dan akademik, ke dalam sistem.
4. Panitia PSB dapat memperbarui atau mengedit data siswa yang sudah ada jika diperlukan.
5. Panitia PSB dapat menghapus data siswa jika diperlukan, misalnya jika ada duplikasi atau kesalahan.

Xref : Bagian 3.2.5, Mengelola Data Siswa

**2.2.6 Panitia PSB Mengelola Biaya Pendaftaran**

Use Case : Mengelola Biaya Pendaftaran

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-7.jpg)

Deskripsi singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola biaya pendaftaran yang diperlukan dari calon siswa sebagai bagian dari proses penerimaan siswa baru. Tujuannya adalah untuk memantau, mengumpulkan, dan mengelola pembayaran biaya pendaftaran.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Biaya Pendaftaran" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah mendaftar dan membayar biaya pendaftaran.
3. Panitia PSB dapat memeriksa status pembayaran biaya pendaftaran untuk masing-masing calon siswa.
4. Panitia PSB dapat mencatat pembayaran yang diterima dari calon siswa.
5. Panitia PSB dapat mengirimkan pemberitahuan kepada calon siswa yang belum membayar atau memberikan informasi tambahan tentang cara membayar biaya pendaftaran jika diperlukan.

Xref : Bagian 3.2.6, Mengelola Biaya Pendaftaran

**2.2.7 Panitia PSB Mengelola Bantuan Online**

Use Case : Mengelola Bantuan Online

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-8.jpg)

Deskripsi singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola bantuan online yang diberikan kepada calon siswa yang memerlukan bantuan atau informasi tambahan dalam proses penerimaan siswa baru. Tujuannya adalah untuk memberikan layanan bantuan dan dukungan online kepada pemohon.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Bantuan Online" dalam antarmuka sistem.
2. Sistem menampilkan daftar permintaan bantuan online yang diterima dari calon siswa.
3. Panitia PSB dapat meninjau dan merespons permintaan bantuan online dengan memberikan informasi atau solusi yang sesuai.
4. Sistem mencatat tanggapan atau bantuan yang diberikan kepada pemohon.

Xref : Bagian 3.2.7, Mengelola Bantuan Online

**2.2.8 Calon Siswa Login**

Use Case : Login

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-19.jpg)

Deskripsi Singkat
Proses  login yang dilakukan oleh calon siswa yang telah mendaftar untuk penerimaan siswa baru. Tujuannya adalah untuk memberikan akses ke informasi dan status pendaftaran mereka serta mengikuti perkembangan selama proses penerimaan.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman login sistem.
2. Calon Siswa memasukkan username dan password yang telah mereka daftarkan sebelumnya.
3. Sistem memeriksa kecocokan informasi login yang dimasukkan dengan data yang ada di basis data pendaftaran.
4. Jika informasi login benar, sistem memberikan akses ke informasi pendaftaran, status seleksi, dan komunikasi terkait.

Xref: Bagian 3.2.8, Login

**2.2.9 Calon Siswa Melihat Profil Sekolah**

Use Case : Melihat Profil Sekolah

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-9.jpg)

Deskripsi singkat
Calon siswa yang berpotensial dapat melihat profil sekolah yang mencakup informasi tentang sejarah sekolah, fasilitas, program pendidikan, prestasi, dan informasi umum lainnya. Tujuannya adalah memberikan pemahaman kepada calon siswa dan orang tua/wali tentang sekolah yang mereka pertimbangkan untuk penerimaan siswa baru.

Deskripsi langkah-langkah
1. Calon Siswa mengunjungi situs web sekolah
2. Mereka menjelajahi bagian "Profil Sekolah" atau "Tentang Kami" yang disediakan dalam antarmuka.
3. Sistem menampilkan informasi tentang sejarah sekolah, fasilitas, program pendidikan, prestasi, visi-misi, dan informasi umum lainnya yang relevan.
4. Calon Siswa  membaca dan mengeksplorasi informasi yang disajikan.
   
Xref: Bagian 3.2.9, Melihat Profil Sekolah

**2.2.10 Calon Siswa Melakukan Pencarian Informasi Pendaftaran**

Use Case: Melakukan Pencarian Informasi Pendaftaran

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-10.jpg)

Deskripsi singkat
calon siswa mencari informasi spesifik atau topik tertentu yang relevan dengan penerimaan siswa baru di sekolah. Tujuannya adalah untuk memberikan akses cepat dan efisien ke informasi yang dibutuhkan.

Deskripsi langkah-langkah
1. Calon Siswa membuka fitur pencarian atau kotak pencarian dalam situs web 
2. Mereka memasukkan kata kunci atau frasa yang relevan terkait dengan informasi yang mereka cari, seperti "persyaratan pendaftaran," "biaya sekolah," atau "jadwal seleksi."
3. Sistem melakukan pencarian dalam basis data informasi yang ada di situs web atau aplikasi.
4. Hasil pencarian ditampilkan dalam bentuk daftar berisi tautan atau artikel yang sesuai dengan kata kunci atau frasa yang dimasukkan.
5. Calon Siswa emilih salah satu hasil pencarian untuk membaca informasi lebih lanjut.

Xref : Bagian 3.2.10, Melakukan Pencarian Informasi Pendaftaran

**2.2.11 Calon Siswa Mengunggah Dokumen Pendaftaran**

Use Case : Mengunggah Dokumen Pendaftaran

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-11.jpg)

Deskripsi singkat
Calon siswa yang sedang mendaftar mengunggah dokumen-dokumen yang diperlukan, seperti akte kelahiran, rapor atau dokumen lainnya sebagai bagian dari proses pendaftaran. Tujuannya adalah untuk memungkinkan calon siswa untuk mengirimkan dan menyimpan dokumen secara elektronik.

Deskripsi langkah-langkah
1. Calon Siswa memasuki sistem pendaftaran atau portal penerimaan siswa baru.
2. Mereka memilih opsi untuk mengunggah dokumen pendaftaran.
3. Sistem menampilkan daftar dokumen yang diperlukan dan instruksi terkait pengunggahan.
4. Calon Siswa mengunggah dokumen-dokumen yang diminta melalui antarmuka pengunggahan.
5. Sistem memeriksa dan mengonfirmasi penerimaan dokumen.

Xref : Bagian 3.2.11, Mengunggah Dokumen Pendaftaran

**2.2.12 Calon Siswa Melihat Status Pendaftaran**

Use Case : Melihat Status Pendaftaran

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-12.jpg)

Deskripsi singkat
Calon siswa yang telah mendaftar dapat memeriksa status pendaftaran mereka, seperti apakah pendaftaran mereka telah diterima, ditolak, atau sedang dalam proses seleksi. Tujuannya adalah untuk memberikan informasi kepada calon siswa tentang perkembangan pendaftaran mereka.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman status pendaftaran di situs web atau aplikasi sekolah.
2. Mereka memasukkan informasi login yang mereka gunakan saat mendaftar atau nomor referensi pendaftaran.
3. Sistem memeriksa informasi dan menampilkan status pendaftaran calon siswa.
4. Calon Siswa dapat melihat apakah pendaftaran mereka diterima, ditolak, atau sedang dalam proses seleksi.

Xref : Bagian 3.2.12, Melihat Status Pendaftaran

**2.2.13 Calon Siswa Melihat Jadwal Seleksi**

Use Case : Melihat Jadwal Seleksi

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-13.jpg)

Deskripsi singkat
Calon siswa yang telah mendaftar untuk penerimaan siswa baru dapat melihat jadwal seleksi, termasuk tanggal, waktu, dan lokasi seleksi. Tujuannya adalah untuk memberikan informasi kepada calon siswa tentang kapan dan di mana seleksi akan berlangsung.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman jadwal seleksi di situs web atau aplikasi sekolah.
2. Mereka dapat memilih program atau tingkat pendidikan yang sesuai untuk melihat jadwal seleksi yang berlaku untuk mereka.
3. Sistem menampilkan informasi jadwal seleksi, termasuk tanggal, waktu, tempat, dan instruksi terkait.
   
Xref : Bagian 3.2.13, Melihat Jadwal Seleksi

**2.2.14 Calon Siswa Melihat Pengumuman Hasil Seleksi**

Use Case : Melihat Pengumuman Hasil Seleksi

Diagram:
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-14.jpg)

Deskripsi singkat
Calon siswa yang telah mengikuti seleksi untuk penerimaan siswa baru dapat melihat pengumuman hasil seleksi, yang mencakup apakah mereka diterima, ditolak, atau berada dalam daftar tunggu. Tujuannya adalah untuk memberikan informasi kepada calon siswa tentang hasil seleksi mereka.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman pengumuman hasil seleksi di situs web atau aplikasi sekolah.
2. Mereka memasukkan informasi login yang mereka gunakan saat mendaftar atau nomor referensi pendaftaran.
3. Sistem menampilkan hasil seleksi calon siswa, seperti apakah mereka diterima, ditolak, atau berada dalam daftar tunggu.

Xref : Bagian 3.2.14, Melihat Pengumuman Hasil Seleksi

**2.2.15 Calon Siswa Mengunggah Bukti Pembayaran**

Use Case : Mengunggah Bukti Pembayaran

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-15.jpg)

Deskripsi singkat
Calon siswa yang telah diterima dalam proses penerimaan siswa baru dapat mengunggah bukti pembayaran biaya pendaftaran atau biaya lain yang diperlukan sebagai langkah akhir dalam pendaftaran mereka. Tujuannya adalah untuk memastikan bahwa calon siswa telah membayar biaya yang diperlukan sebagai syarat penerimaan.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman pengunggahan bukti pembayaran di website pendaftaran
2. Mereka memasukkan informasi login atau nomor referensi pendaftaran yang telah diberikan kepada mereka.
3. Sistem menampilkan informasi tentang biaya yang harus dibayar dan instruksi untuk mengunggah bukti pembayaran.
4. Calon Siswa mengunggah bukti pembayaran, seperti bukti transfer atau kwitansi pembayaran, melalui antarmuka yang disediakan.
5. Sistem memverifikasi bukti pembayaran dan mencatat bahwa biaya telah dibayarkan.

Xref : Bagian 3.2.15, Mengunggah Bukti Pembayaran

**2.2.16 Calon Siswa Melihat Informasi Kontak**

Use Case : Melihat Informasi Kontak

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-16.jpg)

Deskripsi singkat
Calon siswa dapat mengakses informasi kontak sekolah, seperti alamat, nomor telepon, email, atau alamat situs web sekolah. Tujuannya adalah untuk memberikan cara mudah bagi calon siswa dan orang tua/wali untuk menghubungi sekolah jika ada pertanyaan atau keperluan lainnya.

Deskripsi langkah-langkah
1. Calon Siswa atau Orang Tua/Wali membuka halaman informasi kontak di situs web atau aplikasi sekolah.
2. Mereka menelusuri informasi kontak yang tersedia, termasuk alamat sekolah, nomor telepon, email, dan alamat situs web sekolah.
3. Informasi kontak sekolah dapat digunakan untuk menghubungi sekolah jika ada pertanyaan atau keperluan lainnya.
   
Xref : Bagian 3.2.16, Melihat Informasi Kontak

**2.2.17 Calon Siswa Melihat Bantuan Online**

Use Case : Melihat Bantuan Online

Diagram : 
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-17.jpg)

Deskripsi singkat
Calon siswa dapat mengakses layanan bantuan online, seperti FAQ (Frequently Asked Questions), panduan, atau chat dukungan, untuk mendapatkan informasi atau bantuan terkait proses penerimaan siswa baru. Tujuannya adalah untuk memberikan akses mudah kepada sumber daya yang dapat membantu pemohon dalam memahami prosedur penerimaan.

Deskripsi langkah-langkah
1. Calon Siswa membuka halaman bantuan online di website pendaftaran
2. Mereka menjelajahi sumber daya bantuan yang tersedia, seperti pertanyaan yang sering diajukan, panduan pendaftaran, atau opsi untuk menghubungi dukungan online.
3. Jika ada pertanyaan atau kebingungan, mereka dapat mencari jawaban atau meminta bantuan melalui layanan bantuan online yang disediakan.

Xref : Bagian 3.2.17, Melihat Bantuan Online

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
Maksimal penginputan ukuran gambar pada website ini adalah 2048 MB, lebih dari itu program akan muncul peringatan "Anda telah melebihi batas maksimum".

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
Logika Struktur terdapat pada bagian 3.3.1

**3.2.1 Panitia PSB Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Panitia PSB Login |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Halaman login |
| Basic Path | 1. Panitia PSB mengisi form login dengan username dan password <br> 2.Panitia PSB mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Panitia PSB dapat login dan mengakses website Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II|
| Exception Push | Username dan password salah |
      
**3.2.2 Panitia PSB mengelola verifikasi dokumen**

|  |  |
|--|--|
| Nama Fungsi | Verifikasi Dokumen |
| Xref | Bagian 2.2.2, Mengelola Verifikasi Dokumen |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II |
| Precondition | Dokumen yang diunggah harus sesuai dengan persyaratan yang telah ditentukan. |
| Basic Path | 1. Sistem menampilkan daftar dokumen yang diunggah oleh calon siswa yang perlu diverifikasi <br> 2. Panitia PSB memilih dokumen untuk diverifikasi <br> 3. Panitia PSB memeriksa kelengkapan dan keaslian dokumen yang dipilih <br> 4. Jika dokumen lengkap dan sesuai, panitia PSB mengubah status dokumen menjadi "Diterimma" dan mencatat tanggal verifikasi <br> 5. Sistem mengirim notifikasi kepada calon siswa bahwa dokumen mereka telah diterima <6> Data verifikasi disimpan dalam basis data. |
| Alternative | Tidak ada |
| Post Condition | 1. Status dokumen diperbarui dalam sistem <br> 2. Notifikasi dikirim kepada calon siswa <br> 3. Data verifikasi disimpan dalam basis data |
| Exception Push | 1. Jika dokumen tidak lengkap atau tidak sesuai, sistem mengubah status dokumen menjadi "Perlu Klarifikasi" dan mencatat tanggal verifikasi <br> 2. Sistem mengirim notifikasi kepada calon siswa bahwa dokumen perlu klarifikasi <br> 3. Jika dokumen tidak valid, sistem mengubah status dokumen menjadi "Ditolak" dan mencatat tanggal verifikasi. <br> 4.Sistem mengirim notifikasi kepada calon siswa bahwa dokumen mereka telah ditolak. |
   
**3.2.3 Panitia PSB Seleksi Siswa**

|  |  |
|--|--|
| Nama Fungsi | Seleksi Siswa |
| Xref | Bagian 2.2.3, Seleksi Siswa |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II |
| Precondition | Data calon siswa dan dokumen pendaftaran harus sudah tersedia dalam sistem. |
| Basic Path | 1. Sistem menampilkan daftar calon siswa yang telah mendaftar <br> 2. Panitia PSB memilih calon siswa yang akan diproses seleksi <br> 3. Panitia PSB melakukan proses seleksi sesuai dengan kriteria yang ditentukan <br> 4. Data hasil seleksi disimpan dalam basis data. |
| Alternative | Tidak ada |
| Post Condition | Status pendaftaran calon siswa diperbarui dalam sistem |
| Exception Push | Jika ada kesalahan sistem atau masalah teknis saat memproses seleksi, sistem harus memberikan notifikasi kepada panitia PSB dan mencatat masalah tersebut untuk tindakan selanjutnya |
   
**3.2.4 Panitia PSB Mengelola Pengumuman Hasil Seleksi**

|  |  |
|--|--|
| Nama Fungsi | Pengumuman Hasil Seleksi |
| Xref | Bagian 2.2.4, Mengelola Pengumuman Hasil Seleksi |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II |
| Precondition | Hasil seleksi calon siswa harus sudah diproses dan disimpan dalam sistem. |
| Basic Path |1. Sistem menampilkan daftar calon siswa yang telah menjalani proses seleksi <br> 2. Panitia PSB memilih calon siswa yang hasil seleksinya akan diumumkan <br> 3. Panitia PSB memasukkan informasi pengumuman, seperti apakah calon siswa diterima, ditolak, atau sedang diproses <br> 4. Sistem memperbarui status pendaftaran calon siswa sesuai dengan hasil pengumuman <br> 5. Sistem mengirim notifikasi kepada calon siswa yang hasil seleksinya diumumkan <br> 6. Data hasil pengumuman disimpan dalam basis data. |
| Alternative | 1. Jika calon siswa diterima, sistem mengirim notifikasi kepada mereka dengan instruksi selanjutnya <br> 2. Jika calon siswa ditolak, sistem mengirim notifikasi dengan pemberitahuan penolakan dan alasan jika diperlukan <br> 3. Jika calon siswa berada dalam daftar tunggu, sistem mengirim notifikasi tentang status mereka dan instruksi selanjutnya.|
| Post Condition | 1. Status pendaftaran calon siswa diperbarui dalam sistem <br> 2. Notifikasi dikirim kepada calon siswa |
| Exception Push | Jika ada kesalahan sistem atau masalah teknis saat memproses seleksi, sistem harus memberikan notifikasi kepada panitia PSB dan mencatat masalah tersebut untuk tindakan selanjutnya |
   
**3.2.5 Panitia PSB Mengelola Data Siswa**

|  |  |
|--|--|
| Nama Fungsi | Data Siswa |
| Xref | Bagian 2.2.5, Mengelola Data Siswa|
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II  |
| Precondition | Data siswa yang telah diterima dalam proses seleksi harus sudah tersedia dalam sistem.|
| Basic Path | 1. Sistem menampilkan daftar data siswa yang telah diterima <br> 2. Panitia PSB memilih data siswa yang akan dikelola <br> 3. Panitia PSB dapat melakukan berbagai tindakan, seperti memperbarui informasi kontak siswa, mengubah status penerimaan, atau menambahkan catatan tambahan <br> 4. Sistem memperbarui data siswa sesuai dengan tindakan yang diambil oleh panitia PSB <br> 5. Data perubahan disimpan dalam basis data |
| Alternative | 1. Jika ada kesalahan dalam data siswa, panitia PSB dapat memperbaiki atau mengoreksi informasi <br> 2. Jika perlu mengubah status penerimaan siswa, panitia PSB dapat mengubah status dari "Diterima" menjadi "Ditolak" atau sebaliknya <br> 3.Jika perlu menambahkan catatan atau informasi tambahan tentang siswa, panitia PSB dapat memasukkan catatan tersebut |
| Post Condition | Data siswa yang dikelola oleh panitia PSB diperbarui dalam sistem |
| Exception Push | Jika terjadi kesalahan teknis atau kegagalan saat menyimpan perubahan data, sistem harus memberikan notifikasi kepada panitia PSB dan mencatat masalah tersebut untuk tindakan selanjutnya |
   
**3.2.6 Panitia PSB Mengelola Biaya Pendaftaran**

|  |  |
|--|--|
| Nama Fungsi | Biaya Pendaftaran |
| Xref | Bagian 2.2.6, Mengelola Biaya Pendaftaran |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II |
| Precondition | Calon siswa yang telah diterima harus memiliki biaya pendaftaran yang belum terverifikasi atau terbayar |
| Basic Path | 1. Sistem menampilkan daftar calon siswa yang memiliki biaya pendaftaran yang belum terverifikasi atau terbayar <br> 2. Panitia PSB memilih calon siswa yang akan diproses pembayaran biaya pendaftaran <br> 3. Panitia PSB memeriksa status pembayaran dan biaya pendaftaran yang harus dibayarkan oleh calon siswa <br> 4. Panitia PSB dapat memasukkan informasi pembayaran, seperti tanggal pembayaran dan metode pembayaran yang digunakan <br> 5. Sistem memperbarui status pembayaran calon siswa menjadi "Terverifikasi" dan mencatat informasi pembayaran <br> 6. Sistem mengirim notifikasi kepada calon siswa yang pembayarannya telah terverifikasi <br> 7. Data pembayaran disimpan dalam basis data |
| Alternative | 1. Jika calon siswa belum membayar biaya pendaftaran, panitia PSB dapat memberikan instruksi kepada mereka untuk membayar biaya tersebut <br> 2. Jika terjadi masalah dengan proses pembayaran, panitia PSB dapat mencatat masalah tersebut dan memberikan instruksi atau bantuan tambahan |
| Post Condition | 1. Status pembayaran calon siswa diperbarui dalam sistem <br> 2. Notifikasi dikirim kepada calon siswa tentang verifikasi pembayaran |
| Exception Push | Jika terjadi kesalahan teknis atau kegagalan dalam proses pembayaran, sistem harus memberikan notifikasi kepada panitia PSB dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.7  Panitia PSB Mengelola Bantuan Online**

|  |  |
|--|--|
| Nama Fungsi | Bantuan Online |
| Xref | Bagian 2.2.7, Mengelola bantuan online |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II | 
| Precondition | Permintaan bantuan online dari calon siswa  harus telah diterima dalam sistem |
| Basic Path | 1. Sistem menampilkan daftar permintaan bantuan online yang belum ditanggapi <br> 2. Panitia PSB memilih permintaan bantuan yang akan ditangani <br> 3. Panitia PSB membaca dan memahami isi permintaan bantuan online <br> 4. Panitia PSB memberikan respon atau bantuan yang sesuai kepada pemohon melalui sistem <br> 5. Sistem mencatat respon atau bantuan yang telah diberikan <br> 6. Sistem mengirim notifikasi kepada calon siswa yang meminta bantuan online <br> 7. Data respon atau bantuan disimpan dalam basis data |
| Alternative | 1. Jika permintaan bantuan online memerlukan tindakan lanjutan atau klarifikasi, panitia PSB dapat meminta informasi tambahan dari pemohon atau memberikan instruksi selanjutnya <br> 2.Jika bantuan online tidak dapat diberikan melalui sistem, panitia PSB dapat memberikan instruksi tentang cara mendapatkan bantuan lebih lanjut |
| Post Condition | 1. Respon atau bantuan telah diberikan kepada pemohon <br> 2. Notifikasi dikirim kepada pemohon yang meminta bantuan online.
 |
| Exception Push | Jika terjadi masalah teknis dalam proses pengiriman respon atau bantuan online, sistem harus memberikan notifikasi kepada panitia PSB dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.8 Calon Siswa Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.8, Calon Siswa Login |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Halaman login |
| Basic Path | 1. Calon siswa mengisi form login dengan username dan password <br> 2. Calon siswa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Calon siswa dapat login dan mengakses website Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II|
| Exception Push | Username dan password salah |

**3.2.9 Calon Siswa Melihat Profil Sekolah**

|  |  |
|--|--|
| Nama Fungsi | Profil Sekolah |
| Xref | Bagian 2.2.9, Melihat Profil Sekolah|
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Calon siswa harus sudah masuk ke dalam sistem atau situs web dengan autentikasi yang sesuai. |
| Basic Path | 1. Calon siswa mengklik untuk melihat profil sekolah <br> 2. Sistem menampilkan halaman profil sekolah yang berisi informasi tentang sekolah, seperti visi dan misi, kurikulum, fasilitas, prestasi, dan informasi kontak, dll <br> 3. Calon siswa dapat menelusuri dan membaca informasi yang tersedia dalam profil sekolah |
| Alternative | Tidak ada |
| Post Condition | Calon siswa telah melihat profil sekolah dan mendapatkan informasi yang diperlukan |
| Exception Push | Jika ada masalah teknis dalam menampilkan halaman profil sekolah atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.10 Calon Siswa Melakukan Pencarian Informasi Pendaftaran**

|  |  |
|--|--|
| Nama Fungsi | Informasi Pendaftaran |
| Xref | Bagian 2.2.10, Melakukan Pencarian Informasi Pendaftaran |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Calon siswa harus sudah masuk ke dalam sistem atau situs web dengan autentikasi yang sesuai |
| Basic Path | 1. Calon siswa mengklik "Informasi Pendaftaran" <br> 2. Sistem menampilkan kotak pencarian yang memungkinkan calon siswa untuk memasukkan kata kunci atau pertanyaan terkait pendaftaran <br> 3. Calon siswa memasukkan kata kunci atau pertanyaan dalam kotak pencarian <br> 4. Sistem melakukan pencarian dan menampilkan hasil yang sesuai berdasarkan kata kunci atau pertanyaan yang dimasukkan <br> 5. Calon siswa dapat mengeklik hasil pencarian untuk mendapatkan informasi lebih lanjut. |
| Alternative | Jika hasil pencarian tidak memberikan informasi yang diinginkan, calon siswa dapat mencoba kata kunci atau pertanyaan lain atau menghubungi sekolah untuk bantuan tambahan |
| Post Condition | Calon siswa telah melakukan pencarian informasi pendaftaran dan mendapatkan hasil pencarian yang relevan |
| Exception Push | Jika ada masalah teknis dalam proses pencarian atau tampilan hasil pencarian, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.11 Calon Siswa Mengunggah Dokumen Pendaftaran**

|  |  |
|--|--|
| Nama Fungsi | Dokumen Pendaftaran|
| Xref | Bagian 2.2.11, Mengunggah Dokumen Pendaftaran |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Sistem harus memiliki opsi untuk mengunggah dokumen pendaftaran |
| Basic Path | 1. Calon siswa masuk ke akun mereka di dalam sistem <br> 2. Calon siswa memilih opsi untuk mengunggah dokumen pendaftaran <br> 3. Sistem menampilkan antarmuka unggah dokumen yang memungkinkan calon siswa untuk memilih dokumen dari perangkat mereka <br> 4. Calon siswa memilih dokumen yang akan diunggah <br> 5. Sistem memeriksa format dan ukuran dokumen untuk memastikan sesuai dengan persyaratan <br> 6. Jika dokumen sesuai, sistem mengunggah dokumen ke server dan mencatatnya dalam basis data <br> 7. Calon siswa menerima konfirmasi bahwa dokumen telah berhasil diunggah |
| Alternative | 1. Jika dokumen tidak sesuai dengan format atau ukuran yang diperlukan, sistem memberikan pesan kesalahan kepada calon siswa dan meminta mereka untuk mengunggah dokumen yang sesuai <br> 2. Jika terjadi masalah teknis saat mengunggah dokumen, calon siswa dapat menghubungi dukungan teknis |
| Post Condition | 1. Dokumen pendaftaran telah berhasil diunggah dan tersimpan dalam sistem <br> 2. Calon siswa menerima konfirmasi bahwa dokumen telah berhasil diunggah |
| Exception Push | Jika terjadi masalah teknis yang menghentikan proses pengunggahan dokumen, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya. |

**3.2.12 Calon Siswa Melihat Status Pendaftaran**

|  |  |
|--|--|
| Nama Fungsi | Status Pendaftaran |
| Xref | Bagian 2.2.12, Melihat Status Pendaftaran |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Status pendaftaran calon siswa harus sudah dicatat dalam sistem |
| Basic Path | 1. Calon siswa memilih opsi untuk melihat status pendaftaran <br> 2. Sistem menampilkan status pendaftaran calon siswa, termasuk apakah mereka diterima, ditolak, atau sedang proses <br> 4. Calon siswa dapat melihat informasi tambahan, seperti tanggal pemberitahuan hasil seleksi <br> 5. Calon siswa dapat mencetak atau mengunduh status pendaftaran jika diperlukan |
| Alternative | Jika calon siswa memiliki pertanyaan atau butuh bantuan lebih lanjut, mereka dapat menggunakan opsi untuk menghubungi sekolah atau panitia PSB untuk bantuan tambahan |
| Post Condition | Calon siswa telah melihat status pendaftaran mereka dan mendapatkan informasi yang diperlukan |
| Exception Push | Jika terjadi masalah teknis dalam menampilkan status pendaftaran atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.13 Calon Siswa Melihat Jadwal Seleksi**

|  |  |
|--|--|
| Nama Fungsi | Jadwal Seleksi |
| Xref | Bagian 2.2.13, Melihat Jadwal Seleksi |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Jadwal seleksi penerimaan siswa harus sudah tersedia dalam sistem |
| Basic Path | 1. Calon siswa memilih opsi untuk melihat jadwal seleksi <br> 2. Sistem menampilkan jadwal seleksi yang mencakup tanggal, waktu, tempat, dan informasi terkait lainnya <br> 3. Calon siswa dapat menelusuri jadwal seleksi dan melihat informasi yang tersedia <br> 4. Calon siswa dapat mencetak atau mengunduh jadwal seleksi jika diperlukan. |
| Alternative | Jika calon siswa memiliki pertanyaan tambahan atau butuh bantuan lebih lanjut terkait jadwal seleksi, mereka dapat menggunakan opsi untuk menghubungi sekolah atau panitia PSB untuk bantuan tambahan |
| Post Condition | Calon siswa telah melihat jadwal seleksi dan mendapatkan informasi yang diperlukan |
| Exception Push | Jika terjadi masalah teknis dalam menampilkan jadwal seleksi atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.14 Calon Siswa Melihat Pengumuman Hasil Seleksi**

|  |  |
|--|--|
| Nama Fungsi | Hasil Seleksi |
| Xref | Bagian 2.2.14, Melihat Pengumuman Hasil Seleksi |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Pengumuman hasil seleksi harus sudah diunggah dan tersedia dalam sistem |
| Basic Path | 1. Calon siswa memilih opsi untuk melihat pengumuman hasil seleksi <br> 2. Sistem menampilkan pengumuman hasil seleksi yang mencakup status calon siswa (diterima, ditolak, atau sedang diproses) <br> 3. Calon siswa dapat mengeklik pengumuman mereka untuk melihat informasi lebih lanjut, seperti alasan penolakan (jika diperlukan) <br> 4. Calon siswa dapat mencetak atau mengunduh pengumuman hasil seleksi jika diperlukan |
| Alternative | Jika calon siswa memiliki pertanyaan tambahan atau butuh bantuan lebih lanjut terkait pengumuman hasil seleksi, mereka dapat menggunakan opsi untuk menghubungi sekolah atau panitia PSB untuk bantuan tambahan |
| Post Condition | Calon siswa telah melihat pengumuman hasil seleksi dan mendapatkan informasi yang diperlukan |
| Exception Push | Jika terjadi masalah teknis dalam menampilkan pengumuman hasil seleksi atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.15 Calon Siswa Mengunggah Bukti Pembayaran**

|  |  |
|--|--|
| Nama Fungsi | Pembayaran|
| Xref | Bagian 2.2.15, Mengunggah Bukti Pembayaran |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | 1. Calon siswa harus memiliki tagihan pendaftaran yang perlu dibayar <br> 2. Sistem harus memiliki opsi untuk mengunggah bukti pembayaran |
| Basic Path | 1. Calon siswa memilih opsi untuk mengunggah bukti pembayaran <br> 2. Sistem menampilkan antarmuka unggah bukti pembayaran yang memungkinkan calon siswa untuk memilih file bukti pembayaran dari perangkat mereka <br> 3. Calon siswa memilih file bukti pembayaran yang akan diunggah <br> 4. Sistem memeriksa keabsahan bukti pembayaran dan memastikan bahwa jumlah pembayaran sesuai dengan tagihan pendaftaran <br> 5. Jika bukti pembayaran sesuai, sistem mengunggah bukti pembayaran ke server dan mencatatnya dalam basis data <br> 6. Calon siswa menerima konfirmasi bahwa bukti pembayaran telah berhasil diunggah |
| Alternative | 1. Jika bukti pembayaran tidak sesuai dengan jumlah tagihan atau tidak valid, sistem memberikan pesan kesalahan kepada calon siswa dan meminta mereka untuk mengunggah bukti pembayaran yang sesuai <br> 2. Jika terjadi masalah teknis saat mengunggah bukti pembayaran, calon siswa dapat menghubungi dukungan teknis |
| Post Condition | 1. Bukti pembayaran telah berhasil diunggah dan tersimpan dalam sistem <br> 2.Calon siswa menerima konfirmasi bahwa bukti pembayaran telah berhasil diunggah |
| Exception Push | Jika terjadi masalah teknis yang menghentikan proses pengunggahan bukti pembayaran, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.16 Calon Siswa Melihat Informasi kontak**

|  |  |
|--|--|
| Nama Fungsi | Kontak |
| Xref | Bagian 2.2.16, Melihat Informasi Kontak |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Informasi kontak sekolah atau panitia PSB harus sudah tersedia dalam sistem |
| Basic Path | 1. Calon siswa memilih opsi untuk melihat informasi kontak <br> 2. Sistem menampilkan informasi kontak yang mencakup alamat, nomor telepon, alamat email, atau informasi kontak lainnya terkait sekolah atau panitia PSB <br> 3. Calon siswa dapat mencatat atau mencetak informasi kontak jika diperlukan |
| Alternative | Jika calon siswa memiliki pertanyaan tambahan atau butuh bantuan lebih lanjut, mereka dapat menggunakan informasi kontak yang disediakan untuk menghubungi sekolah atau panitia PSB |
| Post Condition | Calon siswa telah melihat informasi kontak sekolah atau panitia PSB yang diperlukan | 
| Exception Push | Jika terjadi masalah teknis dalam menampilkan informasi kontak atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |

**3.2.17 Calon Siswa Melihat Bantuan Online**

|  |  |
|--|--|
| Nama Fungsi | Bantuan Online |
| Xref | Bagian 2.2.17, Melihat Bantuan Online |
| Trigger | Membuka website Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II|
| Precondition | Sistem harus menyediakan opsi untuk bantuan online |
| Basic Path | 1. Calon siswa memilih opsi "Bantuan Online" atau "Pusat Bantuan" <br> 2. Sistem menampilkan halaman bantuan online yang berisi informasi terkait proses penerimaan siswa baru, pertanyaan yang sering diajukan, panduan, atau tautan ke sumber informasi penting <br> 3. Calon siswa dapat menelusuri dan membaca informasi yang tersedia dalam bantuan online <br> 4. Jika calon siswa memiliki pertanyaan tambahan, mereka dapat menghubungi panitia PSB melalui informasi kontak yang disediakan dalam halaman bantuan online |
| Alternative | Jika informasi yang ditemukan dalam bantuan online tidak cukup untuk menjawab pertanyaan calon siswa, mereka dapat menggunakan opsi untuk menghubungi panitia PSB melalui informasi kontak yang disediakan |
| Post Condition | Calon siswa telah melihat bantuan online dan mendapatkan informasi yang diperlukan |
| Exception Push | Jika terjadi masalah teknis dalam menampilkan halaman bantuan online atau mengakses informasi, sistem harus memberikan notifikasi kepada calon siswa dan mencatat masalah tersebut untuk tindakan selanjutnya |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**

Struktur data logika pada Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-ERD.jpg)

**Tabel Calon Siswa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_calon_siswa| varchar | Nomor auto increment Id_calon_siswa |
| Email | varchar | Alamat email calon siswa. Dapat digunakan untuk komunikasi dan verifikasi |
| NISN | int | Nomor unik yang dikeluarkan oleh pemerintah yang digunakan untuk mengidentifikasi siswa secara nasional |
| Nama_lengkap | varchar | Nama lengkap calon siswa |
| Jenis_kelamin | varchar | Jenis kelamin calon siswa  |
| Tempat_tanggal_lahir | varchar | Tempat dan tanggal lahir calon siswa |
| Agama | varchar | Agama atau kepercayaan calon siswa |
| Alamat | varchar | Alamat tempat tinggal calon siswa |
| Anak_ke | varchar | Urutan calon siswa dalam keluarga, misalnya, "anak ke-2." |
| Sekolah_asal | varchar | Nama sekolah asal yang dihadiri oleh calon siswa sebelumnya |
| Nama_orangtua | varchar |Nama orang tua calon siswa|
| No_Telp_OrangTua | varchar | Nomor telepon yang dapat dihubungi untuk menghubungi orang tua calon siswa |
| Kartu_keluarga | varchar | Dokumen kartu keluarga yang mungkin digunakan sebagai bukti identitas atau alamat |
| Akte_kelahiran | varchar | Dokumen akte kelahiran calon siswa |
| Ijazah_terakhir | varchar | Dokumen ijazah terakhir yang mungkin diperlukan sebagai syarat pendaftaran |
| Raport | varchar |  Dokumen raport atau catatan akademis dari sekolah sebelumnya |
| Pas_photo | varchar | Foto calon siswa yang digunakan untuk keperluan identifikasi |
| Status_penerimaan | varchar | Status penerimaan siswa|
| Tanggal_penerimaan | date | Tanggal ketika siswa diterima resmi |

**Tabel Seleksi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_seleksi | varchar | Nomor auto increment Id_seleksi |
| Jenis_seleksi | varchar |  Menyatakan jenis seleksi atau tes yang dilakukan, misalnya, "Tes Tulis," "Wawancara," "Psikotest" |
| Tanggal_seleksi | date | Tanggal ketika seleksi dilakukan |
| Waktu_seleksi | time | Jam atau waktu kapan seleksi dilakukan |
| Tempat_seleksi | varchar | Lokasi atau tempat di mana seleksi dilakukan, misalnya "Gedung Sekolah XYZ." |
| Hasil_seleksi | varchar | Hasil atau status seleksi calon siswa, seperti "Lulus" atau "Tidak Lulus." Apakah calon siswa diterima berdasarkan hasil seleksi tersebut |

**Tabel Panitia PSB**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_panitia_psb | varchar | Nomor auto increment Id_panitia_psb |
| Email_panitia_psb | varchar | Alamat email panitia PSB, digunakan masuk ke sistem atau portal panitia PSB |
| Nama_panitia_psb | varchar | Nama lengkap panitia PSB |
| Password_panitia_psb | varchar | Kata sandi  yang digunakan oleh panitia PSB untuk mengamankan akun mereka |

**Tabel Soal**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_soal| varchar| Nomor auto increment Id_soal |
| Kategori_soal | varchar | Kategori atau subyek tertentu yang terkait dengan soal, seperti matematika, bahasa Inggris, atau kategori lainnya |
| Materi_soal | varchar | Materi atau topik yang diuji oleh soal tersebut |
| Deskripsi_soal | varchar| Deskripsi atau teks soal yang berisi pertanyaan atau tugas yang harus dijawab oleh calon siswa |
| Kunci_jawaban | varchar | Jawaban yang benar atau kunci jawaban untuk soal tersebut, terutama relevan untuk soal pilihan ganda |
| Skor_maksimal | int | Skor maksimal yang dapat diperoleh oleh calon siswa jika mereka menjawab dengan benar|
| Waktu_pengerjaan| int | Waktu yang diberikan untuk menjawab soal |
| Gambar Soal | varchar | Jika soal memerlukan gambar atau ilustrasi, atribut ini bisa berisi tautan atau referensi ke gambar tersebut |

Bab 3.4 Validasi Data
----------

**3.4.1 JobDesk**

| Nama | JobDesk |  
| ------ | ------ |
| Daud Markhesywan | Design |
| Denisa Ruthdiani Siagian | SRS |
| Desfian Zahta Gunawan | Design |

**3.4.2 Dokumentasi Wawancara**
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Dokumentasi%20Wawancara%201.jpg)
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Dokumentasi%20Wawancara%202.jpg)

