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

