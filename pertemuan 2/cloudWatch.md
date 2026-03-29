# Membuat Monitoring Billing Alert 

1. Mencari Menu CLoudWatch dan Klik 

![alt text](image.png)

2. Setelah masuk menu CloudWatch pilih Alarm

![alt text](image-1.png)

3. Pilih Create Alarm dan Pilih Metrics EC2

![alt text](image-11.png)

Pastikan region ada di US N Virginia

klik Metric

klik menu billing

pilih total perkiraan Biaya

ceklis Mata uang USD

Pilih Matrik

beri Nama metrik

scroll bawah pilih USD $

next (konfigurasi)

creat new topic => NIM_BillingAlert => Create

Kirim Pemberitahuan ke ... (NIM_BillingAlert) 
![alt text](image-3.png)
next

alarm name
![alt text](image-4.png)
next
![alt text](image-5.png)
buat alarm

selesai
![alt text](image-6.png)
Buka inbox/spam email dari AWS kemudian Klik Confirm.