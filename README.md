# Pertemuan-12
# OOP

## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Ariq ibtihal |
| **NIM** | 312310446 |
| **Kelas** | TI.22.A.5 |
| **Mata Kuliah** | Bahasa Pemrograman |

### Tugas Praktikum
Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah 
class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:
- Method tambah() untuk menambah data
- Method tampilkan() untuk menampilkan data
- Method hapus(nama) untuk menghapus data berdasarkan nama
- Method ubah(nama) untuk mengubah data berdasarkan nama

![Alt text](Gambar/image.png)

- Membuat `class mahasiswa():` dengan instance class  

![Alt text](Gambar/image-1.png)

- Menambahkan method / fungsi, pada data inputan `Nama`, `NIM`, `UTS`, `UAS`, `Tugas`.


![Alt text](Gambar/image-2.png)

- Menampilkan method / fungsi. `f` = Format

![Alt text](Gambar/image-3.png)

- Menghapus data yg sudah di input. `del self.nama[index]` = menghapus nama
- `[index]` Berfungsi agar inputan menjadi onject


- Mengubah data yg sudah di input
- `index = self.nama.index(nama)` Membuat variable index dengan `self.nama` di dalam ny

![Alt text](Gambar/image-4.png)

`` Python
print("="*20)
print("|PROGRAM INPUT DATA|")
print("="*20)

data = mahasiswa()
`
while True: 
    print()
    menu = input("[(T)ambah, (L)ihat, (H)apus, (U)bah, (K)eluar] : ")
    print("~"*78)
    print()

![Alt text](Gambar/image-5.png)

- Perulangan dengan memilih [T/L/H/U/K] untuk menjalankan program apa yg ingin di gunakan.

### Hasil Program 

#### Menambahkan data 
![Alt text](Gambar/image-6.png)
#### Melihat data
![Alt text](Gambar/image-7.png)
#### Menghapus data
![Alt text](Gambar/image-8.png)
#### Mengubah data
![Alt text](Gambar/image-9.png)
#### Keluar
![Alt text](Gambar/image-10.png)
### FLowchart 
!![Alt text](Gambar/FLOWCHART.png)
# Terima kasih
