Program Tumpukan Majalah di Ruang Tunggu (Stack Array)

Program ini merupakan implementasi struktur data Stack (tumpukan) menggunakan array dalam Python dengan pendekatan dunia nyata, yaitu tumpukan majalah di ruang tunggu. Konsep utama stack adalah LIFO (Last In First Out), artinya data yang terakhir masuk akan menjadi data pertama yang keluar. Dalam kasus ini, majalah yang terakhir ditaruh di atas rak akan menjadi majalah yang pertama diambil.

Program ini memungkinkan pengguna untuk menaruh majalah ke dalam tumpukan, mengambil majalah paling atas, melihat majalah paling atas, serta menampilkan seluruh isi tumpukan. Semua operasi dilakukan melalui menu interaktif berbasis terminal sehingga pengguna bisa mencoba langsung konsep stack secara sederhana dan mudah dipahami.

Source Code:

<img width="128" height="22" alt="Screenshot 2026-05-16 204148" src="https://github.com/user-attachments/assets/9e87aefc-77e3-4358-b723-2c069b9801e7" />
Membuat class bernama StackArray sebagai wadah struktur data stack.
<br><br>
<img width="239" height="66" alt="Screenshot 2026-05-16 204315" src="https://github.com/user-attachments/assets/8a9f54b6-4f25-426b-9c6b-c1fc11f12a01" />
MAX adalah batas maksimal tumpukan,
st adalah array untuk menyimpan data (majalah), dan
top_idx = -1 artinya tumpukan masih kosong
<br><br>
<img width="221" height="45" alt="Screenshot 2026-05-16 204540" src="https://github.com/user-attachments/assets/776a6fb2-ecbf-4fbd-b065-38f42ad62b6d" />
Mengecek apakah tumpukan kosong.
<br><br>
<img width="290" height="43" alt="Screenshot 2026-05-16 204710" src="https://github.com/user-attachments/assets/bc73791a-330e-4aa1-94c4-e0bde0b1194b" />
Mengecek apakah tumpukan sudah penuh.
<br><br>
<img width="128" height="23" alt="Screenshot 2026-05-16 204918" src="https://github.com/user-attachments/assets/6747b490-3ced-4942-8fd8-1e82cfd2ba34" />
Menambahkan majalah ke dalam tumpukan.
<br><br>
<img width="218" height="41" alt="Screenshot 2026-05-16 205029" src="https://github.com/user-attachments/assets/6f1d1b0c-b46b-432c-81c4-54418e209cf5" />
Jika penuh, tidak bisa menambah lagi.
<br><br>
<img width="282" height="62" alt="Screenshot 2026-05-16 205124" src="https://github.com/user-attachments/assets/9a1cd99e-8c22-4543-83a6-c3332c66924b" />
Menambahkan majalah ke posisi paling atas dan menampilkan pesan berhasil.
<br><br>
<img width="98" height="19" alt="Screenshot 2026-05-16 205245" src="https://github.com/user-attachments/assets/5955ce47-6acd-4cd7-965d-b0dbc8594c83" />
Mengambil majalah paling atas.
<br><br>
<img width="213" height="38" alt="Screenshot 2026-05-16 205334" src="https://github.com/user-attachments/assets/33060752-53e2-4aa5-bd6c-5fb458e49e7e" />
Jika kosong, tidak bisa diambil.
<br><br>
<img width="438" height="33" alt="Screenshot 2026-05-16 205429" src="https://github.com/user-attachments/assets/5a4785b3-5805-4f37-9358-875076311f04" />
Menghapus elemen paling atas.
<br><br>
<img width="119" height="18" alt="Screenshot 2026-05-16 205555" src="https://github.com/user-attachments/assets/0440e3fb-3fc3-45f2-8ecd-34e1c4f7f168" />
Melihat majalah paling atas tanpa menghapus.
<br><br>
<img width="222" height="37" alt="Screenshot 2026-05-16 205738" src="https://github.com/user-attachments/assets/2d935e4f-8130-4143-92c2-e6b31cedc241" />
Jika kosong akan menampilkan pesan tidak ada majalah.
<br><br>
<img width="379" height="16" alt="Screenshot 2026-05-16 210006" src="https://github.com/user-attachments/assets/700433f6-23fe-416b-a015-6269970e90c0" />
Menampilkan data teratas.
<br><br>
<img width="140" height="28" alt="Screenshot 2026-05-16 210055" src="https://github.com/user-attachments/assets/ab7992ae-ec54-48da-b9e4-50c183a7fcbf" />
<img width="262" height="56" alt="Screenshot 2026-05-16 210138" src="https://github.com/user-attachments/assets/3c0e3e2f-eb59-4dac-9bbd-93855ea27382" />
Loop dari atas ke bawah.
<br><br>
<img width="88" height="24" alt="Screenshot 2026-05-16 210230" src="https://github.com/user-attachments/assets/60f7e667-d597-4232-a03b-beae7e3f66ba" />
Fungsi utama program.
<br><br>
<img width="155" height="39" alt="Screenshot 2026-05-16 210337" src="https://github.com/user-attachments/assets/76cc8cc5-eba0-4088-a820-b346cedfcc67" />
Membuat objek stack.
<br><br>
<img width="305" height="123" alt="Screenshot 2026-05-16 212357" src="https://github.com/user-attachments/assets/421b8976-b163-4993-8a5a-de97c11ecd51" />
Loop menu yang akan berjalan terus menerus beserta input yang dapat dimasukkan, program akan berhenti jika user memilih opsi ke 5 yaitu keluar
<br><br>
<img width="237" height="96" alt="Screenshot 2026-05-16 210858" src="https://github.com/user-attachments/assets/b8545441-25e2-49f7-bcc8-bfa4b77f95b6" />
try-except ValueError berfungsi untuk menangani kesalahan saat user memasukkan input yang bukan angka agar program tidak error.
<br><br>
<img width="245" height="323" alt="Screenshot 2026-05-16 210950" src="https://github.com/user-attachments/assets/c79bb900-0b0b-4ecb-ada8-f52cfa60646e" />
if,elif, dan else berfungsi sebagai percabangan pilihan supaya hanya satu perintah yang dijalankan sesuai menu yang dipilih user.
<br><br>
<img width="199" height="46" alt="Screenshot 2026-05-16 211312" src="https://github.com/user-attachments/assets/917e7638-2cae-4a3a-a81b-4d9d030fab77" />
berarti program akan langsung menjalankan main() hanya jika file ini dijalankan secara langsung, tapi tidak akan otomatis jalan kalau file ini dipakai di program lain.
<br><br>
<br><br>
Output

<img width="205" height="94" alt="Screenshot 2026-05-16 212513" src="https://github.com/user-attachments/assets/fe6828fc-542e-4714-b3fe-d5b9cac1ad94" />
Menu ini berfungsi untuk mengatur seluruh proses pada tumpukan majalah.
<br><br>
<img width="247" height="146" alt="Screenshot 2026-05-16 212737" src="https://github.com/user-attachments/assets/531bcd8b-d53d-4dea-b22a-0ad35dd93653" />
menambahkan majalah ke tumpukan.
<br><br>
<img width="245" height="126" alt="Screenshot 2026-05-16 212823" src="https://github.com/user-attachments/assets/d0bd66a1-e690-4e73-8f65-3e02015bf4a9" />
mengambil majalah paling atas.
<br><br>
<img width="197" height="126" alt="Screenshot 2026-05-16 212908" src="https://github.com/user-attachments/assets/3b7ceff5-e3b9-49c3-b339-4aac1dd2c528" />
melihat majalah paling atas tanpa menghapus.
<br><br>
<img width="369" height="127" alt="Screenshot 2026-05-16 212954" src="https://github.com/user-attachments/assets/82d3ca6f-b129-4906-b30d-2632b7abdf05" />
menampilkan seluruh isi tumpukan.
<br><br>
<img width="207" height="128" alt="Screenshot 2026-05-16 213051" src="https://github.com/user-attachments/assets/08dd6c01-f54e-47e2-9d10-09a54e56feab" />
menghentikan program.
<br><br>
Link Youtube:
