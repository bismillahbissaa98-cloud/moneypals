MONEYPALS APK

Project ini membuat APK Android yang membuka versi MoneyPals yang sudah aktif di GitHub Pages.

Yang sudah disiapkan:
- Nama aplikasi: MoneyPals
- Package: com.moneypals.app
- Ikon MoneyPals warna kuning/hitam
- WebView dengan JavaScript + penyimpanan browser
- URL aplikasi: https://bismillahbissaa98-cloud.github.io/moneypals/
- GitHub Actions untuk membangun APK secara otomatis

CARA MEMASANG KE REPOSITORY:
1. Buka repository: moneypals
2. Upload folder/files dari ZIP ini ke root repository.
3. Pastikan file berikut berada di tempat yang sama seperti struktur ZIP:
   settings.gradle
   build.gradle
   app/
   .github/workflows/build-apk.yml
4. Commit changes.
5. Buka tab Actions.
6. Pilih "Build MoneyPals APK".
7. Jika workflow belum berjalan, tekan "Run workflow".
8. Setelah selesai hijau, buka hasil workflow dan bagian Artifacts.
9. Download "MoneyPals-APK".
10. Ekstrak ZIP artifact dan instal app-debug.apk di Android.

CATATAN:
APK ini adalah wrapper resmi untuk website MoneyPals. Jadi ketika tampilan/data web diperbarui di GitHub Pages, APK akan menampilkan versi web terbaru saat online.
