# Program 1 Menemukan Bilangan Terbesar dari 3 Variabel
Program 1 untuk menentukan bilangan terbesar dari tiga angka yang diberikan oleh pengguna. Dengan menggunakan struktur kontrol sederhana, program ini akan membandingkan ketiga bilangan dan mengidentifikasi mana yang memiliki nilai tertinggi.

## Deskripsi Program 1
Program ini di buat menggunakan bahasa Python dengan fitur:
* Minta pengguna untuk memasukkan tiga bilangan.
* Simpan nilai-nilai tersebut ke dalam variabel.
* Bandingkan ketiga variabel menggunakan struktur if untuk menentukan nilai maksimum.
* Tampilkan hasilnya ke layar.

## Flowchart Programan
![Flowchart](Flowchart1.png)

## Cara Kerja Program 1
Program meminta pengguna untuk memasukkan tiga angka yang disimpan dalam variabel a, b, dan c. Program menggunakan struktur kondisi if untuk membandingkan nilai dari ketiga variabel tersebut. melakukan pengecekan dengan urutan:
-Program memeriksa apakah a lebih besar dari b.
-Jika benar (a > b), program melanjutkan untuk membandingkan a dengan c.
-Jika a juga lebih besar dari c, maka a adalah yang terbesar, sehingga variabel terbesar diisi dengan nilai a.
-Jika a tidak lebih besar dari c, maka c adalah yang terbesar, sehingga variabel terbesar diisi dengan nilai c.
-Jika salah (a <= b), program melanjutkan ke langkah berikutnya.

## Kode Program
```python
a = int(input ("masukan angka: "))

b = int(input ("masukan angka: "))

c = int(input ("masukan angka: "))

if a > b:
    if a > c :
        terbesar = a
    else:
        terbesar = c       
else:
    if b > c:
        terbesar = b
    else:
        terbesar = c

print ( f"Bilangan terbesar adalah {terbesar}")
```

## Output Program
````
masukan angka: 100
masukan angka: 200
masukan angka: 300
Bilangan terbesar adalah 300
