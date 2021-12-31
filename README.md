# labspy03
## Daftar Isi

- Latihan 1
- Latihan 2
- Program 1

# Latihan 1
Program Untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

Penjelasan:

Import module random untuk membuat bilangan acak

```
from random import random
```

Untuk menginput nilai yang ingin dikonversikan kedalam bilangan bulat (Integer) yang akan di masukan kedalam variabel n

```
n = int(input("Masukan Nilai N: "))
```

Untuk pengulangan range yang diinputkan oleh variable n

```
for i in range(n):
    while True:
        n = random()
        if n < 0.5:
```

Menampilkan hasil dari n

```
print(n)
```

# Latihan 2
Program Sederhana Untuk Menentukan Bilangan Terbesar, dari Data N yang diinputkan

Penjelasan:

Deklarasi Variabel

```
n = 0
```

Untuk perulangan sampai waktu yang tidak ditentukan (While Loop)

```
while True:
```

Untuk menginput bilangan yang akan dimasukan kedalam variabel a

```
a = int(input("Masukan bilangan : "))
```

Jika n kurang dari a, maka variabel n = a (angka yang diinputkan)

```
if n < a:
        n = a
```

Jika a = 0, maka perulangan (loop) akan dihentikan dengan fungsi break

```
if a==0:
        break
```
        
Menampilkan hasil bilangan terbesar dari variabel n

```
print("Bilangan Terbesar Adalah", n)
```

# Program 1
Menghitung Total Keuntungan

Penjelasan:

Dari variabel laba terdapat list modal dari bulan pertama hingga akhir

```
modal = 100000000
laba = [modal * 0, modal * 0, modal * 1/100, modal * 1/100, modal * 5/100, modal * 5/100, modal * 5/100, modal * 3/100]
bulan = 0
sum = 0
```

Menampilkan modal pertama yang diambil dari variabel modal

```
print("Modal awal pengusaha",modal)
```

Untuk melakukan perulangan variabel i kedalam variabel laba. agar variabel i mendapat akses list yang ada didalam variabel laba

```
for i in laba:
```

Variabel sum ditambahkan dengan variabel i yang akan diulang hingga program selesai

```
sum = sum + i
```

Variabel bulan, untuk menentukan bulan yang akan ditambahkan dengan nilai 1 terus menerus hingga program berakhir

```
bulan += 1
```

Menampilkan laba dari bulan pertama hingga bulan terakhir

```
print("Laba pada bulan ke -", bulan, "mendapat laba   =", i)
```

Menampilkan keuntungan yang di dapat selama 8 bulan

```
print("Keuntungan yang didapat selama" , bulan, "bulan =", sum)
```
