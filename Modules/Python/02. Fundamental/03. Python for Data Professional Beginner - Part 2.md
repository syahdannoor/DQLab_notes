Python for Data Professional Beginner - Part 2
=

# Collection Manipulation dengan Python

## Apa itu Collection Manipulation? 

Collections manipulation adalah salah satu teknik yang penting untuk dikuasai setiap programmer. Melalui penguasaan materi collections  manipulation, dapat mengolah berbagai tipe data collections dalam Python yang meliputi:

- List
- Tuple
- Set
- Dictionary

## Mengakses List dan Tuple – Part 1 

```python
bulan_pembelian = ('Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember')
print(bulan_pembelian[0])
print(bulan_pembelian[5])
print(bulan_pembelian[-1])
print(bulan_pembelian[-2])
```

```
Januari
Juni
Desember
November
```

## Mengakses List dan Tuple – Part 2 

```python
bulan_pembelian = ('Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember')
pertengahan_tahun = bulan_pembelian[4:8]
print(pertengahan_tahun)
awal_tahun = bulan_pembelian[:5]
print(awal_tahun)
akhir_tahun = bulan_pembelian[8:]
print(akhir_tahun)
print(bulan_pembelian[-4:-1])
```

```
('Mei', 'Juni', 'Juli', 'Agustus')
('Januari', 'Februari', 'Maret', 'April', 'Mei')
('September', 'Oktober', 'November', 'Desember')
('September', 'Oktober', 'November')
```

## Penggabungan Dua atau Lebih List atau Tuple 

```python
list_makanan = ['Gado-gado','Ayam Goreng','Rendang']
list_minuman = ['Es Teh','Es Jeruk','Es Campur']
list_menu = list_makanan + list_minuman
print(list_menu)
```

```
['Gado-gado', 'Ayam Goreng', 'Rendang', 'Es Teh', 'Es Jeruk', 'Es Campur']
```

## Quiz 

```python
harga = [1000, 2500, 5000, 15000, 30000]
print(harga[:-3])
```

```
[1000, 2500]
```

## List Manipulation – Part 1 

Untuk memanipulasi tipe data list, dapat menggunakan sekumpulan fitur yang telah tersedia dalam bahasa pemrograman Python. Merujuk pada tabel di bawah, fitur-fitur untuk melakukan manipulasi data yang terdiri atas 


- `append()`
- `clear()`
- `copy()`
- `count()`
- `extend()`

![DQLab _ Exercise](https://user-images.githubusercontent.com/20697667/159845618-c8908f20-c58a-4a67-bd36-d27296620b8a.png)

```python
# Fitur .append()
print(">>> Fitur .append()")
list_makanan = ['Gado-gado', 'Ayam Goreng', 'Rendang']
list_makanan.append('Ketoprak')
print(list_makanan)
# Fitur .clear()
print(">>> Fitur .clear()")
list_makanan = ['Gado-gado', 'Ayam Goreng', 'Rendang']
list_makanan.clear()
print(list_makanan)
# Fitur .copy()
print(">>> Fitur .copy()")
list_makanan1 = ['Gado-gado', 'Ayam Goreng', 'Rendang']
list_makanan2 = list_makanan1.copy()
list_makanan3 = list_makanan1
list_makanan2.append('Opor')
list_makanan3.append('Ketoprak')
print(list_makanan1)
print(list_makanan2)
# Fitur .count()
print(">>> Fitur .count()")
list_score = ['Budi', 'Sud', 'Budi', 'Budi', 'Budi', 'Sud', 'Sud']
score_budi = list_score.count('Budi')
score_sud = list_score.count('Sud')
print(score_budi) # akan menampilkan output 4
print(score_sud) # akan menampilkan output 3
# Fitur .extend()
print(">>> Fitur .extend()")
list_menu = ['Gado-gado', 'Ayam Goreng', 'Rendang']
list_minuman = ['Es Teh', 'Es Jeruk', 'Es Campur']
list_menu.extend(list_minuman)
print(list_menu)
```

```
>>> Fitur .append()
['Gado-gado', 'Ayam Goreng', 'Rendang', 'Ketoprak']
>>> Fitur .clear()
[]
>>> Fitur .copy()
['Gado-gado', 'Ayam Goreng', 'Rendang', 'Ketoprak']
['Gado-gado', 'Ayam Goreng', 'Rendang', 'Opor']
>>> Fitur .count()
4
3
>>> Fitur .extend()
['Gado-gado', 'Ayam Goreng', 'Rendang', 'Es Teh', 'Es Jeruk', 'Es Campur']
```

## List Manipulation – Part 2 
## Tuple Manipulation 
## Quiz 
## Set Manipulation – Part 1 
## Set Manipulation – Part 2 
## Quiz 
## Dictionary Manipulation 
## Useful Tips and Tricks 
## Tugas Praktek

# String Manipulation dengan Python

## Tinjauan Ulang String pada Python 
## Apa itu String Manipulation? 
## Operator “+” untuk Tipe Data String 
## Menghilangkan Spasi di Awal dan/atau di Akhir 
## Merubah Caps pada String 
## Pemecahan, Penggabungan, dan Penggantian String 
## Menentukan Posisi dan Jumlah Sub-string pada String 
## Menentukan String Apakah Diawali/Diakhiri oleh Sub-string 
## Tugas Praktek 
## Tugas Praktek

# Functions

## Apa itu Functions? 
## Fungsi Pertama 
## Fungsi Kedua 
## Fungsi Ketiga 
## Tugas Praktek 
## Tugas Praktek 
## Tugas Praktek


# Manipulasi Berkas Teks dan Library Matematika pada Python

## Manipulasi Berkas Teks 
## Membaca Berkas Teks – Part 1 
## Membaca Berkas Teks – Part 2 
## Menulis Berkas Teks – Part 1 
## Menulis Berkas Teks – Part 2 
## Quiz 
## Quiz 
## Library Matematika pada Python 
## Fungsi dalam Library Matematika – Part 1 
## Fungsi dalam Library Matematika – Part 2 
## Quiz 
## Quiz


# Mini Quiz

## Pendahuluan 
## Harga Rumah di Tangerang 
## Hasil Belajarku
 
[Python for Data Professional Beginner - Part 2]
