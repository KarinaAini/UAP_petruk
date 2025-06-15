# UAP_petruk
Kelompok:
- Karina Aini       : 2417051063
- M. Raffi Al-mustafa   : 2457051009
- M.Daffa Alrasy    : 2457051014
- Agung Suari       : 2117051091
# Aplikasi Pemesanan Makanan Sederhana
Materi yang di terapkan array, cstring, class, list, vector, divide and conquer, knapshack, fungsi, queue, deque, dan juga stl atau dengan nama lain short
//
![jimeng-2025-06-02-858-Chibi style illustration of four college students standing together outdoors o](https://github.com/user-attachments/assets/134b6a31-0d46-4ce8-b1e7-5b4f50f05add)
//

Saat program dijalankan maka akan tampil tampilan seperti ini:
APLIKASI WARUNG MAKAN
Ketik angka untuk memilih menu:
1. Lihat Menu
2. Tambah Pesanan Biasa
3. Tambah Pesanan Prioritas
4. Batalkan Pesanan Terakhir (Stack)
5. Proses Semua Pesanan
6. Rekomendasi Menu Hemat (Knapsack)
7. Lihat Riwayat Transaksi
0. Keluar

Pilih (0-7): ...

Yang mana nanti akan di pilih dari kerangka 0-7 tersebut salah satunya.
Jika kerangka angka yang di pilih adalah '1' maka outputnya berupa:
MENU MAKANAN & MINUMAN
1. Nasi Goreng Rp15000
2. Mie Ayam Rp12000
3. Nasi kuning Rp16000
4. Sate Ayam Rp18000
5. Es Teh Rp5000
6. Jus Jeruk Rp8000
7. Jus Stroberi Rp8500
8. Tempe goreng + Sambal terasi Rp4500
9. Tahu goreng + Sambal matah Rp6500
10. Air mineral Rp3500

Jika kerangka angka yang di pilih adalah '2' maka outputnya berupa:
Tempat input nama pelanggan, dan ketika nama pelanggan telah diinputkan maka akan di berikan pilihan menu dari salah satu menu diatas. Setelah itu akan ditanya jumlah yang ingin dipesan, jika sudah masuk maka akan keluar "Tambah lagi? (y/n):" y untuk yes dan n untuk no.
Jika y/n di masukkan dengan selain itu otomatis akan error di pesanan dan langsung keluar dari kerangka pemesanan.

Jika kerangka angka yang di pilih adalah '3' maka outputnya berupa:
Kurang lebih sama dengan kerangka nomor 2, yang membedakan adalah jika pemesanan ini yang digunakan. Pesanan akan di prioritaskan, misal sebelumnya ada yang sudah memesan maka pesanan ini akan di majukan proses pesanannya.

Jika kerangka angka yang di pilih adalah '4' maka outputnya berupa:
Pesanan yang sebelumnya dilakukan akan otomatis langsung di batalkan.

Jika kerangka angka yang di pilih adalah '5' maka outputnya berupa:
Semua pesanan akan di proses, dan struk akan keluar. Ketika ada pesanan prioritas, pesanan tersebut akan keluar di paling atas sebelum pesanan biasa.

Jika kerangka angka yang di pilih adalah '6' maka outputnya berupa:
Merupakan rekomendasi menu yang kira kira memenuhi anggaran atau budget, di sini kita menggunakan patokan 30k. maka rekomendasi yang keluar berupa bermacam kombinasi yang ada di menu yang sekiranya dapat di pesan. contoh : 2x tahu goreng + Sambal matah, 4 + Air mineral => total: Rp27000, dan seterusnya.

Jika kerangka angka yang di pilih adalah '7' maka outputnya berupa:
Maka akan keluar riwayat transaksi yang sudah di proses sebelumnya akan di tampilkan. contoh:
--- Riwayat Transaksi ---
Total: Rp124500 2
n Total: Rp24000

Jika kerangka angka yang di pilih adalah '0' maka outputnya berupa:
untuk keluar dari program.
return 0; :)
