<P>NAMA : MOHAMAD SONY HIDAYATULLAH</P>
<P>NIM : 312410290</P>
<P>KELAS : TI 24 A 4</P>
<P>MATKUL : BAHASA PEMROGRAMAN</P>

# Struktur Kondisi
Pada python dikenal penggunaan struktur kondisi menggunakan statement `if`, Konsep pemrograman yang memungkinkan program untuk mengambil keputusan berdasarkan kondisi atau pernyataan tertentu. Struktur seleksi kondisi yang umum digunakan dalam Python 

<p>If : Kondisi utama</p>
<p>Else if : Kondisi kedua atau ketiga hingga ke-x</p>
<p>Else : Kondisi terakhir jika semua kondisi sebelumnya tidak terpenuhi </p>

## Menentukan Nilai Akhir
```Python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]

if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"

print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````

Untuk menentukan nilai akhir pada Python, Anda bisa menggunakan pernyataan `return` untuk menandai akhir fungsi atau Menggunakan fungsi `print()` dan menentukan nilai yang akan dikembalikan. Pernyataan `return` dapat mengembalikan berbagai jenis data, seperti `integer`, `float`, `string`, `list`, `dictionary`, dan fungsi lainnya. Untuk menentukan nilai akhir dalam Python, Anda bisa membuat program yang menghitung nilai akhir berdasarkan pembobotan nilai. 

```Python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````
Fungsi `input()` dalam Python berfungsi untuk mengambil informasi dari pengguna melalui papan ketik. Fungsi ini membuat program menjadi lebih interaktif.

```Python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````
Fungsi integer `int` dalam bahasa pemrograman adalah menyimpan nilai numerik dalam bentuk bilangan bulat positif atau negatif. Integer merupakan tipe data yang paling umum digunakan oleh programmer untuk menyimpan angka tanpa komponen desimal atau pecahan.

Untuk yang diatas Nilai `int` di `*` dalam bahasa manusia itu di kalikan, Yang artinya "Input Integer dikalikan ` .2` yang aktinya 0,2 yang Hasilnya akan keluar bagaimana mestinya 

<p> Contoh nilai tugas yang di masukan 100, nanti akan dikalikan dengan program diatas .2 yang artiya (0,2) akan keluar cetakan 20  </p>

```Python
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````

Keterangan ini hanya sebuah variable yang nantiya aka di cetakan, dan di hasil akhir akan mengproses [variable akhir lebih besar dari 60.0]

```Python
if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"
````

Ini adalah Struktur Kondisi Yang Menggunakan `If`, `Elif`, dan `Else`

```Python
if akhir > 80:
huruf = "A"
````

Jika Hasil dari variable (Akhir) Lebih besar dari 80 maka output yang keluar (A), dan seterusnya begitu dalam bahasa manusia

```Python
else:
huruf = "E"
````

Jika tidak sesuai semuanya pada program diatas output akan keluar (E)


```Python
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````

Fungsi `Print()` ini aka mencetak Variable-Variable program tersebut

## Menampilkan Status Gaji Karyawan
```Python
gaji = int(input("Masukkan gaji:"))
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]


if gaji > 3000000:
    print ("Gaji sudah diatas UMR")
    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
    if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
else:
    print ("Gaji belum UMR")
````
Struktur Kondisi Ini menggunakan desision `if, `elif`, dan `else`

```Python
gaji = int(input("Masukkan gaji:"))
````

Inputan ini akan memasukan angka Gaji, Karna memiliki fungsi `integer`

```Python
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]
````

Inputan ini menggunakan fungsi `string` yang dimasukan berupa Huruf, dan `(False, True)` ini adalah fungsi pemilihan Y atau T, supaya tidak menggunakan if dilanjutan program tersbut

```Python
if gaji > 3000000:
    print ("Gaji sudah diatas UMR")
    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
````

Jika angka gaji lebih dari 3 juta maka Output yang akan keluar "Gaji sudah diatas UMR", dan jika tidak Output yang keluar "Tidak perlu ikutan asuransi"

```Python
if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
````
Jika Memiliki rumah `Output` yang keluar "Wajib bayar Pajak", jika tidak `output` yang keluar "Tidak wajib bayar pajak"

```Python
else:
    print ("Gaji belum UMR")
````

`else` yang dibawah sendiri ini terhubung dengan `if Gaji > 3000000:`, karna kalau gaji tidak melebihi 3 juta `Output` yang keluar "Gaji belum UMR"

## Menggunakan kondisi or dengan menginputkan 3 bilangan
```Python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
Operator or dalam Python mengevaluasi beberapa kondisi dan mengembalikan True jika salah satu kondisinya benar.

```Python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
````

Program ini akan menginputkan sesuatu `integer` yang menggunakan variable a, b, c.

```python
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````

Jika (a) ditambah (b) hasilnya (c) atau yang bahasa programnya itu `or` (b) ditambah (c) hasilnya a, atau (c) ditambah (a) hasilnya (b), Maka Output yang keluar ialah "BENAR".
<p>Jika tidak sesuai dengan program Output akan Keluar "SALAH"</p>

# Latihan 3
## Pemesanan Tiket Bioskop

![soal pemesanantiket](https://github.com/user-attachments/assets/a530e1ae-d00e-475e-a48d-2e899dee9eb5)

```Python
# harga_reguler = 50000
# harga_vip = 100000

# tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
# status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))

if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    total_harga = None

# Menghitung diskon jika pengguna memiliki kartu member
if total_harga is not None:
    if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
    print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
````


