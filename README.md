# TheCashier
Aplikasi ini merupakan aplikasi untuk menghitung checkout pembayaran.

## Fungsionalitas
- User dapat memasukkan Nama Item, menentukan Tipe Jasa atau Barang, memasukkan harga(rupiah) barang atau jasa
- User dapat menekan tombol "tambahkan" untuk memasukkan item ke dalam daftar item.
- User dapat melihat daftar item, quantity, price, dan subtotal.

## Penjelasan Code
Terdapat dua kelas yaitu kelas Item dan Calcuator
Kelas Item

...
using System;
using System.Collections.Generic;
using System.Text;

namespace TheCashier
{
    class Item
    {
        private int id;
        public string title { get; set; }
        public int quantity { get; set; }
        public double price { get; set; }
        public double subtotal { get; set; }
        private string type;
       public Item(int id, string title, int quantity, string type, double price) 
        {
            this.id = id;
            this.title = title;
            this.quantity = quantity;
            this.type = type;
            this.price = price;
        }

        public string getTitle()
        {
            return title;
        }

        public int getQuantity()
        {
            return quantity;
        }

        public string getType()
        {
            return type;
        }

        public double getPrice()
        {
            return price;
        }

        public double getSubTotal()
        {
            subtotal = price * quantity;
            return subtotal;
        }
    }
}
...
kelas itu
