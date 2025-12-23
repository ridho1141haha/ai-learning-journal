## Day 1 - Python Core

Hari ini belajar:
- list
- function
- loop
- if else

Catatan:
- function bikin kode lebih rapi
- loop kepake banget buat data

Yang masih bingung:
- kapan pakai function, kapan langsung?

# Challenge 1
+ Kenapa hasil harus list?
-> karena input data berjumlah banyak, maka output juga hrus berjumlah banyak
+ Bisa nggak return langsung tanpa list?
-> bisa, tapi nanti ribet

# Challenge 2
+ refactor code 
`def cek_kelulusan(data):
    pass`

# Refleksi
- Hal yang awalnya kukira gampang ternyata lumayan susah
- Bagian yg sulit itu pas di tanya kenapa harus list?, klo yang refactor code ga terlalu sulit sih
- ai itu sebenernya proses komputasi yang berulang

## Day 2 - Numpy

Hal penting:
- Numpy bisa operasi banyak data sekaligus
- Lebih cepat dari list biasa

Insight:
- AI bukan soal pintar, tapi soal efisiensi
- Teks, gambar, dan suara bukan tidak konsisten, tapi data yang belum dalam bentuk yang bisa dihitung. ML hanya bisa melakukan operasi matematika, tapi bukan berarti ga bisa diolah, sebelum diolah data2 tersebut harus ditermahin ke numerik sehingga ml bisa membaca nya.


## Day 3 - Pandas

Yang kupelajari:
- DataFrame itu seperti tabel pintar
- Filtering dan groupby lebih rapi dari loop

Insight:
- Dunia nyata datanya berantakan
- Pandas bikin chaos jadi bisa diproses

## Day 4 - Data Cleaning

Masalah data:
- nilai ada teks
- ada nilai kosong
- ada data duplikat

Kenapa berbahaya:
- ML tidak bisa hitung teks
- missing value bikin bias
- duplikat bikin model berat sebelah

Insight:
- Data bagus lebih penting dari model keren
- Model tidak pernah salah, Engineer-lah yang salah memilih data.
- Data yang diisi dengan asumsi salah lebih berbahaya karena memberikan informasi palsu kepada model, sehingga model belajar pola yang tidak merepresentasikan kenyataan.


sebenernya ini jadwal buat seminggu, tapi karena gabut jadi cuma sehari hehe.
