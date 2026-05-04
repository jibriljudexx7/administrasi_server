# Company Profile Docker - Pertemuan 10

Project ini dibuat untuk tugas Administrasi Server Pertemuan 10.

Website sederhana ini berjalan menggunakan Docker pada server AWS EC2 dengan web server Nginx.

## Teknologi yang digunakan

- AWS EC2
- Ubuntu Server
- Docker
- Nginx
- Docker Hub
- GitHub

## Docker Image

Image Docker sudah dipush ke Docker Hub:

jibriljudex/compro_2388010051:latest

## Cara menjalankan

docker build -t compro_2388010051 .
docker run -d --name web-compro -p 8080:80 compro_2388010051

## Akses website

http://54.169.119.175:8080
