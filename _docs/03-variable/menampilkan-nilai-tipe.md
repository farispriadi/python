---
title: Menampilkan Nilai dan Tipe Variable
category: Variable
order: 3
---

# Menampilkan Nilai Variable

Setelah kita sudah dapat membuat variable yang valid, kita akan mencoba menampilkan variable dengan perintah `print`

```python

nama_lengkap = "Faris Priadi"

print(nama_lengkap)

```

Dengan menggunakan fungsi `print` kita bisa menampilkan nilai dari sebuah variable.
Kita juga bisa menampilkan beberapa variable sekaligus.

```python

nama_lengkap = "Faris Priadi"
nilai = 100
print(nama_lengkap,nilai)

```

Hasil setelah dieksekusi
```

Faris Priadi 100

```

Ketika dua variable tersebut ditampilkan secara default akan dipisahkan dengan spasi.

Kita juga bisa mengganti penghubung antara kedua variable tersebut dengan karakter koma pada saat ditampilkan, dengan menambahkan *keyword argument* `sep`.

```python

nama_lengkap = "Faris Priadi"
nilai = 100
print(nama_lengkap,nilai,sep=',')

```

Hasil setelah dieksekusi
```

Faris Priadi,100

```

Kita juga bisa membuat agar tampilan menjadi sebuah kalimat utuh dengan bantuan format.

```python

nama_lengkap = "Faris Priadi"
nilai = 100
print("Ujian matematika {} mendapatkan nilai {}.".format(nama_lengkap,nilai))

```

Hasil setelah dieksekusi
```

Ujian matematika Faris Priadi mendapatkan nilai 100.

```

# Menampilkan Type Variable

Untuk menampilkan type variable kita bisa gunakan fungsi `type` dan menampilkannya dengan fungsi `print`.

```python

nama_lengkap = "Faris Priadi"
nilai = 100

print(type(nama_lengkap))
print(type(nilai))

```

Hasil setelah dieksekusi
```

<class 'str'>
<class 'int'>

```

Dari penampilan tipe variable di atas kita bisa tahu bahwa tipe data dari nilia dalam variable `nama_lengkap` adalah `str` atau string. Sedangkan variable `nilai` bertipe data `int` atau integer atau bilangan bulat.

Setelah sesi ini kita kan lanjut untuk membahas masing-masing tipe data di dalam bahasa pemrograman Python.


Sebelum lanjut, kira-kira tipe data apa yang akan muncul ketika kode di bawah dieksekusi ya ?

```python

var1 = True
var2 = 100.

print(type(var1))
print(type(var2))

```
