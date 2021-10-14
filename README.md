# TheCashier
Aplikasi ini merupakan aplikasi untuk menghitung checkout pembayaran.

## Fungsionalitas
- User dapat memasukkan Nama Item, menentukan Tipe Jasa atau Barang, memasukkan harga(rupiah) barang atau jasa
- User dapat menekan tombol "tambahkan" untuk memasukkan item ke dalam daftar item.
- User dapat melihat daftar item, quantity, price, dan subtotal.

## Penjelasan Code
Terdapat dua kelas yaitu kelas Item dan Calcuator, berikut penjelasannya:

### Calculator.cs
kelas tersebut merupakan kelas yang berfungsi sebagai operasi perhitungan dalam program ini.

### Item.cs
Kelas tersebut merupakan kelas yang berfungsi sebagai kelas yang mendeklarasikan setiap vaiabel yang diperlukan dan juga terdapat operasi perhitungan sub total.

Lalu ada juga kelas MainWindow.xaml.cs dan MainWindow.xaml yang berguna sebagai konfigurasi antara kelas calculator.cs & Item.cs dengan tampilan program. Berikut penjelasannya:

### MainWindow.xaml.cs
Merupakan kelas penghubung antara tampilan program dengan code program di kelas calculator.cs & item.cs

### MainWindow.xaml
Merupakan kelas yang mengatur tampilan pada program TheChasier
