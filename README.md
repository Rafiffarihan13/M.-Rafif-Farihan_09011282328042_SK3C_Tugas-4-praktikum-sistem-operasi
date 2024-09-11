# Nama : M. Rafif Farihan
# Nim : 09011282328042
# Kelas : SK3C
# Praktikum sistem operasi

## 1. Melihat Peralatan I/O dan Character Device dengan `iostat`
Perintah `iostat` digunakan untuk melihat informasi mengenai peralatan **I/O** dan **character device** yang ada pada sistem komputer. Hasil dari perintah tersebut dapat dilihat pada gambar berikut:
![Lihat Peralatan I/O](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/1.png)
## 2. Membuat Subdirektori Januari, Februari, dan Maret Sekaligus
Perintah `mkdir` digunakan untuk membuat beberapa subdirektori (Januari, Februari, Maret) sekaligus dalam direktori latihan5. Gambar di bawah ini menunjukkan hasil perintah tersebut:
![Membuat Subdirektori](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/2.png)
## 3. Membuat File "dataku" dan Menyalin ke Subdirektori Lain
File **dataku** dibuat menggunakan perintah `touch` dan kemudian diedit menggunakan editor teks **nano** untuk menyimpan nama, NIM, dan alamat. Setelah itu, file tersebut disalin ke subdirektori Februari dan Maret dengan perintah `cp`. Berikut hasilnya:
![Membuat dan Menyalin File](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/3.png)
## 4. Mengubah Izin Akses File "dataku" di Januari
Perintah `chmod` digunakan untuk memberikan hak akses **write** bagi group dan others pada file **dataku** di subdirektori Januari. Berikut hasil perubahannya:
![Mengubah Izin Akses di Januari](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/4.png)
## 5. Mengubah Izin Akses File "dataku" di Februari
Izin akses file **dataku** pada subdirektori Februari diubah sehingga user dapat **read**, **write**, dan **execute**, sedangkan group dan others hanya bisa **read** dan **execute**. Gambar berikut menampilkan hasilnya:
![Mengubah Izin Akses di Februari](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/5.png)
## 6. Mengubah Izin Akses File "dataku" di Maret
Pada subdirektori Maret, semua user diberikan hak akses **write**, **read**, dan **execute** terhadap file **dataku**. Perubahan ini ditunjukkan pada gambar di bawah ini:
![Mengubah Izin Akses di Maret](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/6.png)
## 7. Menghapus Subdirektori Maret
Subdirektori Maret dihapus dengan perintah `rm -r`, seperti yang ditampilkan pada gambar berikut:
![Menghapus Subdirektori Maret](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/7.png)
## 8. Mengubah Kepemilikan dan Hak Akses di Subdirektori Februari
Kepemilikan subdirektori Februari diubah sehingga user dan group hanya dapat melakukan **read**, dan percobaan pembuatan direktori baru bernama **haha** pada subdirektori Februari menunjukkan perintah gagal karena batasan izin. Lihat hasilnya pada gambar:
![Mengubah Kepemilikan di Februari](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/8.png)
## 9. Modifikasi Umask pada File "dataku"
Umask dari file **dataku** pada subdirektori Januari diubah menjadi 027, dan kita juga mengecek nilai default-nya. Hasilnya ditunjukkan pada gambar berikut:
![Modifikasi Umask](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/9.png)
## 10. Membuat Link dari File "dataku"
Link dari file **dataku** ke file **dataku.ini** dan **dataku.juga** dibuat, kemudian perintah `ls -l` digunakan untuk mengecek jumlah link yang dihasilkan. Berikut hasil dari operasi ini:
![Membuat Link dari File "dataku"](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_Tugas-4-praktikum-sistem-operasi/blob/main/gambar/10.png)

