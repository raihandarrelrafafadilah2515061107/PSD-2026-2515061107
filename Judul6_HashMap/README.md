HashMap Buku Perpustakaan (Separate Chaining)


Program ini merupakan implementasi struktur data HashMap dengan metode separate chaining yang digunakan untuk menyimpan data buku perpustakaan. Setiap buku disimpan menggunakan ID sebagai key, lalu dipetakan ke dalam tabel hash menggunakan fungsi hash. Data yang disimpan terdiri dari ID buku, judul buku, dan status ketersediaan (tersedia atau dipinjam).

Pada kasus tertentu, dua atau lebih data bisa memiliki hasil hash yang sama (collision). Untuk mengatasi hal ini, program menggunakan linked list (chaining) pada setiap index tabel. Dengan cara ini, data tidak saling menimpa, tetapi disimpan secara berurutan dalam satu index yang sama sehingga tetap bisa diakses dengan efisien.

Source Code:
<br><br>
<img width="426" height="130" alt="Screenshot 2026-06-09 210758" src="https://github.com/user-attachments/assets/1767d2a8-6f22-4712-9e92-55f3cc1afbf1" />
Class Node berfungsi sebagai struktur dasar penyimpanan data buku. Setiap node menyimpan key sebagai ID buku, judul sebagai nama buku, status sebagai kondisi buku, serta next untuk menghubungkan node lain dalam satu index (chaining).
<br><br>
<img width="331" height="90" alt="Screenshot 2026-06-09 210856" src="https://github.com/user-attachments/assets/fc419ec9-7e37-426c-b092-f7eb254d5a61" />
Class ini adalah inti dari HashMap. SIZE menentukan jumlah slot dalam tabel hash, sedangkan table adalah array yang digunakan untuk menyimpan data buku. Semua slot awalnya diisi None.
<br><br>
<img width="426" height="48" alt="image" src="https://github.com/user-attachments/assets/7e6c0fbc-8eda-4504-afb9-5549d2202582" />
Fungsi ini digunakan untuk menentukan index penyimpanan data berdasarkan key. Operasi modulus memastikan key selalu masuk ke dalam range index tabel hash.
<br><br>
<img width="380" height="75" alt="image" src="https://github.com/user-attachments/assets/45a177a0-0a5d-479b-804f-c738aae71438" />
Fungsi insert digunakan untuk menambahkan data buku. Pertama, key dikonversi menjadi index menggunakan hash function, lalu current menunjuk ke isi pada index tersebut.
<br><br>
<img width="249" height="121" alt="image" src="https://github.com/user-attachments/assets/5aa8faad-eeb1-4b00-b463-63579de2d31e" />
Bagian ini mengecek apakah key sudah ada di dalam linked list pada index tersebut. Jika ditemukan, maka data akan diperbarui (update) tanpa membuat node baru.
<br><br>
<img width="290" height="75" alt="image" src="https://github.com/user-attachments/assets/3976d15b-119c-4ba9-8108-ef6597e534bf" />
Jika key belum ditemukan, maka dibuat node baru. Node ini dimasukkan ke awal linked list pada index tersebut (metode chaining).
<br><br>
<img width="300" height="67" alt="image" src="https://github.com/user-attachments/assets/43c1fc77-6dac-4907-913c-df4985a7da0c" />
Fungsi search digunakan untuk mencari data buku berdasarkan key. Pertama, ditentukan index tempat kemungkinan data berada.
<br><br>
<img width="236" height="106" alt="image" src="https://github.com/user-attachments/assets/72dec1ab-d5f0-43c0-964f-c86ddbfaa0f6" />
Linked list pada index tersebut ditelusuri sampai data ditemukan. Jika tidak ditemukan, fungsi mengembalikan None.
<br><br>
<img width="293" height="94" alt="image" src="https://github.com/user-attachments/assets/8125c056-8315-4f79-8c0b-da3aa0049168" />
Fungsi ini digunakan untuk menghapus data buku. prev digunakan untuk melacak node sebelumnya agar sambungan linked list tetap terjaga setelah penghapusan.
<br><br>
<img width="368" height="131" alt="image" src="https://github.com/user-attachments/assets/bc22f63e-75bc-42b8-8e4e-6568c3993dd7" />
Jika node ditemukan, maka akan dihapus. Jika node berada di awal list, head digeser. Jika di tengah, node sebelumnya disambungkan ke node setelahnya.
<br><br>
<img width="222" height="74" alt="image" src="https://github.com/user-attachments/assets/42ba059e-c516-4884-9a7d-2cfc7e515a25" />
Pointer digeser sampai akhir list. Jika data tidak ditemukan, fungsi mengembalikan False.
<br><br>
<img width="455" height="98" alt="image" src="https://github.com/user-attachments/assets/50f3c989-6e55-4167-8aaf-b583d76ed456" />
Fungsi ini digunakan untuk menampilkan seluruh isi hash table per index.
<br><br>
<img width="607" height="89" alt="image" src="https://github.com/user-attachments/assets/b27f7cf0-a0ab-49d3-a092-dabb194531dc" />
Jika terdapat data dalam index tersebut, seluruh node dalam chain akan ditampilkan secara berurutan hingga Kosong.
<br><br>
<img width="460" height="179" alt="image" src="https://github.com/user-attachments/assets/cd4ed9b6-0319-4c36-b027-ced165939fd9" />
Bagian ini membuat objek perpustakaan dan menambahkan beberapa data buku ke dalam hash table serta menampilkan seluruh isi data perpustakaan.
<br><br>
<img width="508" height="107" alt="image" src="https://github.com/user-attachments/assets/cab5c3f4-555f-4ff7-b272-7f8f2a183270" />
Melakukan pencarian buku dengan ID 11 dan menampilkan hasilnya jika ditemukan.
<br><br>
<img width="332" height="63" alt="image" src="https://github.com/user-attachments/assets/d174d620-4a13-4bd1-93e1-1e9b6e0204dc" />
Menghapus buku dengan ID 11, lalu menampilkan kondisi terbaru hash table.
<br><br>
<img width="224" height="40" alt="image" src="https://github.com/user-attachments/assets/852e8c4a-890a-4551-b3d0-3200ac20683b" />
Menjalankan program utama.
<br><br>
OUTPUT
<BR><BR>
<img width="809" height="476" alt="image" src="https://github.com/user-attachments/assets/cfd5fe6f-d62c-44cb-9184-a8a481de866e" />
Output menampilkan isi hash table dari index 0 hingga 9. Jika terjadi collision, data akan muncul dalam bentuk rantai (linked list) dengan tanda. Setelah itu program menampilkan hasil pencarian buku dengan ID 11. Kemudian data tersebut dihapus, dan tabel hash akan ditampilkan kembali untuk menunjukkan perubahan isi data.

LINK YOUTUBE: https://youtu.be/ii8iamfrBjY?si=U73roU1Fh2B850eR
