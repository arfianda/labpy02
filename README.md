# **Membuat Program dan Flowchart dari program Tiket Bioskop dan juga Kalkulator**

Tugas Pertemuan Ke 6

Nama: Arfianda Firsta Satritama

Kelas: TI 24 A3

NIM: 312410377

# 1. Tiket Bioskop

Program tiket bioskop ini adalah program untuk menghitung harga Tiket bioskop. Konsepnya adalah jika user memiliki kartu member maka user akan mendapatkan diskon 20%

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

3.  Input status member

```
status_member = input("Apakah anda memiliki kartu member? (y/n): ")
```

Program akan meminta input status member dari user.

4. Harga dasar tiket menggunakan operator ternary

```
harga_dasar = 50000 if tipe_tiket == "1" else 100000
```

Jika _tipe_tiket="1"_ maka _harga=50000_ , jika tidak maka harga=100000

5. Hitung Diskon

```
diskon = 0.2 if status_member.lower() == "y" else 0
```

Jika _status_member="y"_ maka _diskon=0.2_ (20%), jika tidak maka diskon=0

6. Menghitung total harga

```
total_harga = harga_dasar - (harga_dasar * diskon)
```

Menghitung total harga setelah diskon

7. Menampilkan output dari input yang dimasukkan user

```
print("\n=== Detail Pembayaran ===")
print(f"Tipe Tiket: {'Reguler' if tipe_tiket == '1' else 'VIP'}")
print(f"Status Member: {'Ya' if status_member.lower() == 'y' else 'Tidak'}")
print(f"Harga Dasar: Rp{harga_dasar:,.0f}")
print(f"Diskon: {diskon*100:.0f}%")
print(f"Total Harga: Rp{total_harga:,.0f}")
```

# 2. Kalkulator sederhana

Program ini adalah program Kalkulator sederhana yang berfungsi untuk menghitung dua angka sesuai dengan operasi hitung yang dipilih.

**Flowchart dari Program Kalkulator sederhana**

<img src="/.img/kalkulator.drawio.png" width="500" alt="Kalkulator">

**Program akan meminta input angka dan Operator perhitungan**

<img src="/.img/KALKULATOR.png" width="500" alt="Kalkulator">

**Contoh apabila kita memilih Operasi hitung Penjumlahan**

<img src="/.img/penjumlahan.png" width="500" alt="Kalkulator">





