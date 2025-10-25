# CCNA-dhcp-explained

-go to the router-

\>en

#conf t

fig#int g#/#

ip address 192.168.1.1 255.255.255.0

fig#ip dhcp excluded-address 192.168.1.1 192.168.1.0 192.168.1.255

fig#ip dhcp pool LAN-POOL, don't but numbers in the name of the pool

dhcp- fig#network 192.168.1.0 255.255.255.0

dhcp- fig#default-router 192.168.1.1
