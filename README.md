# TRUCKING INVENTORY MANAGEMENT SYSTEM — Demo Login Role

Buka `index.html` di browser atau unggah ke root repository GitHub Pages.

## Akun demonstrasi
- Driver: username `drivertrk`, password `123`
- Admin/PIC: username `admintrk`, password `1234`

Role dideteksi otomatis dari username + password, tanpa pilihan role pada layar login. Driver hanya melihat halaman pengajuan IN/OUT dan riwayatnya. Admin melihat monitoring, verifikasi, peminjaman aktif, dan laporan.

**PERINGATAN:** Login ini hanya untuk demonstrasi lokal. Kredensial ada di JavaScript publik dan tidak melindungi data. Data transaksi masih disimpan di `localStorage` per browser/perangkat, bukan Google Sheets. Jangan unggah data nyata atau gunakan sebagai sistem operasional. Autentikasi dan pemeriksaan otorisasi harus dilakukan di backend, misalnya Google Apps Script dengan penyedia identitas yang sesuai.

Ekspor Excel saat ini menghasilkan `.xls` berbasis HTML (bukan `.xlsx` asli), dan PDF menggunakan Print/Save as PDF.
