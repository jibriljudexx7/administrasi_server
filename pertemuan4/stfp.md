# Migrasi File Local ke Cloud Server (AWS EC2)

1. Memilih tools Migrasi File, misal kita akan gunakan Filezilla 
    - unduh dan Install di https://filezilla-project.org/download.php?type=client
    ![alt text](image.png)
    - Buka Filezilla Client
    ![alt text](image-1.png)
    - Aktifkan Instance di AWS
    ![alt text](image-2.png)
    - Kembali ke FileZilla Client
    ![alt text](image-3.png)
    - Klik File > Site Manager
    ![alt text](image-7.png)
    - Klik New Site 

    ![alt text](image-8.png)
    - Protocol > SFTP
    ![alt text](image-6.png)
    - Host > IP Public EC2
    ![alt text](image-9.png)
    - Port > 22
    ![alt text](image-10.png)
    - Logon Type > Key file
    ![alt text](image-11.png)
    ![alt text](image-12.png)
    - Key file > Pilih file .ppk / .pem yg didownload saat membuat instance
    ![alt text](image-13.png)
    - Klik Ok
    - CTRL + S
    - Klik Connect
![alt text](image-14.png)

2. Pada Dashboard utama fileZilla akan terbagi menjadi 2 panel
    - Panel Kiri > File Local (Komputer Anda)
    - Panel Kanan > File Server (AWS EC2)
![alt text](image-15.png)

3. Arahkan directory Cloud (Panel Kanan) ke Folder web server services area
 - /var/www/html
![alt text](image-16.png)

4. untuk solusi Permission Denied pada folder /var/www/html

    - Ubah Kepemilikan Folder
    - Mengubah folder /var/www/html agar bisa diakses oleh user 'ubuntu'
    - Sintaks: sudo chown -R ubuntu:ubuntu /var/www/html
sudo chown -R ubuntu:ubuntu /var/www/html
![alt text](image-17.png)

5. Edit File index.html menjadi company Profile 
    - Klik Kanan pada file index.html
    - Klik Edit
    - Edit File index.html menjadi company Profile 
<img width="1919" height="957" alt="image" src="https://github.com/user-attachments/assets/47f90afa-d68a-4563-961b-670166788f62" />
