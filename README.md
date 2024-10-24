# Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.
## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:

- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan

## flowchart programan
  ![Flowchart](flowchart.png)

  # Kode Program
 ```python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan
    bilangan = int(input("masukan bilangan :"))

print (f"bilangan terbesar= {max}")
```

## output Program
````
masukan bilangan :10
masukan bilangan :20
masukan bilangan :40
masukan bilangan :300
masukan bilangan :60
masukan bilangan :0
bilangan terbesar= 300
````

# cara kerja program
adanya variabel max di isi dengan nilai e, 
setelah itu tardapat variabel inputan dengan nama bilangan, 
jika kondisi bilangan tidak sama dengan maka cari bilangan lebih dari max dan variabel max di set dengan bilangan tersebut. 
Jika bilangan lebih kecil dari max maka bilangan input kembali sehingga akan menghasilkan bilangan terbesar dari operasi tersebut.
