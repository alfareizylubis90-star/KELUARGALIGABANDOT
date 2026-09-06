# KELUARGALIGABANDOT

Aplikasi admin dashboard SPA responsif untuk manajemen anggota, absen paspor, dan perizinan.

## Menjalankan

Buka `index.html` langsung di browser. Tidak membutuhkan build step atau instalasi dependency.

Akun demo:

- `admin` / `admin123`
- `kapten01` / `kapten123`
- `cs01` / `cs123`
- `kasir01` / `kasir123`

## Fitur

- Login session dan menu berbasis role
- Dashboard realtime dengan statistik operasional
- Data anggota, pencarian, filter, tambah/edit/hapus/reset demo
- Absen paspor shift pagi dengan progres
- Pengajuan izin KENCING, BAB, dan BELGI
- Kapasitas izin, modal konfirmasi, countdown, pembatalan, dan auto selesai
- Monitoring, riwayat, rekap, pengaturan durasi, dan activity log
- Responsive desktop/mobile dengan mobile sidebar
- Data demo tersimpan di `localStorage` agar alur dapat dicoba tanpa server

## Catatan produksi

Versi ini sengaja dibuat dapat dijalankan langsung sebagai prototype fungsional tanpa Node.js yang tersedia di environment. Untuk produksi, pindahkan penyimpanan `localStorage` ke backend terpusat dengan password hashing, session cookie httpOnly, validasi endpoint berbasis role, database server, dan WebSocket/SSE untuk realtime lintas perangkat.
