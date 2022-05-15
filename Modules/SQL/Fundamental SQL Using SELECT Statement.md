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

## Mengambil Satu Kolom dari Tabel

![image](https://user-images.githubusercontent.com/20697667/165215572-f68a2efb-7fac-456d-a379-d6c2b03a96dd.png)

```sql
SELECT nama_produk FROM ms_produk;
```

```
+------------------------------------+
| nama_produk                        |
+------------------------------------+
| Kotak Pensil DQLab                 |
| Flashdisk DQLab 64 GB              |
| Gift Voucher DQLab 100rb           |
| Flashdisk DQLab 32 GB              |
| Gift Voucher DQLab 250rb           |
| Pulpen Multifunction + Laser DQLab |
| Tas Travel Organizer DQLab         |
| Gantungan Kunci DQLab              |
| Buku Planner Agenda DQLab          |
| Sticky Notes DQLab 500 sheets      |
+------------------------------------+
```

## Mengambil Lebih dari Satu Kolom dari Tabel

![image](https://user-images.githubusercontent.com/20697667/165216347-6e7bfa00-04a1-4732-942e-3d7966d4a197.png)

```sql
SELECT nama_produk, harga FROM ms_produk;
```

```
+------------------------------------+--------+
| nama_produk                        | harga  |
+------------------------------------+--------+
| Kotak Pensil DQLab                 |  62500 |
| Flashdisk DQLab 64 GB              |  55000 |
| Gift Voucher DQLab 100rb           | 100000 |
| Flashdisk DQLab 32 GB              |  40000 |
| Gift Voucher DQLab 250rb           | 250000 |
| Pulpen Multifunction + Laser DQLab |  92500 |
| Tas Travel Organizer DQLab         |  48000 |
| Gantungan Kunci DQLab              |  15800 |
| Buku Planner Agenda DQLab          |  92000 |
| Sticky Notes DQLab 500 sheets      |  55000 |
+------------------------------------+--------+
```

## Membatasi Pengambilan Jumlah Row Data

![download](https://user-images.githubusercontent.com/20697667/165216592-60c2f956-27a8-49aa-aea9-6f336830591c.png)

```sql
SELECT nama_produk, harga FROM ms_produk LIMIT 5;
```

```
+--------------------------+--------+
| nama_produk              | harga  |
+--------------------------+--------+
| Kotak Pensil DQLab       |  62500 |
| Flashdisk DQLab 64 GB    |  55000 |
| Gift Voucher DQLab 100rb | 100000 |
| Flashdisk DQLab 32 GB    |  40000 |
| Gift Voucher DQLab 250rb | 250000 |
+--------------------------+--------+
```

## Penggunaan SELECT DISTINCT statement

Untuk menghilangkan data duplikasi, gunakan SELECT DISTINCT statement. Dengan SELECT DISTINCT, data yang sama atau duplikat akan dieliminasi dan akan ditampilkan data yang unik saja.

![image](https://user-images.githubusercontent.com/20697667/165216923-62d54d22-10b9-467b-bffb-c35ad3619bcf.png)

```sql
SELECT DISTINCT nama_customer, alamat FROM ms_pelanggan;
```

```
+---------------------+------------------------------------------+
| nama_customer       | alamat                                   |
+---------------------+------------------------------------------+
| Eva Novianti, S.H.  | Vila Sempilan, No. 67 - Kota B           |
| Heidi Goh           | Vila Sempilan, No. 11 - Kota B           |
| Unang Handoko       | Vila Sempilan, No. 1 - Kota B            |
| Jokolono Sukarman   | Vila Permata Intan Berkilau, Blok C5-7   |
| Tommy Sinaga        | Vila Permata Intan Berkilau, Blok A1/2   |
| Irwan Setianto      | Vila Gunung Seribu, Blok O1 - No. 1      |
| Agus Cahyono        | Vila Gunung Seribu, Blok F4 - No. 8      |
| Maria Sirait        | Vila Bukit Sagitarius, Gang. Sawit No. 3 |
| Ir. Ita Nugraha     | Vila Bukit Sagitarius, Gang Kelapa No. 6 |
| Djoko Wardoyo, Drs. | Vila Bukit Sagitarius, Blok A1 No. 1     |
+---------------------+------------------------------------------+
```

# Prefix dan Alias

## Menggunakan Prefix pada Nama Kolom

![image](https://user-images.githubusercontent.com/20697667/165738158-050b052a-e8fb-4e5c-9842-90754d9678e9.png)

```sql
SELECT ms_produk.kode_produk FROM ms_produk;
```

```
+-------------+
| kode_produk |
+-------------+
| prod-01     |
| prod-02     |
| prod-03     |
| prod-04     |
| prod-05     |
| prod-06     |
| prod-07     |
| prod-08     |
| prod-09     |
| prod-10     |
+-------------+
```

## Menggunakan Alias pada Kolom

![image](https://user-images.githubusercontent.com/20697667/165738816-234c6e20-fa7c-448f-97a0-276f8714cf83.png)

```sql
SELECT no_urut AS nomor, nama_produk AS nama FROM ms_produk;
```

```
+-------+------------------------------------+
| nomor | nama                               |
+-------+------------------------------------+
|     1 | Kotak Pensil DQLab                 |
|     2 | Flashdisk DQLab 64 GB              |
|     3 | Gift Voucher DQLab 100rb           |
|     4 | Flashdisk DQLab 32 GB              |
|     5 | Gift Voucher DQLab 250rb           |
|     6 | Pulpen Multifunction + Laser DQLab |
|     7 | Tas Travel Organizer DQLab         |
|     8 | Gantungan Kunci DQLab              |
|     9 | Buku Planner Agenda DQLab          |
|    10 | Sticky Notes DQLab 500 sheets      |
+-------+------------------------------------+
```

## Menghilangkan Keyword 'AS'

![image](https://user-images.githubusercontent.com/20697667/165739692-9603483c-9fe2-41ac-a1f2-4c2e35b9e6c0.png)

```sql
SELECT no_urut nomor, nama_produk nama FROM ms_produk;
```

```
+-------+------------------------------------+
| nomor | nama                               |
+-------+------------------------------------+
|     1 | Kotak Pensil DQLab                 |
|     2 | Flashdisk DQLab 64 GB              |
|     3 | Gift Voucher DQLab 100rb           |
|     4 | Flashdisk DQLab 32 GB              |
|     5 | Gift Voucher DQLab 250rb           |
|     6 | Pulpen Multifunction + Laser DQLab |
|     7 | Tas Travel Organizer DQLab         |
|     8 | Gantungan Kunci DQLab              |
|     9 | Buku Planner Agenda DQLab          |
|    10 | Sticky Notes DQLab 500 sheets      |
+-------+------------------------------------+ 
```

## Menggabungkan Prefix dan Alias

![image](https://user-images.githubusercontent.com/20697667/165740108-7551b2ed-3f0d-45d0-852e-d18372ef88c8.png)

```sql
SELECT ms_produk.harga AS harga_jual FROM ms_produk;
```

```
+------------+
| harga_jual |
+------------+
|      62500 |
|      55000 |
|     100000 |
|      40000 |
|     250000 |
|      92500 |
|      48000 |
|      15800 |
|      92000 |
|      55000 |
+------------+
```

## Menggunakan Alias pada Tabel

![image](https://user-images.githubusercontent.com/20697667/165740288-47652576-6ae0-4786-b6ed-e3adaec49f0b.png)

```sql
SELECT * FROM ms_produk t2;
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

## Prefix dengan Alias Tabel

![image](https://user-images.githubusercontent.com/20697667/165740463-298d3153-8a1b-49ff-84f6-f2a951ddd5e7.png)

```sql
SELECT t2.nama_produk, t2.harga FROM ms_produk t2;
```

```
+------------------------------------+--------+
| nama_produk                        | harga  |
+------------------------------------+--------+
| Kotak Pensil DQLab                 |  62500 |
| Flashdisk DQLab 64 GB              |  55000 |
| Gift Voucher DQLab 100rb           | 100000 |
| Flashdisk DQLab 32 GB              |  40000 |
| Gift Voucher DQLab 250rb           | 250000 |
| Pulpen Multifunction + Laser DQLab |  92500 |
| Tas Travel Organizer DQLab         |  48000 |
| Gantungan Kunci DQLab              |  15800 |
| Buku Planner Agenda DQLab          |  92000 |
| Sticky Notes DQLab 500 sheets      |  55000 |
+------------------------------------+--------+ 
```

Perintah SELECT dapat ditulis dengan variasi identitas kolom dan tabel berupa prefix dan alias.
- Penulisan lengkap untuk nama kolom adalah prefix berupa nama tabel disertai tanda titik sebelum nama kolom itu sendiri.
- Alias adalah nama lain yang diberikan untuk kolom maupun tabel.
- Alias dapat digunakan dengan keyword AS atau tanpa keyword AS setelah nama kolom dan tabel.
- Prefix nama tabel bisa menggunakan alias.

# Menggunakan Filter

Untuk case dimana kita ingin mengambil data berdasarkan kondisi tertentu saja, kita bisa menggunakan filter. SQL memiliki fungsi filter dengan menggunakan klausul WHERE. Jika kondisi WHERE terpenuhi, maka hasil query hanya akan menampilkan data yang sudah terfilter.

Klausul WHERE untuk:

- Filter data dengan kondisi teks tertentu.
- Filter data dengan nilai angka tertentu.
- Filter data dengan dua kondisi menggunakan operator AND dan OR.

## Menggunakan WHERE

Klausul WHERE dari SELECT digunakan untuk memfilter data berdasarkan kondisi tertentu. Untuk syntax lengkapnya adalah sebagai berikut.

![download](https://user-images.githubusercontent.com/20697667/168477449-53d72e2b-a837-4239-9ddf-19a6d99ec8f0.png)

```sql
SELECT * FROM ms_produk WHERE nama_produk = 'Tas Travel Organizer DQLab';
```

```
+---------+-------------+----------------------------+-------+
| no_urut | kode_produk | nama_produk                | harga |
+---------+-------------+----------------------------+-------+
|       7 | prod-07     | Tas Travel Organizer DQLab | 48000 |
+---------+-------------+----------------------------+-------+
```

## Menggunakan Operand OR

![image](https://user-images.githubusercontent.com/20697667/168477609-90134501-da03-4f48-8aae-73001419ded4.png)

```sql
SELECT * FROM ms_produk WHERE nama_produk = 'Gantungan Kunci DQLab' OR nama_produk = 'Tas Travel Organizer DQLab' OR nama_produk = 'Flashdisk DQLab 64 GB';
```

```
+---------+-------------+----------------------------+-------+
| no_urut | kode_produk | nama_produk                | harga |
+---------+-------------+----------------------------+-------+
|       2 | prod-02     | Flashdisk DQLab 64 GB      | 55000 |
|       7 | prod-07     | Tas Travel Organizer DQLab | 48000 |
|       8 | prod-08     | Gantungan Kunci DQLab      | 15800 |
+---------+-------------+----------------------------+-------+ 
```

## Filter untuk Angka

Berikut adalah contoh filter dimana kolom harga harus memiliki nilai di bawah 50000.

![download](https://user-images.githubusercontent.com/20697667/168477879-c2ce24b6-3416-481f-87e3-33c87cf1c4f6.png)

![image](https://user-images.githubusercontent.com/20697667/168477903-a056d9c4-c562-453e-b2f4-1e3866554513.png)

```sql
SELECT * FROM ms_produk WHERE harga > 50000;
```

```
+---------+-------------+------------------------------------+--------+
| no_urut | kode_produk | nama_produk                        | harga  |
+---------+-------------+------------------------------------+--------+
|       1 | prod-01     | Kotak Pensil DQLab                 |  62500 |
|       2 | prod-02     | Flashdisk DQLab 64 GB              |  55000 |
|       3 | prod-03     | Gift Voucher DQLab 100rb           | 100000 |
|       5 | prod-05     | Gift Voucher DQLab 250rb           | 250000 |
|       6 | prod-06     | Pulpen Multifunction + Laser DQLab |  92500 |
|       9 | prod-09     | Buku Planner Agenda DQLab          |  92000 |
|      10 | prod-10     | Sticky Notes DQLab 500 sheets      |  55000 |
+---------+-------------+------------------------------------+--------+
```

## Menggunakan Operand AND

![image](https://user-images.githubusercontent.com/20697667/168478041-d6167cab-43be-4037-8ec3-d06f37f04c12.png)

```sql
SELECT * FROM ms_produk WHERE nama_produk = 'Gantungan Kunci DQLab' AND harga < 50000;
```

```
+---------+-------------+-----------------------+-------+
| no_urut | kode_produk | nama_produk           | harga |
+---------+-------------+-----------------------+-------+
|       8 | prod-08     | Gantungan Kunci DQLab | 15800 |
+---------+-------------+-----------------------+-------+
```



# Mini Project

