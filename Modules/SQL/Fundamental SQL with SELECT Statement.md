![image](https://user-images.githubusercontent.com/20697667/164886560-5f6d89dd-20ec-407c-8b3e-ae2aa227ceb1.png)


> SQL (Structured Query Language)

Fundamental SQL with SELECT Statement
---

# Sistem Database Relational

Struktur Penyimpanan di RDBMS

3 hirarki objek penyimpanan:
* Database
* Table
* Column atau Field

> Isi data akan mengisi table pada tiap column dan membentuk row (baris data)

Table

contoh table : ms_produk

![image](https://user-images.githubusercontent.com/20697667/164886821-7c223d91-8b87-41ec-8216-517858fcced4.png)

**penjelasan**

struktur table *ms_produk* terdiri atas 4 column:
* `no_urut`
* `kode_produk`
* `nama_produk`
* `harga`

table tersebut berisi 10 baris data (row) dengan isi yang bervariasi, contoh isi untuk column `nama_produk` pada baris kelima adalah `Gift Voucher DQLab 250rb`.

# SQl dan perintah SELECT

[Ini Pengertian dari Wikipedia](https://id.wikipedia.org/wiki/SQL)

Apa itu SQL?
SQL merupakan singkatan dari Structured Query Language,  adalah sebuah bahasa komputer yang sederhana dan menjadi standar untuk berkomunikasi dengan sistem database relasional.

Dikatakan bahasa yang sederhana karena cukup mudah dipelajari oleh seorang yang awam, karena cukup mengerti dengan baik pengolahan data dengan aplikasi Microsoft Excel.
SQL dirancang agar terdapat bahasa komunikasi yang standar dan seragam untuk berbagai produk sistem database - dari vendor-vendor yang berbeda. 
Dengan kata lain, kita cukup belajar satu bahasa - walaupun nantinya ada perbedaan sedikit (dialek) antara tiap produk.
SQL dilafalkan dengan membaca tiap karakternya S Q L (es kiu el) atau sikuel.

Perintah SELECT

SELECT adalah bagian perintah SQL yang digunakan untuk mengambil data dari RDBMS. Konstruksi perintahnya bisa sangat kompleks tapi juga sangat bermanfaat.  Perintah ini juga disebut sebagai query SQL.

Query dasar dan sederhana SELECT mengikuti syntax berikut.

![image](https://user-images.githubusercontent.com/20697667/164996818-b5baaee3-f4ff-4171-aa09-3b9f158a05c8.png)


> Jangan gunakan perintah `SELECT *` , bila data nya besar

* Kata awal, yaitu SELECT digunakan untuk menginformasikan kepada sistem kita ingin mengambil data. 
* Tanda * (bintang) artinya seluruh kolom perlu diambil dari table yang dirujuk. Tanda ini sering juga disebut sebagai wildcard.
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

Jenis-jenis Perintah pada SQL

Perintah SELECT pada bagian sebelumnya hanya salah satu jenis perintah yang ada pada SQL, untuk jelasnya mari kita ikuti penjelasan berikut.

Perintah SQL selengkapnya terdiri dari dua kategori:

* DDL (Data Definition Language), yaitu berbagai perintah yang digunakan untuk membuat, merubah, dan menghapus struktur database. Struktur database ini terdiri dari database, table, kolom dan tipe data. 
* DML (Data Manipulation Language), yaitu berbagai perintah yang digunakan untuk 
    * Memasukkan data dengan perintah INSERT
    * Mengambil data atau query dengan perintah SELECT
    * Merubah data dengan perintah UPDATE
    * Menghapus data dengan perintah DELETE

Dari contoh pada praktek sebelumnya, maka dapat disimpulkan perintah yang kita gunakan adalah melakukan query dengan SELECT.

# Menentukan Kolom dan Jumlah Baris Yang Ditampilkan

contoh query untuk mengambil satu kolom saja yaitu nama_produk.

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

berikut adalah perintah SELECT adalah untuk menampilkan dua kolom pada table ms_produk, yaitu kode_produk dan nama_produk.

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

Ini adalah perintah untuk membatasi pengambilan data dari table ms_produk sebanyak tiga baris data (row).

```sql
SELECT nama_produk FROM ms_produk LIMIT 3;
```

```
SELECT nama_produk FROM ms_produk LIMIT 3;
```

# Prefix dan Alias

Contoh untuk pengambilan nama kolom nama_produk data dari table ms_produk dengan penulisan prefix nama table adalah sebagai berikut.

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

contoh untuk merubah nama kolom dari kode_produk menjadi product_code dari table ms_produk.

```sql
SELECT 
no_urut AS nomor,
nama_produk AS nama
FROM
ms_produk;
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

dimana untuk merubah nama kolom dari kode_produk menjadi product_code dari table ms_produk - namun tanpa mengunakan AS.

```sql
SELECT 
no_urut nomor,
nama_produk nama
FROM 
ms_produk;
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

contoh penggunaan prefix nama table dan alias untuk kolom nama_produk.

```sql
SELECT
ms_produk.harga AS harga_jual
FROM
ms_produk;
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

contoh untuk menggunakan alias pada table ms_produk menjadi t2.

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

> Terlihat hasil yang dikeluarkan adalah seluruh isi table ms_produk.

contoh berikut ini dari tabel ms_produk yang telah digunakan sebelumnya.

```sql
SELECT
t2.nama_produk,
t2.harga
FROM
ms_produk t2;
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

# Menggunakan Filter

Filter merupakan salah satu fitur penting terutama ketika data yang perlu diambil untuk diolah harus memenuhi kriteria tertentu. Contohnya, bagaimana cara kita mengambil data dengan constraint berupa nama produk adalah pensil? Filter adalah jawabnya, karena tanpa fitur ini data yang akan diolah nantinya tidak memiliki manfaat yang berarti.

```sql
SELECT *
FROM ms_produk
WHERE nama_produk = 'Tas Travel Organizer DQLab';
```

```
+---------+-------------+----------------------------+-------+
| no_urut | kode_produk | nama_produk                | harga |
+---------+-------------+----------------------------+-------+
|       7 | prod-07     | Tas Travel Organizer DQLab | 48000 |
+---------+-------------+----------------------------+-------+
```

