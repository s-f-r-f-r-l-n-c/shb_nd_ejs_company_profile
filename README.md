# shb_nd_ejs_company_profile - Aplikasi Node.js Dynamic Company Profile

## Software Apakah Ini?

shb_nd_ejs_company_profile adalah source code website company profile yang bisa di-edit di panel admin...

## Cara Kerja

Aplikasi yang dibuat dari source code ini bekerja seperti company profile pada umumnya, hanya saja ada beberapa fitur tambahan seperti admin panel.

Database yang digunakan dalam aplikasi itu adalah MySQL dan library yang digunakan dalam kodenya adalah Knex.

Knex itu sendiri adalah library query builder yang salah satunya untuk MySQL.

## Cara Mencoba Kode Ini

Sekarang, saya akan membahas cara mencoba kode ini di komputer lokal dengan sistem operasi Windows 11.

Untuk mencoba kode ini, copy file .env-example sebagai .env

Sekarang, kita memiliki file .env dalam folder source code.

Selanjutnya, ubah isi dari .env sesuai dengan detail database dan sistem Anda.

Di sana Anda bisa mengubah port, environment, session secret, dan detail database.

Kode ini membutuhkan MySQL, jadi pastikan Anda telah menginstallnya di komputer Anda dan membuat databasenya sesuai konfigurasi yang ada di file .env tadi.

Sekarang, kita telah memiliki database di MySQL dan file .env yang sudah dikonfigurasi.

Pastikan Anda berada dalam folder source code.

Selanjutnya, jalankan:

```
npm install
```

Selanjutnya, jalankan:

```
npm run db:refresh
```

Selanjutnya, jalankan:

```
npm run dev
```

Terakhir, buka browser Anda ke alamat yang tertera di BASE_URL yang ada di .env

Secara default adalah:

http://localhost:3000

Di bagian paling bawah halaman tersebut, ada link login dan register untuk admin.

Default admin login:

```
username: admin@example.com
password: admin
```

Untuk mengubah favicon di halaman depan, replace favicon.png yang ada di folder "/public/img" yang ada di dalam folder source code.

## Screenshot

![ScreenShot](https://github.com/shbfrlnc/shbfrlnc-images/blob/main/gratisan/shb-nd-ejs-company-profile/screenshot-0.png?raw=true)

![ScreenShot](https://github.com/shbfrlnc/shbfrlnc-images/blob/main/gratisan/shb-nd-ejs-company-profile/screenshot-1.png?raw=true)