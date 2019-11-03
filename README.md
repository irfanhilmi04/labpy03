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
4. Setelah itu kita memasukkan fungsi untuk menampilkan nilai secara acak
- from random import random
- a = random()
5. Terakhir kita tinggal membuat syntax untuk mengeluarkan hasil dari looping tersebut
- print("Data ke", i, "=>", a)
![Untitled1](https://user-images.githubusercontent.com/56240221/68084832-84896d00-fe6d-11e9-8a75-6cd7f6370d6b.jpg)
## output
![Untitled](https://user-images.githubusercontent.com/56240221/68084875-b1d61b00-fe6d-11e9-9679-cb9ca5dd51b5.jpg)


## Latihan 2
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
![Untitled 2](https://user-images.githubusercontent.com/56240221/68084926-e518aa00-fe6d-11e9-9516-eeb9a44d52a9.jpg)
## output
![Untitled 2 1](https://user-images.githubusercontent.com/56240221/68084947-26a95500-fe6e-11e9-8b1b-2eb5816b22b8.jpg)
## Pemrograman 1
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
![Untitled 3](https://user-images.githubusercontent.com/56240221/68085014-3cb71580-fe6e-11e9-8df9-c9a65d2e9c1e.jpg)
## output 
![Untitled3 1](https://user-images.githubusercontent.com/56240221/68085027-5fe1c500-fe6e-11e9-87c3-9fd2ffa739fe.jpg)
