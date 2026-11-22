# 💰 Financial Tracker (Offline & Widget Android)

Aplikasi pencatat keuangan pribadi berbasis Android yang ringan, cepat, dan **100% offline**. Dilengkapi dengan fitur **Widget Layar Beranda** untuk memantau sisa saldo secara langsung tanpa perlu membuka aplikasi.

## ✨ Fitur Utama
* **100% Offline & Privasi Terjaga:** Aplikasi ini sengaja dibuat **tanpa izin akses internet** (`INTERNET` permission). Seluruh data keuangan tersimpan secara lokal di perangkat Anda.
* **Widget Layar Beranda ("Sisa Saldo"):** Pantau sisa saldo secara *real-time* langsung dari layar utama (*home screen*) Android Anda.
* **Ringan & Cepat:** Dibangun menggunakan antarmuka web modern yang dibungkus menjadi aplikasi native Android.

## 📥 Cara Mengunduh & Instalasi (Android)
1. Buka halaman [**Releases**](../../releases) di sisi kanan repositori ini.
2. Pilih rilis versi terbaru (paling atas), lalu klik file **`Financial-Tracker.apk`** di bagian *Assets* untuk mengunduh.
3. Buka file APK yang sudah diunduh di HP Android Anda.
4. Jika muncul peringatan keamanan, pilih **Setelan / Settings** dan aktifkan izin **"Izinkan dari sumber ini"** (*Install from unknown sources*), lalu lanjutkan proses instalasi.

## 📱 Cara Memasang Widget Sisa Saldo
Setelah aplikasi terinstal:
1. Tekan dan tahan area kosong di layar beranda (*home screen*) HP Android Anda.
2. Pilih menu **Widget**.
3. Cari **Financial Tracker**, lalu seret widget **Sisa Saldo** ke layar beranda Anda.
4. Ketuk widget kapan saja untuk langsung membuka aplikasi dan mencatat transaksi baru.

## 🛠️ Cara Kerja Build Otomatis
Repositori ini menggunakan **GitHub Actions** (`.github/workflows/build.yml`) yang secara otomatis merakit file `index.html` menjadi proyek Android dan menerbitkan file `.apk` terbaru ke halaman *Releases* setiap kali ada pembaruan kode.
