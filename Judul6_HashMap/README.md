HashMap Buku Perpustakaan (Separate Chaining)


Program ini merupakan implementasi struktur data HashMap dengan metode separate chaining yang digunakan untuk menyimpan data buku perpustakaan. Setiap buku disimpan menggunakan ID sebagai key, lalu dipetakan ke dalam tabel hash menggunakan fungsi hash. Data yang disimpan terdiri dari ID buku, judul buku, dan status ketersediaan (tersedia atau dipinjam).

Pada kasus tertentu, dua atau lebih data bisa memiliki hasil hash yang sama (collision). Untuk mengatasi hal ini, program menggunakan linked list (chaining) pada setiap index tabel. Dengan cara ini, data tidak saling menimpa, tetapi disimpan secara berurutan dalam satu index yang sama sehingga tetap bisa diakses dengan efisien.
