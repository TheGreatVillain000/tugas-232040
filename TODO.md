# TODO - Cloudflare R2 upload (api.php)

- [ ] Refactor `uploadToR2()` dan `deleteFromR2()` di `api.php` agar menggunakan **AWS SDK for PHP (S3 client)** untuk Cloudflare R2.
- [ ] Tambahkan dependency (composer) bila belum ada.
- [ ] Pastikan endpoint R2, credentials, dan region 설정 benar.
- [ ] Uji workflow: add/upload thumbnail+video, update (replace+delete old), delete (remove objects).
- [ ] (Opsional) Tambahkan logging minimal untuk error response dari SDK.

