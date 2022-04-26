Fundamental SQL Using SELECT Statement
---

# Structured Query Language

## Apa itu SQL?
SQL yang merupakan singkatan dari Structured Query Language, yaitu bahasa komputer standar yang digunakan untuk berinteraksi dengan suatu sistem database - atau lebih tepatnya sistem manajemen database relasional. Jadi, user dapat menambahkan, mengubah, mengupdate, mencari dan menghapus data dari suatu sistem database dengan menggunakan SQL.

SQL dilafalkan dengan membaca tiap karakternya S Q L (es kiu el) atau sikuel.


## Contoh komunikasi SQL

Terdapat dua kategori dari interaksi SQL: 

Data Definition Language (DDL), yaitu berbagai perintah yang berfungsi lebih kepada memanipulasi struktur database, seperti Membuat (CREATE), meubah (ALTER), dan menghapus (DROP) struktur penyimpanan data, yaitu database, table, kolom dan tipe data.
Data Manipulation Language (DML), yaitu berbagai perintah yang digunakan untuk Menyisipkan data (INSERT), Mengambil data atau query (SELECT), Meubah data (UPDATE) dan Menghapus data (DELETE).

Berikut adalah satu contoh query atau perintah untuk mengambil data:

```sql
SELECT nama_produk FROM ms_produk;
```

```
nama_produk                        
------------------------------------
Kotak Pensil DQLab                 
Flashdisk DQLab 64 GB              
Gift Voucher DQLab 100rb           
Flashdisk DQLab 32 GB              
Gift Voucher DQLab 250rb           
Pulpen Multifunction + Laser DQLab 
Tas Travel Organizer DQLab         
Gantungan Kunci DQLab              
Buku Planner Agenda DQLab          
Sticky Notes DQLab 500 sheets
```

Terlihat ada sepuluh nama peralatan kantor dengan label DQLab yang ditampilkan. Ini menunjukkan bahwa interaksi antara SQL dan sistem database telah berjalan dengan baik.

## Mengapa Perlu Belajar SQL?

Pada dasarnya, setiap perusahaan memiliki sistem penyimpanan data, khususnya untuk perusahaan yang memiliki sistem IT. Sistem penyimpanan ini bukan di komputer atau laptop dalam bentuk file atau folder, tetapi di suatu sistem database. Nah, sistem database ini biasanya diakses menggunakan SQL. Sebagai analyst, tugas kita tidak hanya menganalisa data yang sudah tersedia tetapi juga mampu untuk mengambil, memodifikasi dan mengakses sendiri data tersebut dari sumber datanya, yaitu dari database

penguasaan SQL akan membantu perusahaan pada area berikut:

* Manajemen memerlukan laporan dengan informasi yang semakin beragam, seperti: tren penjualan bulan ke bulan, pertumbuhan pelanggan, apakah perusahaan mencapai target, dan lain-lain. Dan ini membutuhkan keahlian SQL yang mumpuni.
* Programmer yang membangun sistem aplikasi hampir dipastikan selalu bergantung kepada sistem database SQL agar aplikasinya berjalan dengan baik. Dengan demikian, penguasaan SQL adalah hal mutlak.
* Bisa meningkatkan kinerja perusahaan karena informasi yang kaya dapat dihasilkan melalui SQL.

## Dimana saja SQL Digunakan?

Perusahaan – perusahaan yang sudah menerapkan sistem IT pasti memiliki sistem database dan bisa dipastikan menyimpan datanya dalam suatu database. Contohnya perusahaan berbasis teknologi, seperti e-commerce, menyimpan data baik itu data profile user, data transaksi pembelian dan penjualan, data produk dan data traffic kunjungan user ke halaman website di sistem database - atau lebih tepatnya sistem manajemen database atau database management system (DBMS).

 

Semua informasi ataupun analisa yang dibutuhkan oleh manajemen, umumnya bersumber dan diolah dari data DBMS ini. Dan di perusahaan, sistem database biasanya tidak hanya satu, bisa dua, tiga bahkan puluhan. Oleh karena itu, SQL sangat berperan disini, karena dengan menggunakan SQL dapat memenuhi kebutuhan manajemen tersebut. Tanpa penguasaan SQL  akan kesulitan memperoleh data yang dibutuhkan, dan akan kesulitan dalam melakukan analisa dan menghasilkan informasi yang dibutuhkan manajemen dan perusahaan.

 

Akan tetapi, perlu diketahui bahwa tidak semua sistem database mendukung SQL. Hanya sistem database berbasis relational database management system (RDBMS) yang mendukung bahasa ini. Untuk RDBMS sendiri akan dijelaskan kemudian.

 

SQL hanya digunakan di sistem database berbasis Relational Database Management System.

# Sistem Database Relasional

## Apa itu RDBMS?
Relational Database Management System yang biasa disingkat dengan RDMBS adalah suatu program yang memungkinkan untuk Membuat, Memperbarui, dan Mengelola suatu basis data relasional (Relational Database). Nah, Umumnya RDMBS ini menggunakan SQL untuk mengakses database.

Basis data relasional sendiri merupakan suatu jenis database dimana data – data umumnya disimpan dalam bentuk yang terstruktur berupa tabel (baris dan kolom) dan setiap tabel/ data yang terdapat dalam database memiliki relasi (relational) satu sama lain. Seperti terlihat pada gambar berikut

![download](https://user-images.githubusercontent.com/20697667/165215133-437c9d3b-203a-48f7-8363-0ee3d363bdba.jpg)

Basis data relasional sangat popular dan banyak digunakan oleh perusahaan – perusahaan karena jenis database ini mudah dikelola terlebih jika memiliki banyak data atau informasi yang perlu disimpan, scalable dan flexibel.

* Basis data rasional cukup mudah dikelola. Setiap tabel/data dapat diupdate atau dimodifikasi tanpa mengganggu tabel/data yang lain.
* Flexible : jika perlu memperbarui data, hanya perlu melakukannya sekali saja - jadi tidak perlu lagi mengubah banyak file satu per satu. Selain itu, basis data rasional juga cukup mudah untuk di-extend. Misalnya saat data sudah semakin banyak, dapat dengan mudah memperbesar kapasitas dari database yang dimiliki.

## Produk-produk RDBMS di Pasaran
Selain MySQL, masih ada produk lain RDBMS, baik yang berbayar (proprietary) maupun open source. Berikut adalah sebagian produk yang cukup populer di pasaran :


1. MySQL

    Open-source SQL database yang cukup populer. Umumnya digunakan untuk pengembangan aplikasi web.
2. PostgreSQL
    
    Open-source RDBMS product, dan juga umumnya digunakan untuk pengembangan aplikasi web. Akan tetapi secara kinerja, postgreSQL lebih lambat dibandingkan MySQL.
3. Oracle DB
    
    Produk RDBMS yang dimiliki oleh Oracle Corporation dan produk ini bersifat proprietary atau tidak open source. Oracle DB umumnya digunakan di industri perbankan.
4. Microsoft SQL Server 

    SQL Server adalah produk RDBMS yang dimiliki oleh Microsoft dan sama seperti Oracle DB, SQL Server bersifat proprietary atau tidak open source, SQL Server umumnya digunakan di perusahaan skala besar yang juga menggunakan produk keluaran Microsoft lainnya.
5. SQLite

    Open source RDBMS, umumnya digunakan sebagai database di handphone, MP3 player, and perangkat lainnya.

Selain itu, juga ada MariaDB yang juga gratis atau open source, IBM DB2, Microsoft Access, dan masih banyak lainnya.

 ![image](https://user-images.githubusercontent.com/20697667/165215232-a98ab97c-e9dd-4048-b63f-dc37706b3033.png)

Umumnya RDBMS menggunakan SQL untuk mengakses database dan produk RDBMS tidak hanya satu macam saja tetapi ada berbagai macam produk, maka SQL syntax pun bisa jadi sedikit berbeda untuk setiap produk tersebut. Berikut contoh perbandingan MySQL, Oracle, dan SQLSERVER untuk menampilkan beberapa baris data dari suatu tabel :


## Struktur Penyimpanan RDBMS

Sebagai penyimpan data, sistem database relasional memiliki struktur hirarki objek penyimpanan sebagai berikut:

* Database
* Tabel (table)
* Kolom (column) atau Field

> Setiap database bisa berisi beberapa tabel, dan setiap tabel bisa terdiri dari beberapa kolom. Di setiap database, tabel dan kolom memiliki nama sendiri sebagai identitas mereka. Tabel dan kolom inilah yang akan diisi data yang kemudian membentuk row (baris data). 

## Tabel dan Kolom

Gambar berikut adalah contoh suatu Tabel dalam database. Karena setiap tabel dalam database memiliki nama, maka, nama tabel ini adalah ms_produk.

![image](https://user-images.githubusercontent.com/20697667/165215307-64dc51fa-11cc-4f17-9f23-9c5818284617.png)

Jika aku perhatikan, struktur tabel ms_produk terdiri dari empat kolom (column), masing-masing dengan nama berikut:

* no_urut
* kode_produk
* nama_produk
* harga

Dan dalam tabel tersebut terdapat 10 baris data (row) dengan isi data yang bervariasi, contoh isi data untuk kolom "nama_produk" pada baris kelima adalah "Gift Voucher DQLab 250rb".

## Kesimpulan 

apa yang aku pelajari:

1. Sistem relasional database atau relational database management system (RDBMS) adalah salah satu dari beberapa sistem database paling populer di dunia saat ini dan menggunakan bahasa SQL untuk pengolahannya.
2. Beberapa produk RDBMS yang terkenal antara lain adalah Microsoft SQL Server, Oracle, MySQL, PostgreSQL, IBM DB2, dan masih banyak lainnya.
3. Struktur penyimpanan data di RDBMS menggunakan hirarki:
    * Database
    * Tabel (Table)
    * Kolom (Column)
4. Data akan diisi ke dalam table dalam bentuk Baris (Row) data.

# Penggunaan Perintah SELECT… FROM…

## Mengambil Seluruh Kolom dalam suatu Tabel

![image](https://user-images.githubusercontent.com/20697667/165213634-d17157a7-24d0-4a12-b8cb-88b46444e117.png)

* Kata awal, yaitu SELECT digunakan untuk menginformasikan kepada sistem bahwa kita ingin mengambil data. 
* Tanda * (bintang) artinya seluruh kolom perlu diambil dari tabel yang dirujuk. Tanda ini sering juga disebut sebagai wildcard.
* FROM [NAMA_TABLE], artinya table yang akan diambil datanya.
* Tanda ; (titik koma) adalah tanda yang menyatakan akhir dari perintah SELECT atau SQL lain.

```sql
SELECT * FROM ms_produk;
```

```
+---------+-------------+------------------------------------+--------+
| no_urut | kode_produk | nama_produk                        | harga  |
+---------+-------------+------------------------------------+--------+
|       1 | prod-01     | Kotak Pensil DQLab                 |  62500 |
|       2 | prod-02     | Flashdisk DQLab 64 GB              |  55000 |
|       3 | prod-03     | Gift Voucher DQLab 100rb           | 100000 |
|       4 | prod-04     | Flashdisk DQLab 32 GB              |  40000 |
|       5 | prod-05     | Gift Voucher DQLab 250rb           | 250000 |
|       6 | prod-06     | Pulpen Multifunction + Laser DQLab |  92500 |
|       7 | prod-07     | Tas Travel Organizer DQLab         |  48000 |
|       8 | prod-08     | Gantungan Kunci DQLab              |  15800 |
|       9 | prod-09     | Buku Planner Agenda DQLab          |  92000 |
|      10 | prod-10     | Sticky Notes DQLab 500 sheets      |  55000 |
+---------+-------------+------------------------------------+--------+
```



# Prefix dan Alias

# Menggunakan Filter

# Mini Project
