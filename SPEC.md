# SPEC — PawonBoga

## Tujuan
Katalog dan dashboard produk UMKM makanan-minuman.

## Fitur
1. Katalog: menampilkan daftar produk (nama, harga, kategori, deskripsi).
2. Dashboard: tambah, ubah, hapus produk (CRUD).
3. Penyimpanan: localStorage dengan key `pawonboga:products:v1`, data divalidasi saat dibaca.
4. Import/export data produk dalam format JSON.
5. Tombol pesan via WhatsApp (nomor disimpan di `src/products.js`).

## Teknologi
Vite, JavaScript (vanilla), localStorage, Vitest.

## Batasan
- Tanpa autentikasi dan tanpa backend; bukan sistem produksi.
- Tidak menyimpan data sensitif atau kunci API di kode.

## Kriteria selesai
- Semua fitur di atas berjalan di browser.
- `npm test` lulus.
- Aplikasi ter-deploy dan bisa diakses lewat URL.