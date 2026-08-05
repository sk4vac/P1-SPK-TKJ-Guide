### Hello World

In this repository you can learn and use this as your material or practice reference for completing `P1-SPK-TKJ`, P1 contain a task to make a LAN network environtment consist of Server, Client Devices, Switch, Router then connect it into Internet. We also need to set up a monitoring tools on the server to monitor the activity in network, a Web Server so client devices can access the server through web, and we'll also try to find the vulnerabilities of this network.

## Prerequisite

1. Understanding of
2. VMWare
3. PNETLab
4. Ubuntu Server / Debian Server

For this one I'll be using Ubuntu Server first

## Chapter 1: Set Up Lab, Devices and Cabeling

### Step 1

Power on all your VM, the PNETLab and the Ubuntu Server

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/61f54c9e-8063-40b9-9bf8-3e6aa8d0782f" />

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/aa1c9a3a-8519-46b4-97c4-bec67a7f5a72" />

### Step 2

Login to the PNETLab Web with the IP, e.g. my IP is `192.168.90.128`

<img width="1366" height="737" alt="image" src="https://github.com/user-attachments/assets/5d741124-e4e0-4037-9693-ba48461683c2" />

<img width="1366" height="741" alt="image" src="https://github.com/user-attachments/assets/43f257cd-fce4-4b25-9861-ede1948e71f0" />

### Step 3

Create a new topology file

<img width="1366" height="731" alt="image" src="https://github.com/user-attachments/assets/11cf0ee4-4017-4acc-b743-ab433c6a7956" />

<img width="1366" height="734" alt="image" src="https://github.com/user-attachments/assets/04bc6181-80c5-45bb-b1f3-944994223536" />

### Step 4

Add your first Node, by Right Click and choose `Node`, then choose MikroTik RouterOS

<img width="707" height="437" alt="image" src="https://github.com/user-attachments/assets/3d6053d6-08ba-4ff1-b356-41c8d22f3468" />

<img width="1366" height="523" alt="image" src="https://github.com/user-attachments/assets/617bc9cd-4ebe-4ee8-b86f-d9339236ba36" />

And Match this Configuration for adding a MikroTik 4 Port Router

<img width="901" height="629" alt="image" src="https://github.com/user-attachments/assets/d5e05f3f-5118-42ed-a497-a5f649a75d72" />

<img width="897" height="650" alt="image" src="https://github.com/user-attachments/assets/b11fa166-36ab-45bb-9db6-588f3fab4fed" />

<img width="901" height="619" alt="image" src="https://github.com/user-attachments/assets/253e3951-f395-49c0-9461-2474edf359f2" />

And Save it!

### Step 5

Now let's add the switch by right click then choose node, and choose Mikrotik RouterOS.

<img width="662" height="479" alt="image" src="https://github.com/user-attachments/assets/7a26cefe-3970-43fe-ad4d-226b979689e6" />

And match this configuration for adding a Mikrotik 24 Port Switch.

<img width="899" height="625" alt="image" src="https://github.com/user-attachments/assets/6293edb3-44db-4d3f-b935-43e1897e3f70" />

<img width="901" height="648" alt="image" src="https://github.com/user-attachments/assets/9a07a927-e95c-49e7-9947-68b83c17cb27" />

<img width="895" height="199" alt="image" src="https://github.com/user-attachments/assets/8a437696-71d4-47e2-8d51-58a9044a7be7" />

And save it!

### Step 6

Now you have a Switch and Router, we'll add 5 PC, 1 Internet Node, and 1 Server Node.

<img width="604" height="342" alt="image" src="https://github.com/user-attachments/assets/d653d229-60fc-4bc7-af02-a6fe6916bdb8" />

Right click then choose add node, and choose `VPCS`

<img width="508" height="550" alt="image" src="https://github.com/user-attachments/assets/95e1d2b8-814a-4ea4-abb2-c9c1b3e199fb" />

<img width="1303" height="384" alt="image" src="https://github.com/user-attachments/assets/75c7b168-ef34-4b9b-bc5f-73d279c01dc6" />

No need to configure the PC on here, just set the number of nodes to add to 5, and just straight up save it.

<img width="903" height="617" alt="image" src="https://github.com/user-attachments/assets/86913f48-258e-4018-b5c7-cbda61e3b79d" />

Save!
