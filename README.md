# Pertemuan 06 Nested Loop Python

Nama: Angelita Juliana Siahaan
NIM: 2225250112
Kelas: 3B

## Tujuan
Menggunakan nested loop, pola, akumulasi, dan pencacahan.

## Cara Menjalankan
python tugas/tabel_perkalian_dan_statistik.py

## Algoritma Tugas 3
- Loop luar (i): mengatur baris pada tabel.
- Loop dalam (j): mengatur kolom pada setiap baris.
- total_baris: akumulator jumlah per baris, direset di awal setiap baris.
- total_semua: akumulator jumlah seluruh hasil, dibuat sebelum kedua loop.
- count_genap: counter yang bertambah hanya jika hasil genap.

## Hasil Pengujian
| Input n | Hasil yang diharapkan | Keluaran aktual | Status |
|---|---|---|---|
| 1 | Total 1, genap 0 | Total 1, genap 0 | Berhasil |
| 2 | Total 9, genap 3 | Total 9, genap 3 | Berhasil |
| 3 | Total 36, genap 5 | Total 36, genap 5 | Berhasil |

## Analisis Efisiensi
Badan loop dalam berjalan n x n kali. Contoh: n = 3 berarti 9 kali.

## Refleksi
Kesalahan nested loop yang mudah terjadi adalah salah menempatkan total_baris = 0. Jika diletakkan sebelum loop luar, jumlah tiap baris terus bertambah dan tidak mulai dari nol lagi di baris berikutnya. Saya memperbaikinya dengan memindahkan total_baris = 0 ke dalam loop luar, sebelum loop dalam, sehingga direset setiap kali pindah baris. Saya juga belajar bahwa indentasi menentukan apakah sebuah baris berada di dalam loop dalam, di loop luar, atau di luar keduanya.