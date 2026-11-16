# WBA Expedition Tracker v0.2.0

Dashboard pencatatan ekspedisi West Borneo Alliance dengan penyimpanan lokal browser (IndexedDB).

## Isi folder
- `index.html` — struktur aplikasi
- `style.css` — tampilan dark dashboard
- `script.js` — fitur dan database lokal

## Fitur
- Dashboard statistik ekspedisi dan aktivitas tahunan
- Tambah, edit, hapus, cari, dan filter ekspedisi
- Database anggota dan profil anggota
- Galeri dokumentasi foto/video
- Peta ekspedisi berbasis koordinat
- Mountain Passport
- Laporan, ekspor CSV, cetak PDF, backup dan restore JSON
- Pengaturan identitas komunitas
- **v0.2:** login PIN admin, ganti/hapus logo WBA, pratinjau logo, dan logo ikut tersimpan dalam backup

## Menjalankan di komputer
1. Ekstrak ZIP.
2. Buka folder `WBA-EXPEDITION-TRACKER` di VS Code.
3. Jalankan `index.html` menggunakan ekstensi Live Server.

## Login admin v0.2
- PIN demo awal: `2468`
- Sebelum dipublikasikan, ubah nilai `ADMIN_PIN` di bagian atas `script.js`.
- Format logo: PNG/JPG/WEBP, maksimal 2 MB.

## Catatan penting
Aplikasi ini masih **local-first**. Data tersimpan di browser/perangkat yang digunakan, tidak otomatis tersinkron antarperangkat. Backup secara berkala.

Login PIN v0.2 adalah pengunci antarmuka sisi-klien, bukan autentikasi server yang aman. PIN dapat ditemukan oleh orang yang memeriksa source code JavaScript. Jangan gunakan untuk melindungi data rahasia atau memberi akses aman pada website publik. Untuk autentikasi sungguhan dan sinkronisasi lintas perangkat, diperlukan backend/database dan sistem akun.
