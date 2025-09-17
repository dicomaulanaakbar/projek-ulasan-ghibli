#Proyek API Ulasan Film - Kelompok 3

##Anggota Kelompok

-Faizatul Izzah_362458302002
-Dico Maulana Akbar_362458302060
-Tsabitah Rifdah Nur 'Arifah_362458302064
-Desta Aftahul Qirom_362458302123

##Deskripsi Proyek

API ini adalah layanan internal untuk mengelola ulasan film dari Studio Ghibli, dengan data film yang direferensikan dari Ghibli API publik.

##Cara Menjalankan Proyek

1.Clone repository ini: 'git clone ...'
2.Masuk ke direktori: 'cd projek-ulasan-ghibli'
3.Install dependensi: 'npm install'
4.Jalankan server: 'node server.js'
Server akan berjalan di 'http://localhost:3300'.

##Daftar Endpoint

-'GET /status': Cek status API.
-'GET /reviews': Mengambil semua ulasan.
-'GET /reviews/:id': Mengambil ulasan spesifik.
-'POST /reviews': Membuat ulasan baru.
-'PUT /reviews/:id': Memperbarui ulasan.
-'DELETE /reviews/:id': Menghapus ulasan.