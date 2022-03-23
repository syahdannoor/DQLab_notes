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

Python Operators
=

Pythons Conditioning & Looping
=

Mini Quiz
=
