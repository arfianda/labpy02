# **Membuat Program dan Flowchart dari program Tiket Bioskop dan juga Kalkulator**

Tugas Pertemuan Ke 6

Nama: Arfianda Firsta Satritama

Kelas: TI 24 A3

NIM: 312410377

# 1. Tiket Bioskop

Prog tiket bioskop ini adalah program untuk menghitung harga Tiket bioskop. Konsepnya adalah jika user memiliki kartu member maka user akan mendapatkan diskon 20%

**Flowchart dari Program tersebut**

<img src="/.img/bioskop.drawio.png" width="500" alt="Flowchart Bioskop">

**Program akan meminta user untuk menginputkan tipe tiket**

<img src="/.img/BIOSKOP.png" width="500" alt="Flowchart Bioskop">

**Program akan menanyakan status member**

<img src="/.img/diskon1.png" width="500" alt="Flowchart Bioskop">

Jika user memiliki kartu member maka akan dapat diskon 20%

**Output apabila input yang dimasukkan user adalah _N_ atau tidak memiliki member**

<img src="/.img/nodiskon1.png" width="500" alt="Flowchart Bioskop">


**Penjelasan dari code program tiket bioskop**

1.  Perintah dibawah adalah untuk menampilkan judul program dan pilihan tiket yang tersedia.

```
print("=== Program Hitung Harga Tiket Bioskop ===")
print("1. Reguler (Rp50.000)")
print("2. VIP (Rp100.000)")

```

2. Input tipe tiket

```
tipe_tiket = input("Pilih tipe tiket (1/2): ")
```

Program akan meminta input tipe tiket dari user dan menyimpannya di variabel tipe_tiket

