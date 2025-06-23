Tentu, ini adalah draf `README.md` yang siap Anda gunakan untuk repositori GitHub proyek ini. File ini ditulis dalam format Markdown.

Anda bisa membuat file baru di repositori Anda dengan nama `README.md` dan menyalin-tempel konten di bawah ini.

-----

# Penjadwal Ronda Malam (Web App)

Aplikasi web sederhana untuk membuat, menampilkan, dan mengekspor jadwal ronda malam secara otomatis. Dibuat sepenuhnya dengan HTML, CSS, dan JavaScript (tanpa backend), sehingga sangat ringan dan mudah di-deploy di platform hosting statis seperti GitHub Pages.

*(Ganti URL gambar di atas dengan screenshot aplikasi Anda sendiri jika diinginkan)*

-----

## ✨ Fitur Utama

  - **Formulir Input Dinamis**: Atur tanggal mulai, tanggal berakhir, jumlah tim, nama tim, dan interval pergantian giliran.
  - **Generasi Nama Tim Otomatis**: Jika daftar nama tim dikosongkan, aplikasi akan membuat nama generik (Tim 1, Tim 2, dst.) secara otomatis.
  - **Tampilan Jadwal per Bulan**: Jadwal yang dihasilkan dikelompokkan dengan rapi berdasarkan bulan untuk kemudahan membaca.
  - **Layout Kolom Responsif**:
      - Setiap bulan menampilkan jadwal dalam kolom-kolom berisi maksimal 10 baris.
      - Di layar lebar, kolom akan berjajar ke samping.
      - Di layar ponsel, kolom akan tersusun vertikal untuk keterbacaan optimal.
  - **Sorotan "Hari Ini"**: Baris jadwal untuk tanggal hari ini secara otomatis ditandai dengan gaya visual yang berbeda.
  - **Ringkasan Jadwal**: Menampilkan informasi tim yang akan bertugas selanjutnya di bagian atas halaman.
  - **Ekspor ke Excel**:
      - Menyediakan data dalam format `DD/MM/YYYY,Nama Tim` yang siap disalin.
      - Dilengkapi instruksi `Text to Columns` untuk memisahkan data di Excel.
      - Tersedia tombol "Salin Teks" untuk kemudahan.
  - **Desain Ramah Cetak (Print-Friendly)**: Saat mencetak, elemen yang tidak perlu (form, tombol) akan disembunyikan, menyisakan tabel jadwal yang bersih dan rapi di atas kertas.
  - **100% Client-Side**: Tidak memerlukan server atau database. Semua proses berjalan langsung di browser pengguna.

-----

## 🚀 Live Demo

Anda dapat mencoba aplikasi ini secara langsung di sini:

**[https://NAMA\_ANDA.github.io/NAMA\_REPOSitori\_ANDA/](https://www.google.com/search?q=https://NAMA_ANDA.github.io/NAMA_REPOSitori_ANDA/)**

*(Jangan lupa ganti `NAMA_ANDA` dan `NAMA_REPOSitori_ANDA` dengan URL GitHub Pages Anda)*

-----

## 🛠️ Teknologi yang Digunakan

  - **HTML5**: Struktur dasar halaman web.
  - **CSS3 (Vanilla)**: Styling modern dan responsif, termasuk penggunaan Flexbox dan media queries untuk layout dinamis serta mode cetak.
  - **JavaScript (ES6+)**: Logika inti aplikasi, termasuk manipulasi DOM, pemrosesan tanggal, dan pembuatan jadwal.

Tidak ada *framework* atau *library* eksternal yang digunakan untuk menjaga aplikasi tetap ringan dan mandiri.

-----

## 📖 Cara Menggunakan

1.  Buka aplikasi melalui link demo di atas atau buka file `index.html` di browser Anda.
2.  Isi formulir sesuai kebutuhan:
      - Pilih **Tanggal Mulai** dan **Tanggal Berakhir**.
      - Masukkan **Jumlah Tim** dan **Interval Pergantian**.
      - Isi **Nama Tim** (satu nama per baris). Biarkan kosong untuk menggunakan nama default.
3.  Klik tombol **"Buat Jadwal"**.
4.  Jadwal akan muncul di bawah formulir, dikelompokkan per bulan.
5.  Untuk mengekspor, salin teks dari area **Ekspor ke Excel** dan ikuti petunjuk yang diberikan.

-----

## 🌐 Cara Deploy Sendiri di GitHub Pages

Anda dapat mendeploy versi Anda sendiri secara gratis hanya dalam beberapa langkah:

1.  **Fork** atau **unduh** repositori ini.
2.  Buat repositori baru di akun GitHub Anda.
3.  Unggah file `index.html` ke repositori baru tersebut.
4.  Pergi ke tab **Settings** di repositori Anda.
5.  Di menu samping, pilih **Pages**.
6.  Di bawah bagian "Build and deployment", pilih sumber (Source) dari **Deploy from a branch**.
7.  Pilih branch `main` (atau `master`) dan folder `/root`, lalu klik **Save**.
8.  Tunggu beberapa menit, dan GitHub akan memberikan URL publik untuk aplikasi Anda.

-----

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat file `LICENSE` untuk detail lebih lanjut (jika ada) atau anggap Anda bebas untuk memodifikasi dan mendistribusikan ulang sesuai ketentuan lisensi MIT.
