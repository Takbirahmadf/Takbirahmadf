- #### Takbir Ahmad Fauzan 5311421097

<center><h1>MODUL 4 TEKNIK PENCARIAN BLIND SEARCH</h1></center>

1. Tentukan bagaimana algoritma BFS di atas dapat menentukan node ke 8, 6, dan 7. 2. 


Algoritma Breadth-First Search (BFS) adalah salah satu metode pencarian dalam ilmu komputer yang digunakan untuk menjelajahi atau mencari informasi dalam graf atau struktur data dengan mempertimbangkan tingkat jarak atau kedalaman dari simpul (node) awal. Tujuan utama dari algoritma ini adalah menemukan jalur terpendek dari satu simpul ke simpul lain dalam graf.

Proses pencarian dalam algoritma BFS dapat dijelaskan sebagai berikut:

- Pertama, simpul awal, yaitu simpul 3, diinisialisasi dan dimasukkan ke dalam antrian.
- Selanjutnya, simpul 3 akan mengeksplorasi simpul-simpul yang langsung terhubung dengannya, seperti simpul 2 dan simpul 4, karena simpul-simpul ini memiliki jarak 1 dari simpul 3.
- Simpul 4 akan melanjutkan proses dengan mengeksplorasi simpul 1, simpul 6, dan simpul 5, yang terhubung langsung dengan simpul 4.
- Kemudian, simpul 5 akan mengeksplorasi simpul 8 dan simpul 7.
- Proses ini akan terus berlanjut hingga semua simpul yang terhubung dengan simpul awal telah diperiksa dan diproses sesuai dengan prinsip algoritma BFS.

Oleh karena itu, algoritma BFS akan menemukan dan memproses simpul-simpul 8, 6, dan 7 setelah semua simpul yang lebih dekat dengan simpul awal telah dieksplorasi.

#### Hasil Praktikum

[alt text](!https://github.com/Takbirahmadf/Tugas-AI/blob/main/hasil%20nomor%201.png)

Berdasarkan hasil di atas, algoritma BFS dimulai dari simpul (node) ke-3 (n3) dan berikut adalah langkah-langkah untuk mencapai simpul ke-8, 6, dan 7:
- Simpul 3 (d=0): Algoritma BFS dimulai dari simpul n3 dengan jarak 0.
- Simpul 4 (d=1): Karena n3 memiliki tetangga n4, maka BFS melanjutkan ke simpul n4 dengan jarak 1.
- Simpul 2 (d=1): Meskipun n4 memiliki tetangga n2, n2 sudah diwarnai GRAY dalam proses BFS, sehingga BFS tidak melanjutkan ke simpul n2.
- Simpul 5 (d=2): n4 juga memiliki tetangga n5 yang belum diwarnai, maka BFS melanjutkan ke simpul n5 dengan jarak 2.
- Simpul 6 (d=2): n5 memiliki tetangga n6 yang belum diwarnai, sehingga BFS melanjutkan ke simpul n6 dengan jarak 2.
- Simpul 1 (d=2): n5 juga memiliki tetangga n1 yang belum diwarnai, sehingga BFS melanjutkan ke simpul n1 dengan jarak 2.
- Simpul 7 (d=3): n6 memiliki tetangga n7 yang belum diwarnai, sehingga BFS melanjutkan ke simpul n7 dengan jarak 3.
- Simpul 8 (d=3): n6 juga memiliki tetangga n8 yang belum diwarnai, sehingga BFS melanjutkan ke simpul n8 dengan jarak 3.

2. Membuat tree seperti pada gambar 4.5 yang ada pada jobsheet dengan mengubah method static void main, seperti berikut ini.

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%202-1.png)

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%202-2.png)

#### Hasil Praktikum

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/hasil%20nomor2.png)

Hasil tersebut mengonfirmasi kesesuaian antara hasil yang dihasilkan oleh program dengan Gambar 4.5. Langkah-langkah dalam pencarian simpul 5 melibatkan:
- Algoritma BFS dimulai dengan memasukkan simpul 1 ke dalam antrian.
- Selanjutnya, simpul 1 mengeksplorasi simpul 2 dan simpul 3, yang secara langsung terhubung dengan simpul 1 atau memiliki kedalaman tingkat 1.
- Kemudian, simpul 3 melanjutkan dengan mengeksplorasi simpul yang memiliki jarak atau kedalaman 2, yang dimulai dengan memeriksa simpul 4, simpul 5, simpul 6, dan simpul 7.
- Ketika simpul 5 ditemukan, proses berlanjut hingga semua simpul yang terhubung dengan simpul awal telah diperiksa. Sebagai hasilnya, simpul 5 akan ditemukan dan diproses sesuai dengan ketentuan algoritma BFS.

3.	Membuat tree seperti pada gambar 4.6 yang ada pada jobsheet dengan mengubah method static void main, seperti berikut ini.

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%203-1.png)

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%203-2.png)
![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%203-3.png)

#### Hasil Praktikum

![alt text]()

Hasil tersebut memverifikasi bahwa tree yang dihasilkan oleh program sesuai dengan Gambar 4.6. Proses pencarian simpul 9 melibatkan:
- Algoritma BFS memulai pencarian dengan memasukkan simpul 1 ke dalam antrian.
- Kemudian, simpul 1 memeriksa simpul 2, simpul 3, dan simpul 4, yang secara langsung terhubung dengan simpul 1 atau memiliki tingkat kedalaman 1.
- Selanjutnya, simpul 4 memeriksa simpul yang memiliki tingkat kedalaman 2, dimulai dari pemeriksaan simpul 5, simpul 6, simpul 7, dan simpul 8.
- Proses ini berlanjut dengan simpul 8 yang memeriksa simpul 9. Setelah simpul 9 ditemukan, proses terus berlanjut untuk memeriksa simpul 10, simpul 11, dan simpul 12, hingga semua simpul yang terhubung dengan simpul awal telah diperiksa. Dengan demikian, pada akhir proses BFS, simpul 9 akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.

4.	Membuat tree seperti pada gambar 4.7 yang akan dilakukan beberapa perubahan pada kode program.

Di kelas Node, untuk menerima huruf, perlu mengubah tipe data variabel 'data' dari integer (int) menjadi string (String).

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%204-1.png)

Lalu, dalam metode main, memasukkan nilai node dengan tipe data string seperti yang ditunjukkan di bawah ini.

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%204-2.png)

Kemudian, dalam metode addEdge dan bfs, tambahkan logika pemrosesan data yang sesuai untuk tipe data String seperti di bawah ini.

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/code%20nomor%204-3.png)

Kemudian klik Run sehingga didapatkan hasil pada gambar di bawah ini.

#### Hasil Praktikum

![alt text](https://github.com/Takbirahmadf/Tugas-AI/blob/main/hasil%20nomor4.png)

Hasil tersebut menegaskan kesesuaian antara hasil pohon yang dihasilkan oleh program dengan gambar 4.7. 
- Untuk menemukan node 3 (C), algoritma BFS dimulai dengan memasukkan node 6 (F) ke dalam antrian. 
- Selanjutnya, node 6 akan memeriksa node 2 (B) dan node 7 (G), yang langsung terhubung dengan node 6 atau memiliki tingkat kedalaman 1. 
- Node 7 kemudian akan memeriksa node yang memiliki kedalaman 2, dimulai dengan memeriksa node 1 (A), node 4 (D), dan node 9 (I).
- Setelah itu, node 9 akan memeriksa node 3 (C). Setelah menemukan node 3 (C), proses akan berlanjut untuk memeriksa node 5 (E) dan node 8 (H) hingga semua node yang terhubung dengan node awal telah diperiksa.

Dengan demikian, pada akhir proses BFS, node 3 (C) akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.
