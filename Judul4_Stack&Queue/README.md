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


