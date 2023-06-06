# UAS_PBO (Pemrograman Berorientasi Objek)
Kelompok 2
Nama Anggota Kelompok:
1. Ariq Abdurrahman      (G1A021036)
2. Atika Oktavianti      (G1A022020)
3. ESa Nirza Zakya Putri (G1A022020)

Penjelasan kode:
Kode tersebut adalah sebuah program sederhana yang menggunakan modul Tkinter dalam Python untuk memebuat antarmuka pengguna aplikasi pemesanan makanan.
Berikut adalah penjelasan tentang bagian-bagian kode tersebut:
1. Impor modul: program mengimpor modul 'Tkinter' dan menggantinya menjadi 'tk' untuk penggunaan yang lebih singkat.
2. Fungsi 'pesan_makanan()' : fungsi ini dipanggil saat tombol "pesan" ditekan. fungsi ini mengambil input pengguna dari elemen entry (entry_nama, entry_alamat, entry_pesanan), kemudian menampilkan pesanan tersebut pada label_pesanan.
3. Variabel 'data_makanan' : ini adalah sebuah  kamus (dictionary) yang berisis daftar makanan beserta harganya.
4. Membuat jendela utama: onjek Tkinter 'tk()' digunakan untuk membuat jendela utama aplikasi. Nama jendela diatur dengan 'window.title()'.
5. Membuat elemen antar muka pengguna: Label, entry, dan tombol dibuat menggunakan objek Tkinter seperti 'Label', 'Entry', dan 'Button'. Elemen -elemen ini diatur dengan metode 'pack()' untuk menempatkan secara berurutan dalam jendela.
6. Checkbox untuk makanan: untuk setiap makanan dalam 'data_makanan' sebuah variabel Tkinter 'IntVar()' dibuat untuk melacak apakah makanan tersebut dipilih atau tidak. setiap makanan ditampilkan dengan bantuan onjek Tkinter 'Checkbutton()', dan variabel-variabel ini ditambahkan ke dalam list 'var_makanan'.
7. Tombol pesan: Tombol "pesan" dibuat dengan objek 'Button'. ketika tombol ini ditekan, fungsi 'pesan_makanan()' akan dipanggil.
8. Menampilkan pesananan: Label 'label_pesanan' dibuat untuk menampilkan pesanan yang diinput oleh pengguna dalm fungsi 'pesan_makanan()'.
9. Menjalankan aplikasi: Metode 'mainloop()' dipanggil pada objek 'window' untuk menjalankan aplikasi dan menampilkan jendela utama hingga ditutup
 
Dengan menjalankan kode tersebut, akan melihat jendela aplikasi dengan elemen-elemen yang sesuai, termasuk daftar makanan dengan checkbox dan tombol pesan untuk mengirimkan pesanan. setelah pengguna memasukkan data dan memilih makanan, pesanan akan ditampilka pada label_pesanan ketika tombol "pesan" ditekan. 
