Clay Space Odyssey - Putra Ananta Darmawan

Cara pakai:
1. Ekstrak zip, lalu upload folder ini ke hosting statis (Vercel, Netlify, Cloudflare Pages, GitHub Pages).
   Atau jalankan lokal: npx serve  (jangan buka index.html langsung via file://).
2. index.html sudah berisi semua 15 model 3D (sudah dioptimasi, total ~6,6 MB), jadi tidak butuh folder lain.
3. Butuh internet untuk memuat library dari CDN (three.js r147, GSAP, font Fredoka).

Yang bisa kamu ubah di index.html (cari nama variabelnya):
- CV_URL  : isi dengan link PDF CV agar tombol berubah jadi "Download Resume / CV".
- WEB3KEY : access key dari web3forms.com (gratis, daftar dengan emailmu). Jika diisi, tombol Send Message langsung mengirim pesan ke emailmu tanpa membuka aplikasi email.
- MAIL    : alamat email tujuan formulir kontak.
- Z       : posisi tiap zona di dunia 3D.
- SK      : daftar skill beserta penjelasannya (EN & ID).
- PID/PEN : isi panel dalam Bahasa Indonesia / English.
