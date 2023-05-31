---
title: Aturan Pembuatan Variable Python
category: Variable
order: 3
---

```python

1var = 5.1

var1 = 2

nama_lengkap = "Faris Priadi"

```

**Penulisan mana yang kira2 akan menghasilkan error ?**


Penulisan variable dalam bahasa pemrograman Python mempunyai beberapa aturan. 

1. variable hanya boleh diawali dengan huruf (a-z atau A-Z) atau *underscore* (`_`).
2. jika variable lebih dari satu kata bisa dipisahkan dengan *underscore* (`_`)  bukan bukan oleh karakter spasi.
3. variable harus diberi nama yang dapat membedakan antara variable satu dan lainnya.
4. penamaan variable pada python sebaiknya menggunakan *lower case* atau huruf kecil, karena merupakan konvensi yang termaktub dalam PEP-8.
5. variable dapat langsung diisi dengan nilainya, tidak perlu medeklarasikannya dengan tipe data terlebih dahulu.
6. nama variable tidak boleh sama dengan nama fungsi, nama modul atau keyword bawaan python.
beberapa nama seperti : for, while, break, if, elif, else, in, as, list, type, not, pass, try, except, finally, print, raise, lambda, global, import, from, class, def, return, is, or, and, continue, del, exec, assert, math, sin, asin, pi, acos, cos, int, float, bool, True, False, tuple, dict.


Kembali ke 2 contoh kode di atas. Pada variable `1var` berdasarkan aturan di atas, harusnya akan mendapatkan *error* ketika dieksekusi.

Sedangkan pada variable `var1` dan `nama_lengkap`, karena penamaan tidak diawali dengan angka dan ada pemisah menggunakan `_` maka variable `var1` dan `nama_lengkap` adalah nama yang valid untuk sebuah nama variable.

Namun hanya **aturan nomor 1, 2 dan 6** saja yang menghasilkan error, sedangkan aturan nomor 3-5 tidak menghasilkan error. Hanya saja tidak mengikuti kaidah umum penamaan variable di Python, dan jika tidak diikuti teman-teman akan bermasalah kita berkolaborasi dengan programmer yang lain.


Kalau pada contoh di bawah ini, variable mana yang tidak sesuai dengan aturan penulisan  ?

```python

nama = "Budi"

Nama = "Ani"

try = "Coba"

int = 10

nilai = 9.5

```