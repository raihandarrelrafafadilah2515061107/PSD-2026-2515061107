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

