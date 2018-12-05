# Implementasi docker compose untuk docker-lemp Stack

Menjalankan Nginx, php-fpm dan MariaDB dengan [Docker]

## Kebutuhan
Sistem sudah terinstal [Docker] dan [Compose]

## Penggunaan
* Untuk membuat image docker php-fpm dapat menggunakan perintah:
```
docker-compose build
```
* Kemudian untuk menjalankan seluruh proses pada docker-compose dapat menggunakan perintah:
```
docker-compose up -d
```
* Untuk melihat catatan log dari proses :
```
docker-compose logs
```
* Untuk menghentikan seluruh proses dan container yang berjalan:
```
docker-compose stop
```
* Untuk menghapus:
```
docker-compose rm
```

[Docker]:                      https://www.docker.com/
[Compose]:                     http://docs.docker.com/compose/install/
