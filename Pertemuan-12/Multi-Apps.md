# Deploy Multi Apps CI/CD Docker

1. Start Instance di AWS EC2
2. Patching OS -> sudo apt update && sudo apt upgrade
3. Hapus Layanan nginx dan uinstall -> sudo systemctl stop nginx && systemctl disable nginx
   sudo apt remove nginx nginx-common nginx-core
   sudo apt remove apache2
4. hapus layanan maria db dan uninstall > sudo systemctl stop mariadb && systemctl disable mariadb sudo apt remove mariadb-server mariadb-client mariadb-common
   sudo apt auto-remove mariadb-server
5. testing next.js + db menggunakan user bukan root pada local environment

   -copy project digitech pada pertemuan6 kecuali folder .next, node_modules ,sql ke dalam folder web-dinamis

![alt text](image.png)

-create user baru bukan root di DBMS (laragon,Xampp,etc)

![alt text](image-2.png)

- Sesuaikan isi file .env
- Buka terminal > cd Webb-dinamis
- npm I
- npm run dev

![alt text](image-3.png)
