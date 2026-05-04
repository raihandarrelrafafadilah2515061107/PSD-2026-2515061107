Program Insertion Sort Ukuran Sepatu Mahasiswa

Program ini dibuat menggunakan bahasa Python untuk mengurutkan ukuran sepatu mahasiswa menggunakan metode Insertion Sort. User diminta memasukkan jumlah mahasiswa serta ukuran sepatu masing-masing mahasiswa. Data yang dimasukkan akan disimpan ke dalam array/list, kemudian program akan menampilkan data sebelum dan sesudah diurutkan.

Metode insertion sort bekerja dengan cara membandingkan data satu per satu dari kiri ke kanan. Jika ditemukan nilai yang lebih kecil, maka data yang lebih besar akan digeser, lalu nilai tersebut disisipkan ke posisi yang sesuai. Algoritma ini cocok digunakan untuk data berukuran kecil karena sederhana dan mudah dipahami.


SOURCE CODE:
INPUT


<img width="212" height="26" alt="Screenshot 2026-05-04 201810" src="https://github.com/user-attachments/assets/16a32994-f83f-4cad-9fc3-0112ae42582b" />
Membuat fungsi bernama insertion_sort.
<br><br>
<img width="168" height="20" alt="Screenshot 2026-05-04 202027" src="https://github.com/user-attachments/assets/ce434d8c-48b4-4064-a882-abd56f2a8008" />
Perulangan dimulai dari indeks ke-1 sampai terakhir.
<br><br>
<img width="113" height="20" alt="Screenshot 2026-05-04 202233" src="https://github.com/user-attachments/assets/b99084f3-7207-4cac-808d-683db426bac0" />
Menyimpan nilai yang sedang dibandingkan sementara.
<br><br>
<img width="90" height="25" alt="Screenshot 2026-05-04 202345" src="https://github.com/user-attachments/assets/f31dd970-398d-4403-976a-2bc20bbeac49" />
Variabel j digunakan untuk mengecek data sebelumnya.
<br><br>
<img width="254" height="31" alt="Screenshot 2026-05-04 202431" src="https://github.com/user-attachments/assets/795fec31-6298-4013-a116-e0b798fddf00" />
Perulangan berjalan selama j masih dalam array dan nilai sebelumnya lebih besar dari temp.
<br><br>
<img width="161" height="15" alt="Screenshot 2026-05-04 202731" src="https://github.com/user-attachments/assets/c94e8f38-5a03-47eb-b179-39ff6202e9a1" />
Menggeser nilai yang lebih besar ke kanan.
<br><br>
<img width="64" height="19" alt="Screenshot 2026-05-04 203125" src="https://github.com/user-attachments/assets/8d0566d2-62a0-4a0a-a453-3dde01745886" />
Mundur satu langkah ke kiri untuk membandingkan lagi.
<br><br>
<img width="136" height="25" alt="Screenshot 2026-05-04 203219" src="https://github.com/user-attachments/assets/0cd5745b-5eca-4492-bf6f-d574583ff27a" />
Menaruh nilai temp ke posisi yang benar setelah proses penggeseran selesai.
