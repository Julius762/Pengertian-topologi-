# Pengertian-topologi-
topologi merupakan susunan jaringan  yang saling berhubungan satu sama lain. Sementara jaringan terdiri dari berbagai komponen yang dapat berkomunikasi antara satu sama lain.
Komputer sendiri disebut node yang secara aktif terlibat dalam proses komunikasi.


Jadi, topologi jaringan komputer adalah susunan jaringan yang setiap bagiannya saling berhubungan satu sama lain melalui media fisik seperti kabel dan serat optik.


# Manfaat topologi
jaringan komputer ini adalah untuk memahami bagaimana berbagai jaringan komputer saling bertukar informasi.

Jenis-Jenis Topologi Jaringan Komputer
Ada 2 jenis topologi jaringan komputer, berikut ini jenis topologi jaringan komputer:

# A. Topologi Fisik:
Disebut sebagai jenis koneksi yang nyata dalam jaringan, seperti kabel, saklar, dan router.

1. Point-to-Point Connection
 ![image](https://github.com/user-attachments/assets/ed7c3b1f-0a5c-4a57-ad7e-8caf8d2b3498)
Menggunakan satu link untuk secara langsung menghubungkan 2 node dengan sambungan kabel untuk menghubungkan dua ujung.

Contoh sederhana, yaitu mainan telepon kaleng.

2. Multipoint Connection
![image](https://github.com/user-attachments/assets/0c1c58ec-568d-4dab-8991-668418694d3d)
Koneksi yang melibatkan beberapa perangkat sekaligus dengan perangkat yang memiliki kode khusus untuk bisa mengidentifikasi satu sama lain.
# B. Topologi Logis
1. Topologi Ring
![image](https://github.com/user-attachments/assets/db407911-6a70-4e44-941a-c931f5f72a48)
Jenis topologi yang pertama yaitu topologi ring yang berbentuk lingkaran. Jadi, data mengalir searah jarum jam dan satu loop.

Misal, ada 10 node dalam jaringan dan node 2 ingin mengirim data ke node 5. Maka node 2 mengirim data ke node 3 lalu node 3 mengirim ke node 4 dan kirim lagi ke node 5.

Kelebihan:

Transmisi data sangat cepat
Konfigurasi, pemasangan, dan perluasan sangat terjangkau
Bahkan kabel twisted pair tersedia dengan mudah
Adalah yang terbaik dalam menangani beban daripada topologi bus
Kegagalan mudah dihilangkan tanpa menyebabkan kerusakan jaringan

Kekurangan:

Komunikasi bisa lebih lambat ketika ada perangkat baru yang ditambahkan
Pemecahan masalah sangat sulit
Semua komputer harus dalam keadaan hidup untuk dapat berkomunikasi
Hanya bergantung pada satu kabel

2. Topologi Bus
![image](https://github.com/user-attachments/assets/812acb17-b4d6-446d-a9ae-a39c23d42faa)
Selanjutnya ada topologi jaringan bus yang memiliki fungsi dua arah dan disebut juga sebagai topologi bus linier. Contoh topologi jaringan Bus yaitu pada jaringan penghubung antara televisi dengan antena

Kelebihan:

Lebih murah dan familiar
Konstituen perangkat keras tersedia dengan mudah
Sesuai untuk jaringan kecil seperti LAN
Kerusakan tidak berdampak pada node lainnya
Proses konfigurasi dan penginstalan yang mudah
Dapat diperpanjang sesuai kebutuhan

Kekurangan:

Kerusakan pada kabel bisa membuat seluruh jaringan mati
Jumlah stasiun sedikit karena terbatasnya ukuran kabel
Ketika terjadi kesalahan maka dapat memperburuk rekonstruksi
Ketika jumlah node meningkat, maka kinerja dapat kejatuhan jaringan

3. Topologi Mesh
   ![image](https://github.com/user-attachments/assets/3bada851-5e49-4890-97e9-ec40b547af8c)
Menggunakan koneksi point-to-point untuk menghubungkan setiap node sehingga mendukung kecepatan komunikasi. Semua node saling terhubung tanpa adanya perangkat pusat.

Ada 2 jenis topologi mesh:

Topologi Mesh Parsial, hanya 2 atau 3 node yang terhubung dalam jaringan, semenatara sebagian besranya terhubung dengan topologi penuh.
Topologi Mesh Penuh, setiap node terhubung, jadi ketika satu node gagal maka beban akan beralih ke node yang lain.
Kelebihan:

Transmisi data sangat handal
Kegagalan pada satu node tidak mempengaruhi yang lain
Memiliki sifat yang kuat
Jalur pengiriman sangat banyak sehingga minim terjadi tabrakan arus data

Kekurangan:

Membutuhkan lebih banyak kabel dan media transmisi
Konfigurasi dan penginstalan sangat sulit
Pemeliharaan cukup sulit
Metode transmisi yang dilakukan yaitu routing dan flooding.

4. Topologi Star
![image](https://github.com/user-attachments/assets/8601e745-be9a-4211-abbc-a2277e70b12f)
Topologi star memiliki perangkat pusat (switch) yang menghubungkan semua node. Jadi, ketika sebuah node ingin mengirimkan data ke node yang lain harus melalui perangkat pusat dan perangkat pusat akan meneruskannya ke node yang dituju.

Dalam topologi ini antar node ada koneksi poin-to-point dan disebut sebagai yang paling menuntut dalam implementasi jaringan.

Kelebihan:

Troubleshooting cukup efektif
Konfigurasi, penginstalan, dan modifikasi sangat mudah
Peningkatan hub dan saklar cukup mudah
Mudah menemukan kesalahan jaringan, cukup melalui perangkat pusat.

Kekurangan:

Ketika saklar pusat mati, maka antar node tidak dapat terhubung
Biaya jaringan cukup mahal dengan adanya penggunaan saklar atau hub pusat
Biaya instalasi dan konfigurasi juga mahal
Kapasitas hub menentukan batasan penambahan node

5. Topologi Tree
![image](https://github.com/user-attachments/assets/d10c43fd-40de-4d92-84f0-44a7c23b4c82)
Disebut juga topologi hierarkis yang terdiri dari beberapa level yang terhubung dengan bantuan media seperti serat optik, koaksial, dan pasangan terpilin. Paling umum digunakan serta memiliki sifat topologi bus dan topologi star.

Properti yang digunakan juga serupa dengan topologi bus


Pada bagian atas ada root node dan semua yang berada di bawah disebut turunan dari root node. Sementara itu setiap dua node memiliki satu jalur untuk transmisi bit.


Semua komputer dalam jaringan ini terdiri dari 3 lapisan:

Lapisan Inti (Lapisan Tertinggi)
Merupakan titik pusat yang bertindak sebagai akar pohon. jadi ketika lapisan inti mati, maka seluruh lapisan juga akan mati.

Lapisan Distribusi (Lapisan Tengah)
Bertindak sebagai kulit dan cabang pohon. Lapisan ini yang menghubungkan lapisan bawah dan lapisan atas untuk dapat berkomunikasi.

Access Level (Lapisan Bawah)
Lapisan terendah yang bertindak sebagai kulit dan cabang pohon yang ketika terjadi masalah di sini, maka tidak mempengaruhi lapisan tengah dan atas.

Kelebihan:

Mudah menskalakan jaringan
Mendukung semua perangkat keras dan perangkat lunak
Mudah menambahkan node baru dalam jaringan
Mudah mencari kesalahan
Setiap node bersifat individual, jadi permasalahan mudah diselesaikan
Permasalahan yang terjadi juga tidak mempengaruhi jaringan yang lain.
Risiko kehilangan data sangat minim
Efisiensi penerimaan data semua node berkat koneksi point-to-point

Kekurangan:

Jika jaringan inti mati, maka turunannya juga akan mati
Butuh lebih banyak kabel ketika hendak menambahkan node baru
Biaya transmisi broadband sangat mahal
Cukup sulit mengkonfigurasi dan menginstal sistem baru
Peningkatan node yang melebihi batas akan mempersulit pemeliharaannya

6. Topologi Hybrid
![image](https://github.com/user-attachments/assets/39ef0a1a-2411-473e-ace7-0cc67b5474d8)
Merupakan jenis topologi jaringan komputer yang terdiri dari beberapa topologi yang digabungkan.

Sangat umum digunakan dalam organisasi yang memiliki beberapa bagian berbeda. Di mana setiap bagian memiliki topologinya sendiri dan akan dihubungkan ke satu titik pusat atau hub.

Kelebihan:

Sangat fleksibel sehingga mudah dirancang sesuai permintaan
Sangat mudah mendeteksi dan menyelesaikan masalah
Menggunakan beberapa teknologi yang membuatnya efisien
Mudah memperluas ukuran jaringan ketika menambahkan sistem baru

Kekurangan:

Mahal
Rumitnya proses instalasi dan konfigurasi
Tidak mudah merancang arsitektur jaringan hybrid
Untuk mendapatkan dan memelihara hub membutuhkan biaya yang tidak murah

7. Topologi Peer to Peer
![image](https://github.com/user-attachments/assets/29952212-d33f-4539-9b75-07d28fb2e450)
Untuk menghubungkan 2 komputer dan hanya membutuhkan 1 kabel.

Kelebihan topologi jaringan komputer Peer to Peer, yaitu:

Rendahnya biaya instalasi
Mudahnya proses instalasi
Setiap node bisa bertindak sebagai client maupun server

Kekurangan:

Sulit untuk dikembangkan
Masalah keamanan sering terjadi
Rumitnya proses troubleshooting
