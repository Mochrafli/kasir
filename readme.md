## Deskripsi Aplikasi 
Source Code Aplikasi Penjualan Barang sederhana berbasis Website dengan PHP & MYSQL.
<br>
<br>
Source Blog : <a href="https://www.codekop.com/read/source-code-aplikasi-penjualan-barang-kasir-dengan-php-amp-mysql-gratis.html" target="_blank">
https://www.codekop.com/read/source-code-aplikasi-penjualan-barang-kasir-dengan-php-amp-mysql-gratis.html</a>
<br>
<br>
<span style="color:red"><b> * Untuk Reuploader Source Code tolong cantumin sumber juga ya, terima kasih :)</b></span>

## Setting Koneksi PHP
setting koneksi di config.php dan ganti username, password dan dbname nya

## Penggunaan Login
Username : admin
<br/>
Password : 123
<br>
<span style="color:red">* Penggunaan Login untuk <b>single User</b> </span>

## Contoh Program 
## 📸 Tampilan Aplikasi Kasir

### 🔐 Login
<img src="assets/img/pic/Login.png">

### 📊 Dashboard
<img src="assets/img/pic/Dashboard.png">

### 📦 Data Barang
<img src="assets/img/pic/Data barang.png">

### 🗂️ Data Kategori
<img src="assets/img/pic/Data katagori.png">

### 🛒 Keranjang / Transaksi
<img src="assets/img/pic/keranjang penjualan.png">

### 📑 Laporan Penjualan
<img src="assets/img/pic/laporan penjualan.png">

### 🏪 Pengaturan Toko
<img src="assets/img/pic/pengaturan toko.png">

### 👤 Profil Pengguna
<img src="assets/img/pic/Profil pengguna.png">


## Changelog
31 Januari 2021<br>
- Tambah Sortir khusus stok kurang dari >= 3
- Cari Per Tanggal Laporan 
- Cari Per bulan Laporan
- Fix Perhitungan Laporan

06 Oktober 2020<br>
- revisi session error pada hosting dengan error : 
Warning: session_start(): Cannot send session cookie - headers already sent by (output started at [duplicate] -> fixed
- Ganti background login, header
- Ganti Header table barang, table keranjang, table laporan
- Fix transaksi -> transaksi stok < keranjang tidak bisa diproses
- penghapusan trigger sql
- penambahan fungsi transaksi untuk pengurangan stok barang setelah transaksi bayar 

23 Agustus 2020<br>
- revisi print
- menambahkan alert telah di bayar di bagian bayar transaksi penjualan

18 Juli 2020<br>
- fix edit kategori
- fix modal tambah barang
- rapihin form laporan

29 Agustus 2019 <br>
- laporan tampilan error  -> fixed
- klik button bayar transaksi  tidak masuk ke laporan -> fixed
- pencarian barang pada menu transaksi sudah otomatis dengan tambahan jquery ajax
- data laporan dapat dicari berdasarkan periode bulan dan tahun

<br>
** Jika ada issues atau revisi atau menambahkan fitur silahkan pull request di repository ini

## Contributors
<a href="https://fauzan.codekop.com/"> Fauzan Falah</a>

My Blog : <a href="https://www.codekop.com/"> Codekop.com</a>

Gunakan Aplikasi dengan bijak, dan Selamat Belajar
