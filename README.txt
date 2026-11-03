DIHO KASIR PRO — PWA starter package

FITUR DEMO
- POS: cari barang berdasarkan nama/SKU, keranjang, checkout, pengurangan stok.
- Inventaris: tambah/hapus barang dan stok.
- Membership: daftar member dan poin awal.
- Back-office: ekspor data JSON.
- Laporan: ringkasan penjualan dan ekspor CSV.
- Keamanan: backup dan pulihkan JSON.
- PWA: manifest, service worker, cache offline.

CARA MENJALANKAN
1. Ekstrak ZIP.
2. Untuk uji lokal, jalankan server web di folder ini (service worker memerlukan HTTPS atau localhost).
   Contoh komputer: python -m http.server 8000
   Buka http://localhost:8000
3. Untuk HP Android: unggah isi folder ke hosting HTTPS seperti GitHub Pages.
   Buka URL di Chrome > menu ⋮ > Tambahkan ke layar utama / Install app.

CATATAN
Ini paket prototipe front-end dengan penyimpanan lokal browser. Belum terhubung ke server,
printer kasir, perangkat barcode khusus, sinkronisasi multi-kasir, atau sistem resmi Indomaret.
Gunakan nama/logo dan aset yang Anda punya hak untuk gunakan. Data demo disimpan pada perangkat.
