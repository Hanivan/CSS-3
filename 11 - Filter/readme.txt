Filter adalah property CSS3 yang digunakan untuk memberikan efek visual pada gambar, background, atau border
 Penulisan:
  filter: <tipe-filter>;

Jangan lupa juga tambahkan verdor prefix untuk property ini. Karena property hanya didukung oleh browser-browser tertentu saja.

Tipe-tipe filter:
 - blur (px)
 - brightness (angka | %)
 - contrast (angka | %)
 - saturate (angka | %)
 - grayscale (angka | %)
 - sepia (angka | %)
 - hue-rotate (deg)
 - invert (angka | %)
 - opacity (angka | %)
 - drop-shadow (sama seperti box-shadow)

Perbedaan property opacity pada filter dan property opacity pada CSS3 yaitu... Jika memakai property filter, maka prosesnya akan lebih cepat dibanding memakai property CSS3 opacity. Tetapi filter: opacity(); ini.. Masih experimental.

drop-shadow pada filter itu lebih keren dibandingkan dengan property CSS3 yaitu box-shadow. Karena filter: drop-shadow(); ini, bisa diterapkan pada image atau text.

drop-shadow juga sangat OP jika diterapkan pada gambar yang backgroundnya transparant/.png. Jadi si drop-shadow ini akan memberikan efek shadow-nya pada objek-nya, bukan pada kotak gambar-nya/container

Kita juga bisa menumpuk efek-efek dari property filter ini. Jadi mirip seperti efek pada Instagram.

Jika tidak ingin mengira-ngira berapa tajam efek-nya. Kita bisa kunjungi website http://html5-demos.appspot.com/static/css/filters/index.html