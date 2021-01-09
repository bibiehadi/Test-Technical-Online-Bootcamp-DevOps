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
