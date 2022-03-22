# Lab2Web
## Nama : Prananda Aditya
## NIM  : 312010130
## Kelas : TI.20.A1
## Mata Kuliah : Pemograman Web

# langkah-langkah Praktikum
<br>yang pertama adalah membuka text editor, saya disini menggunakan text editor VSCode.
![p](img/SS1.png)

# 1. Membuka Dokumen HTML
![p](img/SS2.png)
<br>Selanjutnya buka browser untuk melihat hasilnya
![p](img/SS3.png)

# 2. Mendeklarasikan CSS Internal
<br>Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen. Seperti gambar dibawah ini :
![p](img/SS4.png)
<br>Selanjutnya buka browser kembali untuk melihat hasilnya.
![p](img/SS5.png)

# 3. Menambahkan Inline CSS
<br>Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti gambar dibawah ini :
![p](img/SS6.png)
<br>Simpan kembali dan refresh kembali browser untuk melihat perubahannya.
![br](img/SS7.png)

# 4. Membuat CSS Eksternal
<br>Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti gambar berikut :
![p](img/SS8.png)
<br>Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>` seperti gambar berikut :
![p](img/SS9.png)
<br>Selanjutnya refresh kembali browser untuk melihat perubahannya.
![p](img/SS10.png)

# 5. Menambahkan CSS Selector
<br>Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file 
style_eksternal.css, tambahkan kode berikut.
![p](img/SS11.png)
<br>Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.
![p](img/SS12.png)

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS 
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan 
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada 
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan 
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut 
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? 
Berikan penjelasan dan contohnya! ( `<p id="paragraf-1" class="text-paragraf">` )

# jawaban
<br> 1. Saya akan mengubah dan menambah properti dan nilai pada kode CSS, dimulai dari membuat kerangka html nya. Seperti gambar berikut :
![p](img/SS13.png)
<br>Kemudian membuat CSS nya dengan menambahkan nilai dan properti pada kode diatas Disini Saya menambahkan 4 selector kedalam CSS, diantaranya body, h2, .avatar, .header-profile. Masing - masing memiliki fungsi untuk mengatur tampilan pada HTML

<br>Pada selector body saya menambahkan properti, yaitu width, font-size, color, width, DST. Pada selector h2 saya menambahkan properti, yaitu font-width, fonth-size Pada selector .avatar saya menambahkan properti, yaitu width, border-radius Pada selector .header-profile saya menambahkan properti, yaitu justify-content, align-items
![p](img/SS14.png)
<br>Pada hasil tersebut dapat dilihat, pada mode mobile lebar body terlalu ke tengah, karena widht pada selektor body diatur dengan nilai 50% pada ukuran desktop, agar dapat terlihat proporsional pada ukuran mobile dapat ditambahkan selektor @media only screen and (max-width: 760px), dan hasil nya bisa dilihat.
![p](img/SS15.png)

<br>2.Perbedaan antara element h1 {...} dengan #intro h1 {...} adalah : h1 {...} Antuk memberikan style pada semua h1 sedangkan, #intro h1 {...} Awalan simbol hash (#) memungkinkan kita untuk memberikan style pada id. selector id bersifat kaku dan tidak bisa digunakan kembali pada element yang lainnya. Menurut saya lebih baik menggunakan selektor class untuk mendefinisikan element yang ingin diberi nilai.
![p](img/SS16.png)

<br>3.Setelah dilakukan pengujian, deklarasi CSS Inline lebih dahulu tampil di browser, itu dikarenakan permintaan HTTP yang sangat kecil memungkinkan untuk ditampilkan dahulu

<br>Berikut merupakan hasil pengujian deklarasi CSS

<br>CSS Inline `blue`

<br>CSS Internal `red`

<br>CSS Eksternal `yellow`

![p](img/SS17.png)

<br>4.Deklarasi `id="paragraf-1"` akan ditampilkan pada browser, karena selektor id lebih spesifik dari class atau bahkan element P itu sendiri, kecuali jika kita menambahkan property pada inline element P maka selektor id tersebut akan tertimpa, karena inline lebih spesifik daripada id, class, dan element
![p](img/SS18.png)