# TUGAS PRAKTIKUM 3

## Latihan 1
pada latihan 1 kita akan mencari angka terkecil yang kurang dari 0,5
1. Langkah pertama kita membuat syntax untuk memasukan nilai pada N
- num = int(input("Masukan Nilai N:")
2. langkah kedua membuat variable untuk menentukan berapa jumlah data yang kita cari 
- jumlah = num+1
- start = 1
- stop = jumlah
- step = 1
3. Masukan syntax looping for
- for i in range(start, stop, step):

### Latihan 2
1. Memperkenalkan variable x integar, kemudian menginput nilainya
- a = int()
2. Memperkenalkan variable b dengan nilai 0 
- b = 0
3. Looping WHILE apabila nilai X tidak sama dengan 0
- while a >= 0:
4. Program yang akan di looping
- a=int(input("Masukkan Bilangan:")
5. if kondisi apabila nilai a lebih besar dari nilai b
- if a > b:
6. Nilai b sama dengan nilai a
- b = a
7. if kondisi apabila nilai a sama dengan 0 
- if a == 0:
8. Fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai
- break
9. Mencetak bilangan terbesar
- print("Bilangan terbesar adalah",b)
10. Selesai

#### Pemrograman 1
1. Nilai modal
- modal = 100000000
2. Nilai laba 0
- laba = 0
3. Nilai untung 0
- untung = 0
4. perulangan i dengan nilai awal 1, nilai akhir 9 dan step 1
- for i in range (1,9):
5. Kondisi apabila belum bulan ke 3 laba masih 0%
- if (i < 3):
- laba = c
- untung = untung + laba
6.  kondisi apabila belum memasukan bulan ke 5 mendapat laba sebesar 1%
- elif(1 < 5):
- laba = modal*1/100
- untung = untung + laba 
7. kondisi apabila belum memasukan bulan ke 8 mendapatkan laba sebesar 5%
- elif(1<8):
- laba = modal*1/100
- untung = untung + laba
8. Pada bulan ke 8 laba menurun 2% sehingga laba bulan ke 8 sebesar 3%
- else:
- laba = modal*2/100
- untung = untung + laba
9. Mencetak laba per bulan
- print("Laba bulan ke", i, "sebesar:", laba)
10. Menghitung total laba selama 8 bulan 
- print("Total laba adalah:", untung)
11. Selesai
