# WEB GALLERY

## Tentang Website

Aplikasi web ujikom galeri sederhana dengan framework Laravel

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- add poto
- add album
- add comment
- delete poto
- delete album

## Tampilan Website
![Screenshot (13)](https://github.com/revagusta/galeryy-ujikom/assets/141296050/a1e997ea-b918-45cb-929e-af5db120c3a9)

![Screenshot (14)](https://github.com/revagusta/galeryy-ujikom/assets/141296050/b91e9e1e-5d26-4d31-a085-ea7b29ca73a4)

![Screenshot (15)](https://github.com/revagusta/galeryy-ujikom/assets/141296050/a08b880b-9518-4cde-b874-9989704ecba9)


## ERD, Relasi dan UML Use Case

- ERD
![ERD](https://github.com/revagusta/galeryy-ujikom/assets/141296050/948873be-69a3-45d9-b9b8-8b57e83ca9db)


- Relasi
![Relasi](https://github.com/revagusta/galeryy-ujikom/assets/141296050/862602e8-57b9-4cb1-9c9c-6c3e972c0e74)


- UML
![Use Case](https://github.com/revagusta/galeryy-ujikom/assets/141296050/ada4c331-60d4-4cb6-a2dc-c826bb6abf7d)


## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, Microsoft Edge dll)

## Instalasi
1. Clone Repository
```
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. Jalankan Serve
```
php artisan serve
```

