# Basic Config URL

## Penjelasan

Berikut ini beberapa konfigurasi dasar yang bisa lo masukin di file `.htaccess`:

- **RewriteEngine On**  
  Ini buat ngasih tahu server kalau kamu mau mulai rewrite URL.

- **RewriteCond**  
  Kondisi untuk ngecek sesuatu, misalnya kalo HTTPS belum aktif, dia akan ngarahin ke HTTPS.

- **RewriteRule**  
  Aturan buat nge-rewrite URL. Contohnya, URL kayak `produk/12` akan diarahin ke `index.php?page=produk&id=12`.

- **ErrorDocument 404**  
  Ini buat ngarahin user ke halaman custom kalo ada link yang nggak ditemukan.

> **Catatan**  
> Simpan file `.htaccess` ini di root folder website lo (biasanya di `public_html` atau folder project Laravel kalo lo pake).

Tinggal modif aja sesuai kebutuhan, bro! 🚀
