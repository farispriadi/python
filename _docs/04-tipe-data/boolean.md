---
title: Boolean
category: Tipe Data
order: 3
---

Tipe boolean adalah tipe yang hanya ada pada dua nilai yaitu `True` dan `False`.

Fungsi tipe data ini adalah untuk melakukan evaluasi 2 buah nilai dengan penghubung operator logika.
Sebagai catatan, Operator sendiri akan di bahas di [Chapter Operator]({{site.baseurl}}/05-operator/operator-logical/).

```python

print(7 == 8)
print(type(7 == 8))

```
Kode pada baris pertama akan melakukan evaluasi apakah nilai 7 sama dengan nilai 8.
Kode pada baris kedua akan melakukan hal yang sama, namun akan menampilkan tipe data outputnya.


Setelah dieksekusi akan menampilkan

```

False
<class 'bool'>

```

Pada hasil di atas nilai `False` merupakan nilai dengan tipe boolean.


Bagaimana jika kode di bawah ini dieksekusi?

Output apa yang akan muncul ?

```python

a = 8 != 9
print(a)
print(type(a))

```