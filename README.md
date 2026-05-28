# Project-Sistem-Tiket-Bioskop
Tugas Project Kelompok 4 - Algoritma Struktur Data

Instruksi Run
Verifikasi Load Data & Tampil Data: Pastikan program memuat 30 data awal, lalu tampilkan daftarnya. Input: Ketik 2 pada Menu Bioskop lalu tekan Enter. Ekspektasi Output: Muncul tulisan === DATA FILM === diikuti daftar 30 film (mulai dari 112 | Avengers hingga 117 | Shrek).

Menguji Fitur Tambah Data: Tambahkan satu film baru ke dalam sistem. Input: Ketik 1 (Tambah Data). Masukkan ID: 999 Masukkan Nama Film: Avatar 2 Masukkan Kategori: Sci-Fi Masukkan Jumlah Tiket: 100 Ekspektasi Output: >> Data berhasil ditambahkan! (Opsional: Anda bisa menekan 2 lagi untuk mengecek apakah Avatar 2 sudah ada di paling bawah daftar).

Menguji Fitur Edit Data: Ubah data film "Avatar 2" yang baru saja ditambahkan. Input: Ketik 3 (Edit Data). Masukkan ID Film: 999 Nama Baru: Avatar: The Way of Water Kategori Baru: Sci-Fi Jumlah Tiket Baru: 150 Ekspektasi Output: >> Data berhasil diupdate!

Menguji Fitur Transaksi (Beli Tiket Sukses & Gagal): Uji pengurangan stok tiket dan validasi jika tiket tidak cukup. a. Pengujian Berhasil: Input: Ketik 12 (Beli Tiket). Masukkan ID Film: 112 (Avengers). Jumlah tiket dibeli: 5 Ekspektasi Output: >> Tiket berhasil dibeli! >> Sisa tiket: 45 b. Pengujian Gagal (Stok Kurang): Input: Ketik 12 lagi. Masukkan ID Film: 112 Jumlah tiket dibeli: 100 Ekspektasi Output: >> Stok tiket tidak mencukupi!

Menguji Fitur Sorting (Pengurutan): Uji apakah algoritma Bubble Sort atau Selection Sort bekerja mengatur ulang array. Input: Ketik 6 (Urutkan ID). Ekspektasi Output: Daftar film akan dicetak ulang, namun kali ini dimulai dari ID paling kecil (101 | Frozen) ke paling besar. Input: Ketik 11 (Urutkan Jumlah Tiket). Ekspektasi Output: Daftar film dicetak berdasarkan sisa tiket dari yang paling sedikit ke paling banyak.

Menguji Fitur Searching (Pencarian Biner): Cari film menggunakan ID (Binary Search mewajibkan data diurutkan dulu, dan sistem Anda sudah menanganinya). Input: Ketik 8 (Cari ID). Masukkan ID yang dicari: 121 Ekspektasi Output: >> Film ditemukan: Joker

Menguji Fitur Hapus Data (Soft Delete): Hapus data film Avatar (ID 999) yang tadi ditambahkan. Input: Ketik 4 (Hapus Data). Masukkan ID Film: 999 Ekspektasi Output: >> Data berhasil dihapus!

Cek Statistik dan Keluar: Input: Ketik 10 (Statistik). Ekspektasi Output: Total Film Aktif : 30 (karena data ke-31, yaitu The Way Of Water, sudah dihapus). Input: Ketik 0 (Keluar). Ekspektasi Output: Program selesai. dan aplikasi berhenti berjalan.
