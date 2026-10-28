VIRTUAL SPACE OPPO — PROTOTIPE UJI 0.1

Yang dapat diuji:
- Membuka pemilih file dan menyalin file .apk ke penyimpanan internal aplikasi.
- Menampilkan daftar file APK yang sudah disalin.
- Meminta izin Android untuk menampilkan panel melayang.
- Panel melayang dapat digeser dan ditutup.

Yang BELUM tersedia:
- APK yang diimpor TIDAK dipasang atau dijalankan di ruang virtual.
- Belum ada mesin virtualisasi seperti VirtualApp.
- Belum ada beberapa aplikasi pihak ketiga yang benar-benar berjalan bersamaan.
Ini adalah prototipe antarmuka dan overlay, bukan aplikasi clone/virtualisasi lengkap.

Build:
1. Buka folder proyek ini di Android Studio.
2. Gunakan JDK 17 dan Android SDK Platform 35 (Android Gradle Plugin 8.6.1).
3. Tunggu Gradle Sync selesai.
4. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug biasanya berada di app/build/outputs/apk/debug/app-debug.apk.
6. Pasang di HP Android 13 untuk menguji impor file dan izin overlay.

Catatan:
- Perangkat perlu mengizinkan instalasi aplikasi dari sumber yang dipilih.
- Proyek ini memerlukan internet saat pertama kali mengunduh plugin Gradle jika belum tersimpan di cache.
