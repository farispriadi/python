---
title: Membuat Variable
category: Variable
order: 1
---

Variable adalah nama untuk menampung nilai tertentu yang mengacu pada objek pada alamat memori tertentu. 

Karena pada dasarnya setiap nilai yang kita definisikan itu disimpan dalam sebuah alamat memeori. 

Alamat memori itu seperti sebuah alamat atau label dari tempat penyimpanan di komputer.

Untuk membuat variable kita memerlukan nama yang unik yang disebut **identifier**, operator *assignment* yaitu tanda `=` dan nilai tertentu.

```python

x = 5
y = 2.5
z = "Python"

```
Contoh diatas adalah variable dengan nama `x` yang diisi dengan nilai `5` yang bertipe `int` dan variable dengan nama `y` yang diisi dengan nilai `2.5` yang bertipe `float`. Sedangkan `z` adalah variable yang diisi dengan nilai berupa teks yang bertime `str`.

Dalam praktiknya, variabel digunakan untuk mempermudah penulisan nilai yang berulang-ulang dalam sebuah kode, sehingga mempermudah dalam pemanggilannya.  Seperti pada contoh  di bawah ini.


```python

a = 5
b = 10
c = 25

x = a + b
y = a + c
z = x + y 

```

Kira-kira berapa hasilnya untuk variable `z` ya ?