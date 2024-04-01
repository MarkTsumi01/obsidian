

Common Network Protocols 

3 Categories of network protocols 

	Communication Protocols
			TCP (Transmission Control Protocol) 
				is an internet communication protocol that allows two devices to form a connection and stream data. TCP uses a three-way handshake process. First, the device sends a synchronize (SYN) request to a server. Then the server responds with a SYN/ACK packet to acknowledge receipt of the device's request. Once the server receives the final ACK packet from the device, a TCP connection is established. In the TCP/IP model, TCP occurs at the transport layer.
				
			UDP (User Datagram Protocol)
				is a connectionless protocol that does not establish a connection between devices before a transmission. This makes it less reliable than TCP. But it also means that it works well for transmissions that need to get to their destination quickly. For example, one use of UDP is for sending DNS requests to local DNS servers. In the TCP/IP model, UDP occurs at the transport layer.
				
			HTTP (Hypertext Transfer Protocol)
				- is an application layer protocol that provides a method of communication between clients and website servers. HTTP uses port 80. HTTP is considered insecure, so it is being replaced on most websites by a secure version, called HTTPS that uses encryption from SSL/TLS for communication. However, there are still many websites that use the insecure HTTP protocol. In the TCP/IP model, HTTP occurs at the application layer.
	
			DNS (Domain Name System)
				is a protocol that translates internet domain names into IP addresses. When a client computer wishes to access a website domain using their internet browser, a query is sent to a dedicated DNS server. The DNS server then looks up the IP address that corresponds to the website domain. DNS normally uses UDP on port 53. However, if the DNS reply to a request is large, it will switch to using the TCP protocol. In the TCP/IP model, DNS occurs at the application layer.

	Management Protocols
			SNMP (Simple Network Management Protocol)
				is a network protocol used for monitoring and managing devices on a network. SNMP can reset a password on a network device or change its baseline configuration. It can also send requests to network devices for a report on how much of the network’s bandwidth is being used up. In the TCP/IP model, SNMP occurs at the application layer.
				
			ICMP (Internet Control Message Protocol)
				is an internet protocol used by devices to tell each other about data transmission errors across the network. ICMP is used by a receiving device to send a report to the sending device about the data transmission. ICMP is commonly used as a quick way to troubleshoot network connectivity and latency by issuing the “ping” command on a Linux operating system. In the TCP/IP model, ICMP occurs at the internet layer.

	Security Protocols
			HTTPS (Hypertext Transfer Protocol Secure)
				is a network protocol that provides a secure method of communication between clients and website servers. HTTPS is a secure version of HTTP that uses secure sockets layer/transport layer security (SSL/TLS) encryption on all transmissions so that malicious actors cannot read the information contained. HTTPS uses port 443. In the TCP/IP model, HTTPS occurs at the application layer.
			SFTP (Secure File Transfer Protocol)


Private IP Address and Public IP Address


| Private IP Address                                                                                                                             | Public IP Address                                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Assign by router                                                                                                                               | Assign by ISP and IANA                                                                                                                                                                                                   |
| Unique only within private network                                                                                                             | Unique address is global internet                                                                                                                                                                                        |
| No cost to use                                                                                                                                 | Costs to lease a public IP address                                                                                                                                                                                       |
| Address ranges:<br><br>     10.0.0.0-10.255.255.255<br><br>     172.16.0.0-172.31.255.255  <br><br>     192.168.0.0-192.168.255.255   <br><br> | Assignable address ranges:<br><br>    1.0.0.0-9.255.255.255<br><br>    11.0.0.0-126.255.255.255<br><br>    128.0.0.0-172.15.255.255<br><br>    172.32.0.0-192.167.255.255<br><br>    192.169.0.0-233.255.255.255<br><br> |
|                                                                                                                                                |                                                                                                                                                                                                                          |
|                                                                                                                                                |                                                                                                                                                                                                                          |


## Dynamic Host Configuration Protocol

Dynamic Host Configuration Protocol (DHCP) is in the management family of network protocols. DHCP is an application layer protocol used on a network to configure devices. It works with the router to assign a unique IP address to each device and provide the addresses of the appropriate DNS server and default gateway for each device. DHCP servers operate on UDP port 67 while DHCP clients operate on UDP port 68.


## Address Resolution Protocol

By now, you are familiar with IP and MAC addresses. You’ve learned that each device on a network has a public IP address, a private IP address, and a MAC address that identify it on the network. A device’s IP address may change over time, but its MAC address is permanent because it is unique to a device's network interface card. The MAC address is used to communicate with devices within the same network, but sometimes, the MAC address is unknown. This is why the Address Resolution Protocol (ARP) is needed. ARP is mainly a network access layer protocol in the TCP/IP model used to translate the IP addresses that are found in data packets into the MAC address of the hardware device. 

Each device on the network performs ARP and keeps track of matching IP and MAC addresses in an ARP cache. ARP does not have a specific port number since it is a layer 2 protocol and port numbers are associated with the layer 7 application layer.


