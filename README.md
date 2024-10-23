<P>NAMA : MOHAMAD SONY HIDAYATULLAH</P>
<P>NIM : 312410290</P>
<P>KELAS : TI 24 A 4</P>
<P>MATKUL : BAHASA PEMROGRAMAN</P>

# Struktur Kondisi
<p>Pada python dikenal penggunaan struktur kondisi menggunakan statement `if`, Konsep pemrograman yang memungkinkan program untuk mengambil keputusan berdasarkan kondisi atau pernyataan tertentu. Struktur seleksi kondisi yang umum digunakan dalam Python </p>
<P>`If`: Kondisi utama</p>
<p>`Else if`: Kondisi kedua atau ketiga hingga ke-x</p>
<p>`Else`: Kondisi terakhir jika semua kondisi sebelumnya tidak terpenuhi </P>

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
Fungsi input() dalam Python berfungsi untuk mengambil informasi dari pengguna melalui papan ketik. Fungsi ini membuat program menjadi lebih interaktif.

```Python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````
Fungsi integer `int` dalam bahasa pemrograman adalah menyimpan nilai numerik dalam bentuk bilangan bulat positif atau negatif. Integer merupakan tipe data yang paling umum digunakan oleh programmer untuk menyimpan angka tanpa komponen desimal atau pecahan.
<p>Untuk yang diatas Nilai `int` di `*` dalam bahasa manusia itu di kalikan, Yang artinya "Input Integer dikalikan ` .2` yang aktinya 0,2 yang Hasilnya akan keluar bagaimana mestinya</p>
<p>Contoh nilai tugas yang di masukan 100, nanti akan dikalikan dengan program diatas .2 yang artiya (0,2) akan keluar cetakan 20  </p>




