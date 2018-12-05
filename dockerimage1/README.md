## Dockerfile NGINX Alpine
Berisi instruksi atau konfigurasi untuk membuat docker images. Digunakan untuk building image nginx pada alpine linux. 


## Membangun Docker images
Membuat direktori baru untuk kebutuhan eksperiment :
```
mkdir nginxweb
```
Masuk kedalam direktori tersebut
```
cd nginxweb
```
Kemudian buat Dockerfile dengan konten seperti dalam repository ini atau silahkan gunakan git clone.

Untuk membangun docker image, gunakan perintah
```
docker build -t nginxweb .
```

## Menjalankan container
```
docker run -d -p 80:80 --name nginxtest nginxweb
```
