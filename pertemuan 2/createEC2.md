# Membuat EC2 / Instance / VM

1. Pilih Menu All Services -> EC2

![alt text](image-2.png)

2. Di dalam Menu EC2 kita pilih instance

![alt text](image-3.png)

3. di dalam Menu Instance pilih launch Instance

![alt text](image-4.png)

4. Beri nama Instance kita dengan format NIM_Server

![alt text](image-5.png)

5. Kita Pilih OS Server untuk instance

![alt text](image-6.png)


6. Pilih Resource instance T3.Micro (2VCPU, 1GB Memory)

![alt text](image-7.png))

7. Membuat Key Pair, Pilih New key Pair, isi nama Key, pilih RSA, format File .pem, create key Pair

![alt text](image-8.png)

8. Setting Kebijakan keamanan / Security Group
   - Allow SSH -> Artinya membolehkan Remote SSH dari luar 
   - Allow HTTPS -> Artinya Instance bisa di akses dari protocol HTTPS
   - Allow HTTP -> Artinya instance bisa di akses dari protocol HTTP

![alt text](image-9.png)


9. Selesai Set-Up Pilih Launch Instance

![alt text](image-11.png)

10. Pastikan Launch Instance Sukses

![alt text](image-10.png)