
## Installation

Laravel 5.6 menggunakan PHP versi 7.0. Jadi kalau belum update dulu. Lalu pastikan sudah menginstal composer.

1. Clone repository, bisa di download .zip atau dengan perintah git clone seperti ini

```
git clone https://github.com/AnjaniCH/restoan_laravel.git
```

2. Pada cmd, pindah ke folder restoran_laravel contohnya

```
cd c:/xampp/htdocs/restoran_laravel
```

lalu instal composer

```
composer install
```

3. Edit pengaturan database di file `.env`, juga masukkan perintah ini untuk mengisi `APP_KEY`

```
php artisan key:generate
```

4. Migrasi tabelnya ke database dengan perintah

```
php artisan migrate
```

Lalu masukkan perintah berikut untuk insert beberapa data ke database

```
php artisan db:seed
```

5. Siap dijalankan...

<p align="center">Apabila memerlukan database sqldump, file bernama resto.sql</p>

## Contributing

1. Jika sudah di clone, pull dulu repository ini dengan perintah berikut, supaya dapat editan terbaru

```
git pull origin master
```

2. Edit projek sesuai keinginan
3. Kalau sudah diedit, push kembali seperti perintah berikut

```
git add .
```

```
git commit -m "pesan"
```

```
git push origin master
```

