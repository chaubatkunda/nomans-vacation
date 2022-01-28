## Website Nomands Vacation

#### requires

php 7.2

Download atau clone project dari github:

```sh
git clone
```

```sh
composer install
```

copy atau rubah file env.example menjadi .env dan isi kan nama database anda.
setelah itu ketikkan pada terminal

```sh
php artisan migrate
php artisan key:generate
php artisan storage:link
php artisan optimize
php artisan db:seed
```
