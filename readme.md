# Cek ID Game API

Api untuk cek username game

## INSTALL DI VPS

1. Siapkan vps
2. Jangan Lupa install nodejs, dan pm2, nginx/apache (opsional)
3. Deploy Aplikasi Kamu dengan perintah diterminal
   -  npm install
   -  node 'index.js' atau 'pm2 start index.js'

## Install di Vercel

Gapunya VPS? Gapunya Hosting Node? Tenang, Bisa hosting Gratisan di vercel

-  Upload scriptnya di github
-  Buka Akun vercel
-  Import Project

## Install DI CPANEL NODE (node 18 recomended)

1. upload ke file manager hosting
2. Jalanin node js di cpanel, kalau kurang ngerti bisa google caranya
   -  startup file index.js

## CARA UPDATE LIST GAME JIKA ADA PERUBAHAN DARI PROVIDERNYA

1. Wajib dijalanin di computer atau di vps gabisa langsung di cpanel
2. Update Codashop Jalanin perintah dibawah (pastikan sudah berada di directory script gamenya)
   -  npm run update:coda
      atau
   -  node update-list-game/codashopUpdate.js
      Update DuniaGames Jalanin perintah dibawah (pastikan sudah berada di directory script gamenya)
   -  npm run update:dg
      atau
   -  node update-list-game/duniagamesUpdate.js

Kalo scriptya di cpanel Gimana gabisa update dong kan ga suport terminal? Tenang!
Jalanin dulu cara diatas di pc lokal
lalu pergi ke folder utils/data
disini kalian copy saja list gamenya dari file codasshop.json atau duniagames.json (sementara hanya 2 provider ini yang suport)
lalu kalian edit file kalian yg di cpanel dengan list game yg baru

### ERROR ATAU BUG

Kalo Error atau ada game yang gabisa bisa hubungi saya. (Sertakan nama game dan id yang work)
Mau Nambah game jg bisa.

Gabisa install? Langsung saja hubungi untuk jasa install.
