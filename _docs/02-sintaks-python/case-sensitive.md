---
title: Case Sensitive
category: Sintaks Python
order: 1
---

Apa yang terjadi jika kode Python di bawah ini dieksekusi ?

```python

x = 5
print(X)

```

Hasilnya akan error, tepatnya _NameError_. 

```bash

Traceback (most recent call last):
  File "main.py", line 2, in <module>
    print(X)
NameError: name 'X' is not defined. Did you mean: 'x'?

```

Pada contoh diatas, sebuah variable 'x' diisi dengan nilai 5. Kemudian dibaris selanjutnya, dengan menggunakan fungsi `print`, program akan menampilkan nilai dari variable yang diisi sebelumnya.

Ternyata yang dipanggil dalam funsi `print` bukanlah variable 'x', namun 'X' dalam bentuk kapital, yang dianggap berbeda oleh Python.

Python menganggap variabel 'X' dengan kapital, belum didefinisikan sebelumnya.

Sehingga menyebabkan Python memunculkan pesan error pada saat dieksekusi.

Hal ini dikarenakan Python bersifat _case sensitive_. Artinya Python adalah bahasa pemrograman yang membedakan antara huruf Kapital dan kecil.

![Case Sensitve](/images/02-sintaks-python/case-sensitive.png)

Case sensitive Python berlaku juga dengan nama fungsi bawaan dan sintaks Python.
Ketika fungsi `print` ditulis diwali dengan huruf kapital maka yang terjadi adalah error.

![Case Sensitve](/images/02-sintaks-python/case-sensitive2.png) 