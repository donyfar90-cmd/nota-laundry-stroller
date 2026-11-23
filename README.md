# KasirNota Pro — Web App + Android APK via GitHub Actions

Repositori ini berisi aplikasi web kasir **KasirNota Pro** (Mode Laundry & Persewaan Barang/Stroller) sekaligus proyek **Android WebView** yang otomatis membangun file `.apk` menggunakan **GitHub Actions** tanpa perlu menginstal Android Studio di komputer lokal.

## Cara Upload ke GitHub & Mendapatkan File APK

1. Buat repositori baru di **GitHub** (misalnya bernama `kasirnota-pro`).
2. Ekstrak file ZIP ini, lalu *upload* semua isinya (termasuk folder tersembunyi `.github/workflows/build-apk.yml`) ke repositori GitHub Anda.
3. Buka tab **Actions** di repositori GitHub Anda.
4. Workflow **Build Android APK** akan berjalan otomatis (atau klik **Run workflow** jika perlu).
5. Setelah statusnya hijau (*Success*), klik nama *workflow run* tersebut, lalu gulir ke bawah ke bagian **Artifacts** dan unduh **`KasirNota-Pro-APK`**.
6. Ekstrak file ZIP artifact tersebut untuk mendapatkan **`app-debug.apk`**, lalu pindahkan ke HP Android dan instal.
