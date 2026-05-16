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
