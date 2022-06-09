# Tugas-Akhir-AJT-Naufal-
Mahasiswa FILKOM-UB

195150307111024

Arsitektur Jaringan Terkini A

Tugas Akhir Jaringan Terkini



Tugas 1 - Membuat Instance dan Instalasi OpenFlow, Mininet dan Ryu

Pada tugas satu ini saya membuat virtual machine dengan spesifikasi yang disebutkan pada deskripsi tugas.

A. Saya membuat virtual machine dengan deskripsi sebagai berikut.
-Nama : Tugas Akhir.

-OS Image : Ubuntu Server 22.04 LTS 64-bit.

-Instance type : t2.medium.

-Keypair : vockey.

-Edit network settings : allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081

-Konfigurasi penyimpanan : 30 Gigabyte, gp3.
![image](https://user-images.githubusercontent.com/107117812/172874384-c3230a51-33ce-41a2-a107-36df69d2f690.png)

B. Kemudian setelah mesin selesai dibuat, saya menginstall openflow, ryu, flowmanager, serta mininet.
![image](https://user-images.githubusercontent.com/107117812/172874708-3d167793-11dd-48a7-a66f-1a9abd947d9b.png)
![image](https://user-images.githubusercontent.com/107117812/172874744-56f1c2e4-3cb3-436c-a450-4874db04e7ba.png)
![image](https://user-images.githubusercontent.com/107117812/172874799-efa5f692-fdeb-4f2e-8bf6-4ce008164c35.png)
![image](https://user-images.githubusercontent.com/107117812/172874820-26250752-94fb-4970-b816-bfe9c5ef7d81.png)

C. Jangan lupa untuk mengecek kembali apakah openflow, flowmanager, ryu, flowmanager.
![image](https://user-images.githubusercontent.com/107117812/172875380-14b0d547-4284-4d32-b848-6e70078f1179.png)

D. Semua sudah terinstall pada virtual machine, selanjutnya saya mengetes guna memastikan Mininet, Ryu, Flowmanager dan OpenFlow telah ter-install dan melakukan uji koneksi antara host dan switch.

E. Setelah saya uji coba, semua berjalan dengan baik.

Demikianlah tugas satu ini saya buat, selanjutnya akan berlanjut ke tugas dua.


Tugas 2 - Custom Mininet Topology

Melanjutkan tugas satu sebelumnya, pada tugas dua kali ini saya membuat sebuah custom topology, kemudian membuat flow data antara host 1 dan host 2, kemudian menguji koneksinya.

A. Saya membuka aws instructure, kemudian menyalakan kembali mesin virtual.
![image](https://user-images.githubusercontent.com/107117812/172877530-f9de0795-e0d7-4fda-8b12-e8ddc407cb78.png)

B. Ketik "nano" pada virtual machine, kemudian kita tuliskan source code yang diperlukan untuk mengerjakan tugas dua ini. Setelah saya tuliskan, saya menyimpan kode. Kode disini saya simpan dengan nama "tugasakhir.py".
![image](https://user-images.githubusercontent.com/107117812/172878839-fd44d461-1203-47fb-9e84-c20449ba5420.png)

C. Setelah menulis dan menyimpan kode pada langkah sebelumnya, saya menjalankan perintah "sudo mn --controller=none --custom tugasakhir.py --topo mytopo --mac --arp".
![image](https://user-images.githubusercontent.com/107117812/172878657-ab99bb26-49f0-413d-b1fc-eb02b9a9c12f.png)

D. Perintah sudah jalankan pada virtual machine, saya melakukan tes koneksi host dan switch dengan perintah "h1 ping -c2 h2". 
![image](https://user-images.githubusercontent.com/107117812/172879280-14b789c6-8c06-4808-98d0-f598dc26b71d.png)

E. Uji koneksi sudah saya lakukan dan tidak ada permasalahan yang muncul, dengan demikian tugas dua sudah terselesaikan.
![image](https://user-images.githubusercontent.com/107117812/172879456-be250b7b-7bac-42d7-88cc-99754cd54b4b.png)

Demikian tugas dua ini saya buat, Demikianlah tugas satu ini saya buat, selanjutnya akan berlanjut ke tugas tiga.


Tugas 3 - Ryu Load Balancer

Pada tugas tiga kali ini, saya membuat load balancer, dan melakukan percobaan.

![image](https://user-images.githubusercontent.com/107117812/172880887-fee811eb-3f35-46fb-bea6-04ceef76e5e2.png)
![image](https://user-images.githubusercontent.com/107117812/172880919-edf294ff-0691-4dcc-9e04-96fd9f4c8ac0.png)

Load balancer merupakan proses pembagian beban traffic pada sebuah aplikasi atau server. manfaat dari load balancer adalah traffic tidak akan dibebankan ke beberapa jalur koneksi, sehingga pemrosesan dapat dilakukan lebih singkat serta mampu untuk menghindari overloading.




