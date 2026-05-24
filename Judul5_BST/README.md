Program BST Reservasi Meja Restoran


Program ini dibuat menggunakan konsep Binary Search Tree (BST) dengan studi kasus sistem reservasi meja restoran. BST digunakan untuk menyimpan data nomor meja agar tersusun secara teratur dan lebih mudah dikelola. Dalam struktur BST, setiap data yang memiliki nilai lebih kecil akan ditempatkan di sisi kiri, sedangkan data yang lebih besar berada di sisi kanan. Dengan cara kerja seperti ini, proses pencarian dan pengelolaan data menjadi lebih cepat dibandingkan penyimpanan biasa.

Pada program ini, pengguna dapat melakukan beberapa operasi seperti menambahkan reservasi meja, menghapus reservasi, menampilkan daftar meja yang sudah dipesan, menghitung jumlah reservasi, mencari meja selanjutnya, dan mencari meja sebelumnya. Program juga menggunakan try dan except untuk mencegah error ketika pengguna memasukkan input yang tidak sesuai sehingga program tetap berjalan dengan aman.
<br><br>
<br><br>
SOURCE CODE:

<img width="308" height="119" alt="Screenshot 2026-05-24 113338" src="https://github.com/user-attachments/assets/0eac6f47-9ac9-47bb-8aef-e528c63bd2dc" />
Class Node digunakan untuk membuat node pada Binary Search Tree.
Setiap node menyimpan data nomor meja serta cabang kiri dan kanan yang nantinya digunakan untuk membentuk struktur tree.
<br><br>
<img width="212" height="70" alt="Screenshot 2026-05-24 113942" src="https://github.com/user-attachments/assets/2abe6717-a09c-45dc-9b8c-e1be077cfec8" />
Class BSTRestoran digunakan sebagai tempat seluruh operasi BST dijalankan.
root berfungsi sebagai akar utama tree dan pada awal program nilainya masih kosong.
<br><br>
<img width="317" height="64" alt="Screenshot 2026-05-24 114206" src="https://github.com/user-attachments/assets/b9a45a03-aecb-4a32-9a5a-043b5ea7a3ee" />
Function ini digunakan untuk menambahkan data nomor meja ke dalam BST secara rekursif.
Data yang lebih kecil akan masuk ke kiri, sedangkan data yang lebih besar masuk ke kanan.
Jika posisi node masih kosong, maka program akan membuat node baru menggunakan nomor meja yang dimasukkan pengguna.
<br><br>
<img width="273" height="102" alt="Screenshot 2026-05-24 114457" src="https://github.com/user-attachments/assets/317f75c8-b1c0-4efa-b70b-d3745ec7d377" />
Kondisi ini digunakan untuk mengecek apakah nomor meja lebih kecil dari node saat ini.
Jika benar, data akan ditempatkan di cabang kiri.
<br><br>
<img width="279" height="108" alt="Screenshot 2026-05-24 114549" src="https://github.com/user-attachments/assets/114d9b1e-8ed3-49b7-aec4-8935054f37ad" />
Kondisi ini digunakan untuk mengecek apakah nomor meja lebih besar dari node saat ini.
Jika benar, data akan ditempatkan di cabang kanan.
<br><br>
<img width="271" height="110" alt="Screenshot 2026-05-24 115142" src="https://github.com/user-attachments/assets/d2e340a7-c644-4a0f-b58b-d47d5b1d5833" />
Function ini digunakan untuk mempermudah pemanggilan proses insert tanpa perlu mengatur root secara manual.
<br><br>
<img width="473" height="142" alt="Screenshot 2026-05-24 115405" src="https://github.com/user-attachments/assets/7329402a-cab2-41ea-9c71-5697c88cd7cc" />
Function ini digunakan untuk mencari node dengan nilai paling kecil pada BST.
Pencarian dilakukan dengan terus bergerak ke sisi kiri tree.
<br><br>
<img width="322" height="65" alt="Screenshot 2026-05-24 115512" src="https://github.com/user-attachments/assets/f86bbc08-07c5-424f-99f3-61db23821189" />
Function ini digunakan untuk menghapus data reservasi meja dari BST.
Proses penghapusan dilakukan dengan menyesuaikan struktur tree agar tetap memenuhi aturan BST setelah data dihapus.
<br><br>
<img width="281" height="107" alt="Screenshot 2026-05-24 115607" src="https://github.com/user-attachments/assets/c1c0462f-f85b-4563-bff8-4f7e45dfb62b" />
Function ini digunakan sebagai penghubung agar proses penghapusan dapat dipanggil dengan lebih sederhana.
<br><br>
<img width="322" height="226" alt="Screenshot 2026-05-24 115707" src="https://github.com/user-attachments/assets/2abe6142-2f59-424b-8f99-d88141a50e45" />
Function ini digunakan untuk menampilkan seluruh nomor meja yang tersimpan pada BST.
Data ditampilkan menggunakan traversal inorder sehingga hasilnya terlihat berurutan.
<br><br>
<img width="309" height="184" alt="Screenshot 2026-05-24 115801" src="https://github.com/user-attachments/assets/156f8b33-01d0-4851-a29b-4a5524bee279" />
Function ini digunakan untuk menghitung total reservasi meja yang ada pada BST dengan cara menghitung seluruh node yang tersimpan.
<br><br>
<img width="372" height="274" alt="Screenshot 2026-05-24 115909" src="https://github.com/user-attachments/assets/4b17449d-aa75-41a6-aed6-2d83f8264c74" />
Function ini digunakan untuk mencari nomor meja berikutnya berdasarkan nomor meja tertentu.
Successor berarti nilai yang lebih besar terdekat dari suatu node.
<br><br>
<img width="366" height="267" alt="Screenshot 2026-05-24 120000" src="https://github.com/user-attachments/assets/0b042cad-3ba7-44ee-bd61-9c5edeced099" />
Function ini digunakan untuk mencari nomor meja sebelumnya berdasarkan nomor meja tertentu.
Predecessor berarti nilai yang lebih kecil terdekat dari suatu node.
<br><br>
<img width="189" height="66" alt="Screenshot 2026-05-24 120119" src="https://github.com/user-attachments/assets/bb71c750-b33a-4eca-aa57-dfd328948f04" />
Function def main() berfungsi sebagai pusat utama jalannya program.
Di dalamnya terdapat menu, input pengguna, serta pemanggilan seluruh function BST seperti insert, delete, tampilkan data, successor, dan predecessor.
<br><br>
<img width="373" height="183" alt="Screenshot 2026-05-24 120232" src="https://github.com/user-attachments/assets/0b669990-1934-4310-bf1c-9805f7ee5be9" />
Perulangan ini digunakan agar menu program terus berjalan sampai pengguna memilih opsi keluar.
<br><br>
<img width="280" height="107" alt="Screenshot 2026-05-24 120314" src="https://github.com/user-attachments/assets/c37995f6-aaee-46b4-b6bb-adb2e9543ec0" />
Bagian ini digunakan untuk menangani kesalahan input.
Jika pengguna memasukkan huruf atau karakter lain selain angka, program tidak akan error dan akan menampilkan pesan kesalahan.
<br><br>
<br><br>
Output
<br><br>
<img width="267" height="201" alt="Screenshot 2026-05-24 120454" src="https://github.com/user-attachments/assets/c33c63d8-dadb-43b9-81e8-f049531630fb" />
Output ini muncul ketika pengguna berhasil menambahkan nomor meja ke dalam BST.
<br><br>
Link Youtube: https://youtu.be/kC6DuHiFL3k?si=ukj-Nyqduj0FaG-0
