# Deploy Multi Apps CI/CD Docker

1. Start instances AWS 
2. Paching OS -> sudo apt-get update && sudo apt-get upgrade

3. Hapus Layanan nginx -> sudo systemctl stop apache2 && sudo systemctl disable apache2 -> sudo apt remove apache2
   - docker ps -la
   - docker start compro_2388010052
4. Hapus layanan Mariadb dan uninstall -> sudo systemctl stop mariadb && suddo systemctl desable mariadb
   - sudo apt auto-remove mariadb-server -> systemctl status mariadb mariadb-client mariadb-common
5. Testing Next.JS + db menggunakan user bukan root pada local environment
   - copy project Digitech pertemuan 6 kecuali folder .nex, node_modules, sql 
   <img width="445" height="961" alt="image" src="https://github.com/user-attachments/assets/2a361f3f-32a4-494e-aaaf-5aa0e3be32fc" />
   - Create user baru bukan root di BMS (Laragon, xampp)
     - ke user akun
     - add user
     - username = usercompro_nim
     - Host name = localhost
     - pasword = *****
     - langsung go /  create
   - Klik user yang sudah di buat -> pilih database -> pilih dbcompro -> terus klik all -> go
   <img width="1600" height="841" alt="image" src="https://github.com/user-attachments/assets/14d08487-8380-4237-ba9b-bf3f363f776f" />
   <img width="1600" height="843" alt="image" src="https://github.com/user-attachments/assets/545f91e4-6594-464a-91c2-31520fa7a97b" />
   <img width="1600" height="844" alt="image" src="https://github.com/user-attachments/assets/5102aeb7-bbb6-46a0-8a9e-4b97ef31fdb9" />
   <img width="1600" height="839" alt="image" src="https://github.com/user-attachments/assets/94083536-5c0e-496e-ba4a-77f96ed29acc" />
   <img width="1600" height="840" alt="image" src="https://github.com/user-attachments/assets/aa6b8d6a-437b-4cb1-a402-b7ba2340b089" />

    - sesuaikan file .env
    - open terminal -> cd web-dinamis
    - npm i
    - npm run dev -> cek website localhost
    <img width="1600" height="845" alt="image" src="https://github.com/user-attachments/assets/102bb34f-a3c5-434f-934b-47a075426146" />
