## IP Addressing Netmask - (193.16.20.35/29)

Address: 193.16.20.35 => 11000001.00010000.00010100.00100011
Subnet Mask: 255.255.255.248 => 11111111.11111111.11111111.11111000

[//]: <> (To find the Network IP for this particular subnet, we make use of Bitwise & Operator)

IP:      11000001.00010000.00010100.00100011 => 193.16.20.35
Subnet Mask: 11111111.11111111.11111111.11111000 => 255.255.255.248
________________________________________________
Network IP: 11000001.00010000.00010100.00100000 => 193.16.20.32

[//]: <> (To calculate the number of IP Address(hosts), we use 2^n where n = no of host bits(0 bits))
The number of 0 bits in the new subnet mask is 3. Therefore, the number of IP addresses in each subnet is:
          2^3 = 8

[//]: <> (To calculate the number of usable IP Addresses(hosts), we use 2^n - 2)
The number of usable IP Addresses is:
    2^3 - 2 = 6

The first and last IP addresses are not assignable. The first IP is the network IP (193.16.20.32) and the last IP is the broadcast IP. 

Number of hosts is 6, as only 6 hosts are assignable.


The range of usable IP addresses is 193.16.20.33 - 193.16.20.38
193.16.20.33
193.16.20.34
193.16.20.35
193.16.20.36
193.16.20.37
193.16.20.38

The broadcast IP = 193.16.20.39