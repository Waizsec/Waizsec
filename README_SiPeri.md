# SIPERI.KERJA
-------------

Selamat datang di catatan teknis untuk SIPERI.KERJA.

## 🔧 Instalasi 

Untuk melakukan instalasi, ikuti langkah-langkah di terminal/cmd:

1. Arahkan ke direktori utama aplikasi:
```bash
cd /lokasi/folder/penilaian360
```

2. Install paket-paket yang diperlukan:
```bash
npm install # Install npm (node package manager)
composer install # Install vendor (composer)
```

## 💡 Penggunaan

Untuk menjalankan program, pastikan terminal berada di direktori utama aplikasi (lihat instalasi), kemudian lakukan langkah-langkah berikut:

### 1. Jalankan Server Pengembangan (Development)
```bash
php artisan serve # Jalankan Server Laravel
npm run dev # Jalankan Server Node
```
Catatan: Kedua server harus berjalan dalam mode pengembangan.

### 2. Proses Deployment
```bash
npm run build # Jalankan Proses Produksi
```
Dengan ini, folder `build` akan terbentuk di dalam folder `public`.

### 3. Deployment ke XAMPP (PHP 8.2)

Untuk deployment ke XAMPP dengan PHP 8.2, ikuti langkah-langkah berikut:

a. **Masukkan Folder Aplikasi ke dalam XAMPP:**
   - Copy folder aplikasi ke dalam direktori XAMPP 8.2.

b. **Salin Isi dari Folder `public`:**
   - Salin semua isi folder `public` dari aplikasi.

c. **Paste di dalam `htdocs` (Ganti Semua File):**
   - Tempelkan isi tersebut di dalam direktori `htdocs` XAMPP, ganti semua file yang ada.

d. **Ubah Path dalam File `index.php`:**
   - Buka file `index.php` yang berada di dalam direktori `htdocs`.
   - Update path agar sesuai dengan struktur folder aplikasi.

## ⚙️ Konfigurasi

Untuk proses pengembangan program secara rinci, bisa dilihat dalam gdocs berikut : https://docs.google.com/document/d/1VAqUfFXkeceOqfsNNn1qA4AhTSnZRlUMuf2XQoJK3N4/edit?usp=sharing

