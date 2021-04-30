<h1 align="center">Tugas Besar PWL</h1>
<p>
</p>

## Install

```sh
npm install
composer install
```
```sh
## fix if php error
composer self-update
composer clear-cache
rm -rf vendor
rm composer.lock
composer install --ignore-platform-reqs
npm install
```
## Usage

```sh
cp .env.example .env
php artisan key:generate
php artisan migrate:refresh --seed
php artisan storage:link
```

## Run tests

```sh
php artisan serve
```
## Use
```
admin : admin@hilman.com
password : 123456
user : user@hilman.com
password : 123456
pegawai : pegawai@hilman.com
password : 123456

