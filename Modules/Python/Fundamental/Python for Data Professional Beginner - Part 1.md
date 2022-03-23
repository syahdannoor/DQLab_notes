# Mari Mengenal Python

Apa itu bahasa pemograman Python, "Hello World" di Python, dan struktur bahasa pemograman Python.

## Apa dan Kenapa Python – Part 1?

![image](https://user-images.githubusercontent.com/20697667/159636002-67f463e2-65b1-4fdd-b7a8-f3e4d40efed7.png)


Python adalah bahasa pemrograman yang ditujukan untuk general-purpose programming dan termasuk dalam kategori high-level programming language.

Sebagai general-purpose programming language, Python digunakan untuk berbagai macam permasalahan seperti: pengembangan aplikasi web ataupun mobile, data science, dll.

Python masuk ke dalam kategori high-level programming language dikarenakan bahasa pemrograman Python yang mudah untuk dibaca dan dituliskan oleh manusia.

Bahasa  pemrograman  Python  diciptakan  oleh Guido van Rossum dan pertama kali diperkenalkan pada tahun 1991 sebagai sebuah proyek open-source.

Sifat open-source dari Python mengartikan bahwa setiap orang dapat mengembangkan program komputer dengan menggunakan bahasa pemrograman Python baik untuk tujuan komersil/non-komersil.

## Apa dan Kenapa Python – Part 2?
Bahasa pemrograman Python bersifat dynamically typed (Python akan secara otomatis mengubah masukan dari pengguna) dan mendukung berbagai paradigma pemrograman baik pemrograman secara prosedural, berbasis objek (Object-Oriented), ataupun fungsional.

Selain alasan di atas terdapat beberapa alasan lain untuk menggunakan bahasa pemrograman Python:

1. Python dikembangkan untuk bersifat extendible yang mengartikan bahwa Python dapat dikembangkan untuk berbagai macam tugas baik untuk pembuatan aplikasi web ataupun desktop, proses analisis data, dll.
2. Python memiliki komunitas yang besar yang secara aktif berkontribusi untuk menyediakan berbagai macam fungsionalitas (third-party libraries). Third-party libraries yang tersedia dalam bahasa pemrograman Python memungkinkan para pengembang untuk dapat fokus menyelesaikan permasalahan yang ada. Per Januari 2020, terdapat 214,922 modul third-party yang dapat kita gunakan secara cuma-cuma.
3. Python terintegrasi dengan baik dengan berbagai macam bahasa pemrograman dan layanan enterprise. Untuk bagian-bagian yang melibatkan sumber daya komputasi yang besar, pengembang dapat menggunakan fungsionalitas dalam bahasa pemrograman lainnya yang bersifat low-level yang telah dikemas ke dalam fungsionalitas Python.

## Program pertama: "Hello World"

```python
print("Hello World!")
```
```
Hello World!
```

## Program Pertamaku

```python
print("Halo Dunia")
print("Riset Bahasa Python")
```
```
Halo Dunia
Riset Bahasa Python
```

## Struktur Program Python - Part 1

sebuah program Python pada umumnya terdiri dari:

1. Statements: Instruksi yang diberikan secara baris per baris untuk dijalankan oleh mesin. Contoh:
![image](https://user-images.githubusercontent.com/20697667/159637760-9df71105-e058-444c-bf86-755f12615f51.png)

2. Variables: Lokasi penyimpanan yang dapat digunakan untuk menampung sebuah data atau informasi. Contoh: aku mempunyai variabel yang bernama bilangan1, bilangan2, dan kalimat1
![image](https://user-images.githubusercontent.com/20697667/159637775-50065c89-9c4a-46d6-85d9-d0269fe58853.png)

3. Literals: Simbol-simbol yang dapat kita gunakan untuk mengisi suatu variabel. Pada kode yang telah dicontohkan di atas, angka 5 dan 10 serta 'Belajar Bahasa Python' disebut sebagai literal.

4. Operators: Simbol-simbol yang dapat digunakan untuk mengubah nilai dari satu variabel dengan melibatkan satu atau lebih variabel dan literal. Contoh: Tanda + merupakan salah satu contoh operator. Dengan menggunakan tanda +, aku berhasil menambahkan isi dari bilangan1 dan bilangan2!
![image](https://user-images.githubusercontent.com/20697667/159637808-8d0f3996-d309-4669-930d-9618f4f8a0e5.png)

Adapun operator yang lain selain operator + adalah sebagai berikut.
1. Operator - yang berfungsi sebagai operator pengurangan,
2. Operator * yang berfungsi sebagai operator perkalian, dan
3. Operator ** untuk pemangkatan

```python
# Statement
print("Belajar Python menyenangkan") 
print("Halo Dunia")
print("Hello World!")
# Variables & Literals
bilangan1 = 5
bilangan2 = 10
kalimat1 = "Belajar Bahasa Python"
# Operators
print(bilangan1 + bilangan2)
```
```
Belajar Python menyenangkan
Halo Dunia
Hello World!
15
```

## Tugas Praktek

Deklarasi variable bilangan1 dengan 20, dan bilangan2 dengan 10 dan tampilkan hasil pengurangan bilangan1 & bilangan 2.
```python
bilangan1 = 20
bilangan2 = 10
print(bilangan1 - bilangan2)
```
```
10
```

## Tugas Praktek

kalkulator sederhana untuk potongan harga dan pajak

1. Aku diminta menghitung harga_setelah_potongan dan harga_final. harga_final diperoleh dengan mengalikan harga_setelah_potongan dengan angka 1.1 karena PPN sebesar 10% (100% + 10% = 110% atau 1.1)
2. Aku menggunakan variabel harga_asli dengan nilai 20000 dan variabel potongan dengan nilai 2000.

```python
harga_asli = 20000
potongan = 2000
harga_setelah_potongan = harga_asli - potongan
harga_final = harga_setelah_potongan * 1.1
print(harga_final)
```
```
19800.0
```

## Struktur Program Python - Part 2

Berikut adalah hal-hal baru yang aku pelajari mengenai Python:

1. Reserved Words: Kumpulan kata-kata yang memiliki makna khusus dalam bahasa pemrograman Python. Kata False, return, dan for merupakan contoh dari reserved words. 
> Catatan: Ternyata, aku tidak dapat mendeklarasikan variabel dengan menggunakan sebuah reserved word!

2. Whitespace: Pada bahasa Python, spasi dan tab memiliki makna khusus untuk menandai serangkaian blok dalam kode Python. Hal ini akan dijelaskan secara lebih lanjut pada bagian struktur pemilihan dan struktur pengulangan pada bahasa Python.

3. Comments: Comments merupakan sekumpulan teks yang dituliskan di dalam sebuah program yang tidak akan mempengaruhi hasil dari sebuah program. Walaupun tidak mempengaruhi hasil program, comments merupakan salah satu komponen yang penting dalam pengembangan program. Hal tersebut dikarenakan comments dapat diselipkan di antara sekumpulan statements yang telah dituliskan, untuk berkomunikasi dengan rekan programmer lainnya dalam satu tim. 

Terdapat dua jenis comments di dalam Python, yaitu:

a. single line comment (comments dalam satu baris) seperti pada contoh berikut:
![image](https://user-images.githubusercontent.com/20697667/159638766-24ef4029-3882-4f70-aa11-3fe62504f79a.png)

b. multi line comment (comments dalam beberapa baris) yang dapat dituliskan seperti pada contoh berikut:
![image](https://user-images.githubusercontent.com/20697667/159638815-d5477d52-07ef-4168-9553-d2d2d211ae4e.png)

Python Variables & Data Types
=
## Python Variables

> Tips: Dalam mendeklarasikan sebuah variabel, berilah nama yang mewakili isi dari variabel tersebut.
![image](https://user-images.githubusercontent.com/20697667/159652022-3ec63b09-3cba-40c5-9640-9d65d39ec9d2.png)

## Aturan Penamaan Python Variables

Penamaan suatu variabel pada python dapat dikatakan valid selama memenuhi aturan-aturan berikut:

1. Nama dari sebuah variabel harus dimulai dengan huruf (a-z, A-Z) atau karakter garis bawah underscore (_) dan tidak dapat dimulai dengan angka (0-9).
2. Variabel hanya boleh mengandung karakter alfabet, bilangan dan underscore (a-z, A-Z, 0-9, _)
3. Variabel bersifat case-sensitive yang mengartikan bahwa variabel TINGGI, tinggi, dan Tinggi merujuk pada tiga variabel berbeda.

Selain dapat mendeklarasikan nilai dari suatu variabel secara baris per baris, aku juga dapat mendeklarasikan beberapa variabel dalam satu baris dengan menggunakan ekspresi seperti:

![image](https://user-images.githubusercontent.com/20697667/159652391-b7a15cb4-589e-4418-9da4-5a32c230e1e4.png)

## Tipe Data Dasar: Null, Boolean, Numeric dan Text

1. **Null Type**: Tipe data null dalam Python digunakan untuk menyimpan nilai kosong atau tidak ada yang dinyatakan dengan **None**.

2. **Boolean Type**: Tipe data boolean atau **bool** digunakan untuk menyimpan nilai kebenaran (True, False) dari suatu ekspresi logika.

3. **Numeric Type**: Tipe data yang digunakan untuk menyimpan data berupa angka. Terdapat dua macam tipe data numeric, yaitu **int** untuk menyimpan **bilangan bulat** (e.g.: 0, 1, 2, 404, -500, -1000) dan **float** untuk menyimpan **bilangan riil** (e.g.: 0.5, 1.01, 2.05, 4.04)

4. **Text Type**: Pada Python, tipe data string (**str**) digunakan untuk menyimpan data teks. Tipe data string dimulai dengan tanda kutip (baik kutip satu/ dua) dan diakhir dengan tanda kutip. Contoh: "Teks", "Contoh teks menggunakan Python", dan 'Teks pada Python'.

## Sequence Type – Part 1

Tipe data ini digunakan untuk menampung sekumpulan data secara terorganisir.

Bentuk dari tipe data sequence ini adalah **List** dan **Tuple**.

Pada part 1 ini, aku akan mempelajari tipe data **list** terlebih dahulu.

Tipe data list diawali dengan tanda kurung siku buka ( `[` ), memisahkan setiap elemen di dalamnya dengan tanda koma ( `,` ) dan ditutup dengan kurung siku tutup ( `]` ). Sebagai contoh:

![image](https://user-images.githubusercontent.com/20697667/159655230-91a7fa9b-8c17-4a97-96c7-ff09cc53defb.png)

Setiap elemen dari list memiliki indeks yang dimulai dari angka 0 dan terus bertambah satu nilainya hingga elemen terakhir dari list. Sebagai contoh:

![image](https://user-images.githubusercontent.com/20697667/159655295-407440a7-84d3-4380-a19b-2483995a0f08.png)

Tipe data list bersifat mutable yang berarti setiap elemen di dalam list dapat dirubah nilainya setelah proses pendeklarasian list. Sebagai contoh:

![image](https://user-images.githubusercontent.com/20697667/159655349-5ae9fdb1-73b1-4fb8-8780-f5f9f9da26f3.png)

Tugas:

Petunjuk 1: Input data `1, 'dua', 3, 4.0, 5` ke dalam contoh_list

Petunjuk 2: Ambil Elemen pertama dari `contoh_list` untuk menampilkan output `1` menggunakan print statement

Petunjuk 3: Ambil Elemen ke empat dari `contoh_list` untuk menampilkan output `4.0` menggunakan print statement

Petunjuk 4: Input data `1, 'dua', 3, 4.0, 5` ke dalam `contoh_list`

Petunjuk 5: Rubah Elemen keempat dalam contoh_list menjadi `'empat'`

Petunjuk 6: Tampilkan output elemen keempat yang telah dirubah tersebut menggunakan print statement

```python
contoh_list = [1, 'dua', 3, 4.0, 5]
print(contoh_list[0])
print(contoh_list[3])
contoh_list = [1, 'dua', 3, 4.0, 5]
contoh_list[3] = 'empat'
print(contoh_list[3])
```

```
1
4.0
empat
```

## Sequence Type – Part 2

Tipe data tuple juga berfungsi untuk menampung sekumpulan data. Tipe data ini diawali dengan tanda kurung buka ( `(` ), memisahkan setiap elemen di dalamnya dengan tanda koma ( `,` ) dan ditutup dengan tanda kurung tutup ( `)` ). Sebagai contoh:

![image](https://user-images.githubusercontent.com/20697667/159656745-ebc03acf-0f0b-40f3-bc99-47bea3fadb6a.png)

Aturan indeks dan cara mengakses elemen pada sebuah tuple serupa dengan list. Sebagai contoh:

![image](https://user-images.githubusercontent.com/20697667/159656790-60fad78c-c84d-40fb-a1d1-78628d4fbff0.png)

Berbeda dengan tipe data list, tipe data tuple bersifat **immutable** yang berarti elemen pada tipe data tuple tidak dapat diubah setelah proses pendeklarasiannya.

Pada saat mengubah elemen pada tuple seperti pada kode berikut, 

![image](https://user-images.githubusercontent.com/20697667/159657027-3cb4879c-544b-4b04-bdb2-77063175705a.png)

akan menghasilkan error di console, yaitu `TypeError`

![image](https://user-images.githubusercontent.com/20697667/159657113-e248f22e-7e91-4d03-b9d3-aedb786c9e41.png)

Tugas:

Petunjuk 1: Input data **Januari sampai dengan April** ke dalam `contoh_tuple`

Petunjuk 2: Ambil Elemen pertama dari `contoh_tuple` untuk menampilkan output 1 menggunakan print statement

Petunjuk 3: Input kembali data **Januari sampai dengan April** ke dalam `contoh_tuple`

Petunjuk 4: Rubah Elemen pertama dalam `contoh_tuple` menjadi `'Desember'`

```python
contoh_tuple = ('Januari', 'Februari', 'Maret', 'April')
print(contoh_tuple[0])
contoh_tuple = ('Januari', 'Februari', 'Maret', 'April')
contoh_tuple[0] = 'Desember'
```
```
Januari
Traceback (most recent call last):
  File "<stdin>", line 4, in <module>
TypeError: 'tuple' object does not support item assignment
```

## Set Type

Serupa dengan tipe data sequence, tipe data set digunakan untuk menampung sekumpulan data dengan tipe lainnya. Terdapat dua jenis dari tipe data set yaitu, set dan frozenset.

Tipe data set diawali dengan tanda kurung buka kurawal ( `{` ), memisahkan setiap elemen di dalamnya dengan tanda koma ( `,` ) dan ditutup dengan tanda kurung tutup ( `}` ). Namun berbeda dengan tipe data sequence, seperti list, tipe data objek tidak mengizinkan adanya elemen dengan nilai yang sama dan tidak memperdulikan urutan dari elemen.

Sebagai contoh:

![download](https://user-images.githubusercontent.com/20697667/159658566-dfb3c38a-6af0-4f8d-85a3-d52a7a24859d.png)

Akan menghasilkan output:
 
![download](https://user-images.githubusercontent.com/20697667/159658666-f9ad4914-73d7-46d6-92a2-36cc300d6144.png)

sedangkan pada tipe data set:

![download](https://user-images.githubusercontent.com/20697667/159658750-b2c54b3f-156b-4483-92da-a30fd5d4280a.png)

Akan menghasilkan output :

![image](https://user-images.githubusercontent.com/20697667/159658931-e10e9e18-c96c-48da-96d1-de961e1aba15.png)

Dari kedua contoh output pada program, dapat terlihat:

1. Berbeda dengan tipe data set, tipe data list memperdulikan urutan dari setiap elemen saat list dideklarasikan.

2. Berbeda dengan list yang mengizinkan adanya duplikasi elemen, **tipe data set tidak mengizinkan adanya elemen dengan nilai yang sama di dalamnya.**

Keunikan dari kedua tipe data ini tentunya menjadi pengetahuan yang berguna.

Dan aku akan mempelajarinya kembali pada bagian struktur kontrol pengulangan!

Bagaimana dengan tipe data **frozenset**? Tipe data frozenset sebenarnya hanya merupakan set yang bersifat **immutable**, yang artinya setiap elemen di dalam frozenset tidak dapat diubah setelah proses deklarasinya. Untuk membuat tipe data frozenset, aku dapat merujuk potongan kode di bawah ini:

![image](https://user-images.githubusercontent.com/20697667/159659590-a932bc48-fdfc-4e15-ac7e-4e8180271f29.png)

Akan menghasilkan output:

![image](https://user-images.githubusercontent.com/20697667/159659620-3692af1a-b3d8-467f-a746-62fb14921ee6.png)

Tugas:

1. Input data Dewi, Budi, Cici, Linda, Cici kedalam tipe data list dan tampilkan hasilnya
2. Input data Dewi, Budi, Cici, Linda, Cici kedalam tipe data set dan tampilkan hasilnya
3. Input data Dewi, Budi, Cici, Linda, Cici kedalam tipe data frozenset dan tampilkan hasilnya

```python
contoh_list = ['Dewi', 'Budi', 'Cici', 'Linda', 'Cici']
print(contoh_list)
contoh_set = {'Dewi', 'Budi', 'Cici', 'Linda', 'Cici'}
print(contoh_set)
contoh_frozen_set = ({'Dewi', 'Budi', 'Cici', 'Linda', 'Cici'})
print(contoh_frozen_set)
```

```
['Dewi', 'Budi', 'Cici', 'Linda', 'Cici']
{'Cici', 'Dewi', 'Budi', 'Linda'}
{'Cici', 'Dewi', 'Budi', 'Linda'}
```

## Mapping Type

Tipe data **mapping** dapat digunakan untuk memetakan sebuah nilai ke nilai lainnya. Dalam Python, tipe data mapping disebut dengan istilah **dictionary**. Tipe data dictionary dapat dideklarasikan dengan diawali oleh tanda kurung buka kurawal ( `{` ), memisahkan setiap elemen di dalamnya dengan tanda koma ( `,` ) dan ditutup dengan tanda kurung tutup ( `}` ). Setiap elemen pada tipe data dictionary dideklarasikan dengan format:

`"kunci" : "nilai"`

Hal inilah yang membedakan tipe data mapping dengan tipe data set. Untuk lebih memperjelas tipe data mapping, aku mempelajari potongan kode berikut:

![download](https://user-images.githubusercontent.com/20697667/159660399-41e47946-be29-42dc-a686-f0b7605eb62e.png)

Potongan kode di atas adalah contoh pendeklarasian dari tipe data dictionary. Kemudian, bagaimana dengan cara mengakses informasi dari tipe data ini?

![download](https://user-images.githubusercontent.com/20697667/159660447-d6c1922d-9ea7-4a7e-accb-53bfc445620c.png)

Dengan mencoba potongan code ini pada live code editor, maka aku akan mendapatkan output: 

![image](https://user-images.githubusercontent.com/20697667/159660555-2f11e20c-3d13-4a36-b4da-ac41a1521a76.png)

Untuk mengakses elemen dari sebuah _dictionary_, aku hanya perlu menspesifikasikan kata kunci yang terdapat dalam _dictionary_ tersebut.

 

Tugas:
Menggunakan tipe data _mapping_, aku diminta Senja untuk menampilkan nama & pekerjaan John Doe, seorang _Programmer_.

```python
person = {'nama':'John Doe', 'pekerjaan':'Programmer'}
print(person['nama'])
print(person['pekerjaan'])
```

```
John Doe
Programmer
```

## Tugas Praktek

program kalkulator potongan harga ini untuk beberapa barang sekaligus agar lebih fungsional

![image](https://user-images.githubusercontent.com/20697667/159662930-23e8c371-e76f-47bb-b040-8bf959fa0e09.png)

```python
sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000 }
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000}
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000}
```

## Tugas Praktek

```python
sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000 }
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000}
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000}
daftar_belanja = [sepatu, baju, celana]
```

## Tugas Praktek

Tips 1. # Data yang dinyatakan ke dalam dictionary

Tips 2. # Hitung harga masing-masing data setelah dikurangi diskon

Tips 3. # Hitung harga total

Tips 4. # Hitung harga kena pajak

Tips 5. # Cetak `total_harga + total_pajak`

```python
# Data yang dinyatakan ke dalam dictionary
sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000} 
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000} 
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000}
# Hitunglah harga masing-masing data setelah dikurangi diskon
harga_sepatu = sepatu["harga"] - sepatu["diskon"] 
harga_baju = baju["harga"] - baju["diskon"]
harga_celana = celana["harga"] - celana["diskon"]
# Hitung harga total
total_harga = harga_sepatu + harga_baju + harga_celana
# Hitung harga kena pajak
total_pajak = total_harga * 0.1
# Cetak total_harga + total_pajak
print(total_harga + total_pajak)
```

```
365200.0
```

Python Operators
=

## Pendahuluan

Di dalam Python, operator terbagi ke dalam 6 kelompok:

1. Arithmetic operators

2. Assignment operators

3. Comparison operators

4. Logical operators

5. Identity operators

6. Membership operators

## Arithmetic Operators

Operator arithmetic digunakan pada tipe data numerik, untuk melakukan operasi matematika sederhana yang terdiri atas:

| Simbol Operator | Keterangan | Contoh |
| --- | --- | --- |
| \+ | Penambahan | 3 + 2 akan menghasilkan output: 5 |
| \- | Pengurangan | 4 - 2 akan menghasilkan output: 2 |
| \* | Perkalian | 3 * 2 akan menghasilkan output: 6 |
| \/ | Pembagian | 3 / 2 akan menghasilkan output: 1.5 |
| \% | Modulo/sisa bagi | 3 % 2 akan menghasilkan output: 1. dikarenakan 3 tidak habis dibagi 2 dan menyisakan 1. 8 % 2 akan menghasilkan output: 0. dikarenakan 8 habis dibagi 2 |
| \** | Pangkat | 3 ** 2 akan menghasilkan output: 9 |
| \// | Pembagian dengan pembulatan ke bawah | 3 // 2 akan menghasilkan output: 1. dikarenakan 1.5 akan menjadi 1 saat dibulatkan ke bawah. |

## Assignment Operators

Operator assignment digunakan untuk mendeklarasikan nilai secara langsung ke suatu variabel.

| Simbol Operator | Keterangan                           | Contoh                                                                         |
| --------------- | ------------------------------------ | ------------------------------------------------------------------------------ |
| +=              | Penambahan                           | `x = 3` `x += 2` ekivalen dengan x = x + 2 akan mengubah nilai x menjadi 5     |
| \-=             | Pengurangan                          | `x = 3 ` `x -= 2` ekivalen dengan x = x - 2 akan mengubah nilai x menjadi 1    |
| \*=             | Perkalian                            | `x = 3` `x \*= 2` ekivalen dengan x = x \* 2 akan mengubah nilai x menjadi 6   |
| /=              | Pembagian                            | `x = 3` `x /= 2` ekivalen dengan x = x / 2 akan mengubah nilai x menjadi 1.5   |
| %=              | Modulo/sisa bagi                     | `x = 3` `x %= 2` ekivalen dengan x = x % 2 akan mengubah nilai x menjadi 1     |
| \*\*=           | Pangkat                              | `x = 3` `x \*\*= 2` ekivalen dengan x = x \*\* 2 akan mengubah nilai x menjadi 9 |
| //=             | Pembagian dengan pembulatan ke bawah | `x = 3` `x //= 2` sama dengan x = x // 2 akan mengubah nilai x menjadi 1       |

## Comparison Operators

Operator comparison dapat digunakan untuk membandingkan dua buah nilai, berikut merupakan contoh-contoh operator komparasi.

| Simbol Operator | Keterangan                   | Contoh                                                                                                                                                                                                                                                     |
| --------------- | ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `==`             | Persamaan                    | `33 == 33 akan menghasilkan output: True dikarenakan benar 33 sama dengan 33` `34 == 33 akan menghasilkan output: False dikarenakan 34 tidak sama dengan 33`                                                                                               |
| `!=`              | Pertidaksamaan               | `34 != 33 akan menghasilkan output: True dikarenakan benar bahwa 34 tidak sama dengan 33` `33 != 33 akan menghasilkan output: False dikarenakan 33 sama dengan 33`                                                                                        |
| `>`              | Lebih besar dari             | `34 > 33 akan menghasilkan output: True dikarenakan 34 lebih besar dari 33` `33 > 34 akan menghasilkan output False dikarenakan tidak benar 33 lebih besar dari 34`                                                                                     |
| `<`               | Lebih kecil dari             | `33 < 34 akan menghasilkan output True dikarenakan benar 33 lebih kecil dari 34` `34 < 33 akan menghasilkan output: False dikarenakan tidak benar 34 lebih kecil dari 33`                                                                                    |
| `>=`             | Lebih besar atau sama dengan | `34 >= 33 akan menghasilkan output True dikarenakan 34 lebih besar dari 33` `34 >= 34 akan menghasilkan output True dikarenakan 34 sama dengan 34` `33 >= 34 akan menghasilkan output False dikarenakan 33 tidak lebih besar dari 34 dan tidak sama dengan 34` |
| `<=`              | Lebih kecil atau sama dengan | `33 <= 34 akan menghasilkan output True dikarenakan 33 lebih kecil dari 34` `33 <= 33 akan menghasilkan output True dikarenakan 34 sama dengan 33` `34 <= 33 akan menghasilkan output False dikarenakan 34 tidak lebih kecil dari 33 dan tidak sama dengan 34` |

## Logical Operators

Operator logical digunakan untuk menggabungkan beberapa nilai kebenaran atas suatu statemen logika.

| Simbol Operator | Keterangan | Contoh |
| --- | --- | --- |
| `and` | dan - menerima dua nilai kebenaran dan mengembalikan nilai benar jika keduanya benar | `x = 5` `x >= 1 and x <= 10` akan mengembalikan nilai True `x = 5` `x >= 1 and x <= 4` akan mengembalikan nilai **False** |
| `or` | atau - menerima dua nilai kebenaran dan mengembalikan nilai benar jika salah satu benar | `x = 3` `x >= 1 or x <= 2` akan mengembalikan nilai **True** dikarenakan statemen logika pertama terpenuhi `x = 3` `x >= 5 or x <= 0` akan mengembalikan nilai **False** dikarenakan kedua statemen logika tidak terpenuhi (bernilai False) |
| `not` | negasi - menerima sebuah nilai kebenaran dan mengembalikan komplemennya | `x = 7` `not(x == 7)` akan mengembalikan nilai **False** `not(x >= 10)` akan mengembalikan nilai **True** |

## Identity Operators
## Membership Operators
## Nilai Prioritas Operator dalam Python – Part 1
## Nilai Prioritas Operator dalam Python – Part 2
## Quiz
## Tugas Praktek


Pythons Conditioning & Looping
=

Mini Quiz
=
