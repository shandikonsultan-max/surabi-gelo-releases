# Surabi Gelo — Rilis APK

Repo **publik** ini hanya menampung berkas APK aplikasi kasir Surabi Gelo.
Kode sumbernya ada di repo privat `pos-surabi-gelo-mobile` dan **tidak** ada di sini.

Kenapa terpisah: tablet mengunduh pembaruan tanpa login, jadi berkasnya harus
bisa diakses publik. Membuat repo kode jadi publik hanya demi ini tidak sepadan
risikonya.

Aplikasi mengecek `latest.json` di Supabase Storage (bucket `app-releases`),
lalu mengunduh APK dari sini.

| Versi | Build | Berkas |
|---|---|---|
| 1.2.4 | 71 | `surabi-gelo-71.apk` |
| 1.2.3 | 70 | `surabi-gelo-70.apk` |
| 1.2.2 | 69 | `surabi-gelo-69.apk` |
| 1.2.1 | 68 | `surabi-gelo-68.apk` |
