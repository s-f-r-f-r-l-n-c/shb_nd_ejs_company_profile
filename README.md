# shb-nd-ejs-company-profile - Aplikasi Node.js Dynamic Company Profile

## Software Apakah Ini?

shb-nd-ejs-company-profile adalah website company profile yang bisa di-edit di panel admin.

## Screenshot

![ScreenShot](.readme-assets/shb-nd-ejs-company-profile-1.png?raw=true)

![ScreenShot](.readme-assets/shb-nd-ejs-company-profile-2.png?raw=true)

## Cara Mencoba Kode Ini

Untuk mencoba kode ini, buat file .env di dalam foldernya.

Selanjutnya, isi .env sesuai .env-example. Di sini Anda bisa mengubah port, environment, dan detail database.

Kode server-knex membutuhkan MySQL, jadi pastikan Anda telah menginstallnya dan membuat databasenya sesuai konfigurasi tadi.

Sekarang, pastikan Anda berada dalam folder ini.

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

Terakhir, buka browser Anda ke alamat yang tertera di BASE_URL yang ada di .env.

Default admin login:

```
username: admin@example.com
password: admin
```

## Pendahuluan

Kali ini, saya akan memberikan contoh website company profile dengan Node.js.

## Cara Kerja

Aplikasi ini bekerja seperti company profile pada umumnya, hanya saja ada beberapa fitur tambahan seperti admin panel.

## Struktur Project

Untuk melihat struktur project aplikasi ini, silakan buka project ini di text editor.
