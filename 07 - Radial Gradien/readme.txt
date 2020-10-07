Sintaks sederhana dari radial gradien:

background-image: radial-gradient(<warna-awal>, <warna-akhir>);
 Contoh
  background-image: radial-gradient(red,blue);
 Atau
  background-image:
  	radial-gradient(<warna-1>, <warna-2>, ... , <warna-3>);
 Sintaks Lengkap
  background-image: radial-gradient(
  <tipe> <jangkauan> at <posisi-x> <posisi-y>,
  <warna-1>, <warna-2>, ... , <warna-n>
  );

Penjelasan:
Ada dua tipe dari radial-gradient, yaitu:
 - ellipse
 - circle

Nilai default dari tipe radial-gradient adalah ellipse

Maksud dari jangkauan diatas adalah Jarak pusat gradient ke sisi terluarnya. Ada 4 tipe, yaitu:
 - closest-corner => Jarak dari pusat gradient ke Sudut Terdekat element
 - closest-side => Jarak dari pusat gradient ke Sisi Terdekat element
 - farthest-corner => Jarak dari pusat gradient ke Sudut Terjauh element
 - farthest-side => Jarak dari pusat gradient ke Sisi Terjauh element

Nilai default dari tipe jangkauan radial-gradient adalah farthest-corner

Untuk posisi, kita bisa menggunakan value:
 Posisi-y:
  - top
  - bottom
  - center
  - px (satuan)
 Posisi-x:
  - left
  - right
  - center
  - px (satuan)