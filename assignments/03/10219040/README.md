# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219040'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined
```

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```
1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
4:◻◻◻◻
0:
```

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```
1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
4:◼◼◼◼
0:
```

## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ Kode di atas berfungsi sebagai konversi angka menjadi kotak sebanyak angka dari variabel "n" sesuai dengan warna yang diinginkan (char1 untuk kotak berwarna putih, char2 untuk kotak berwarna hitam).
+ Kode pada answer 1 terjadi error karena di dalam kode tersebut, "char" tidak terdefinisi, sedangkan "char1" dan "char2" terdefinisi sebagai kotak berwarna putih dan hitam.

Tested on Compiler 
[Answer 1](https://onecompiler.com/python/3xrz4zs73)
[Answer 2](https://onecompiler.com/python/3xrz5vdkr)
[Answer 3](https://onecompiler.com/python/3xrz5x3a6)
