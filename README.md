# CCNA-project-in-packet-tracer

This is a simple "simulation" of a college network topology.  
We implement a multitude of different routing protocols like DHCP, OSPF, EIGRP, VLANs, and NAT.
![toplogy](https://i.imgur.com/byzac8n.png)

Server 0 Students is using DHCP protocol connecting to the student VLAN.
![Server_0](https://i.imgur.com/45uCfsn.png)

Server 1 Faculty is using DHCP protocol connecting to the VLAN faculty.
and it's unable to ping the ISP since router 2 is configured with a NAT protocol

![Server_1](https://i.imgur.com/J4UQUcn.png)

Server 4 Library is using DHCP and connected to the VLAN Libary.

![Server_4](https://i.imgur.com/uf0ESw0.png)

Server 5 Staff is configured with DHCP protocol and connected to the VLAN Staff.
It is also unable to ping the ISP since NAT remapped its ip. 

![Server_5](https://i.imgur.com/pwbhNN0.png)

Switches 0 and 1 are configured with 4 VLAN one for each server.
Switch 0 is configured with a student and faculty VLAN. 
switch 1 is configured with a library and staff VLAN. 

![vlan](https://i.imgur.com/vKbMYSK.png)

Mutli Layer Switch is configurd to with both OSPF and EIGRP. 
It is configured to allow both the ISP is connected through an OSPF
and the alamo colleges website server who is configured with EIGRP.

![MULTI](https://i.imgur.com/Yj2B15i.png)


Router 1 is configured with EIGRP protocol 
and router 2 is configured wit OSPF protocol and a NAT protocol 
remapping its getaway and preventing it to connect with the faculty and staff server

![sleepy](https://i.imgur.com/eY8y4im.png)



