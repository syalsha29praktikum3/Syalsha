 1. Buat flowchart untuk menentukan bilangan terbesar dari 3 buah bilangan yang diinputkan Jawaban

~Definisi Fungsi: def cari_terbesar_dari_tiga():
-Program dimulai dengan mendefinisikan sebuah fungsi bernama cari_terbesar_dari_tiga
-Fungsi ini tidak memiliki parameter.

~Input Pengguna:
-Program meminta pengguna memasukkan tiga bilangan
-float() digunakan untuk mengkonversi input (yang awalnya string) menjadi bilangan desimal
-Bilangan-bilangan tersebut disimpan dalam variabel a, b, dan c

~Output:
-Program mencetak bilangan terbesar yang ditemukan
-Menggunakan f-string untuk memformat output

~Pemanggilan Fungsi:
cari_terbesar_dari_tiga()
Program diakhiri dengan memanggil fungsi yang telah didefinisikan

2. Buat flowchart untuk menentukan bilangan terbesar dari N bilangan yang diinputkan, untuk menentukan jumlah N, berikan masukan angka 0 Jawaban

~Definisi Fungsi: def cari_terbesar_dari_n():
-Program dimulai dengan mendefinisikan fungsi bernama cari_terbesar_dari_n
-Fungsi ini akan mencari nilai terbesar dari N bilangan yang dimasukkan pengguna.

~Inisialisasi Variabel:
-Membuat variabel terbesar dengan nilai awal negatif tak hingga (-inf)
-Ini memastikan bahwa bilangan pertama yang dimasukkan akan selalu lebih besar dari nilai awal

~Input Jumlah Bilangan:
-Meminta pengguna memasukkan berapa banyak bilangan yang akan dibandingkan
-Input dikonversi ke integer menggunakan int()

~Pengecekan Input Awal:
-Jika pengguna memasukkan 0, program akan menampilkan pesan dan mengakhiri fungsi
-Return digunakan untuk keluar dari fungsi

~Perulangan dan Perbandingan:
-Menggunakan loop for untuk meminta input sebanyak N kali
-Setiap input dikonversi ke float dan dibandingkan dengan nilai terbesar saat ini
-Jika bilangan yang baru dimasukkan lebih besar, nilai terbesar diperbarui

~Output Hasil: 
-Setelah semua bilangan dimasukkan, program mencetak bilangan terbesar yang ditemukan

~Pemanggilan Fungsi: cari_terbesar_dari_n()
-Program diakhiri dengan memanggil fungsi yang telah didefinisikan
