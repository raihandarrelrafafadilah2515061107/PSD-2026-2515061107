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
<br><br>
<img width="87" height="32" alt="Screenshot 2026-05-04 203404" src="https://github.com/user-attachments/assets/97db39bb-97e9-44f5-b5b3-a9fb2e02128c" />
Membuat fungsi utama program.
<br><br>
<img width="387" height="103" alt="Screenshot 2026-05-04 203645" src="https://github.com/user-attachments/assets/dd3a208d-ad10-4af9-9ac0-217e5f57154b" />
Digunakan untuk meminta user memasukkan data dan mencegah terjadinya error jika yang dimasukkan adalah selain angka serta menghentikan fungsi main jika terjadi error.
<br><br>
<img width="331" height="52" alt="Screenshot 2026-05-04 203936" src="https://github.com/user-attachments/assets/c00f6a96-9194-4738-9ade-2eaa8c5d9c5b" />
Membuat list kosong untuk menyimpan ukuran sepatu dan menampilkan instruksi input.
<br><br>
<img width="147" height="23" alt="Screenshot 2026-05-04 204037" src="https://github.com/user-attachments/assets/1573d0d2-6fbe-4782-802e-209061558d7c" />
Perulangan sebanyak jumlah mahasiswa.
<br><br>
<img width="97" height="28" alt="Screenshot 2026-05-04 204136" src="https://github.com/user-attachments/assets/12e4a9e8-9d7f-460a-83c5-6dc6e7d4f8e8" />
<img width="87" height="14" alt="Screenshot 2026-05-04 204207" src="https://github.com/user-attachments/assets/a11a397e-8188-4705-97dc-2d5e42badc4b" />
Perulangan tanpa batas dan akan berhenti jika input valid.
<br><br>
<img width="205" height="75" alt="Screenshot 2026-05-04 204459" src="https://github.com/user-attachments/assets/86b053ec-5647-4fe6-a20a-5abadf4c0ca3" />
Memasukkan ukuran sepatu lalu mengubahnya menjadi integer dan menambahkan ukuran sepatu ke dalam array serta menghentikan while True jika input berhasil.
<br><br>
<img width="424" height="40" alt="Screenshot 2026-05-04 204905" src="https://github.com/user-attachments/assets/2446540d-e31d-4645-a21e-be3dd5e4c7d8" />
Menangani dan menampilkan pesan kesalahan apabila input yang dimasukkan tidak sesuai
<br><br>
<img width="319" height="41" alt="Screenshot 2026-05-04 205038" src="https://github.com/user-attachments/assets/80716eaf-7aa4-48cb-b3e1-8ddf79e5ee30" />
Menampilkan data sebelum sorting dan memanggil fungsi insertion sort untuk mengurutkan data.
<br><br>
<img width="463" height="17" alt="Screenshot 2026-05-04 205141" src="https://github.com/user-attachments/assets/0aee81c6-f808-4544-90b5-97f74fbd71c1" />
Menampilkan teks hasil sorting dan end=" " berfungsi supaya output berikutnya tetap di baris yang sama.
<br><br>
<img width="218" height="38" alt="Screenshot 2026-05-04 205310" src="https://github.com/user-attachments/assets/c0fcfaae-1fd3-425b-9b2f-ae5a0203d892" />
Perulangan untuk menampilkan semua isi array dan menampilkan tiap ukuran sepatu dalam satu baris.
<br><br>
<img width="56" height="22" alt="Screenshot 2026-05-04 205423" src="https://github.com/user-attachments/assets/bcbe7c47-bad3-4372-ada9-703468be97ab" />
Membuat pindah baris setelah output selesai.
<br><br>
<img width="224" height="56" alt="Screenshot 2026-05-04 205515" src="https://github.com/user-attachments/assets/c7f04a6c-a8af-4314-8850-18d85d153a18" />
Mengecek apakah file dijalankan langsung dan menjalankan fungsi utama program.

<br><br>

OUTPUT
<img width="403" height="35" alt="Screenshot 2026-05-04 210007" src="https://github.com/user-attachments/assets/032ed62a-9895-4b38-b41b-2052ef6fdb6e" />
User diminta untuk memasukkan jumlah mahasiswa
<br><br>
<img width="457" height="154" alt="Screenshot 2026-05-04 210108" src="https://github.com/user-attachments/assets/fb5e86ec-1363-420b-a93a-b736fbad9b71" />
Setelah memasukkan jumlah mahasiswa, selanjutnya adalah memasukkan ukuran sepatu masing-masing mahasiswa, lalu data tersebut di sorting berdasarkan terkecil hingga terbesar

<br><br>

PROGRAM SELESAI

<BR><BR>

LINK VIDEO YOUTUBE: https://youtu.be/pU3SE7O1R6k
