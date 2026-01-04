1. pengguna
- username, email, password, nama, no telpon
2. crud outlet
- nama outlet, alamat, id_perusahaan
3. crud produk
- outlet, nama, sku, deskripsi, kategori, monitoring stok, harga jual, harga diskon, persen diskon, harga modal (opsional)
4. kelola stok
- produk, stok
5. laporan
- penjualan
6. pos 
- pos detail => produk, qty, diskon di akhir transaksi pakai vocer, status
- cetak label/struk
- pos transaksi => jumlah, diskon, jenis pembayaran, kasir
7. pelanggan / member
- nama, nomor telpon
8. pivot pengguna - outlet
- pengguna, outlet
9. hak akses
- id_parent, nama hak akses, deskripsi, level
10. perusahaan / bisnis
- nama, telpon, alamat
11. crud vocer kupon
- nama, diskon, kode, stok, tanggal berlaku, tanggal expired
12. dashboard utama
- total penjualan perbulan
- total transaksi
- pelanggan baru
- rata rata transaksi
- produk terlaris
- transaksi 10 terakhir
13. hak akses - pengguna
- id_hak akses, id pengguna
14. notifikasi
- stok produk