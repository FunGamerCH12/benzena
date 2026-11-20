# AromatikLab (APK)

Web app `www/index.html` dibungkus Capacitor jadi APK Android lewat GitHub Actions.

## Cara pakai
1. Push ke branch `main` -> tab **Actions** -> workflow **Build APK** jalan otomatis.
2. Selesai (~3-5 menit), unduh artifact **AromatikLab-apk** (zip berisi `AromatikLab.apk`).
3. Mau jadi Release: `git tag v1.0.0 && git push origin v1.0.0`.

Update konten: edit `www/index.html`, commit, push.
