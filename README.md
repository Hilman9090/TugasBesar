<h1 align="center">Tugas Besar PWL</h1>
<p>Hilman Saepul Anwar</p>
<p>5520119016</p>
<p>IF A 2019</P>

## Install

```sh
npm install
composer install
```
```sh

## Fix if php error  
composer self-update
composer clear-cache
rm -rf vendor
rm composer.lock
composer install --ignore-platform-reqs
```
## Usage

```sh
cp .env.example .env
php artisan key:generate
php artisan migrate:refresh --seed
php artisan storage:link
```

## Run test

```sh
php artisan serve
```

## Account

```sh
Admin
Email    : admin@hilman.com
password : 123456
```

```sh
User
Email    : user@hilman.com
password : 123456
```

```sh
Pegawai
Email    : pegawai@hilman.com
password : 123456
```
<h1 align="center">>> TERIMA KASIH <<</h1>
