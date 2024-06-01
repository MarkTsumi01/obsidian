คือระบบเครือข่ายที่เครื่อง host อยู่บนสถานที่ใดสถานที่หนึ่งแต่มีการให้บริการบนอินเทอร์เน็ต

	TCP/IP an internet communication protocol that allows two devices to form a connection and stream data 

	ip (internet protocol) A set of standards used for routing and addressing data packets as they travel between devices on a network


TCP/IP model:

- The TCP/IP model is a framework used to conceptualize how data is organized and transmitted across a network. It has 4 layers: the application layer, transport layer, internet layer, and network access layer.

- The network access layer deals with creating and transmitting data packets over the network. It uses the ARP protocol to map between IP and MAC addresses.

- The internet layer is responsible for delivering data to the correct destination, potentially on a different network. It uses protocols like IP and ICMP.

- The transport layer manages end-to-end communication between systems/networks. It uses the TCP and UDP protocols.  

- The application layer handles access to network services and applications. It uses protocols like HTTP, SMTP, SSH.

- The TCP/IP model is a simplified version compared to the OSI model, but both models serve the purpose of helping communicate network processes.

- Both the TCP/IP and OSI models are conceptual frameworks used by network professionals to visualize and discuss network operations and potential issues/threats.



The OSI model:

The OSI (Open Systems Interconnection) model is a standardized concept that describes the 7 layers computers use to communicate and send data over a network:

1. Physical layer - Deals with the physical hardware components like cables, hubs, modems that are used to transmit data.

2. Data link layer - Handles sending and receiving data packets within a single network using protocols like NCP, HDLC, SDLC. 

3. Network layer - Responsible for routing data packets between networks using IP addresses and delivering frames to the intended destination.

4. Transport layer - Manages end-to-end communication, segmentation of data, and flow control using protocols like TCP and UDP.

5. Session layer - Establishes, maintains, synchronizes and terminates sessions/connections between applications. 

6. Presentation layer - Translates data between different formats and handles encryption/decryption.

7. Application layer - The layer that interfaces directly with network services and applications used by the end user like HTTP, SMTP, DNS.

The 7-layer OSI model provides a more detailed breakdown compared to the simpler 4-layer TCP/IP model. Both models help network professionals visualize and discuss network operations, processes and troubleshoot issues across the different layers.



## Network layer communication:

The network layer (layer 3 of the OSI model) is responsible for addressing, routing and delivering data packets across networks from the source to the destination device. Its main functions include:

- Organizing packet addressing using IP addresses contained in the packet header
- Routing packets across networks by forwarding them from one router to the next based on the destination IP address
- Fragmenting larger packets into smaller pieces for transmission

The packet header in IPv4 contains fields like source/destination IP addresses, packet length, time-to-live counter, checksum for error detection and options like prioritization. 

IPv6 was developed to replace IPv4 to overcome IPv4 address exhaustion by using 128-bit addresses instead of 32-bits, allowing many more possible addresses.

Key differences between IPv4 and IPv6:
- IPv6 addresses are 128-bits long represented in hexadecimal format
- IPv6 packet header is simpler, removing fields like fragmentation flags
- IPv6 adds better security by eliminating private address collisions

Understanding the fields in IP packet headers provides important security information like source, destination, protocol being used which allows analysts to assess potential threats.


## Glossary module 1

## Terms and definitions from Course 3, Module 1

**Bandwidth:** The maximum data transmission capacity over a network, measured by bits per second

**Cloud computing:** The practice of using remote servers, application, and network services that are hosted on the internet instead of on local physical devices

**Cloud network:** A collection of servers or computers that stores resources and data in remote data centers that can be accessed via the internet

**Data packet:** A basic unit of information that travels from one device to another within a network

**Hub:** A network device that broadcasts information to every device on the network

**Internet Protocol (IP):** A set of standards used for routing and addressing data packets as they travel between devices on a network

**Internet Protocol (IP) address:** A unique string of characters that identifies the location of a device on the internet

**Local Area Network (LAN):** A network that spans small areas like an office building, a school, or a home

**Media Access Control (MAC) address:** A unique alphanumeric identifier that is assigned to each physical device on a network

**Modem:** A device that connects your router to the internet and brings internet access to the LAN

**Network:** A group of connected devices

**Open systems interconnection (OSI) model:** A standardized concept that describes the seven layers computers use to communicate and send data over the network

**Packet sniffing:** The practice of capturing and inspecting data packets across a network

**Port:** A software-based location that organizes the sending and receiving of data between devices on a network

**Router:** A network device that connects multiple networks together

**Speed:** The rate at which a device sends and receives data, measured by bits per second

**Switch:** A device that makes connections between specific devices on a network by sending and receiving data between them

**TCP/IP model:** A framework used to visualize how data is organized and transmitted across a network

**Transmission Control Protocol (TCP):** An internet communication protocol that allows two devices to form a connection and stream data

**User Datagram Protocol (UDP):** A connectionless protocol that does not establish a connection between devices before transmissions

**Wide Area Network (WAN):** A network that spans a large geographic area like a city, state, or country
