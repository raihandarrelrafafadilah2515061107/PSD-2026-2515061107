Program Sistem Toko Sederhana Menggunakan List Python

Program ini merupakan implementasi sederhana sistem toko menggunakan struktur data list (array) pada bahasa pemrograman Python. Program digunakan untuk menyimpan dan mengelola data harga barang dalam sebuah toko melalui menu interaktif. User dapat menampilkan address array, melihat address setiap elemen, menginput harga barang, dan menampilkan daftar harga barang yang telah disimpan.

Struktur data yang diterapkan pada program ini adalah List (Array 1 Dimensi). List digunakan untuk menyimpan beberapa data harga barang dalam satu variabel. Program juga menerapkan konsep perulangan, percabangan, fungsi, dan exception handling untuk validasi input agar program dapat berjalan dengan baik tanpa error.

source code:

INPUT
<br><br>
<img width="92" height="19" alt="Screenshot 2026-04-29 180850" src="https://github.com/user-attachments/assets/93c69edd-0748-4608-88cb-81a8fedb1f5d" />
Digunakan untuk membuat fungsi menu yang menampilkan daftar pilihan program
<br><br>
<img width="161" height="15" alt="Screenshot 2026-04-29 181051" src="https://github.com/user-attachments/assets/75c881fe-b0b9-4dc3-a248-6c225b446aeb" />
Menampilkan judul menu toko
<br><br>
<img width="351" height="97" alt="Screenshot 2026-04-29 181232" src="https://github.com/user-attachments/assets/aa86bef1-c6f3-4180-b5c5-f1c6b1f33c60" />
Menampilkan pilihan menu yang dapat dipilih user
<br><br>
<img width="90" height="17" alt="Screenshot 2026-04-29 181352" src="https://github.com/user-attachments/assets/49c68033-5797-4085-9d66-f07cd64b6d50" />
Fungsi utama program yang menjalankan seluruh proses program
<br><br>
<img width="199" height="18" alt="Screenshot 2026-04-29 182246" src="https://github.com/user-attachments/assets/0833a274-04e6-4e84-97a9-b71e65536624" />
Membuat list berisi 5 elemen dengan nilai awal 0
<br><br>
<img width="133" height="17" alt="Screenshot 2026-04-29 182545" src="https://github.com/user-attachments/assets/d651289f-6816-4fa0-a03b-b9b69f5c9835" />
Digunakan sebagai kontrol perulangan program
True = program berjalan
False = program berhenti
<br><br>
<img width="118" height="22" alt="image" src="https://github.com/user-attachments/assets/6e131347-b42a-413b-87e9-42aa63744be3" />
Program akan terus berjalan selama variabel running bernilai True
<br><br>
<img width="73" height="29" alt="Screenshot 2026-04-29 182817" src="https://github.com/user-attachments/assets/448b5bbe-4dc3-4860-8387-8d7412bbb5f9" />
Menampilkan menu program ke layar
<br><br>
<img width="319" height="26" alt="Screenshot 2026-04-29 182921" src="https://github.com/user-attachments/assets/8ba2b022-9eb2-4417-9a8b-7b89e4b6fc2b" />
User memasukkan nomor menu yang diinginkan
<br><br>
<img width="263" height="66" alt="Screenshot 2026-04-29 183342" src="https://github.com/user-attachments/assets/9fdeb76d-e580-4d98-a7c1-ce6892558c98" />
Digunakan untuk menangani kesalahan input jika user memasukkan selain angka
<br><br>
<img width="430" height="56" alt="Screenshot 2026-04-29 183443" src="https://github.com/user-attachments/assets/ff3f4cca-b675-48c1-8304-c04dbc3799e7" />
Menampilkan address memory dari list menggunakan fungsi id()
<br><br>
<img width="470" height="105" alt="Screenshot 2026-04-29 183756" src="https://github.com/user-attachments/assets/ce9fc846-60c2-4363-ac43-35f1d8a10013" />
Melakukan perulangan dari index 0 sampai 4 dan Menampilkan address setiap elemen list
<br><br>
<img width="557" height="162" alt="Screenshot 2026-04-29 184018" src="https://github.com/user-attachments/assets/36a9977f-e455-4869-8634-3ff6449ada99" />
Digunakan untuk menginput harga barang ke dalam list
<br><br>
<img width="251" height="47" alt="Screenshot 2026-04-29 184126" src="https://github.com/user-attachments/assets/6799b3f9-ed6e-46ce-8999-b13c75483a9d" />
Jika user memasukkan huruf atau simbol, program meminta input ulang
<br><br>
<img width="338" height="25" alt="Screenshot 2026-04-29 184225" src="https://github.com/user-attachments/assets/e122f662-22f0-4047-a000-3159dbbca6bb" />
Menampilkan seluruh isi list setelah data diinput
<br><br>
<img width="453" height="105" alt="Screenshot 2026-04-29 184316" src="https://github.com/user-attachments/assets/ad104d10-d5eb-4249-9dd3-ba9fa1e88148" />
Menampilkan daftar harga barang satu per satu
<br><br>
<img width="237" height="64" alt="Screenshot 2026-04-29 184418" src="https://github.com/user-attachments/assets/a8a38db0-5547-4a4a-b30e-f7f609ff2c9f" />
Menghentikan program dan keluar dari menu
<br><br>
<img width="254" height="54" alt="Screenshot 2026-04-29 184505" src="https://github.com/user-attachments/assets/8ee803db-c748-4040-90c9-179ace479c5e" />
Menampilkan menu tidak tersedia jika user memasukkan angka selain 1 sampai 5
<br><br>
<img width="213" height="45" alt="Screenshot 2026-04-29 184622" src="https://github.com/user-attachments/assets/617c18eb-9805-43bf-b1ad-50a92ce91dc1" />
Digunakan untuk menjalankan fungsi main()

OUTPUT
<br><br>
<img width="291" height="126" alt="Screenshot 2026-04-29 184743" src="https://github.com/user-attachments/assets/d8c12b8e-9884-4c5a-bccf-5d83bc7782d6" />
Program menampilkan menu utama yang dapat dipilih user
<br><br>
<img width="288" height="36" alt="Screenshot 2026-04-29 185013" src="https://github.com/user-attachments/assets/615d8e24-da18-4f0c-92eb-45ca889f3b4c" />
Menampilkan address list barang
<br><br>
<img width="187" height="120" alt="Screenshot 2026-04-29 185106" src="https://github.com/user-attachments/assets/06d7a862-4c5e-483b-92e2-d8f4c0098c86" />
Menampilkan address tiap barang
<br><br>
<img width="431" height="138" alt="Screenshot 2026-04-29 185252" src="https://github.com/user-attachments/assets/f2e9f9ab-25a2-4067-9e54-159378fda871" />
Memasukkan harga barang
<br><br>
<img width="175" height="117" alt="Screenshot 2026-04-29 185343" src="https://github.com/user-attachments/assets/7b2ee850-403f-4de2-bfdf-faa8756f2a31" />
Program berhasil menampilkan seluruh data harga barang yang telah diinput tanpa error
<br><br>
<img width="134" height="37" alt="Screenshot 2026-04-29 185446" src="https://github.com/user-attachments/assets/3bf05e88-eba7-41f6-be18-d35492231409" />
Program selesai
