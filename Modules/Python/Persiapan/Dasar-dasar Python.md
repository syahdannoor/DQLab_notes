Apa itu Python?
=
Python adalah bahasa pemrograman yang ditujukan untuk general-purpose programming dan termasuk dalam kategori high-level programming language.

Sebagai general-purpose programming language, Python digunakan untuk berbagai macam permasalahan seperti: pengembangan aplikasi web ataupun mobile, data science, dll.
Python masuk ke dalam kategori high-level programming language dikarenakan bahasa pemrograman Python yang mudah untuk dibaca dan dituliskan oleh manusia.
Bahasa  pemrograman  Python  diciptakan  oleh  Guido  van Rossum dan pertama kali diperkenalkan pada tahun 1991 sebagai sebuah proyek open-source. Lisensi dari Python bersifat open-source dari Python, atau dengan kata lain setiap orang dapat mengembangkan program komputer dengan menggunakan bahasa pemrograman Python baik untuk tujuan komersil/non-komersil.


## note :  

Python adalah bahasa yang ditujukan untuk general-purpose programming, jenis high-level programming language dan berlisensi open source

Karena tiga karakteristik itulah, banyak pengembang membuat library python ditujukan untuk data science dan tentunya memudahkan pengguna dalam melakukan analisis dan membuat model prediktif dalam data science.

## List Library Python

![image](https://user-images.githubusercontent.com/20697667/159612104-2a427c9b-1f86-429a-a602-56f108162123.png)

1. Numpy (numerical python) merupakan library yang memudahkan dalam pendefinisian array (1D, 2D, 3D atau nD) dan digunakan  untuk komputasi aljabar linier.
2. Scipy (Scientific Python) merupakan library yang melengkapi numpy untuk keperluan komputasi saintifik lanjut seperti aljabar linier, integrasi dan diferensiasi numerik, transformasi Fourier, optimasi, interpolasi, statistik dan yang lainnya.
3. Pandas adalah library untuk pengolahan data dalam bentuk tabular (seperti excel) yang merupakan de facto library (pustaka yang umum digunakan dalam prakteknya) bagi data scientist dalam mengolah data dari berbagai sumber seperti file CSV, TSV, Excel, SQL queries, Google BigQuery, SAS, Stata, SPSS, dsb.
4. Matplotlib digunakan untuk visualisasi dari data ke dalam berbagai bentuk grafik 2D atau 3D, seperti line chart, bar chart, histogram, polar chart, error bar plot, dan jenis grafik lainnya.
5. Scikit-learn adalah Scipy Toolkit yang ditujukan untuk menghasilkan model prediktif dengan menggunakan machine learning.
6. Seaborn merupakan library yang dibuat dari matplotlib yang ditujukan oleh visualisasi grafik statistik dengan warna yang menawan, dan terintegrasi dengan baik dengan pandas.

Masih banyak library lainnya yang memiliki kemampuan yang sama atau lebih dari yang telah dijelaskan. Tetapi list library ini adalah library dasar yang wajib dikuasai oleh pemula.

## Struktur Bahasa Python

| No | STRUKTUR       | KETERANGAN                                                                                                                           |
| -- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| 1  | Statements     | instruksi yang diberikan secara baris per baris untuk dijalankan oleh program                                                        |
| 2  | Variables      | pengindentifikasian yang  digunakan untuk menampung sebuah data atau informasi                                                       |
| 3  | Literals       | data atau informasi yang digunakan untuk mengisi suatu variabel                                                                      |
| 4  | Operators      | simbol-simbol yang digunakan untuk mengubah nilai dari satu variabel dengan melibatkan satu atau lebih variabel dan literal.         |
| 5  | Reserved Words | kumpulan kata-kata yang memiliki makna khusus dalam bahasa pemrograman Python dan tidak dapat digunakan untuk variables dan literals |
| 6  | Whitespace     | pada bahasa Python, spasi dan tab memiliki makna khusus untuk menandai serangkaian blok dalam kode Python                            |
| 7  | Comments       | merupakan sekumpulan teks yang dituliskan di dalam sebuah program yang tidak akan mempengaruhi hasil dari sebuah program             |

## Python “Hello World” & Statement

```python
print("Hello World.")
print("Saya Aksara, baru belajar Python.")
```
```
Hello World.
Saya Aksara, baru belajar Python.
```

## Variables di Python

 tiga aturan penting yang wajib diikuti pada saat kita mendeklarasikan suatu variabel di Python. 

1. Nama dari sebuah variabel harus dimulai dengan huruf (a-z, A-Z)
atau karakter garis bawah/underscore _ dan tidak dapat dimulai dengan angka (0-9).
2. Variabel hanya boleh mengandung karakter alfabet dan bilangan dan underscore
(a-z, A-Z, 0-9, _)
3. Variabel bersifat case-sensitive yang mengartikan bahwa
variabel TINGGI, tinggi, dan Tinggi merujuk pada tiga variabel berbeda.

```python
bil1 = 10
Bil_2 = 20
Frasa = "Halo Dunia"
bil1, Bil_2 = 10, 20
salam = "Selamat Pagi"; Penutup = "Salam Sejahtera"
```

## Comments di Python
Comments adalah sekumpulan teks yang dituliskan dalam sebuah program dan tidak akan mempengaruhi hasil dari sebuah program. Berikut adalah contoh penulisan single line comment & multi line comment pada python. 

"Walaupun tidak mempengaruhi hasil program, comments adalah salah satu komponen yang penting dalam pengembangan program. Hal tersebut dikarenakan comments dapat kita selipkan di antara sekumpulan statements untuk dapat berkomunikasi dengan rekan data lainnya dalam satu tim.” Senja kembali menjelaskan.

```python
# perintah pada baris ini tidak mempengaruhi program
'''
perintah ini tidak akan dieksekusi oleh Python
dan perintah ini juga tidak akan dieksekusi
perintah ini juga tidak akan dieksekusi
'''
print("jadi # digunakan untuk membuat comment pada Python")
```
```
jadi # digunakan untuk membuat comment pada Python
```

## Tipe Data Python

Secara garis besar, ada beragam tipe data di Python seperti yang digambarkan pada diagram dibawah:

![image](https://user-images.githubusercontent.com/20697667/159623501-4b67b139-e620-481f-9d05-3288d12b0def.png)

Tabel berikut menjelaskan keterangan dari tipe data NoneType, int, float, dan bool:

![image](https://user-images.githubusercontent.com/20697667/159630663-986ba880-b598-4d0f-9fad-a02190178148.png)

Tabel berikut menjelaskan keterangan dari tipe data sequence, set, dan map:

![image](https://user-images.githubusercontent.com/20697667/159630958-920c37be-de94-41df-818c-2511299060b6.png)

## Tugas Praktek

![image](https://user-images.githubusercontent.com/20697667/159631052-8a6ea00a-10ab-4e13-be02-0b105c6f4bcb.png)

![image](https://user-images.githubusercontent.com/20697667/159631103-20b7f1d3-4326-4ef7-8cc7-7a89094e4acd.png)

1. Pada baris 2, perintah list akan mengubah text menjadi tipe data list dan mencetak nilainya.

2. Pada baris 3, perintah tuple akan mengubah text menjadi tipe data tuple dan mencetak nilainya.

3. Pada baris 4, perintah set akan mengubah text menjadi tipe data set dan mencetak nilainya.

```python
text = "Belajar Python di DQLab."
print(list(text))
print(tuple(text))
print(set(text))
```

## Menggunakan Library di Python

Menggunakan perintah import nama_library atau import nama_library as alias.

Contoh yang umum untuk penggunaan ini adalah:

![image](https://user-images.githubusercontent.com/20697667/159631319-8c3a5817-dc1c-455f-8bf0-6513b2feddc7.png)

```python
import math
import numpy as np
import pandas as pd
import seaborn as sns
```

