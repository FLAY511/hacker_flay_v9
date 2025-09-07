# CYBER FLAY v9 (SAFE)

Ini paket CYBER FLAY v9 (SAFE) - berisi script bawaan untuk Termux dengan fitur:
- OSINT Optimal (gabungan: whois, dns, subdomain, ip geolocation, port scan ringan, headers, whatcms demo)
- Username checker (cek 1x per situs, keluarkan link jika ketemu)
- Phone lookup (cek link/kemungkinan pada berbagai platform: wa.me, t.me, truecaller, google, pastebin)
- JSO helper (buka haxor.my.id, tempel HTML -> simpan .jso)
- Menu Lain (10 utilities)
- Dark Web informational link
- About + banner

## Install di Termux
pkg update -y
pkg install -y git curl openssl bc coreutils
unzip hacker_flay_v9.zip
cd hacker_flay_v9
chmod +x hacker_flay_v9.sh
./hacker_flay_v9.sh

## Catatan
- SAFE edition: tidak ada fitur deface/exploit. Jika ingin fitur lanjutan yang butuh API, sediakan API key dan aku bisa tambahkan.
- Beberapa hasil pencarian bergantung pada index mesin pencari dan rate-limiting.
