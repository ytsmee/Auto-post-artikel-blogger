Cara menggunakan script ini

🧰 Yang Kamu Butuhkan
Akun Google (Gmail)

Akun Blogger (sudah punya blog)
Akses ke Google Apps Script
RSS feed dari sumber berita (contoh: Kompas, Sindonews)

📜 Langkah-Langkah
1. Buka Google Apps Script
Kunjungi script.google.com
Klik + Project Baru

2. Copy dan Paste Script Txt

3. Aktifkan Blogger API
Klik menu Layanan (ikon puzzle di kiri)
Klik + tambahkan layanan
Cari Blogger API lalu klik Tambah

4. Ambil ID Blog Kamu
Masuk ke Blogger
Pilih blog kamu
Lihat URL-nya, misalnya:
Edit
https://www.blogger.com/blog/posts/1234567890123456789
Maka ID blog-nya adalah: 1234567890123456789
Ganti GANTI_DENGAN_ID_BLOG_KAMU di kode dengan ID tersebut.

5. Jalankan dan Izinkan Akses
Klik fungsi fetchAndPostRSS
Klik ikon ▶️ untuk menjalankan
Izinkan akses ke akun Google kamu

6. Buat Jadwal Otomatis
Klik menu Triggers (ikon jam ⏰ di kiri)
Klik + Add Trigger
Pilih fungsi: fetchAndPostRSS
Pilih waktu misalnya: Time-driven → Hourly
