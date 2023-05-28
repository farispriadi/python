---
title: Indentasi
category: Sintaks Python
order: 3
---

Hal lain yang membedakan bahasa pemrograman Python dengan bahasa yang lain adalah penggunaan indentasi.

Indentasi dalam python adalah bagian kosong pada awal baris kode, yang menjadikan kode terlihat menjorok ke dalam.

indentasi dapat menggunakan karakter 1 tab atau 4 spasi, yang menandakan kode tersebut berada dalam satu blok kode.

Blok kode adalah sebuah kode yang terdiri dari beberapa perintah program atau _statement_ yang dijadikan satu kelompok.




Berikut contoh satu blok kode.

```python

if 5 > 0:
    print("5 lebih besar dari 0")

```

atau 

```python

for i in [1,2,3,4,5]:
    x = i*10
    print("{}x10 = {}".format(i,x))

```


Sedangkan perintah program atau _statement_ adalah instruksi spesifik yang dikirim ke komputer. Perintah program dapat berupa pengisian nilai, pemanggilan fungsi atau pemanggilan kata kunci lainnya.

Contoh satu perintah program.

```python

print("5 lebih besar dari 0")

```


### Apa yang terjadi jika dalam satu blok kode tidak terdapat indentasi?

Silakan teman-teman coba copy blok kode di bawah lalu jalankan menggunakan Replit.


```python

for i in [1,2,3,4,5]:
x = i*10
print("{}x10 = {}".format(i,x))

```