# labpy02
# BIODATA
# Nama : Fajar Fawwaz Atallah
# Nim : 312410357
# Kelas : TI.24.A4
# BAHASA PEMROGRAMAN
## Latihan 1
## Membuat Program Nilai Akhir
## Deskripsi
Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.

- 20% untuk nilai tugas
- 40% untuk nilai UTS
- 40% untuk nilau UAS
## PENJELASAN PROGRAM
1. Input: Meminta nama siswa dan nilai UTS, UAS, serta tugas.
2. Perhitungan: Menghitung nilai akhir dengan bobot yang sesuai.
3. Keterangan: Menentukan apakah siswa lulus atau tidak berdasarkan nilai akhir.
4. Penentuan Huruf: Mengonversi nilai akhir menjadi huruf sesuai dengan kriteria yang diberikan.
5. Output: Menampilkan hasil perhitungan
# STRUKTUR PROGRAM
Input:

• Nama siswa

• Nilai UTS (float)

• Nilai UAS (float)

• Nilai Tugas (float)

Output:

• Nama siswa

• Nilai UTS

• Nilai UAS

• Nilai Tugas

• Nilai Akhir

• Nilai Huruf

• Keterangan ("LULUS" atau "TIDAK LULUS")

BERIKUT SCREENSHOT VISUAL
# ![Screenshot 2024-10-25 041102](https://github.com/user-attachments/assets/c40e7100-7e24-4568-a585-b3141d1628cc)

## LATIHAN 2
## MEMBUAT PROGRAM MENAMPILKAN GAJI KARYAWAN
## DESKRIPSI
Program ini menerima input gaji, status keluarga (sudah berkeluarga atau belum), dan status kepemilikan rumah dari pengguna, kemudian melakukan beberapa pengecekan sebagai berikut:

1. Apakah gaji di atas UMR (Upah Minimum Regional).
2. Jika gaji di atas UMR, program akan mengecek apakah pengguna sudah berkeluarga untuk menentukan kewajibam mengikuti asuransi dan menabung.
3. Program juga mengecek apakah pengguna memiliki rumah untuk menentukan kewajiban membayar pajak rumah.

# PENJELASAN PROGRAM
1. Input Data Karyawan:
Program meminta input dari pengguna untuk nama karyawan, gaji pokok, dan total potongan gaji. Menghitung Gaji Bersih:
2. Menghitung Gaji Bersih:
Gaji bersih dihitung dengan mengurangi gaji pokok dengan total potongan:
gaji_bersih
gaji_pokok − potongan
gaji_bersih=gaji_pokok−potongan
3. Output:
Program mencetak rincian gaji karyawan, termasuk nama, gaji pokok, potongan, dan gaji bersih.

## STRUKTUR PROGRAM
Input:

• Gaji (int)

• Status berkeluarga (Y/T)

• Status kepemilikan rumah (Y/T)

• Output:

• Apakah gaji sudah di atas UMR atau belum

• Kewajiban mengikuti asuransi jika sudah berkeluarga

• Kewajiban membayar pajak rumah jika punya rumah

## BERIKUT HASIL SCREENSHOT VISUALCODE
# ![Screenshot 2024-10-25 041614](https://github.com/user-attachments/assets/8fd35475-60f9-42e6-972b-da2c201cd398)

## LATIHAN 3
### PENGGUNAAN KONDISI OR
### DESKRIPSI
Kondisi OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih ekspresi kondisi. Dalam bahasa pemrograman Python, operator ini memungkinkan kita untuk memeriksa beberapa kondisi sekaligus. Jika salah satu atau lebih dari kondisi tersebut bernilai True, maka keseluruhan pernyataan akan dianggap True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False. Penggunaan kondisi OR sangat berguna dalam berbagai situasi di mana beberapa kondisi perlu dievaluasi. Operator ini memudahkan pengambilan keputusan dalam logika program, sehingga membuat kode menjadi lebih ringkas dan efisien. Dengan memahami cara kerja OR, programmer dapat menciptakan skrip yang lebih kompleks dan dinamis.
## PENJELASAN OR
1. Definisi Operator OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih kondisi. Dalam Python, operator ini ditulis sebagai or. Jika salah satu dari kondisi tersebut bernilai True, maka keseluruhan ekspresi juga akan bernilai True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.
  
2. Sintaksis Penggunaan dasar operator OR dalam Python adalah sebagai berikut:
if kondisi1 or kondisi2:
    # lakukan sesuatu

3. Contoh Penggunaan:
A. Pemeriksaan Sederhana Misalnya, kita ingin mengecek apakah sebuah angka berada di luar rentang tertentu:
```Python
angka = 7
if angka < 5 or angka > 10:
    print("Angka tidak dalam rentang 5 hingga 10")
else:
    print("Angka dalam rentang 5 hingga 10")
```
B. Kelayakan dalam Konteks Bisnis Dalam bisnis, kita mungkin perlu memverifikasi kelayakan berdasarkan beberapa syarat:
```Python
gaji = 2500000
memiliki_rumah = True

if gaji > 5000000 or memiliki_rumah:
    print("Kelayakan pinjaman terverifikasi")
else:
    print("Kelayakan pinjaman tidak terpenuhi")
```
