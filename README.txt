#FokusCapital: PCPM 41 — Paket Deploy
======================================

Isi paket:
  - index.html   -> aplikasi planner (single-file, semua CSS/JS ada di dalamnya)
  - README.txt   -> file ini

CARA DEPLOY (pilih salah satu):

1) GitHub Pages (disarankan — paling stabil untuk kasus kamu sebelumnya)
   - Buat repo baru di GitHub (atau pakai repo lama yang sama, JANGAN buat
     repo baru tiap kali update — ini penyebab data hilang yang kamu alami
     di Netlify sebelumnya).
   - Upload index.html dan naruto-motivasi.jpg ke root repo (branch main).
   - Settings -> Pages -> Source: Deploy from branch -> pilih "main" / "root".
   - Tunggu 1-2 menit, situs aktif di https://<username>.github.io/<repo>/
   - Untuk update berikutnya: commit/replace file di REPO YANG SAMA, jangan
     bikin repo baru.

2) Netlify
   - Login ke situs Netlify yang SUDAH ada (jangan "Add new site" tiap deploy).
   - Site settings -> Deploys -> drag & drop folder ini (index.html +
     naruto-motivasi.jpg sekaligus, bukan satu-satu).
   - Ini akan meng-update site yang sama, progres tersimpan.

3) Vercel / Cloudflare Pages
   - Sama prinsipnya: upload kedua file ke project yang SAMA setiap kali
     ada update, jangan buat project baru.

CATATAN PENYIMPANAN DATA:
Progres belajar (checklist, pomodoro, catatan) disimpan otomatis di
browser (localStorage) begitu di-deploy di luar Claude.ai. Artinya data
tersimpan per-browser/per-device — kalau buka dari HP dan laptop, datanya
terpisah (tidak sinkron otomatis). Jangan clear browser data/cache kalau
belum ada backup progres.

Semangat, kejar kursi PCPM 41. 🎯
