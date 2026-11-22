# 💰 Financial Tracker (Offline & Widget Android)

Aplikasi pencatat keuangan pribadi berbasis Android yang ringan, cepat, dan **100% offline**. Dilengkapi dengan fitur **Widget Layar Beranda** untuk memantau sisa saldo secara langsung tanpa perlu membuka aplikasi.

## ✨ Fitur Utama
* **100% Offline & Privasi Terjaga:** Aplikasi ini sengaja dibuat **tanpa izin akses internet** (`INTERNET` permission). Seluruh data keuangan tersimpan secara lokal di perangkat Anda.
* **Widget Layar Beranda ("Sisa Saldo"):** Pantau sisa saldo secara *real-time* langsung dari layar utama (*home screen*) Android Anda.
* **Ringan & Cepat:** Dibangun menggunakan antarmuka web modern yang dibungkus menjadi aplikasi native Android.

## 🛠️ Cara Kerja Build Otomatis
Repositori ini menggunakan **GitHub Actions** (`.github/workflows/build.yml`) yang secara otomatis merakit file `index.html` menjadi proyek Android dan menerbitkan file `.apk` terbaru ke halaman *Releases* setiap kali ada pembaruan kode.
