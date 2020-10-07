Penggunaan font pada CSS:
 - font-family: "Arial Narrow", arial, sans-serif;
 	Pada property "font-family" ini, value font-nya harus ada di sisi sistem operasi client/pengguna, jika tidak ada. Maka value kedua dan seterusnya akan menggantikan value pertama
 - Google Fonts http://www.fonts.google.com, ini adalah font berbasis cloud yang dimiliki oleh perusahaan google. Otomatis, jika web kalian yang tadinya offline, maka web kalian akan membutuhkan koneksi internet untuk memakai font dari google.

Ada teknik dari CSS 3 untuk font Face, yaitu:
 @font-face {
 font-family: 'namaFontBaru';
 src: url('lokasi/file/fontBaru.eot');
 src: url('lokasi/file/fontBaru.eot?#iefix') format('embedded-opentype'),
 	url('lokasi/file/fontBaru.woff2') format('woff2'),
 	url('lokasi/file/fontBaru.woff'), format('woff'), -- Didukung oleh semua browser versi terbaru
 	url('lokasi/file/fontBaru.ttf') format('truetype'), -- Didukung oleh semua browser versi terbaru
 	url('lokasi/file/fontBaru.svg#svgFontName') format('svg');
 }
Untuk properti css 3 ini, kita harus mempunyai type font-nya. format font yang berbeda juga mempengaruhi dukungan browser-nya terhadap format" font diatas

Untuk format ttf, biasanya akan lambat dimuat oleh website. Untuk mengatasi masalah tersebut, maka dikeluarkan format woff. Perhatikan juga sisi free/berbayar dan license-nya

Layanan-layanan font populer:
 - fonts.google.com
 - fontsquirell.com
 - fontspiring.com
 - webtype.com
 - typotheque.com
 dll.