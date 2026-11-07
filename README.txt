WEB-AK PWA STARTER

Isi paket:
- index.html: dashboard responsif, demo login, data karyawan dan absensi lokal
- manifest.webmanifest: identitas aplikasi PWA
- sw.js: cache app shell untuk akses offline setelah kunjungan pertama
- icons/: ikon aplikasi

CARA MEMASANG KE GITHUB PAGES:
1. Buka repository GitHub kamu: Web-Ak.
2. Pilih Add file > Upload files.
3. Ekstrak ZIP ini di komputer terlebih dahulu.
4. Upload semua ISI folder web-ak-pwa (index.html, manifest.webmanifest, sw.js, dan folder icons), bukan folder induknya.
5. Pastikan index.html berada di root repository, sejajar dengan README.md.
6. Klik Commit changes ke branch main.
7. Tunggu GitHub Pages selesai deploy, lalu buka ulang alamat website.

LOGIN DEMO:
Username: admin
Password: admin123

PENTING:
Ini adalah prototipe awal. Login demo hanya pemeriksaan di sisi browser dan TIDAK aman untuk data nyata. Data karyawan dan absensi disimpan di localStorage browser/perangkat ini saja; belum tersinkron antarperangkat dan belum memiliki backend/database server. Jangan masukkan data pribadi atau data penggajian sungguhan sebelum autentikasi server, database terpusat, backup, dan kontrol akses dibuat.

OFFLINE:
Buka website saat online setidaknya sekali agar service worker dapat menyimpan app shell. Setelah itu halaman dapat dibuka kembali secara offline pada browser yang sama. Data lokal tetap berada di perangkat/browser tersebut.
