# Tugas-Akhir-Arsitektur-Jaringan-Terkini

Fachry Arsyad Salam
195150307111039
Arsitektur-Jaringan-Terkini - TKOM A

**Tugas 1 - Membuat Instance dan Instalasi OpenFlow, Mininet dan Ryu**

![image](https://user-images.githubusercontent.com/99635670/172663262-14c33d71-a2e9-4ac2-8c26-93ae0c551098.png)
![image](https://user-images.githubusercontent.com/99635670/172663341-242a97b2-e4e6-424f-8dc0-56ebfaf50b98.png)

Buat EC2 Instance di AWS Academy:
Name and tags: Tugas Akhir
OS Images: Ubuntu Server 22.04 LTS 64 bit
Instance type: t2.medium
Key pair: vockey
Edit Network settings: allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081
Configure storage: 30 GiB, gp3

Mininet
![image](https://user-images.githubusercontent.com/99635670/172664107-8c14ff7d-182e-426d-b20d-754c56f9f78c.png)
![image](https://user-images.githubusercontent.com/99635670/172665452-0f09592f-2493-45ed-859d-aae64fe6ef6c.png)

mencoba salah satu perintah pada sudo mn 'help'

**Tugas 2 - Mininet Custom Topology**

![image](https://user-images.githubusercontent.com/99635670/172666843-261cc524-d793-4064-b49c-83cc38c6990f.png)

Tugas 2 disini kita membuat custom topologi dengan membuat flow antara host 1 dan host 2 kemudian melihat koneksinya.

**Tugas 3 - Ryu Load Balancer**

Terminal 1
![image](https://user-images.githubusercontent.com/99635670/172668266-bff4694c-c839-4c8d-a5d8-6eda1582941c.png)
![image](https://user-images.githubusercontent.com/99635670/172668313-15df809b-9b98-428e-b264-31b5eeae2fe8.png)

Terminal 2
![image](https://user-images.githubusercontent.com/99635670/172668372-63fb1b02-8e9e-48d7-baf7-ec15385d437e.png)

**Tugas 4 - Shortest Path Routing**

Terminal 1 
![image](https://user-images.githubusercontent.com/99635670/172669154-ef3d741e-b6c1-4fa6-b034-5c223df6507f.png)

Screenshot hasil menulis perintah “$ ryu-manager --observe-links dijkstra_Ryu_controller.py”

Terminal 2 
![image](https://user-images.githubusercontent.com/99635670/172669302-e298ae96-cf82-4651-b01b-4eac7351d5c0.png)

Screenshot hasil menulis perintah “$ sudo python3 topo-spf_lab.py” 

Screenshot hasil menulis perintah “h1 ping -c 4 h4” pada ke 2 terminal untuk melihat konektivitas

![image](https://user-images.githubusercontent.com/99635670/172669693-9eee9cc2-9c1b-4be2-9fed-1e0ee10e4d29.png)
Terminal 1

![image](https://user-images.githubusercontent.com/99635670/172669741-fa13d261-45df-4965-b1de-b561d078ebce.png

Terminal 2

Screenshot hasil menulis perintah “h5 ping -c 4 h6” pada kedua terminal untuk melihat konektivitas

![image](https://user-images.githubusercontent.com/99635670/172669840-0714f250-2a64-497b-b734-6541d5d704c8.png)
Terminal 1

![image](https://user-images.githubusercontent.com/99635670/172669938-086aed26-ff36-42c0-abea-f8d77577b60e.png)
Terminal 2


