# Mailcow + CasaOS + Cloudflare Tunnel

Ini adalah konfigurasi ringan untuk menjalankan Mailcow di CasaOS, dengan akses aman melalui Cloudflare Tunnel Zero Trust.

## Fitur:
- Akses webmail dan admin panel: https://mail.oxdel.my.id
- Kirim email keluar dengan SMTP relay (contoh: Mailjet)
- Tidak perlu buka port 25 di router

## Cara Instal:
1. Upload repo ini ke GitHub.
2. Di CasaOS > App Store > Custom Install.
3. Masukkan URL GitHub repo ini.
4. Tunggu hingga selesai dan jalankan dari App List.
5. Akses via https://mail.oxdel.my.id (pastikan tunnel sudah aktif).

## SMTP Relay (Opsional tapi disarankan):
Gunakan layanan seperti Mailjet, SendGrid, Mailgun, dll. Edit konfigurasi relay setelah Mailcow aktif
