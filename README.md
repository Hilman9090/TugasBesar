<h1 align="center">Tugas Besar PWL</h1>
<p>Hilman Saepul Anwar</p>
<p>5520119016</p>
<p>IF A 2019</p>

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

## Run test

```sh
php artisan serve
```

## Account

```sh
admin : admin@hilman.com
password : 123456
```

```sh
user : user@hilman.com
password : 123456
```

```sh
pegawai : pegawai@hilman.com
password : 123456
```

## Show your support

Give a ⭐️ if this project helped you!
