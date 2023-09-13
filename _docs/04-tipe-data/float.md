---
title: Float (Bilangan Riil)
category: Tipe Data
order: 2
---

Jika kamu melihat di bagian sebelumnya pasti sudah bisa menebak tipe bilangan dari variable di bawah ini.

```python

y = 8.9 


```

Penulisan di atas digunakan menyatakan bilangan riil atau `float`.

Bilangan riil adalah bilangan yang mempunyai pecahan atau koma( atau titik dalam penulisan di Python) di belakangnya.


Cara mengeceknya kita bisa gunakan fungsi `type` untuk mengetahui tipe data apa dari variable di atas.

```python

print(type(y))

```

Hasil setelah dieksekusi akan muncul.
```

<class 'float'>

```

Bilangan riil juga dapat dinyatakan dalam bentuk eksponen seperti contoh di bawah ini.

```python

y = 8.9e-4


```
Variable di atas sama nilainya dengan 0.00089, hanya penulisannya saja dalam bentuk eksponen.


Jika angka dibelakang koma terlalu banyak dan ingin kita bulatkan, kita bisa memakai fungsi `round`

```python

y = 1.23456789
z = round(y)

```
Hasil setelah dieksekusi akan muncul.
```

1

```

Bagaimana klo kita ingin pembulatan dengan 2 angka di belakang koma?

```python

y = 1.23456789
print(round(y,2))

```
Hasil setelah dieksekusi akan muncul.
```

1.23

```


Apa yang yang akan muncul pada output setelah kode di bawah ini di eksekusi ?

```python

y = 4.567890123
print(round(y,3))

```
