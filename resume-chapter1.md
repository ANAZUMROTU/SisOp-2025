# Resume Chapter 1: 1.34 - 1.40

Name: Ana Zumrotu Nailir Rif Ah

NRP: 3124521005

Class: 1 TI A


## TRANSISI DARI MODE PENGGUNA KE MODE KERNEL  

Transisi dari mode pengguna ke mode kernel terjadi Ketika :
1.	Sebuah proses membuat permintaan layanan system operasi.
2.	Sebuah interupsi perangkat keras terjadi (misalnya, klik ke mouse)
3.	Sebuah pengecualian terjadi (misalnya, pembagian oleh nol)

## MANAJEMEN PROSES
Proses adalah program yang sedang dijalankan. Program adalah entitas pasif, sedangkan proses adalah entitas aktif. Proses membutuhkan sumber daya untuk menyelesaikan tugasnya menggunakan CPU, memori, I/O, file.
Proses single-threaded memiliki satu penghitung program yang menentukan, yaitu lokasi instruksi berikutnya yang akan dieksekusi Proses mengeksekusi instruksi secara berurutan, satu per satu, hingga selesai.
Sedangkan Proses multi-threaded memiliki satu penghitung program per thread, Biasanya sistem memiliki banyak proses, beberapa pengguna, beberapa sistem operasi yang berjalan secara bersamaan pada satu atau lebih CPU

## AKTIVITAS MANAJEMEN PROSES

System operasi bertanggung jawab untuk aktivitas berikut yang berkaitan dengan manajemen proses, yaitu :
1.	membuat dan menghapus proses
2.	menangguhkan dan melanjutkan proses
3.	menyediakan mekanisme untuk sinkronasi proses
4.	menyediakan mekanisme untuk komunikasi proses
5.	menyediakan mekanisme untuk penanganan kebuntuan






## MANAJEMEN MEMORI

Untuk menjalankan suatu program, semua (atau sebagian) instruksi harus berada di dalam memori Semua (atau sebagian) data yang dibutuhkan oleh program harus ada di memori.
Kegiatan manajemen memori, antara lain :
1.	Melacak bagian memori mana yang sedang digunakan
2.	digunakan dan oleh siapa
3.	Memutuskan proses (atau bagian-bagiannya) dan data mana yang akan dipindahkan ke dalam dan keluar dari memori
4.	Mengalokasikan dan mendealokasi ruang memori sesuai kebutuhan

## MANAJEMEN SISTEM BERKAS

OS menyediakan tampilan penyimpanan informasi yang seragam dan logis.
Setiap media dikontrol oleh perangkat (misalnya, disk drive, tape drive). Properti yang bervariasi meliputi kecepatan akses, kapasitas, laju transfer data, metode akses (berurutan atau acak).
File biasanya diatur dalam direktori, Kontrol akses pada sebagian besar sistem untuk menentukan siapa yang dapat mengakses.
Kegiatan OS meliputi :
1.	Membuat dan menghapus file dan direktori
2.	Primitif untuk memanipulasi file dan direktori
3.	Memetakan file ke penyimpanan sekunder
4.	Cadangkan file ke media penyimpanan yang stabil (non-volatil)

## MANAJEMEN PENYIMPANAN MASAL

Biasanya disk digunakan untuk menyimpan data yang tidak muat di memori utama atau data yang harus disimpan dalam jangka waktu “lama”. Seluruh kecepatan operasi komputer bergantung pada subsistem disk dan algoritma, aktivitas sistem operasi :
1.	emasang dan melepas
2.	Manajemen ruang bebas
3.	Alokasi penyimpanan 
4.	Penjadwalan disk

## COACHING (PENYIMPANAN SEMENTARA)

Prinsip penting, dilakukan di banyak level dalam computer (dalam perangkat keras, sistem operasi, perangkat lunak). Informasi yang digunakan disalin dari penyimpanan yang lebih lambat ke penyimpanan yang lebih cepat, untuk sementara Penyimpanan yang lebih cepat (cache) diperiksa terlebih dahulu untuk menentukan apakah informasi ada di sana.
Jika ya, informasi digunakan langsung dari cache (cepat). Jika tidak, data disalin ke cache dan digunakan di sa
