## Soal 8
Membuat Web Server Di MacOS, sebagai contoh (PHP)
1. Membuka Terminal 
2. login as root 
```
sudo su
```
3. Mencoba menstart service apache
```
apachectl start
```
![](folder-images-jawaban/8-1.png)
4. Mengenable PHP di Apache
- buka file /etc/apache2/httpd.conf
```
nano /etc/apache2/httpd.conf
```
- mencari kode php, dengan menekan tombol ctrl + w lalu masukan 'php' enter
![](folder-images-jawaban/8-2.png)
- setelah ketemu LoadModule php7_module libexec/apache2/libphp7.so hapus tanda # di depan script tersebut dan simpan
![](folder-images-jawaban/8-3.png)
![](folder-images-jawaban/8-4.png)

5. restart service apache
```
apachectl restart
```

6. Menambahkan file phpinfo.php di DocumentRoot
```
nano /Library/WebServer/Documents/phpinfo.php
```
Dan menambahkan script
```
<?php

phpinfo();

 ?>
```
![](folder-images-jawaban/8-9.png)

7. Buka browser dan access http://localhost/phpinfo.php
![](folder-images-jawaban/8-5.png)

8. Merubah localhost ke domain dumbways-bibiehadi.xyz
buka /etc/host, dan tambahkan 127.0.0.1       dumbways-bibiehadi.xyz
```
nano /etc/host

127.0.0.1       dumbways-bibiehadi.xyz
```
![](folder-images-jawaban/8-6.png)

9. Mencoba webserver dengan mengakses dumbways-bibiehadi.xyz
![](folder-images-jawaban/8-7.png)
![](folder-images-jawaban/8-8.png)




