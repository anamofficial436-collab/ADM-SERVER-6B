#Membuat EC2/ Instance / VM

1. Pilih menu all services -> Pilih EC2

![alt text](image.png)

2. Di dalamn EC2 kita pilih Instance

![alt text](image-1.png)

3. Di dalam menu instance pilih menu low instance

![alt text](image-2.png)

4. Beri nama Instance kita dengan Nama_Nim dan Pilih Ubuntu

![alt text](image-3.png)

5. Pilih resource instance T3.Micro (2VCPU, 1GB Memory)

![alt text](image-4.png)

6. Membuat Key Pair, pilih new key pair, isi nama key, pilih RSA untuk enkripsi, format file.pem, create key pair

![alt text](image-5.png)

7. Setting kebijakan keamanan atau security group

allow SSH = membolehkan remote SSH dari luar
allow HTTPS = instance bisa diakses dari protokol HTTPS
allow HTTP = instance bisa diakses dari protokol HTTP

![alt text](image-6.png)

8. Selesai set up Klik Launch Instances

![alt text](image-7.png)

9. Succes

![alt text](image-8.png)
