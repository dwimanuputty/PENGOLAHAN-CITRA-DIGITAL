Penjelasan no 1
Konsep:
4-connectivity berarti sebuah piksel dianggap terhubung dengan tetangganya hanya jika bersentuhan secara horizontal atau vertikal (atas, bawah, kiri, kanan).
Piksel yang bersentuhan secara diagonal tidak dianggap terhubung.
Dengan aturan ini, kita bisa mendeteksi berapa banyak kelompok piksel 1 yang membentuk objek terpisah.

Jadi dengan aturan 4-connectivity, matriks biner yang diberikan menghasilkan 4 objek terpisah.


Penjelasan no 2
Konsep:
Sampling dalam pengolahan citra berarti mengubah jumlah piksel (resolusi) dari sebuah gambar.
Proses ini dilakukan dengan metode interpolasi, misalnya Nearest Neighbor (memilih piksel terdekat) atau Bilinear (menghitung rata-rata tetangga).
Semakin kecil ukuran gambar, semakin sedikit informasi visual yang tersisa, sehingga detail gambar berkurang.

Jadi resize bertahap dari 512×512 ke 64×64 menunjukkan bagaimana resolusi memengaruhi detail gambar. Semakin kecil ukuran, semakin sedikit informasi visual yang tersisa.


Penjelasan no 3
Konsep:
Citra grayscale normal biasanya direpresentasikan dengan 8-bit, artinya setiap piksel memiliki nilai intensitas antara 0–255 (total 256 level keabuan).
Kuantisasi adalah proses mengurangi jumlah level intensitas sehingga citra menjadi lebih sederhana.
Semakin sedikit level, semakin kasar tampilan citra karena detail hilang.

Jadi kuantisasi mengurangi jumlah level keabuan dari citra grayscale. Semakin kecil jumlah bit, semakin sedikit detail yang bisa ditampilkan, sehingga citra terlihat lebih sederhana.