# Docker Windows


Struktur file Project Laraval + Docker

_![Screenshot 2022-08-04 191907](https://user-images.githubusercontent.com/18047284/182845294-43635c71-820c-49df-bf9d-43ae7a3982c7.png)

#Rule

Contoh membuat file docker compose untuk projek laravel.
Container  dan Image ini dibuat langsung melalui docker-compose.yml yang nanti ketika di build akan dibuat di docker
untuk menjalankan build ini lakukan perintah berikut

# 1. Nyalakan Docker Desktop ( Windows )
  Klik icon docker desktop untuk pengguna Windows
  
# 2. Setelah Running jalankan perintah berikut
  docker-compose build && docker-compose up -d
  
# 3. Tunggu sampai selesai di build

# 4 . Menjalankan PhpMyadmin 
  ketik di browser dengan perintah localhost:5050
  Jika berjalan berarti berhasil di build.
  
# 5. download file laravel dengan perintah berikut
  Sebelumnya silakan Masuk ke directory Project Kamu, dan jalankan perintah
  composer create-project laravel/laravel . atau jika tidak berhasil hapus file src dan jalankan perintah download file laravel lagi.
  
