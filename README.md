# Nabung 20K

Aplikasi tabungan harian bertema galaksi. Semua data tersimpan lokal di HP.

## Dapatkan APK lewat GitHub (tanpa Android Studio)

1. Buat repo baru di GitHub, lalu upload SEMUA isi folder ini (termasuk folder `.github`).
2. Buka tab **Actions** > **Build APK** > tunggu sampai centang hijau (sekitar 5-8 menit).
   Kalau tidak jalan otomatis: **Run workflow**.
3. Buka run yang berhasil > bagian **Artifacts** > unduh `Nabung20K-apk` (zip berisi `Nabung20K.apk`).
4. Ekstrak zip, kirim APK ke HP, buka, lalu izinkan "Pasang dari sumber tidak dikenal".

### Biar ada tombol unduh langsung (Releases)
Beri tag versi: `git tag v1.0.0 && git push origin v1.0.0`. APK muncul di **Releases**.

## Catatan
- APK yang dibuat adalah **debug** (bisa langsung dipasang, bukan untuk Play Store).
- Ubah aplikasi: edit `index.html`, push lagi, APK baru dibuild otomatis.
- Pengingat hanya berbunyi saat aplikasi terbuka.
- Tombol Unduh backup di APK membuka menu Bagikan (simpan ke Drive/WhatsApp dsb.).
