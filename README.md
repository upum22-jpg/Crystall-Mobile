# Crystall Mobile (APK)

1. Upload semua isi folder ini ke repo GitHub (branch main).
2. Buka tab Actions, tunggu "Build APK" selesai (sekitar 5-10 menit).
3. Buka run yang berhasil, bagian Artifacts, unduh CrystallMobile-APK.
4. Ekstrak zip, pasang CrystallMobile.apk di HP.

Agar APK bisa di-update tanpa hapus aplikasi lama, isi 4 GitHub Secrets
(Settings > Secrets and variables > Actions): KEYSTORE_BASE64, KEYSTORE_PASSWORD, KEY_ALIAS, KEY_PASSWORD.
