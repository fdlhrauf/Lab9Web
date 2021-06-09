# Lab9Web
# Praktikum 9 : Modular
Modularisasi sendiri merupakan proses penyederhanaan program yang kompleks menjadi lebih efisien. Program disusun berdasarkan modul-modul yang berupa function atau prosedur.
Sebagai contoh, dalam pembuatan website terdapat halaman index/utama yang terdiri dari header, konten, dan footer. Apabila halaman index tersebut diselesaikan tanpa menggunakan modul, maka akan hanya ada satu file php saja, namun dengan banyak baris kode program didalamnya. Kendalanya adalah ketika terjadi kesalahan, maka akan terlihat rumit untuk menemukan dan memperbaiki kesalahan tersebut.

Modularisasi didalam PHP terdiri dari:

- Require, merupakan bentuk modular yang digunakan untuk menggabungkan file PHP atau file lain dengan file PHP yang memanggilnya. File yang digabungkan tidak harus script PHP.
- Include, hampir sama dengan require namun bedanya adalah include digunakan untuk menggabungkan file PHP dengan file pemanggilnya. Include dapat digunakan didalam pengulangan untuk memanggil file-file yang berbeda.
- Require_once, pada dasarnya sama dengan require, perbedaannya adalah jika menggunakan require_once apabila terjadi duplikasi fungsi atau duplikasi pemanggilan maka akan terhindar karena require_once akan memaksa PHP untuk menggunakan nama fungsi dan pemanggilan yang telah ada.
- Include_once, hampir sama dengan require_once, perbedaannya adalah include_once apabila dijalankan akan selalu ada evaluasi ulang.

# Langkah-langkah Praktikum

Aktifkan XAMPP

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/xampp.JPG)

Kali ini saya menggunakan App Sublime TEXT

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/sublime.JPG)

Membuat Folder

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/file.JPG)

Lihat hasil akses nya di Crom atau Google

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/indexof.JPG)

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/header2.JPG)

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/home1.JPG)

Hasil ouput Home

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/home.JPG)

Input About

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/about1.JPG)

Output About

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/foto/about.JPG)

# Tugas

Implementasikan konsep modularisasi padakode programpraktikum 8tentang database,sehingga setiap halamannya memiliki template tampilan yang sama.

Membuat file footer.php untuk kemudian di masukan ke index dengan menggunakan require

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/footer1.JPG)

Buat file baru dengan nama header.php

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/header1.JPG)

Menambahkan Style CSS

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/stylecss1.JPG)

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/stylecss2.JPG)

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/stylecss3.JPG)

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/stylecss4.JPG)

Dan lihat Hasil Home nya :

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/home3.JPG)

Hasil Tambah Barang

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/tambah4.JPG)

Hasil Ubah Barang

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/ubah5.JPG)

Untuk Hapus

![imag](https://github.com/fdlhrauf/Lab9Web/blob/main/lab9php/foto/hapus2.JPG)
