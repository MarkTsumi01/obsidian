
OSI Model

The OSI (Open Systems Interconnection) Model is a conceptual framework developed by the International Organization for Standardization (ISO) to describe the functions of a networking system
[1](https://www.forcepoint.com/cyber-edu/osi-model)[
3

](https://aws.amazon.com/what-is/osi-model/). It serves as a universal set of rules and requirements to ensure interoperability between different products and software in network communications. The model divides network communications into seven abstraction layers:

1. **Physical Layer:** Concerned with transmitting raw data bits across the network using physical resources like cabling, voltages, and radio frequencies.
2. **Data Link Layer:** Involves node-to-node data transfer, error correction, and encompasses sub-layers like Media Access Control (MAC) and Logical Link Control (LLC).
3. **Network Layer:** Responsible for routing frames to their destinations based on logical addresses like IP, utilizing routers to direct information between networks.
4. **Transport Layer:** Manages data packet delivery, error checking, sequencing, and regulates data transfer between systems using protocols like TCP.
5. **Session Layer:** Controls conversations between computers, sets up connections, manages sessions, and includes services like authentication.
6. **Presentation Layer:** Formats data for the application layer based on syntax or semantics accepted by applications, handling encryption and decryption.
7. **Application Layer:** Directly interacts with end-user applications like web browsers or email clients, providing network services and identifying communication partners.


### What is MikroTik?


- Mikrotik is from micro and tik แปลว่า ระบบเครือข่ายขนาดเล็ก
- There have software and hardware 
- Hardware has a differentsize small, middle, large.
- We can install only software on Virtual machine or Others hardware by bought license.
- A lot of company and customer using it like ISP, Personal.
- Used for improve network performance
- Established 1996 in Latvia.
- 1997 : RounterOS software for x86 (PC)
- 2002 : First RounterBOARD device
- 2006 : First MikroTik User Meeting (MUM)
- 2017 : Biggest MUM: Indonesia, 3000+


### Basic conneting Internet


##### Why using router

- ประหยัดค่าใช้จ่าย
- Policy
- เพื่อใช้ในการจัดสรรการใช้ Internet

### Process

- Wan
- Lan
- NAT
- DNS

##### Wan has a lot of pattern

- PPoE Client
- Static IP
- DHCP Client
- Wireless Client
- 3G/4G Module/USB


Account 
	username : admin
	 password : ""

		neighbor => refresh => connect => system => identity
		 PPP => interface => add => pppoe client => general => interface (ether1) => dial Out => user and password is Our number (3) => ppoe scan (ether1)

			R = Running
			IP => Address => Add => interface ether2 => address (192.168.3.1/24) => apply => 
			 IP => DHCP Server => DHCP Setup ether(2) 192.168.3.1
			 IP => Firewall => NAT => Add => Chain(srcnat) => Out interface (pppoe out1) => action (masqu) => apply => ping 8.8.8.8
			 IP => DNS => Servers (8.8.8.8, 1.1.1.1) => Allow remote click => Apply  => Ok
			  
			 Tool => RoMon => Click Enabled => apply => ok



Mikrotik has 2 way to backup

	1.Files => Delete All => Backup 

	 2.New terminal => export file="name"


Module 2

IP => DHCP Client => ether1
DHCP ถูกสร้าง 3 ขั้นตอน 1.DHCP 2.NETWORK 3.IP AND POOL


fig ip => DHCP Server => leases => right click ip => make static

![[Pasted image 20240312112047.png]]


### What is ARP?

- Address Resolution Protocol
- Working in Layer2(MAC) and Layer3(IP)
- matching IP/MAC address  and save to table
- Find IP from MAC and read from table