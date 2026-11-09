MDA UNIVERSE — VISUAL UPGRADE

Isi ZIP ini adalah pengganti untuk 3 file website:
- index.html
- style.css
- app.js

JANGAN ganti atau hapus config.js milikmu. File itu berisi URL dan Publishable Key Supabase.
JANGAN jalankan ulang atau menghapus tabel database hanya untuk memasang tampilan ini.

Cara pasang:
1. Ekstrak ZIP.
2. Buka repository GitHub MDA-WEBSITE.
3. Upload/replace index.html, style.css, dan app.js di root repository.
4. Commit changes.
5. Buka ulang website dan refresh.

Fitur:
- Login dan daftar melalui Supabase Auth.
- Profil username dan bio.
- Cari pemain dan kirim/terima permintaan pertemanan.
- Status online/offline berbasis Supabase Realtime Presence (teman online terlihat saat membuka website).
- Chat realtime antarteman.
- Mini games offline: Puzzle 3x3, Memory Match, Tap Race, Tic-Tac-Toe lokal dua pemain.

Catatan:
- Gunakan config.js yang sudah berisi Project URL dan Publishable Key.
- Social login eksternal, upload storage, dan multiplayer game belum diaktifkan.
- Pastikan Supabase Realtime aktif untuk tabel messages dan kebijakan RLS sudah benar.
