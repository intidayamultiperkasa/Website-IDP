WEBSITE PT INTI DAYA MULTI PERKASA

ISI FOLDER
  index.html        halaman utama (edit di VS Code)
  images/           semua foto dan logo (ganti file di sini, nama sama)
  favicon.ico, site.webmanifest, robots.txt, sitemap.xml  -> jangan dihapus

EDIT DI VS CODE
  1. File > Open Folder > pilih folder ini
  2. Pasang ekstensi "Live Server", klik kanan index.html > Open with Live Server
  3. Ctrl+S untuk menyimpan, browser otomatis menyegarkan

LOKASI BAGIAN YANG SERING DIUBAH (Ctrl+F di index.html)
  var P=[       daftar proyek 2026
  var C=[       daftar klien
  var POSTS=[   artikel blog
  :root{        warna dan font
  6285869577639 nomor WhatsApp (pakai Ctrl+H untuk ganti semua)

PUBLISH
  Netlify / Cloudflare Pages: seret SELURUH folder ini ke halaman Deploy.
  cPanel: unggah semua isi folder ke public_html.

SETELAH DOMAIN FIX
  Jika domain bukan www.intidayamultiperkasa.com, ganti alamat tersebut di
  index.html (canonical, og:url, og:image, JSON-LD), robots.txt, dan sitemap.xml
  (Ctrl+H, Replace All).
