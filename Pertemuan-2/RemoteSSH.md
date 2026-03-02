#Remote Instance with SSH putty

1. Pastikan sudah install putty (putty.org/index.html)

![alt text](image-9.png)

2. Konversi file public key dari .pem menjadi .ppk di putty

- Buka puttyGen
- Load file.pem
- Save as .ppk

![alt text](image-10.png)

3. SetUp putty untuk remote SSH

- Buka apps putty
- Isi IP publik sesuai instance masing-masing
- Isi form untuk SSH sesuai Security Group di Instance
- Isi nama session agar saat konek lagi tinggal load saja
- Load file .ppk (klik SSH -> pilih auth -> credentials -> load file .ppk)
- Kembali ke session klik save
- Masukkan username ubuntu

![alt text](image-11.png)

![alt text](image-12.png)

4.  Sudo apt-get Update (Update OS) sudo apt-det upgrade

![alt text](image-17.png)
![alt text](image-19.png)

5.  Pembuktian remote SSH secara visual -copy publik IP address instance paste ke browser

- Isntall web server apache/nginx
- Sudo apt install apache2 -y

![alt text](image-18.png)

6.  Matikan instance agar tidak kena tagihan

![alt text](image-20.png)
![alt text](image-21.png)
