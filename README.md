## SOAL 1
DevOps merupakan serangkaian pekerjaan yang mengoptimalkan dan mengefisienkan proses antara software development (tim development) dengan system administrator (tim opration) agar mereka dapat melakukan proses developing/building, testing, dan release perangkat lunak yang telah dikembangkan lebih cepat, lebih efisien dan lebih handal. 

DevOps sangat penting bagi perusahaan. Dimana dengan adanya DevOps pengembangan aplikasi akan lebih cepat, lebih efisien, serta mengurangi adanya bottleneck antara tim developer dengan tim operation. Tim Developer akan memiliki access untuk deploy ke server tanpa harus meminta izin tim operation serta tim operation bertugas menjadi tim membuat otomasi dan menciptakan sistem baru yang kontinyu serta terintegrasi agar tim developer mampu leluasa mendeploy kode mereka ke server dengan cepat dan mudah. Dan merubah segala proses yang manual menjadi otomatis.

Flow DevOps kurang lebih yaitu development -> deploy ke server testing -> testing -> jika terdapat error kembali ke development untuk fix bug, jika tidak -> deploy ke production & monitoring -> kembali lagi ke development untuk mengerjakan fitur lainnya.

//https://blog.cilsy.id/2018/07/apa-itu-devops.html
https://medium.com/programmer-geek/apa-itu-devops-dca7c1c2dc92

## Soal 2


## Soal 3
Load balancing merupakan teknik untuk membagi atau mendistribusikan beban traffic/resource ke 2 buah server atau lebih sehingga dapat traffic dapat berjalan dengan optimal, memaksimalkan troughput, serta menghindari akan terjadinya overload.

SSL (Secure Sockets Layer) merupakan jenis keamanan digital yang memperbolehkan komunikasi terenkripsi antara website dengan web browser. Tujuan pemasangan ssl yaitu untuk sebagai pengaman pertukaran data yang terjadi melalui jaringan internet, dengan menggunakan ssl data yang dikirim dan diterima akan dienkripsi sehingga data tidak mudah dibaca oleh sniffer dan data tidak mudah dicuri.

contoh web server yang saya ketahui antara lain : Apache, Ms. IIS, Nginx, Tomcat, Lite Speed.

## Soal 4
CI/CD diperlukan sebagai pendorong proses pengembangan software sekaligus mengurangi resiko dalam setiap pengembangan dan lebih mudah untuk mencapai level production dan dapat digunakan oleh customer. selain itu CI/CD juga untuk mendapatkan feedback lebih cepat membantu untuk memeriksa kualitas dan kegunaan dari setiap code software, visibilitas lebih baik dan transparan memungkinkan developer untuk mengatur perubahan dan menghindari kerusakan softwarem, dan dengan CI/CD deteksi bug dapat lebih awal dengan fungsi test otomatis dan mengurangi terjadinya error ketika software sudah di deploy.

Tahap CI/CD:
1. Version control. - Developer menulis code dan mempush ke version controlller system seperti git, svn, dsb
2. Build 
3. Unit Test
4. Deploy 
5. Integration Test
6. Deploy To Production

## Soal 5
Perbedaan Container dengan VM yaitu :

Virtuam Machine merupakan tiruan dari sebuah sistem komputer. VM menjadikan resource hardware dari satu hardware fisik menjadi beberapa sistem komputer. Jadi disebuah satu hardware fisik (PC atau server) terinstall sebuah Host OS yang berfungsi sebagai hypervysor sebagai contoh Proxmox, VMWare vSphere, atau Windows/Linux/Mac yang diintall VMWare Desktop/Virtualbox. Kemudian di HypervysirOS tersebut dapat membuat sebuah VM dengan menentukan resource yang dibutuhkan dan menginstall OS di VM tersebut. Dengan VM maka dapat menginstall berbagai OS di setiap sistem komputer dan menjalankannya bersama-sama seolah memiliki banyak hardware yang berbeda.

Container merupakan virtualisasi OS yang dapat membungkus suatu aplikasi beserta dependency dan evironmentnya. Setiap container ini memiliki process yang terisolir sehingga tidak mengganggu hostOS ataupun container lain. Prinsip dari container ini mirip dengan kontainer yang terdapat di kapal cargo dimana kapal cargo tersebut ibarat HostOS. Berbeda dengan VM, pengaturan resource lebih flexible dan scalable daripada VM dan juga tidak perlu menginstall OS di setiap kontainer.



Perbedaan VM dan Container :
VM                              
- VM lebih berat                
- Performa terbatas pada konfigurasi VM
- Virtualisasi di level hardware
- Waktu startup VM dalam hitungan menit
- Terisolasi penuh pada level hardware sehingga lebih aman

Container 
- Ringan
- Performa tergantung pada resource hardware fisik
- Virtualisasi di level software
- Waktu startup hitungan detik
- Terisolasi pada level proses


Contoh Public Cloud :
GMail, Facebook, Twitter, ICloud, MegaUP, Google Drive, Adobe Creative Cloud, 

Contoh Private Cloud : 
SaaS (Software As A Service) : Web Application Internal, Mail Server Internal, Database Server Internal, -Engineer hanya maintenance softwarenya saja tanpa perlu repot mengurusi machine (VM/Baremetal Server) dan OS.

PaaS (Platform As A Service) : Engineer mengurus dan memaintenance sendiri layer OS sampai layer Aplikasi tanpa harus mengurus machinenya.

IaaS (Infrastruktur As A Service) : Engineer mengurus dan memaintenance semua dari Machine (VM / Baremetal), OS yang digunakan, serta Aplikasinya.


## SOAL 6

## SOAL 7

## SOAL 8
Membuat Web Server Di MacOS, sebagai contoh (PHP)
1. Open Terminal 
2. login as root 
```
sudo su
```
3. 
