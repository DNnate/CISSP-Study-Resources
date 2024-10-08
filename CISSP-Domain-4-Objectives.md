[Domain 4](#domain4-top) **Communication and Network Security**

Networking can be one of the more complex exam topics; if you have a networking background, you likely won’t find this domain difficult-- if not, spend extra time in this section and consider diving deeper into topics that are fuzzy

- **ACK**: an acknoledment of a signal being received
- **ARP**: used at the Media Access Control (MAC) layer to provide for direct communication between two devices within the same LAN segment
- **APT**: Advanced Persistent Threat is an agent/org that plans, organizes, and carries out highly sophisticated attacks against a target person, org, or industry over a period of time (months or even years); usually with a strategic goal in mind
- **API**: Application Programming Interface; code mechanisms that provide ways for apps to share data, emthods, or functions over a network (usually implemented in XML or JavaScript Object Notation (JSON))
- **Bandwidth**: amount of information transmitted over a period of time; can be applied to moving bits over a medium, or human processes like learning or education
- **Bluetooth**: wireless personal area network, IEEE 802.15; an open standard for short-range RF communication used primarily with wireless personal area networks (WPANs).  A bluejacking attack is a wireless attack on Bluetooth, and the most common device compromised in a bluejacking attack is a cell phone
- **Bound networks**: AKA wired/Ethernet networks, where devices are connected by physical cables
- **Boundary routers**: they advertise routes that external hosts can use to reach internal hosts
- **Bridge**: device that aggregates separate network segments into a single network segment, operating at OSI layer 2
- **CSMA/CA**: Carrier Sense Multiple Access with Collission Avoidance is a method of network flow control. 802.11 📝wireless networking is an example of a network that employs CSMA/CA technologies. CSMA/CA attempts to avoid collisions by granting only a single permission to communicate at any given time. IEEE 802.11 wireless networks use Carrier-Sense Multiple Access with Collision Avoidance (CSMA/CA) to manage (technically avoid) collisions.
    - CSMA/CA is used in wireless networks. Collisions are avoided by having the host/wireless device select a random number and then transmit after counting to that number. This reduces the chance that two devices will transmit at the same time, thereby having the frames collide. 
- **CSMA/CD**: Carrier Sense Multiple Access with Colliion Detection is a method of network flow control, where if > 1 station accesses the network at the same time, other stations detect and re-try their transmission. 📝Ethernet networks employ the CSMA/CD technology. CSMA/CD responds to collisions by having each member of the collision domain wait for a short but random period of time before starting the process over. Ethernet (IEEE 802.3) uses Carrier-Sense Multiple Access with Collision Detection (CSMA/CD).
    - Ethernet is a shared media Local Area Network (LAN) technology that allows numerous devices to communicate over the same medium but requires that the devices take turns communicating and performing collision detection or avoidance. Ethernet is based on the IEEE 802.3 standard and employs broadcast and collision domains. Devices communicate over Ethernet using a Media Access Control (MAC) address. Ethernet is a data link layer technology.
    - Carrier-Sense Multiple Access with Collision Detection (CSMA/CD) is a media access control method primarily in wired Ethernet technology for local area networking. It uses the following steps:
        - 🆎The client listens to the LAN media to determine if it's in use
        - 🆎If the media is clear, the client sends the transmission
        - 🆎While transmitting, the client listens for collisions
        - 🆎If a collision is detected, the client sends a jam signal
        - 🆎If a jam signal is received, all hosts stop transmitting and wait a random backoff time before starting over again at step 1 
    - A collision domain is the set of systems that could cause a collision if they transmitted at the same time. Systems outside a collision domain cannot cause a collision if they send at the same time. This is important, as the number of systems in a collision domain increases the likelihood of network congestion due to an increase in collisions.
    - A broadcast domain is the set of systems that can receive a broadcast from each other.
- **Circuit-switched network**: network that uses a dedicated circuit between endpoints
- **CDMA**: Code-Division Multiple Access: a method of encoding several sources of data so they can all be transmitted over a single RF carrier by one transmitter, or by using a single RF carrier frequency with multiple transmitters; the data from each call is encoded with a unique key, and calls are transmitted at once
- **Concentrator**: provides communication capability between many low-speed, usually asynchronous channels and one or more high-speed, usually synchronous channels. Usually different speeds, codes, and protocols can be accommodated on the low-speed side; multiplexed into one signal
- **CDN**: Content Distribution Network is a large distributed system of servers deploye in multiple data centers, with a goal of Quality of Service (QoS) and availability requirements
- **Control plane**: part of a network that controls how data packets are forwarded — meaning how data is sent from one place to another; e.g. the process of creating a routing table is considered part of the control plane; control of network functionality and programmability is directly made to devices at this layer
- **Northbound/Southbound interface**: A northbound interface lets a specific component communicate with a higher-level component in the same network; a southbound interface is the opposite — enabling a specific component to communicate with a lower-level component
- **East/West traffic**: network traffic that is within a data, control, or application plane; within a data center or between geo dispersed locations. East-west traffic is the traffic flow that occurs within a specific network, datacenter, or cloud environment.
- **North/South traffic**: in SDN terms, data flowing up (northbound) and down (southbound) the stack of data/control/application planes; data flowing from the organization to external distinations (northbound), or into the org from external sources (southbound). North-south traffic is the traffic flow that occurs inbound or outbound between internal systems and external systems.
- **Converged protocol**: combines/converges standard protcols (such as TCP/IP) with proprietary/non-standard ones; they can complicate enterprise-wide security engineering efforts requiring specialist knowledge. eg Fibre Channel over Ethernet (FCoE), Internet Small Computer Systems Interface (iSCSI), and Voice over Internet Protocol (VoIP) are all examples of converged protocols that combine specialized protocols with standard protocols like TCP/IP.
- **DNS**: Domain Name Service is three in interrelated elements: a service, a physical server, and a network protocol
    - DNS Cache Poisoning involves corrupting the DNS cache of a DNS resolver or server. The DNS cache stores recent DNS query results to improve performance and reduce lookup times. An attacker manipulates this cache to insert false DNS records, causing users to be redirected to incorrect or malicious IP addresses.
    - DNSSEC uses certificates to perform mutual authentication between DNS servers, and thus public key infrastructure (PKI) is needed to provide and support those certificates.
- **DHCP**: Dynamic Host Configuration Protocol is an industry standard used to dynamically assign IP addresses to network devices
- **FDDI**: Fiber Distributed Data Interface is an ANSI X3T9.5 LAN standard; 100Mbps, token-passing using fiber-optic, up to 2 kilometers
- **FCoE**: Fibre Channel over Ethernet is a lightweight encapulsation protocol without the reliable data transport of TCP
- **Gateway device**: a firewall or other device that sits at the edge of the network to regulate traffic and enforce rules
- **ICMP**: Internet Control Message Protocol, standardized by IETF via RFC 792 to determine if a particular host is available
- **IGMP**: Internet Group Management Protocol, used to manage multicasting groups
- **Internetworking**: two different sets of servers/communication elements using network protocol stacks to communicate and coordinate activities
- **LDAP**: lightweight directory access protocol uses simple (basic) authentication such as SSL/TLS, or SASL (Simple Authentication and Security Layer)
- **Microsegmentation**: part of a zero trust strategy, that breaks LANs into very small highly localized zones using firewalls or similar; note that at the limit, this places a firewall at every connection point
- **NFV**: Network Function Virtualization (AKA Virtual Network Function) that seeks to decouple functions, such as firewall management, intrusion detection, NAT and name service resolution, from specific hardware solutions, and make them virtual/software; the focus is to optimize distinct network services
- **PLC**: Packet Loss Concealment used in VoIP communications to mask the effect of dropped packets
- **Packet-Switched Network**: a network that doesn't use a dedicated connection between endpoints
- **Point-to-Point Protocol**: a standard method for transporting multiprotocol datagrams over point-to-point links
- **NAT**: Network Address Translation (NAT) is used to translate between two Internet Protocol (IP) addresses. Typically, NAT is enabled on a router connected to the internet. The router will translate all the internal private IP addresses to a public IP address when outgoing connections are made and translate the return traffic back to the private IP address. NAT operates at the 📝network layer of the Open System Interconnection (OSI) model.
- **Port Address Translation**: an extension of NAT (Network Address Translation) translating all addresses to one routable IP address and translate the source port number in the packet to a unique value. NAT offers many benefits.
     - NAT hides the internal IP addressing scheme
     - Network Address Translation (NAT) rewrites Internet Protocol (IP) headers
     - NAT enables the sharing of a few public internet addresses with a large number of internal clients.
     - NAT supports the use of the private IP addresses from RFC 1918 on an internal network.
     - Static NAT is needed to allow an outside entity to initiate communications with an internal system behind a NAT proxy. 
- **RPC**: Remote Procedure Call is a protocol that enables one system to execute instructions on other hosts across a network infrastructure. RPC is an Application Programming Interface (API) like SOAP and Representation State Transfer (ReST).
- **Root of Trust**: a source that can always be trusted within a cryptographic system; because cryptographic security is dependent on keys to encrypt and decrypt data and perform functions such as generating digital signatures and verifying signatures, RoT schemes generally include a hardened hardware module; a RoT guarantees the integrity of the hardware prior to loading the OS of a computer
- **SNMP**: Simple Network Management Protocol, is a protocol for collecting and organizing info about managed devices on IP networks; it can be used to determine the health of devices such as routers, switches, servers, workstations, etc
- **Smurf attack**: ICMP echo request sent to the network broadcast address of a spoofed victim causing all nodes to respond to the victim with an echo reply
- **Teardrop attack**: exploits reassembly of fragmented IP packets in the fragment offset field (indicating the start position or offset of data contained in a fragemented packet)
- **Terminal Emulation Protocol**: AKA Telnet, is a command-line protocol designed to provide access between hosts
- **Unbound (Wireless) Network**: network where the physical layer interconnections are done using radio, light, or some other means (not confined to wires, cables, or fibers); may or may not be mobile

[4.1](#4.1) Assess and implement secure design principles in network architectures (OSG-9 Chpts 11,12)

- 4.1.1 Open System Interconnection (OSI) and Transmission Control Protocol/Internet Protocol (TCP/IP) models
    - **OSI**: Open Systems Interconnection (OSI) Reference Model developed by ISO (International Organization for Standardization) to establish a common communication structure or standard for all computer systems; it is an abstract framework
        - Communication between layers via **encapsulation** (at each layer, the previous layer's header and payload become the payload of the current layer) and **deencapsulation** (inverse action occurring as data moves up layers)

    | Layer | OSI model layer | TCP/IP model | PDU | Devices | Protocols | 
    |-----|---------------| -------------------|------------| ----------------|-----------|
    | 7     | Application     | Application |Data               | L7 firewall, Application FW                                | HTTP/s, DNS, DHCP, FTP,S-HTTP, TPFT, Telnet, SSH, SMTP, POP3, SNMP, PEM, IMAP, NTP, SNMP, TLS/SSL, GBP, RIP, SIP, S/MIME etc. |
    | 6     | Presentation    | Application |Data               | L7 firewall                                | JPEG, ASCII, and MIDI                                                |
    | 5     | Session         | Application| Data               | L7 firewall, Circuit Proxy FW, Circuit GW                                | PAP, CHAP, EAP, NFS, SQL, and RPC                                                |
    | 4     | Transport       | Transport (host-to-host) | Segments           | L4 firewall                                | TCP (connection oriented), UDP (connectionless), TLS     |
    | 3     | Network         | Internet/IP | Packets            | Router, Multiplayer Switch, Router, Packet Filter FW         | IPv4, IPv6, IPSec, OSPF, EIGRP, IGMP, ICMP                               |
    | 2     | Data Link       | Network Access | Frames             | Switch, Bridge, NIC, Wireless Access Point | MAC, ARP Ethernet 802.3 (Wired), CDP, LLDP, HDLC, PPP, DSL, L2TP, IEEE 802.11 (Wireless), SONET/SDH |
    | 1     | Physical        | Network Access | Bits               | All the above                              | Electrical signal (copper wire), Light signal (optical fibre), Radio signal (air) |

Note: Data streams are associated with the Application, Presentation, and Session layers. Once they reach the Transport layer, they become segments (TCP) or datagrams (UDP). From there, they are converted to packets at the Network layer, frames at the Data Link layer, and bits at the Physical layer.

### OSI layers in detail
- Mnemonics:
        - from top: All People Seem To Need Delicious Pizza
        - from bottom: Please Do Not Throw Sausage Pizza Away
    - ❄️**Application Layer (7)**
        - Responsible for:
            - interfacing user applications, network services, or the operating system with the protocol stack 
            - identifying and establishing availability of communication partners 
            - determining resource availability and 
            - synchronizing communication
            - The application layer contains protocols such as HTTP (HyperText Transfer Protocol), SMTP (Simple Mail Transfer Protocol), and File Transfer Protocol (FTP).
            - The application layer is not the user's application, but rather the protocol that interacts with the application and takes the data, voice, or video and sends it down through the OSI model for transmission to the machine on the other side of the network that the application is communicating with. 
    - ❄️**Presentation Layer (6)**
        - Responsible for transforming data into the format that any system following the OSI model can understand.  Examples of presentation layer formats include the American Standard Code for Information Interchange (ASCII) and the Extended Binary-Coded Decimal Interchange Code (EBCDIC). It is commonly thought that 🚫JPEG and 🚫MPEG would be at the presentation layer, however, those are file extensions created by actual specific applications and therefore reside above the OSI layer.
        - Associated tasks:
            - data representation
            -  it provides coding and conversion functions to data.
            - character conversion
            - data compression
            - data encryption
    - ❄️**Session Layer (5)**
        - Responsible for establishing, maintaining, and terminating communication sessions between two computers
        - The session layer is used primarily to track application dialogue.
        - It is responsible for establishing, maintaining, and terminating communications between applications, and managing these in simplex, half-duplex, and full-duplex modes
        - The session layer (Layer 5) establishes, coordinates, and terminates communication sessions between applications. Examples of session layer protocols are Remote Procedure Call (RPC) and Network File System (NFS).
        - Three communication session phases: 
            - connection establishment
                - 🎈**simplex**: one-way. In simplex mode, a one-way communications path is established with a transmitter at one end of the connection and a receiver at the other end. e.g car radio
                - 🎈**half-duplex**: both comm devices can transmit/receive, but not at the same time. In half duplex both communicating devices can transmit and receive messages but cannot do so simultaneously. e.g walkie-talkie
                - 🎈**full-duplex**: both comm devices can transmit/receive at same time. In Full-duplex mode, both communicating devices are capable of transmitting and receiving simultaneously. e.g cellular phone
            - data transfer
            - connection release
            - it establishes, coordinates, and terminates a communication session.
            - 📝Data streams exist at the Application, Presentation, and Session layers
    - ❄️**Transport Layer (4)**
        - Responsible for managing the integrity of a connection and controlling the session; providing transparent data transport and end-to-end transmission control
        - The Transport layer provides logical connections between devices, including end-to-end transport services to ensure that data is delivered. Transport layer protocols include TCP, UDP, SSL, and TLS.
        -  A 📝port is a transport layer identifier for the type of traffic that is being transported across the network using either Transmission Control Protocol (TCP) or User Datagram Protocol (UDP).
        -  📝circuit level firewalls and proxies operate at this layer
        -  The primary VPNs at the Transport layer are 📝TLS and 📝SSH. 
        - Defines session rules like how much data each segment can contain, how to verify message integrity, and how to determine whether data has been lost
        - Protocols that operate at the Transport layer:
            - 🛠️Transmission Control Protocol (TCP)
                - the major transport protocol in the internet suite of protocols providing reliable, connection-oriented, full-duplex streams
                - The key to connection-oriented is that the packets are numbered so that if there is one missing, it can be retransmitted.
                - emphasizing: full-duplex, connection-oriented protocol
                - uses three-way handshake, which makes it a connection-oriented protocol.
                - It supports full-duplex communications, is connection-oriented, and employs reliable sessions.
                - 🔨Flow control, or congestion control, is manipulated by using sliding windows in the Transmission Control Protocol (TCP). Sliding windows change the number of packets that can be sent 📝before an acknowledgment is required.  If any packets are missing within that window they can be retransmitted. This allows the window size to change if congestion or packet loss is detected. Larger windows increase the number of packets that can be sent before an acknowledgment is required, and smaller windows decrease the number of packets that can be sent before an acknowledgment is required.
                - 🔨TCP Checksum: Instead of CRC, TCP uses a checksum to verify data integrity. The checksum is a simpler form of error detection than CRC. It is calculated over the TCP header and data and included in the TCP segment. The receiving end performs the same checksum calculation and compares the result with the checksum received. If they match, the data is accepted; if not, it is rejected. UDP Checksum provides integrity for UDP datagrams; it is optional in IPv4 but mandatory in IPv6.
            - 🛠️User Datagram Protocol (UDP)
                - connectionless protocol that provides fast, best-effort delivery of **datagrams** (self-container unit of data)
                - User Datagram Protocol (UDP) does not employ a handshake
                - it is also considered a 📝simplex protocol (Typically, there is no acknowledgment or feedback from the receiver to the sender, because the channel only allows data to flow in one direction.)
                -  It's used for communication when there is no need to guarantee that the packet was received. For instance, chat programs, video streaming, and voice communication commonly use the UDP protocol.
            - 🛠️SSH: Secure Shell (SSH) provides 📝end-to-end encryption and exchange keys using the Diffie-Hellman algorithm. The encryption is negotiated between the client and server and does not rely on lower-layer encryption methods to protect the payload.
            - 🛠️Transport Layer Security (TLS): Transport Layer Security (TLS) is a cryptographic protocol that provides secure communication over a network. It is commonly used to establish secure connections between clients (such as web browsers) and servers (such as web servers) to ensure the confidentiality, integrity, and authenticity of data transmitted between them.
                - Transport Layer Security (TLS) uses asymmetric encryption and Public Key Infrastructure (PKI) to securely exchange a client-generated session key, after which all traffic is encrypted using symmetric encryption. TLS superseded Secure Socket Layer (SSL).  
    - ❄️**Network Layer (3)**
        - Responsible for logical addressing, and providing routing or delivery guidance (but not necessarily verifying guaranteed delivery), manages error detection and traffic control
        - 🔨IP Header Checksum: In the IPv4 protocol, the Network Layer uses a checksum in the IP header to ensure that the header itself has not been corrupted during transmission. The checksum is calculated by summing all the 16-bit words in the IP header. The result is then complemented, and this value is placed in the checksum field of the IP header. When the packet is received, the checksum is recalculated. If the result differs from the checksum in the header, the packet is considered corrupt and is discarded.  The checksum only covers the IP header, not the payload (the data part of the packet). IPv6, the newer version of the Internet Protocol, does not use a checksum in the IP header.
        - 🔨**Routing Protocols**: move routed protocol messages across a network
            - it ensures that messages are delivered to the proper device across a physical network link
            - includes RIP, OSPF, IS-IS, IGRP, and BGP
            - routing protocols are defined at the Network Layer and specify how routers communicate
            - routing protocols can be static or dynamic, and categorized as interior or exterior
            - The network layer is where addressing is found. The most common addressing in use today is the Internet Protocol (IP) address using v4 and now also using v6 (IPv4 and IPv6).
            - Routers and most routing protocols are also found here. A common mistake made is to include the Router Information Protocol (RIP) here. RIP is actually a layer seven protocol.
            - 🏺**Static routing protocol**: requires an admin to create/update routes on the router
            - 🏺**Dynamic**: can discover routers and determine best route to a given destination; routing table is periodically updated
            - 🏺**Deterministic Routing** In deterministic routing, the path between the source and destination is 📝predefined and doesn't change unless manually reconfigured. Typically used in static routing and 📝VOIP, where routes are manually set and fixed in the routing table. More predictable but less flexible. May be easier to secure because changes must be manually made, but it's also more vulnerable to outages or failures without dynamic adaptation.
            - 🏺**Distributed Routing**: In distributed routing, routing decisions are made independently by each router in the network based on the current network state. Each intermediate 📝node has the freedom to influence routing decisions. It contrasts with centralized routing, where one entity makes all routing decisions. Used in dynamic routing protocols like OSPF (Open Shortest Path First) or EIGRP (Enhanced Interior Gateway Routing Protocol). Each router shares its routing information with others to adapt to changes in the network.More flexible and resilient to changes, but can introduce security risks if malicious routing updates (e.g., route poisoning) are sent.
            - 🏺**Source Routing**: In source routing, the source node\sender of the packet specifies the entire route the packet should take through the network. Used for troubleshooting or network testing but less common in normal network operations.Considered a security risk since attackers can specify a route that avoids security controls or monitoring devices. Source routing is typically disabled in most secure networks.
            - 🍍**Distance-vector**: (interior) makes routing decisions based on distance (e.g. hop count), and vector (router egress interface);  Distance-vector protocols use metrics including the direction and distance in hops to remote networks to make decisions. examples:
                - **Routing Information Protocol (RIP)**: a distance-vector protocol that uses hop count as its routing metric
                - Interior Gateway Routing Protocol (IGRP)
                - Enhanced Interior Gateway Routing Protocol (EIGRP). This is Cisco Proprietary.
            - 🍍**Link state**: (interior) uses router characteristics (e.g. speed, latency, error rates) to make next hop routing decisions based on the shortest distance to a remote network. examples:
                - **Open Shortest Path First (OSPF)**: an interior gateway routing protocol developed for IP networks based on shorest path first or link-state algorithm
                - Intermediate System to Intermediate System (IS-IS)
            - interior vs exterior:
                - 🍎interior routing protocols ("myopic") make next hop decisions based only on info related to the next immediate hop
                - 🍎exterior routing protocols ("far-sighted") make hop decisions based on the entire remaining path (i.e.) vector
                - **Border Gateway Protocol (BGP)**: an exterior/path vector protocol
        - Routed protocols include Internetwork Package Exchange (IPX) and Internet Protocol (IP)
        - 📝Network hardware devices, including routers, function at layer 3
        - 📝IPsec operates at the Network layer (layer 3)
        - 📝Internet Control Message Protocol (ICMP)operates at layer 3 of the OSI model.
    - ❄️**Data Link Layer (2)**
        - Responsible for formatting a packet for transmission
        - The primary Data Link VPNs are 📝L2TP and 📝PPTP, although wireless encryption occurs here as well.
        - 📝Frame Relay is a Layer 2 protocol that uses packet-switching technology to create virtual circuits between routers
        - When a message reaches the Data Link layer, it is called a frame
        - Adds the source and destination hardware addresses to the frame
        - The data link layer contains Ethernet, token ring, Point to Point Protocol (PPP), and so on.
        - Media Access Control (MAC) - (hardware-based) address/AKA NIC address
            - MAC address is a 6-byte (48-bit) binary address written in hex
                - 📝first 3b/24-bits: Organizationally Unique Identifier (OUI) - denotes manufacturer
                - last 3b/24-bits: unique to that interface
        - 🐤**MACsec**: MACsec (Media Access Control Security) operates at Layer 2 (Data Link Layer). MACsec is a security protocol that provides confidentiality, integrity, and origin authenticity for data at the Data Link Layer. It encrypts and authenticates packets between directly connected nodes (e.g., switches, routers) on a LAN, ensuring that even if data is intercepted at this level, it cannot be understood or tampered with. 📝802.1AE, also known as MACsec, is an Institute of Electrical and Electronics Engineers (IEEE) standard that provides confidentiality and integrity at the data link layer of the Open Systems Interconnection (OSI) model. MACsec adds additional headers to the frame that identify it has been protected with MACsec. MACsec provides Hop-to-Hop encryption or link encryption, not end-to-end encryption.
        - 🐤CRC (Cyclic Redundancy Check) is used at the data link layer (Layer 2) for ensuring data integrity. CRC is a method used to detect errors in data transmission. It is commonly used in network protocols at the data link layer, such as Ethernet and Wi-Fi. It ensures that data frames sent over the network are not corrupted during transmission. When data is transmitted, a CRC value (a type of checksum) is calculated from the data and sent along with it. The receiving device recalculates the CRC value from the received data and compares it with the transmitted CRC. If they match, the data is considered intact; if not, an error is detected, and the data may be discarded or requested for retransmission.
        - 🐤**Address Resolution Protocol (ARP)**: operates at layer 2. Address Resolution Protocol (ARP) is a communication protocol used for discovering the link-layer address associated with a given Internet Protocol version four (IPv4) address and is a critical function in the Internet protocol suite.
        - Reverse Address Resolution Protocol 📝(RARP) works in the opposite direction from ARP. RARP allows a device to obtain its Internet Protocol (IP) address when it joins a network. It requires the network administrators to 📝manually program a link between a device's MAC address and an assigned IP address. It is not commonly used.
        - Switches & bridges function at this layer
            - 💥**Switch** operates at Layer 2 (Data Link Layer): A switch is more sophisticated than a hub and can forward data based on MAC addresses. It uses these addresses to direct traffic to the appropriate device, reducing collisions and improving network efficiency. A switch generally does not send frames to interfaces where the traffic is not destined
            - 💥**Bridge**: It is used to divide a network into segments and filter traffic between them based on MAC addresses. Used in smaller networks or to segment traffic in larger networks but less commonly used in modern networking due to the limitations in performance and scalability. Typically, it is used to connect two networks as if they were a single network.
        - Logical Link Control (LLC) is one of two sublayers that make up the Data Link Layer
            - 🔨**ARP Poisoning**: also known as ARP spoofing, is a type of cyber attack in which an attacker sends falsified Address Resolution Protocol (ARP) messages over a local network. 
                - ARP poisoning can use unsolicited or gratuitous replies—­specifically, ARP replies for which the local device did not transmit an ARP broadcast request.
                - in ARP poisoning,  an attacker sends malicious ARP replies to the network. These replies contain incorrect mappings of IP addresses to MAC addresses. Devices on the network, upon receiving these forged ARP replies, update their ARP tables with the incorrect information.
                - It can be used for Man-in-the-Middle (MitM) Attacks, Denial of Service (DoS), and Session Hijacking.
            - 🔨**VLAN hopping** occurs when an attacker manipulates a frame, so the switch moves it to a different VLAN. VLAN hopping can happen by spoofing a switch, setting up a dynamic trunk or tagged interface, or creating a 📝double-encapsulated 802.1Q tag. Network administrators should disable dynamic trunk or tagged interfaces and use separate VLANs for access interfaces.
            - 🔨**VSpanning Tree Protocol (STP) attack**, also known as a Spanning Tree Protocol manipulation attack, is a type of network security threat that exploits the vulnerabilities of the STP protocol, which is commonly used in Ethernet networks to prevent loops in redundant network topologies. The goal of an STP attack is to disrupt the network's normal operations and potentially cause network outages or other security issues.
            - 🔨**Forwarding table (CAM) overflow attack**: A switch references its forwarding table, also called the Content Addressable Memory (CAM) table, when sending frames out interfaces. If the switch does not know what interface the destination Media Access Control (MAC) address is connected to, it will send the frame out to all interfaces except the source interface. Once it learns the device's MAC address, it stores it in the forwarding table for future forwarding decisions.
                - If the forwarding table exceeds the allocated memory of the switch, it will begin to forward frames out of all interfaces. Attackers can exploit this vulnerability by creating thousands of bogus MAC addresses that overflow the forwarding table. This allows the attacker to see unicast traffic between devices on a network.
                - A Forwarding Table Overflow attack, also known as a Content-Addressable Memory (CAM) table overflow attack, is a type of Denial-of-Service (DoS) attack that targets network switches or routers. The attack exploits the limitations of CAM tables, which are used by these devices to store information about the MAC (Media Access Control) addresses of connected devices on the local network.

    - ❄️**Physical Layer (1)**
        - Converts a frame into bits for transmission/receiving over the physical connection medium
        - The Physical layer includes electrical specifications, protocols, and standards that allow control of throughput, handling line noise, and a variety of other electrical interface and signaling requirements
        - Network hardware devices that function at layer 1 include 📝NICs, 📝hubs, 📝repeaters, 📝concentrators, 📝amplifiers
            - 💥**Hub** operates at Layer 1 (Physical Layer): A hub is a simple device that transmits electrical signals to all connected devices. It does not understand MAC addresses or any other data beyond the raw physical signals. Hubs transmit frames out all interfaces regardless of the source and destination Media Access Control (MAC) address.
        - The physical layer contains wire, fiber, wireless, Binary digITs (BIT), and so on.
        - provides or defines the type of media to be used and defines the representation of data on the medium. The physical layer is where messages are transferred to electrical impulses.
        - Know four basic network topologies:
            - 🍌**Star**: each individual node on the network is directly connect to a switch/hub/concentrator. A star topology has a single point of failure at its center device. However, it allows nodes to fail without impacting other nodes on the network.
            - 🍌**Mesh**: all systems are interconnected; partial mesh can be created by adding multiple NICs or server clustering. Mesh topologies provide redundant connections to systems, allowing multiple segment failures without seriously affecting connectivity. This redundancy makes them highly resilient to link failures.
            - 🍌**Ring**: closed loop that connects end devices in a continuous ring (all communication travels in a single direction around the ring); A ring topology is a single point of failure at any location around the cable ring. Ring topologies connect devices in a loop where traffic can only flow one way. The right to send data is managed by a 📝token, which is passed around until it is claimed by a device. In this topology, any link failure breaks the ring, rendering communication impossible.
                - **Multistation Access Unit** (MSAU or MAU) connects individual devices
                - used in token ring and FDDI networks. When all nodes are connected in a closed loop it is a ring, so it would be a Token Rink or Fiber Distributed Data Interface (FDDI).
            - 🍌**Bus**: all devices are connected to a single cable (backbone) terminated on both ends. A bus topology has a single point of failure at its central backbone cable. When all nodes are connected to a single cable it is considered a BUS network. Bus topology contains one trunk cable and each computer is connected to this one trunk. Collisions are avoided by listening for traffic, waiting if it is heard, and sending if it hears nothing. In this topology, the bus is a single point of failure.
        - 📚Local Area Network (LAN) is a data network that operates across a small geographic area such as a single building or floor.
        - 📚Wide Area Network (WAN) is a geographically broad network that can cover multiple cities or even countries. A WAN connects multiple Local Area Networks (LANs) and other WANs by using telecommunications devices and facilities to form an internetwork.
        - 📚Metropolitan Area Network (MAN) extends across a large area, such as a city.
        - 📚Personal Area Network (PAN) is a small, personal-use network such as Bluetooth. Bluetooth max coverage is roughly 📝33 feet

- 4.1.2 Internet Protocol (IP) networking (e.g., Internet Protocol Security (IPSec), Internet Protocol (IP) v4/6)
     - IP is part of the TCP/IP (Transmission Control Protocol/Internet Protocol) suite
        - TCP/IP is the name of IETF's four-layer networking model, and its protocol stack; the four layers are link (physical), internet (network-to-network), transport (channels for connection/connectionless data exchange) and application (where apps make use of network services)
        - Network layer’s packet header includes the source and destination IP addresses. IP provides the foundation for other protocols to be able to communicate; IP itself is a connectionless protocol
        - TCP or UDP is used to communicate over IP 
        - IPSec provides data authentication, integrity and confidentiality
    - **Logical Address**: occurs when an address is assigned and used by software or a protocol rather than being provided/controlled by hardware.
         - 🍎**Multicast:** One to Many. Supported by both IPv4 and IPv6. Multicasting is the transmission of data to multiple specific recipients. Internet Group Management Protocol 📝(IGMP) is used to register a host's dynamic multicast group membership in order to receive a copy of the data stream. TFTP systems can be used to host or cache multicast datasets that are to be sent to the multiple recipients. It optimizes bandwidth usage by delivering content to a specific group of recipients who have expressed interest in receiving the data.
         - 🍎**Broadcast:** One to all. Not Supported by IPv6. IPv6 replaces broadcast with multicast and anycast to improve network efficiency and reduce unnecessary traffic.
         - 🍎**Unicast:** One to One communication. Supported by both IPv4 and IPv6. It uniquely identifies a single destination for communication within the network.
         - 🍎**Anycast:** From single source to the nearest or optimal recipient or group of recipients. Supported natively by 📝IPv6. Used for CDN and for streaming. Anycast addresses are sent to just one device like a unicast, but, the way it works is, that the first of any devices that can handle that request will answer, and the rest would then ignore the traffic. Anycast addresses are primarily used for load balancing and redundancy purposes in distributed networks.  This means that when a packet is sent to an anycast address, it is routed to the nearest (topologically closest) device that holds that anycast address. This routing decision is typically based on routing protocols and network topology.
        - 🍏**IPv4**:
             - dominant protocol that operates at layer 3; IP is responsible for addressing packets, uses 32-bit addresses. The  (TTL) IPv4 header values is used to prevent infinite transmission. 
             - IPv4 supports QoS priority values, but it is called "type of service" in the IPv4 header.
             - Format: IPv4 addresses are 📝32-bit numerical labels written in decimal format as four octets separated by periods (e.g., 192.168.1.1).
             - IPv4 = 32 bits divided into four groups of 8 bits each versus
             - Size: The IPv4 header is 20 to 60 bytes in length.
             - Fragmentation: Routers can fragment IPv4 packets to accommodate the maximum transmission unit (MTU) of the network path.
             - Built-in Security: IPv4 does not have built-in security features, but it can use IPsec (Internet Protocol Security) for encryption and authentication.
        - 🍏**IPv6**:
             - modernization of IPv4, uses 📝128-bit addresses, supporting 2128 hosts.
             - supports auto-configuration without DHCP, and supports Quality of Service (QoS) priority values
             - The hop limit IPv6 header value is used to prevent infinite transmission. 
             - Format: IPv6 addresses are 128-bit hexadecimal labels written in eight groups of four hexadecimal digits separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
             - IPv6 = 128 bits divided into eight groups of 16 bits
             - Size: The IPv6 header is 40 bytes in length.
             - Fragmentation: IPv6 requires fragmentation to be handled by the sending host rather than by routers, improving efficiency.
             - Built-in Security: IPv6 was designed with IPsec as a mandatory component, providing native support for encryption and authentication.
        - 🍏**IPV4 to IPV4 Transition**: The means by which IPv6 and IPv4 can coexist on the same network is to use one or more of three primary options: dual stack, tunneling, or NAT-­PT.
             - 🎈Dual stack is to have most systems operate both IPv4 and IPv6 and use the appropriate protocol for each conversation.
             - 🎈Tunneling allows most systems to operate a single stack of either IPv4 or IPv6 and use an encapsulation tunnel to access systems of the other protocol.
                  - 🐝6to4: Encapsulates IPv6 packets within IPv4 packets, allowing IPv6 communication over an IPv4 network
                  - 🐝Toredo Tunneling: Windows implementation. Provides IPv6 connectivity through NAT (Network Address Translation) devices using UDP (User Datagram Protocol) to encapsulate IPv6 traffic.
                  - 🐝ISATAP (Intra-Site Automatic Tunnel Addressing Protocol): Allows IPv6 packets to be transmitted over an IPv4 network within an organization and with 📝compatibile routers and endpoints.
             - 🎈Network Address Translation-­Protocol Translation (NAT-­PT) (RFC-­2766) can be used to convert between IPv4 and IPv6 network segments similar to how NAT converts between internal and external addresses.
             -  🎈Translation Techniques
                  -  🐝NAT64 (Network Address Translation 64):  Translates IPv6 addresses to IPv4 addresses and vice versa, allowing IPv6-only devices to communicate with IPv4 devices. Requires NAT64 📝gateways or appliances
                  -  🐝DNS64: Works with NAT64 to synthesize IPv6 addresses from IPv4 addresses in DNS responses.
             
    - 🔴**TCP/IP Model**
        - 📝Application layer: Application Layer: defines protocols for node-to-node application communication and provides services to the application software running on a computer. HTTP, FTP, SMTP, DNS, SNMP.
        - 📝Transport layer: Transport Layer: defines protocols for setting up the level of transmission service for applications; this layer is responsible for the reliable transmission of data and the error-free delivery of packets. TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
        - 📝Internet layer: Internet Layer: defines the protocols for logically transmitting packets over the network.  Internet Protocol (IP).
        - 📝Network Access layer: Network Access Layer: defines the protocols and hardware required to deliver data across a physical network. It handles the physical transmission of data over a network, including hardware addressing (MAC addresses), framing, and error detection at the hardware level.
        - the TCP/IP model can also be listed as:
            - 💠Application
            - 💠Host-to-Host
            - 💠Internet
            - 💠Link
            - 💠Physical
        - Sometimes the physical and the link layers are considered one and called network access. The host-to-host layer equates to the transport layer of the OSI model and is sometimes called the transport layer. The top three layers of the OSI model are represented in the TCP/IP model as the application layer. There is often confusion in conversations due to this.

- 4.1.3 Secure protocols
    - ❄️**Kerberos**: standards-based network authentication protocol, used in many products (most notably Microsoft Active Directory Domain Services or AD DS)     
        - Kerberos is mostly used on LANs for organization-wide authentication, single sign-on (SSO) and authorization
    - ❄️**SSL and TLS**: data protection used for protecting website transactions (e.g. banking, ecommerce)
        - SSL and TLS both offer data encryption, integrity and authentication 
        - TLS has supplanted SSL (the original protocol, considered legacy/insecure) 
        - TLS was initially introduced in 1999 but didn’t gain widespread use until years later
        - The original versions of TLS (1.0 and 1.1) are considered deprecated and organizations should be relying on TLS 1.2 or TLS 1.3
        - TLS supports both one-­way and two-­way authentication.
        - TLS and SSL are not interoperable or backward compatible.
    - ❄️**SFTP**: a version of FTP that includes encryption and is used for transferring files between two devices (often a client / server). TFTP is trivial FTP, an insecure quick transfer method often used to transfer files for network devices, among other uses. SCP (Secure Copy), is a secure file transfer method.
    - ❄️**SSH**: remote management protocol, which operates over TCP/IP
        - all communications are encrypted
        - primarily used by IT administrators to manage devices such as servers and network devices
        - SSH2 adds support for 📝simultaneous shell sessions over a single SSH connection. Both SSH1 and SSH2 are capable of supporting multifactor authentication. SSH2 actually drops support for the IDEA algorithm, whereas both SSH1 and SSH2 support 3DES.
    - ❄️**IPSec**: an IETF standard suite of protocols that is used to connect nodes (e.g. computers or office locations) together
        - widely used in virtual private networks (VPNs)
        - IPSec provides encryption, authentication and data integrity
        - IPsec is a security protocol that automatically performs 📝reauthentication of the client system throughout the connected session in order to detect session hijacking.

- 4.1.4 Implications of multilayer protocols
    - TCP/IP is a multilayer protocol, and derives several associated benefits
        - this means that protocols can be encapsulated within others (e.g. HTTP is encapsulated within TCP, which is in turn encapsulated in IP, which is in Ethernet), and additional security protocols can also be encapsulated in this chain (e.g. TLS between HTTP and TCP, which is HTTPS)
        - note that VPNs use encapsulation to enclose (or tunnel) one protocol inside another
    - 🍀Multilayer benefits:
        - many different protocols can be used at higher layers
        - encryption can be incorporated (at various layers)
        - it provides flexibility and resiliiency in complex networks
    - 🍀Multilayer disadvantages:
        - nothing stops an added layer from being covert
        - encapsulating can be used to bypass filters: Encapsulation is both a benefit and a potentially harmful implication of multilayer protocols. Encapsulation allows for encryption, flexibility, and resiliency, while also enabling covert channels, filter bypass, and overstepping network segmentation boundaries.
        - logical network segments can be traversed
        - Generally, Multilayer protocols include the risk of VLAN hopping, multiple encapsulation, and filter evasion using tunneling.
            - 🔥Multiple Encapsulation: Encapsulation is a process where data is wrapped (or encapsulated) with protocol-specific headers and trailers as it moves down the layers of the OSI model. In multilayer protocols, this encapsulation can occur multiple times as data passes through different protocols and layers. Multiple Encapsulation happens when a packet is encapsulated within several layers of different protocols. For example, data might be encapsulated by a TCP header, then by an IP header, and then within a VPN tunnel, adding another layer of encapsulation. Multiple layers of encapsulation add complexity to the data packet, which can make it harder for security devices like firewalls, intrusion detection/prevention systems (IDS/IPS), or other filtering mechanisms to inspect the contents of the packet effectively. The more encapsulation layers there are, the harder it becomes to analyze the packet for potential threats. Malicious actors can hide malicious content inside deeply encapsulated packets, evading detection.
            - 🔥Filter Evasion Using Tunneling: Tunneling involves encapsulating a network protocol within packets carried by a different protocol. This is often done to bypass network restrictions, such as firewall rules or access controls. For example, an IP packet can be encapsulated within an HTTP packet to bypass firewall rules that only allow HTTP traffic. Bypassing Security Controls: By encapsulating one protocol within another, attackers can potentially bypass security controls that are configured to block certain types of traffic. For example, if a firewall is set to block non-HTTP traffic but allows HTTP traffic, an attacker could tunnel malicious traffic through an allowed protocol, like HTTP or HTTPS, to evade detection. IDS/IPS devices might not be able to properly inspect the tunneled traffic, especially if the tunneling protocol uses encryption. This can allow malicious payloads to pass through the network without being detected.
            - 🔥Virtual Local Area Network (VLAN) hopping occurs when an attacker manipulates a frame so the switch moves it to a different VLAN. VLAN hopping can happen by spoofing a switch, setting up a dynamic trunk or tagged interface, or creating a double-encapsulated 802.1q tag. Network administrators should disable dynamic trunk or tagged interfaces and use separate VLANs for access interfaces.
            - 🔥Spanning Tree Protocol (STP) attack refers to malicious activities that exploit vulnerabilities or manipulate the STP in a network. Attackers may attempt to disrupt or manipulate the STP topology to create loops, leading to network outages or unauthorized access.
            - 🔥Link Layer Discovery Protocol (LLDP) spoofing is a network attack where an attacker sends fake LLDP frames to deceive network devices about their neighbors. This can lead to misconfigurations, unauthorized access, or other security risks.
            - 🔥Address Resolution Protocol (ARP) poisoning attacks, also known as ARP spoofing, are cyber-attacks where an attacker sends falsified ARP messages over a local area network. By linking their Media Access Control (MAC) address to the Internet Protocol (IP) address of a legitimate network device, the attacker can intercept and manipulate network traffic, leading to various security threats such as eavesdropping, man-in-the-middle attacks, or session hijacking. 
        - **DNP3 (Distributed Network Protocol 3)**: Multilayer protocols like DNP3 allow SCADA and other systems to use TCP/IP-based networks to communicate. DNP3 is primarily used in the electric and water utility and management industries. It is used to support communications between data acquisition systems and the system control equipment. This includes substation computers, remote terminal units (RTUs) (i.e., devices controlled by an embedded microprocessor), intelligent electronic devices (IEDs), and SCADA primary stations (i.e., control centers). DNP3 is an open and public standard. It is a multilayer protocol that functions similarly to TCP/IP in that it has link, transport, and transportation layers.
             - It utilizes the **Data Link Layer** for reliable node-to-node data transfer.
             - At the **Trasnsport layer**, DNP3 uses this layer to provide end-to-end communication, ensuring that data packets are transmitted across the network reliably and in the correct sequence.
             - At the **Application Layer**, DNP3 defines the format of messages, the functions that can be requested (e.g., reading or writing data points), and the way in which data points are represented.
             - At the **Network layer**, DNP3 messages can be encapsulated within IP packets for transmission over IP networks.

- 4.1.5 Converged protocols (e.g., Fiber Channel Over Ethernet (FCoE), Internet Small Computer Sysetms Interface (iSCSI), Voice over Internet Protocol (VoIP))
    - **Converged protocols**: merged specialty or proprietary with standard protocols, such as those from the TCP/IP suite
        - converged protocols provide the ability to use existing TCP/IP supporting network infrastructure to host special or proprietary services without the need to deploy different hardware
    - Examples of converged protocols:
        - 🔴**Storage Area Network (SAN)**: a secondary network (distinct from the primary network) used to consolidate/manage various storage devices into single network-accessible storage. The Storage Area Network (SAN) connects servers to a network-attached storage device. Fundamentally, it is a Local Area Network (LAN) that has only storage devices. The technology used facilitates the large transfer of data across the LAN. The protocols commonly used are Fibre Channel and iSCSI. Storage can be attached using Internet Small Computer Systems Interface 📝(iSCSI), 📝Fibre Channel (FC), or Network File System 📝(NFS).
           -  🍍Deduplication: is particularly effective when an organization is dealing with a large amount of redundant data, as it ensures that only unique instances of data are stored, thereby optimizing storage utilization and improving overall efficiency.
                - In some instances, a SAN may implement deduplication in order to save space by not retaining multiple copies of the same file. However, this can sometimes result in data loss if the one retained original is corrupted.
                - Deduplication replaces multiple copies of a file with a 📝pointer to one copy. If the one remaining file is damaged, then all of the linked copies are damaged or inaccessible as well.
           -  🍍Compression: While compression reduces the size of data, it does not specifically address the problem of redundant data. Compression can help save space but may not be as effective in cases where the primary issue is data redundancy.
           -  🍍Caching: Caching improves performance by temporarily storing frequently accessed data in a faster storage medium, but it does not address storage issues related to redundant data. It’s more about speeding up access rather than optimizing storage space.
        - 🔴**Fibre Channel over Ethernet (FCoE)**: operating at 📝Data Link Layer (layer 2), Fibre Channel is a network data-storage solution (SAN or network-attached storage (NAS)) that allows for high-speed file transfers of (up to) 📝128 Gbps
        - designed to be operated over fiber-optic cables support for copper cables was added later to offer less expensive options. Fibre Channel typically requires its own dedicated infrastructure (separate cables). However, Fibre Channel over Ethernet (FCoE) can be used to support it over the existing network infrastructure.
        - FCoE is used to encapsulate Fibre Channel storage communications over Ethernet networks and is primarily used in the deployment of a SAN.
            - FCoE can be used over existing network infrastructure
            - FCoE typically requires 📝10 Gbps Ethernet in order to support the Fibre Channel protocol.
            - FCoE used to encapsulate Fibre Channel over Ethernet networks
            - with this technology, FCoE operates at Layer 2, but the Fibre Channel operates as a Network layer (OSI layer 3) protocol, replacing IP as the payload of a standard Ethernet network. So FCoE often relies on an underlying Layer 3 infrastructure (such as IP) to handle network routing and management tasks. 
        - 🔴**Internet Small Computer Sysetms Interface (iSCSI)**: operating at 📝Network Layer (OSI layer 3), iSCSI is a network storage standard based on IP, used to enable location-independent file storage, transmission, and retrieval over LAN, WAN, or public internet connections. It encapsulates SCSI commands and responses within TCP/IP packets, which means it operates over IP networks at the 📝transport layer (Layer 4) but leverages the network's Layer 3 capabilities for addressing and routing. iSCSI is a converged protocol that allows location-independent file services over traditional network technologies. It costs less than traditional Fibre Channel. iSCSI is a converged protocol that supports SCSI storage access via Ethernet.
            - Internet Small Computer System Interface (iSCSI) is used to transmit SCSI commands through Transmission Control Protocol (TCP) packets. iSCSI is frequently found in Storage Area Networks (SANs) and allows a server to attach storage through Ethernet.  
        - 🔴**Multiprotocol Label Switching (MPLS)**: a WAN protocol that operates at both layer 2 and 3 and does label switching; MPLS is a high-throughput/high-performance network technology that directs data across a network based on 📝short path labels rather than longer network addresses. It requires the first router in the path to determine the full path the packet will travel, removing the need for other routers in the path to make independent determinations. MPLS (Multiprotocol Label Switching) is a high-throughput, high-performance network technology that directs data across a network based on short path labels rather than longer network addresses. It uses encapsulation to handle a wide range of protocols. This technique saves significant time over traditional IP-based routing processes, which can be quite complex.
        - 🔴**Voice over Internet Protocol (VoIP)**: a tunneling mechanism that encapsulates audio, video, and other data into IP packets to support voice calls and multimedia collab
            - VoIP is considered a converged protocol because it combines audio and video encapsulation technology (operating as application layer protocols) with the protocol stack of TCP/IP
        - 🔴**Infini Band Over Ethernet**: a network protocol that allows 📝remote direct memory access (RDMA) over ethernet network. It is a low-latency high throughput networking technology commonly used in high-performance computing (HPC), data centers, and enterprise environments. Supports speeds of up to 📝200Gbps per link. Infiniband over Ethernet is commonly used for allowing direct memory access over Ethernet while providing high bandwidth and low latency
        - 🔴**Compute Express Link (CXL)**: is an open standard interconnect designed to improve communication between CPUs and other high-speed devices such as accelerators, memory expanders, and smart I/O devices. It is used for 📝high-speed, 📝high-capacity 📝CPU-to-Device and 📝CPU-to-Memory connections. CXL is Compute Express Link, often used to interconnect memory, GPUs, CPUs, and accelerators. It is a converged protocol that is an open standard for high-speed communications with accelerators, GPUs, CPUs, and similar device

- 4.1.6 Micro-segmentation:
- 📁**Micro-Segmentation**: involves creating fine-grained, policy-driven segments that can isolate individual workloads or devices. It takes the concept of logical segmentation to a more granular level. The small segments contain specific workload or functionally similar or identical nodes. It limits scope of breach and lateral movement. Micro-segmentation is used to logically separate systems and services by defining boundaries between them. This is often part of a zero trust architecture including the use of on-demand access to services. Cisco Trsutsec is an example of Micro segmentation.
     - Microsegmentation can be implemented using internal segmentation firewalls (ISFWs),
     - transactions between zones are filtered, and
     - it can be implemented with virtual systems and virtual networks. (e.g., Software Defined Networks 📝(SDN), Virtual eXtensible Local Area Network 📝(VXLAN),Encapsulation, Software-Defined Wide Area Network 📝(SD-WAN)). Virtual local area networks 📝VLAN, air gaps, and Demilitarized Zones 📝(DMZ) are network segmentation methods, either physical or logical.
    - Virtual Local Area Networks (VLANs) provide segmentation at the data link layer of the Open System Interconnection (OSI) model; this is accomplished by assigning a VLAN tag to switch interfaces. 
    - Air gap networks are physically separated, meaning they physically have no connections between them.
    - A Demilitarized Zone (DMZ) is segmented away from other networks using firewalls. It is the space between the internal trusted network and the external untrusted network. It is created using one or two firewalls (as a basic description) that include a Local Area Network (LAN) between them. On this LAN, the website is placed, and the email gateway and anything else the company wants is accessible from outside of the network.
    - ❄️**Software-defined networks (SDN)**:
        - SDN is a broad range of techniques enabling network management, routing, forwarding, and control functions to be directed by software
        - SDN is effectively network virtualization, and 📝separates the infrastructure layer (aka the data or forwarding plane) - hardware and hardware-based settings, from the control layer - network services of data transmission management
        - Software-defined networking provides a network architecture that can be defined and configured as code or software and separates routing processes from packet switching while centralizing control. 
        - Software-defined networking (SDN) is a converged protocol that allows virtualization concepts and practices to be applied to networks.
        - Software-defined networking (SDN) uses code to configure and control the network. This allows for agile, programmatic control and configuration as needed from a central control point. ❗SD-WAN provides the same sort of control for wide area network links
        - SDN introduces a centralized controller that manages the network infrastructure and allows for dynamic and programmable network configurations. While SDN offers advantages in terms of flexibility and automation, it also 🧠expands the attack surface of the network. With SDN, there is a single point of control that, if compromised, can have a significant impact on the entire network.
            - NOTE: the 👘**control plane**: uses protocols to decide where to send traffic, The control plane receives instructions and sends them to the network. The 👘**data plane**: includes rules that decide whether traffic will be forwarded. The 👘**application plane** of a software-defined network (SDN) is where applications run that use application programming interfaces (APIs) to communicate with the SDN about needed resources.
        - typically ABAC-based. A software-defined network (SDN) typically uses an attribute-based access control (ABAC) model. 
        - an SDN solution provides the option to handle traffic routing using simpler network devices that accept instructions from the SDN controller
        - SDN offers a network design that is directly programmable from a central location, is flexible, vendor neutral, and based on open standards
        - Allows org to mix/match hardware
    - ❄️**Virtual extensible local area network (VXLAN)**:
        - an encapsulation protocol that enables VLANs to be stretched across subnets and geographic distances
        - VLANs allow network admins to use switches to create software-based LAN segments that can be defined based on factors other than physical location
            - **⚒️VLAN:** Virtual Local Area Networks (VLANs) can be used to provide logical separation between internal departments, such as engineering, sales, and marketing. VLANs provide scalability and segmentation and are separated logically by tags. The tags are used by the switches to determine where to send frames that pass through it. 
        - VXLAN is an encapsulation protocol that enables switch-created network segments (i.e., VLANs) to be 📝stretched across subnets and geographic distances.
        - Typically restricted to layer 2
        - VXLAN tunnels layer 2 connections over a layer 3 network, in essence extending a LAN over distances or networks that it might not otherwise function over.
        - Allows up to 16 million virtual networks (VLAN limit is 4096)
        - VXLAN can be used as a means to implement microsegmentation without limiting segments to local entities only
        - Defined in RFC 7348
    - ❄️**Encapsulation:**
        - the OSI model represents a protocol stack, or a layered collection of multiple protocols, and communication between protocol layers occurs via encapsulation and deencapsulation (defined above) as data moves from layer to layer. Encapsulation adds to the header (and sometimes to the footer) of the data provided by the previous layer. The main body of the data is not modified.
    - ❄️**Software-defined wide area network (SD-WAN)**: an evolution of SDN that can be used to manage the connectivity and control services between distant data centers, remote locations, and cloud services over WAN links; put another way, SDN-WAN is an extension of SDN practices to connect entities spread across the internet, supporing WAN architecture; espcially related to cloud migration
        - The network uses predefined rules to optimize performance.
        - The network conducts continuous monitoring to support better performance.
        - The network uses self-learning techniques to respond to changes in the network.
        - SDN offers a new network design that is directly programmable from a central location, flexible, vendor neutral, and open standards based. 
    - ❄️**Transport Architecture**:
     - ✈️Management Plane: The management plane is responsible for network administration tasks. It handles configuration, monitoring, security management, and policy enforcement. E.g SNMP, SSH, NETCONF
     - ✈️Control Plane: is responsible for making decisions and determine optimal paths about where and how data packets should be forwarded. It manages routing, signaling, and network topology. E.g routing protocols like OSPF, BGP
     - ✈️Data Plane: is responsible for the actual movement of packets through the network. It handles the forwarding of data based on the decisions made by the control plane. e.g QOS, packet forwarding by switch or router using mac address table or routing tables respectively, packet filtering e.g firewalls, load balancers
       - 🍊Cut-Through Switching:  is a method of forwarding packets in which a switch starts forwarding a frame before the entire frame has been received. There is minimal error checking and it is used in low-latency networks. Cut-through switching forwards a frame as soon as it reads the destination address, providing low latency and suitability for low-latency applications. It does not address integrity. 
       - 🍊Store-and-forward Switching: is a method where the entire frame is received and error-checked before being forwarded. Used in environements where liability is essential. Store-and-forward switching receives and stores the entire frame in a buffer before forwarding, offering greater error checking and suitability for ensuring data integrity. Store-and-forward waits for the entire frame to allow it to be checked using a cyclic redundancy check (CRC) before forwarding.
       - 🍊Arbitration is a media access protocol where a central authority or a predefined set of rules determines which device has the right to access the communication medium at any given time. It does not address integrity
       - 🍊Deconfliction is a media access protocol that aims to avoid collisions and conflicts by assigning specific time slots or frequency bands to different devices for communication. It does not address integrity.

- 📁**Network Segmentation**: Benefits include boosting performance where system that need to communicate are located in the same segment. It reduces communication problems such as broadcast storms to individual segments, and improves security by isolating traffic to segments
     - 🐝Intranet: Data traffic that moves between a data center and external networks or clients.
     - 🐝Extranet: A controlled private network allowing access to partners, vendors, or clients. This section of the network has been sectioned off to act as as an intranet for the private network but also to serve information to the public internet. A cross between the internet and the intranet. An extranet is a type of screened subnet typically separated from the intranet and internet by firewalls.
     - 🐝DMZ: A buffer zone between the internal network and the external network, hosting public-facing services. An extranet for public consumption. Typically labelled perimeter network. DMZ is a specific implementation with a focus on isolating external-facing services from the internal network.
     - 🐝Screened subnet: is a type of security zone that can be positioned so that it operates as a buffer network between the secured private network and the internet and can host publicly accessible services. It is often placed between an internal network and an external network and can be seen as a specific type of DMZ. Static NAT can be appropriately and securely used to grant external entities access to resources positioned in a screenedsubnet or an extranet, especially when those resource hosts are using private IP addresses
         - A screened subnet creates three networks using two routers or firewalls. One network is the internal trusted network, the second is the network attached to the external untrusted network (usually the Internet), and the third is the network usually referred to as a Demilitarized Zone (DMZ). Designated systems are placed in the DMZ with firewall policies that allow internet users access, such as web servers. This allows firewall administrators to expose only a small network to the Internet without adding private networks.
         - A network protected by a single router/firewall is sometimes referred to as a screened subnet, but the description above is more commonly accepted. 
 - 📁**Physical Segmentation**:
      - 🎤Out-of-Band: physically seperating networks into distinct zones using hardware. It is an alternate communication path for different types of traffic. Separate, physically isolated Ethernet networks that require strong authentication are a commonly used out-of-band (OOB) option
      - 🎤Air Gap: Complete physical isolation of a network by having no wired or wireless communications. Common in high security government networks or critical infrastructures e.g industrial systems and public utilities. Air-gaps are physical separations between systems or devices that prevent communications or connections between them. This prevents network-based attacks and limits the ways that attackers could access the devices.
 - 📁**Logical Segmentation**:
     - 🍊In-Band: seperate networks by configuring routers, switches, firewalls to control traffic flow e.g subnets, VLANs
          - ⚒️Switches: switch is a networking device that can be used to create 🔥digital virtual network segments (i.e., VLANs) that can be altered as needed by adjusting the settings internal to the device.
              - A VLAN (virtual LAN) is a hardware-imposed network segmentation created by switches that requires a routing function to support communication between different segments. 
          - ⚒️Router: Provides connection to disparate networks (i.e., subnets)
          - ⚒️Proxy and Firewalls: Can be positioned between network segments to control and manage traffic
     - 🍊Virtual Routing and Forwarding VRF: facilitates the co-existence of multiple routing table instances on a router simultenously. Virtual routing and forwarding (VRF) allows multiple routing tables to be used on the same device simultaneously. This is similar to the concept of VLANs on a layer 2 switch but operating at layer 3. Routing instances operate independently, allowing IP addresses to overlap without conflict, supporting segmentation and thus permitting flexibility for zero trust implementations and other security solutions. 
     - 🍊VLANs
     - 🍊VPNs
     - 🍊Virtual Domain VDOM: Network segments/chunks created through logical segmentation techniques like VRFs. In the VRF context, they are called VRF domains. Virtual domains (often referred to as virtual contexts or virtual systems) allow for the creation of separate, isolated security domains within a single firewall or security device. VDOMs are instances of firewalls, each with their own interfaces and rulesets allowing granular configurations based on security requirements. VDOMs are commonly used to accommodate different purposes, customers, or other needs where separately managed firewall instances are desirable.
- **Firewall Types**: - 📝IM clients can utilize random port numbers which makes it challenging for firewalls to control.
   - 🍇**Next-­generation firewall (NGFW)** is a unified threat management (UTM) device that is designed to provide advanced security features at the network perimeter and is based on a traditional firewall with numerous other integrated network and security services. It provides a comprehensive range of security features, including perimeter protection, application control, and advanced threat detection.
   - 🍇**Internal Segmentation Firewall (ISFW)** is a security device or technology used to enforce security policies and controls within an internal network, particularly to segment different internal network zones. Unlike traditional firewalls that primarily focus on perimeter security, an ISFW operates within the internal network to create additional layers of security. It focuses on internal network segmentation and access control between internal segments.
   - 🍇**Application-­level firewall** is able to make access control decisions based on the content of communications as well as the parameters of the associated protocol and software. application-level gateway firewalls proxy traffic for specific applications. Often application-aware devices are able to provide 📝deep packet or content inspection and filtering based on their focus on specific applications and protocols. A web application firewall (WAF) is an example of an application-aware device that can provide deep packet or content inspection.
   - 🍇**Web Application Firewall WAF\Web Security Gateway**: is a software-based app that monitors and filters exchanges between applications and a host; usually inspect and filter conversations like HTTP/S. It is an appliance, server add-­on, virtual service, or system filter that defines a strict set of communication rules for a website. A web security gateway blocks access to certain websites based on their URL or content, which can often be set by content category (e.g. gambling, social media, games). Web security gateways are sometimes integrated into proxy servers or next-generation firewalls.
   - 🍇**Stateful inspection firewalls** make access control decisions based on the content and context of communications, but are not typically limited to a single application-­layer protocol. Stateful packet inspection firewalls, also known as dynamic packet filtering firewalls, 📝track the state of a conversation and can allow a response from a remote system based on an internal system being allowed to start the communication.
       - A stateful firewall monitors the current state of network connections and blocks packets that are invalid in context (OSI Layers 3 and 4) 
   - 🍇**Circuit-­level firewalls** are able to make permit and deny decisions in regard to circuit establishment either based on simple rules for IP and port, using 📝captive portals, requiring 📝port authentication via 802.1X, or more complex elements such as context-­or attribute-­based access control.
       - A circuit-level firewall ensures that the TCP handshake was completed and conceals information about the protected network. (Theoretically OSI Layer 5, but also looks at TCP data at Layer 4.) SOCKS proxies are examples of circuit firewalls. 
   - 🍇**Static packet-­filtering firewalls** filter traffic by examining data from a message header. Usually, the rules are concerned with source and destination IP address (layer 3) and port numbers (layer 4).
       - A static packet filtering, screening router, or stateless firewall evaluates each packet independently based on its header fields (OSI Layer 3). 
   - 🍇**TCP Wrapper**: is a host-based access control system that can be used to restrict access to Internet services based on IP address or hostname. It acts as a gateway between network services and the network, allowing administrators to control which hosts can connect to services like SSH, FTP, and others. TCP Wrapper allows administrators to specify which hosts (by IP address or hostname) are allowed or denied access to specific services, such as SSH, FTP, or HTTP, based on the requesting host.
   - 🍇**A Database Activity Monitor (DAM)** is a security tool that continuously monitors and audits database activity to detect unauthorized access, data breaches, or suspicious activities. It provides real-time alerts, log analyses, and forensic capabilities to enhance database security and compliance.
   - 🍇**A File Activity Monitor (FAM)** is a security tool designed to track and monitor user interactions with files and data stored on a computer or network. It records file access, modification, deletion, and transfer activities to detect unauthorized or suspicious actions, prevent data leaks, and ensure compliance with security policies. File activity monitors provide real-time alerts, detailed logs, and reporting capabilities to enhance data security and protect sensitive information. DAMs and FAMs  initially only monitored traffic, however, they are now starting to block traffic like a firewall does.

- 4.1.7 Wireless networks (e.g. LiFi, Wi-Fi, Zigbee, satellite)
    - ❄️**Light fidelity (Li-Fi)**: a form of wireless communication technology that relies on 📝light (in the visible, infrared, or ultraviolet spectrums) to transmit data, with theorectical speeds up to 224Gbits/sec. It is not susceptible to EM interference. While LiFi transmissions cannot penetrate walls like WiFi (which utilizes radio frequency) can, because the light spectrum is significantly larger than the radio frequency spectrum, 📝faster data rates are supported. LiFi, or Li-Fi, is a term coined by Professor Harold Haas from the University of Edinburgh.
    - ❄️**Wi-Fi**: Wirless LAN IEEE 802.11x; associated with computer networking, Wi-Fi uses 802.11x spec to create a public or private wireless LAN. There are several modes of connecting to WiFi
        - 🎈Ad hoc mode: Directly connects two clients.
        - 🎈Standalone Mode: Ad hoc mode can be easy to confuse this with standalone mode, which connects clients using a wireless access point but not to wired resources like a central network.
        - 🎈Infrastructure mode connects endpoints to a central network, not directly to each other.
        - 🎈Wired extension mode uses a wireless access point to link wireless clients to a wired network. A wired extension is often a single WAP.
        - 🎈Enterprise extended infrastructure mode exists when a wireless network is designed to support a large physical environment through the use of a single SSID but numerous access points. An enterprise extension is often used as an extension to a wired network and requires only a single logon event for each connected session for workers no matter where in the building they are located.
        - 🎈A wireless bridge is used to connect to moderate distant networks together using two bridge access points.
        - Techniques used in wireless communication (Wireless Frequencey Access Methods) and modulating wireless signals:
            - 📚**FHSS (Frequency-Hopping Spread Spectrum):** FHSS is a method of transmitting radio signals by rapidly switching the carrier frequency among many predefined channels in a pseudo-random sequence, which helps avoid interference and eavesdropping. It also Spreads the signal across a wider bandwidth, which improves resistance to interference and jamming. Bluetooth uses FHSS.
                - Frequency Hopping Spread Spectrum (FHSS) is a wireless communication technique used in radio transmission. It works by continuously switching frequencies over a wide band of frequencies according to a predetermined sequence known to both the transmitter and receiver. This hopping pattern provides several benefits in terms of security, reliability, and resistance to interference.
            - 📚**DSSS (Direct Sequence Spread Spectrum):** DSSS is a 📝spread spectrum technique where the data signal is multiplied by a 📝pseudorandom noise (PN) sequence, resulting in a wider bandwidth signal. Data is modulated by a pseudorandom sequence, which spreads the signal over a wider frequency band. It provides resistance to narrowband interference and improves signal robustness. Requires precise synchronization between transmitter and receiver to decode the signal correctly. The 📝802.11b standard uses DSSS for spreading data signals and achieving robustness against interference. 📝GPS (Global Positioning System) signals use DSSS to maintain signal integrity and resist interference.
                - DSSS is a modulation technology that increases bandwidth and adds redundancy by adding sub-bits to messages. These sub-bits are called 📝“chips” and can be used to reconstruct data similar to how a RAID-5 reconstructs data after a drive failure.
            - 📚**Chirp Spread Spectrum (CSS)** is a modulation technique used in wireless communication systems to transmit data signals over a wide frequency range. It differs from traditional spread spectrum techniques like Frequency Hopping Spread Spectrum (FHSS) and Direct Sequence Spread Spectrum (DSSS) in that it modulates the frequency of the transmitted signal continuously 📝over time, rather than using discrete frequency hops or spreading codes.
            - 📚**Orthogonal Frequency-Division Multiplexing OFDM:** is a method of encoding digital data on multiple carrier frequencies. It divides a high-data-rate signal into several lower data-rate streams, each transmitted simultaneously over a different frequency band.  OFDM offers 📝high throughput with the least interference. OFDM employs a digital 📝multi-carrier modulation scheme that allows for a more tightly compacted transmission. The modulated signals are 📝perpendicular (orthogonal) and thus do not cause interference with each other. This makes OFDM superior to FHSS and DSSS in throughput and interference.
                - Orthogonal Frequency Division Multiplexing (OFDM) is a digital modulation technique used in telecommunications, particularly in wireless communication systems such as Wi-Fi, LTE, and digital television broadcasting. OFDM is designed to address issues related to multipath interference, frequency-selective fading, and spectral efficiency.
- ⚓**Wireless Attacks**:
    - 🔥Evil twin: attack works by manipulating a wireless client to connect to a malicious access point. Hackers do this by spoofing a legitimate Service Set Identifier (SSID) and Basic Service Set Identifier (BSSID) that the wireless client already trusts. When a client connects to the malicious access point, the hacker can see all network traffic between the client and web servers. This is a type of Man-In-The-Middle (MITM) attack.
    - 🔥Rogue AP: An unauthorized access point that has been added by a user or attacker on the company network is called a rogue access point.
    - 🔥DDOS: Deauthentication frames are defined in the IEEE 802.11 standard and are used to terminate a wireless connection. So, flooding the environment with frames like that would cause a Denial of Service (DoS) attack. Attackers flood the wireless network with traffic or send de-authentication packets to disconnect legitimate users. Legitimate users are unable to access the network or experience degraded performance.
    - 🔥Wireless Eavesdropping (Packet Sniffing): Intercepting and capturing data packets transmitted over wireless networks. Attackers can steal sensitive information like passwords and personal data.
    - 🔥Man-in-the-Middle (MITM) Attacks: The attacker intercepts communications between two wireless devices and can modify or steal the data being transmitted. Sensitive data can be stolen, or malicious commands can be injected into the communication.
    - 🔥Replay Attacks: Capturing and replaying wireless communication packets to trick the network or device into allowing unauthorized access. Attackers can gain access or repeat transactions without legitimate authentication.
    - 🔥WEP/WPA Cracking: Exploiting vulnerabilities in older encryption standards like WEP and weak configurations in WPA (e.g., WPA2 using weak passwords). Once cracked, attackers can gain unauthorized access to the wireless network.
    - 🔥Bluesnarfing: 📝Unauthorized access to a Bluetooth-enabled device to steal data. Bluesnarfing allows hackers to connect to a Bluetooth device without the user's knowledge and extract information from the device.
    - 🔥Bluebugging: Gaining full remote 📝control of a device over Bluetooth. Confidential data can be stolen, or devices can be hijacked for further exploitation.
    - 🔥Bluejacking: is a type of Bluetooth-based attack in which an attacker sends 📝unsolicited messages to nearby Bluetooth-enabled devices, typically in public places. The attacker exploits Bluetooth's discoverability mode to send messages or contact details to other devices without proper authentication. It's a relatively harmless attack compared to other forms of Bluetooth exploits, as it typically involves sending messages rather than gaining access to the device or stealing data. However, it can be used to annoy or distract users. The recipient has to be within a certain range (typically 10 meters or less), and Bluetooth must be turned on and set to "discoverable" mode for this attack to work.
    - 🔥Jamming Attacks: Attackers use radio frequency (RF) interference to disrupt wireless communications. Can cause wireless networks to be unusable, interrupting services and communications.
    - 🔥War Driving: Scanning for wireless networks while moving around a physical location (often in a car) to find unsecured or vulnerable networks. Attackers can find and exploit unprotected or poorly configured networks.
    - 🔥Wireless Phishing (Wi-Phishing): Using rogue APs or social engineering techniques to trick users into providing sensitive information, often via fake captive portals. Credentials, payment data, and personal information can be stolen.
    - 🔥MAC Address Spoofing: An attacker impersonates a legitimate device’s MAC address to bypass network security controls. Allows unauthorized devices to access restricted networks or bypass network filters.
    - 🔥De-authentication/Disassociation Attacks: Sending fake de-authentication or disassociation frames to wireless clients to disconnect them from the network. Disrupts wireless connections and could be used as a precursor to other attacks, like man-in-the-middle.
    - 🔥Krack Attack (Key Reinstallation Attack): A vulnerability in WPA2 protocol that allows an attacker to decrypt or manipulate traffic in a Wi-Fi network by manipulating the handshake process. Allows attackers to intercept data, inject malicious traffic, or potentially decrypt sensitive information.
- 📙**2.4 GHz Wireless Channels:** The 2.4 GHz band typically has 11 channels in the United States (14 in some other countries), but due to overlap, only 3 of these channels (1, 6, and 11) are non-overlapping and commonly used to avoid interference.The Federal Communications Commission (FCC) has allocated 11 channels that may be used on the 2.4 GHz spectrum. Channels overlap and, if used incorrectly, can create interference. It is recommended to only use channels 1, 6, and 11.
    - More prone to interference because it's a crowded band shared with many devices, like microwaves, cordless phones, and other wireless networks.
    - Better range and penetration through walls and obstacles, making it suitable for larger areas.
    - Typically slower due to more interference and less available bandwidth.
    - Better for coverage in larger spaces or environments with many obstacles.
        - Disabling the 2.4GHz radios on the WiFi access points (APs) is the most cost-efficient way to improve network performance if the neighboring offices are not using the same frequency band. The 2.4GHz band is often more crowded and subject to interference from other devices. By disabling it, you can reduce interference and congestion, potentially improving performance for devices using the 5GHz band. 
- 📙**5 GHz Wireless Channels:** The 5 GHz band offers significantly more channels—up to 25 or more non-overlapping channels, depending on the region and the specific portion of the 5 GHz spectrum being used. In the U.S., for instance, there are 24 non-overlapping channels available.
    - Less interference and congestion due to more available channels and less crowded spectrum.
    - Shorter range and poorer penetration through walls, but offers faster speeds over shorter distances.
    - Typically faster due to wider channels and less interference.
    - Better for high-speed connections in smaller areas with less interference.
        - 📘**Wired Equivalent Privacy (WEP)**:
            - WEP is defined by the original IEEE 802.11 standard
            - WEP uses a predefined shared Rivest Cipher 4 📝(RC4) secret key for both authentication (SKA) and encryption
            - Shared key is static
            - The Wired Equivalent Privacy (WEP) protocol defined in IEEE 802.11 uses a shared key between clients and access points. The access point sends the client a random value and the client encrypts this value using its shared key and sends it back to the access point. The access point decrypts the value with the shared key, and if the decrypted value is equal to the original, the access point authenticates the client. WEP is no longer considered secure and has many security flaws.
            - The shared key may appear to be a password that the user must type in, but it is actually the key. 
            - WEP is weak from RC4 flaws 
        - 📘**Wi-Fi Protected Access (WPA)**: WPA uses the Temporal Key Integrity Protocol (TKIP) to generate a unique key for each frame transmitted. TKIP-generated keys are fed into the RC4 encryption algorithm to encrypt traffic. This combination of TKIP and RC4 improves the original standard Wired Equivalent Privacy (WEP).
            - Temporal Key Integrity Protocol 📝(TKIP) is a combination of 📝RC4 and the hashing algorithm of Michael that is used in Wireless Encryption Protocol (WEP).
            - When RC4 is used with the WPA protocol and Temporal Key Integrity Protocol (TKIP), the key changes for every frame transmitted. 
        - 📘**Wi-Fi Protected Access II (WPA2)**:
            - IEEE 802.11i WPA2 replaced WEP and WPA.
            - WPA2 enterprise uses 📝RADIUS authentication for users rather than a preshared key. This means a password attack is more likely to fail as password attempts for a given user may result in account lockout.
            - TKIP was introduced with the original version of WPA and was replaced with the 📝AES-based CCMP in WPA2
            - EAP is an authentication framework used in wireless networks to provide various methods for authenticating users. In WPA2, 📝EAP is often used in conjunction with the Advanced Encryption Standard (AES) to provide strong encryption and secure authentication for wireless communications.
            - Uses AES-CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol)
            - WPA2 uses 📝AES to encrypt traffic, however, it can be downgraded to use TKIP and RC4 to maintain compatibility with older devices.
        - Frequency table:
            
        | Amendment | Wi-Fi Alliance | Speed | Frequency |
        |-----|---------------| -------------------|------------|
        | 802.11    |   --   | 2 Mbps |2.4 GHz               |
        | 802.11a 🚒  |  Wi-Fi 2    | 🧯54 Mbps |🔥5 GHz                |
        | 802.11b   |  Wi-Fi 1    | 11 Mbps |2.4 GHz (DSSS)             |
        | 802.11g 🚒  |  Wi-Fi 3    | 🧯54 Mbps |🔥2.4 GHz              |
        | 802.11n   |  Wi-Fi 4    | 200+ Mbps |2.4GHz or 5 GHz    |
        | 802.11ac   | Wi-Fi 5    |1-5.9Gbps  |5 GHz              |
        | 802.11ax   | Wi-Fi 6/Wi-Fi 6E     |9.5 Gbps |1-5(6)GHz  |

        - 📘**Wi-Fi Protected Access 3 (WPA3)**: WPA3-ENT uses 192-bit AES CCMP encryption, and WPA3-PER remains at 128-bit AES CCMP.
             - Wi-Fi Protected Access 3 (WPA3) is the latest secure protocol, providing enhanced Wi-Fi security with the inclusion of the Diffie-Hellman key exchange and a secret session key. This process is also known as the Simultaneous Authentication of Equals (SAE).
             - WPA3 supports ENT (Enterprise Wi-Fi authentication, aka IEEE 802.1X) and 📝SAE authentication. Simultaneous authentication of equals (SAE) still uses a password, but it no longer encrypts and sends that password across the connection to perform authentication. Instead, SAE performs a zero-knowledge proof process known as 📝Dragonfly Key Exchange, which is itself a derivative of 📝Diffie–Hellman.
             - WPA3-PER replaces the preshared key authentication with Simultaneous Authentication of Equals (SAE).
             - WPA3's new SAE (simultaneous authentication of equals) mode improves on WPA2's PSK mode by allowing for secure authentication between clients and the wireless network without enterprise user accounts.
             - Simultaneous Authentication of Equals (SAE) was introduced with WPA3 as an alternative to preshared keys.
             - SAE performs a zero-knowledge proof process known as Dragonfly Key Exchange, which is itself a derivative of Diffie–Hellman.
             - However, consider using a 📝captive portal if the end goal is to gather data from customers such as email address, but customer data will not be encrypted. 
- 📗**802.1X/EAP**: WPA, WPA2, and WPA3 support the enterprise (ENT) authentication known as 802.1X/EAP, a standard port-based network access control.
         - ⚒️**802.1X** is an Institute of Electrical and Electronics Engineers (IEEE) standard that requires network devices to be authenticated before accessing network resources. 802.1X can be used to dynamically assign a device to the correct Virtual Local Area Network (VLAN). It can be implemented on wired and wireless networks. Administrators can implement 802.1X using RADIUS as the centralized authentication protocol. It also uses Extensible Authentication Protocol (EAP) as a local protocol to transmit the authentication information to the access point when used in wireless networks.
     - Through the use of 802.1X, other solutions such as Remote Authentication Dial-In User Service (RADIUS), Terminal Access Controller Access Control System (TACACS), certificates, smartcards, token devices, and biometrics can be integrated into wireless networks, providing techniques for both mutual and multifactor authentication.
     - 802.1x is frequently used with wireless networks but can also be used for wired networks. 802.1x has three roles: Supplicant, Authenticator, and Authentication server.
         - 🎈Supplicant is the device attempting to authenticate.
         - 🎈Authenticator is either the switch or wireless access point the supplicant is connected to.
         - 🎈Authentication server is the server that informs the authenticator if the supplicant should or should not be authorized.
- 📗**Extensible Authentication Protocol (EAP)**: is not a specific mechanism of authentication; rather it is an authentication 📝framework. Effectively, EAP allows for new authentication technologies to be compatible with existing wireless or point-to-point connection technologies. More than 40 EAP methods have been defined, including ✏️LEAP, ✏️PEAP, ✏️EAP-­SIM, ✏️EAP-­FAST, ✏️EAP-­MD5, ✏️EAP-­POTP, ✏️EAP-­TLS, and ✏️EAP-­TTLS.
    - Extensible Authentication Protocol (EAP) is a 📝framework for authentication rather than a standalone authentication protocol. EAP is used to negotiate the best authentication method that both a client and server agree on. The authentication types that it can carry include smartcards, tokens, and biometrics, as well as the traditional password.
    - EAP is used to negotiate the best authentication method that both a client and server agree on.
- 📗**LEAP**: Lightweight Extensible Authentication Protocol (LEAP) is a 📝Cisco proprietary alternative to TKIP for WPA.
     - This was developed to address deficiencies in TKIP before the 802.11i/WPA2 system was ratified as a standard.
     - An attack tool known as asleap was released in 2004 that could exploit LEAP;
     - use of EAP-TLS as an alternative is recommended, but if LEAP is used, a complex password is strongly recommended.
- 📗**PEAP**:Protected Extensible Authentication Protocol (PEAP) encapsulates EAP methods within a 📝TLS tunnel that provides authentication and potentially encryption.
     - Since EAP was originally designed for use over physically isolated channels and hence assumed secured pathways, EAP is usually not encrypted.
     - So PEAP can provide encryption for EAP methods.
     - Protected Extensible Authentication Protocol (PEAP) is similar to EAP but is 📝encapsulated in a Transport Layer Security (TLS) session using a server-side certificate.
- 📗**CHAP**:Challenge-Handshake Authentication Protocol, or CHAP, is used by PPP servers to authenticate remote clients.
     - It encrypts both the username and password and performs periodic reauthentication while connected using techniques to prevent replay attacks.
     - CHAP was the next protocol after PAP, but it also only carries passwords
     - CHAP is one of the authentication protocols used over Point-to-Point Protocol (PPP) links. CHAP 📝hashes 📝usernames and 📝passwords to prevent them from being transmitted in clear text. It performs authentication using a challenge-response that is resistant to replay attacks.
     -  It was an improvement from the previous Password Authentication Protocol (PAP) which sent the password in clear text. CHAP hashes the password in combination with a challenge number called a Number used ONCE 📝(NONCE).
- 📗**Password Authentication Protocol (PAP)**: PAP transmits usernames and passwords in 📝cleartext.
     - It offers no form of encryption;
     - it simply provides a means to transport the logon credentials from the client to the authentication server.
     - Also used by PPP servers.
     - PAP is one of the oldest authentication protocols that transports a password and only a password.
- 📗**Zigbee**: IoT equipment communications concept based on Bluetooth. It requires close proximity of devices and communications are encrypted.
     - Low power/low throughput
     - Requires close proximity
     - Encrypted using 128-bit AES symmetric algorithm
     - Uses AES to prtect traffic
- 📗**Satellite***: primarily uses radio waves between terrestrial locations and an orbiting artificial satellite
     - Supports telephone, tv, radio, internet, military communications
     - 3 primary orbits:
          - 🎤LEO: low Earth orbit (160-2k km)
               - have stronger signals
               - multiple devices needed to maintain coverage (e.g. Starlink)
               - LEO offers high-speed communications with minimal latency when compared to other satellite offerings.
          - 🎤MEO: medium Earth orbit (2k-35768 km)
               - above a terrestrial location longer than LEO
               - higher orbit, additional delay/weaker signal
          - 🎤GEO: geostationary orbit (35768 km)
               - maintain a fixed position above a terrestrial location, and ground stations can use fixed antennas
               - larger transmission footprint than MEO, but higher latency
- **Network Performance Metrics**:
  -  🍎Bandwidth: The maximum amount of data or capacity that can be transmitted over a network in a given amount of time. Theoretical maximum transfer rate. Key: A highway with many lanes can carry more cars than a highway with only one lane.
  -  🍎Throughput: The actual amount of data successfully transferred over the network in a given amount of time. Actual data transfer rate considering factors like latency, packet loss and congestion. Key: How many cars actually pass through a toll booth per hour, not just how many cars the highway can theoretically handle.
  -  🍎Latency: The time it takes for a data packet to travel from the source to the destination. It has an inverse relationship to throughput. Latency is a delay in the delivery of packets from their source to their destination.
  -  🍎Jitter: The variation in time delay between data packets arriving. Affects QOS for real-time applications. Key: If some cars on a highway arrive faster than others even though they left at the same time. Jitter is a variation in the latency for different packets.
  -  🍎Packet Loss: Packet loss is the disappearance of packets in transit that requires retransmission.
  -  🍎Signal to Noise Ratio (SNR): A measure of the signal strength relative to background noise. Commonly used in wireless communications. Key: How clearly you can hear someone speaking in a noisy room; higher SNR means a clearer signal and less interferance.
- 4.1.8 **Cellular networks** (e.g. 4G, 5G)
    - A cellular network or a wireless network is the primary communications technology used by many mobile devices
    - Cells are primary transceiver (cell site/tower)
    - Cellular networks have the same issues that any public network does.
    - The National Institute of Standards and Technology (NIST) Special Publication (SP) 800-187 is security for Long Term Evolution (LTE) cellular technology.
    - Generally encrypted between mobile device and transmission tower; plaintext over wire; use encryption like TLS/VPN
    - ❄️**4G**
        - 4G allows for mobile devices to achieve 📝100 Mbps, and stationary devices can reach 📝1 Gbps
        - LTE and WiMAX are common 4G transmission systems
        - **WiMAX**: Broadband Wireless Access IEEE 802.16 is a well-known example of wireless broadband; WiMAX can potentially deliver data rates of > 30 Mbps
        - 4G has been in use since the early 2000s and most cellular devices support 4G communications. 
    - ❄️**5G**
        - 5G uses higher frequencies than previous tech, allowing for higher transmission speeds — up to 10 Gbps, but at reduced distances
        - 5G supports up to 10 Gbps
        - Enhanced subscriber identity protection
        - Mutual authentication capabilities
        - 5G coverage is the most limited since it is the latest technology and still not universally deployed
        - 5G tower covers less area than a 4G tower.
        - Orgs need to enforce security requirements on 5G
        - 5G is the latest mobile service technology that is available for use on some mobile phones, tablets, and other equipment.
        - Many ICS, IoT, and specialty devices may have embedded 5G capabilities.
    - Security issues with wireless:
        - provider network (voice or data) is not necessarily secure
        - your cell phone can be intercepted
        - provider's towers can be simulated to conduct man-in-the-middle/on-path attack
        - using cell connectivity to access the internet or your office network creates a potential bridge, provider attackers with another avenue
    -  Cellular services, such as 4G and 5G, raise numerous security and operational concerns. Although cellular service is encrypted from device to tower, there is a risk of being fooled by a false or rogue tower. A rogue tower could offer only plaintext connections, but even if it supported encrypted transactions, the encryption only applies to the radio transmissions between the device and the tower. Once the communication is on the tower, it will be decrypted, allowing for eavesdropping and content manipulation. Even without a rogue tower, eavesdropping can occur across the cellular carrier’s interior network as well as across the internet, unless a VPN link is established between the remote mobile device and the network of the organization.
    -  Being able to establish a connection can be unreliable as 3G, 4G, and 5G coverage is not 100 percent available everywhere.
- **Traffic FLows**:
     - 📘East-West Traffic: Data traffic that moves laterally within a data center, between servers or virtual machines. Involves trusted nodes and networks. Traffic remains withing the internal network or cloud. Access controls, micro-segmentation and isolations policies are used here for security.
     - 📘North-South Traffic: Data traffic that moves between a data center and external networks or clients. Traffic moves to/from endpoints on internal network to nodes on the public cloud/internet. Involves untrusted nodes. This brings security concerns like data comprise, DDoS attacks, inadequate authentication. 

- 4.1.9 Content Distribution Networks (CDN)
    - 🔴**Content Distribution Network (CDN)**: a collection of resource services deployed in numerous data centers across the internet in order to provide low latency, high performance, and high availability of the hosted content
        - CDNs provide multimedia performance quality through the concept of distributed data hosts, geographically distributed, closer to groups of customers
        - It is true that a CDN is able to maintain customer demand levels of multimedia performance quality,
        - avoids straining individual servers, and stores data close to customers,
        - and that a client-based CDN (aka P2P) can support high-speed file exchange (i.e., BitTorrent)
        - Provides geographic and logical load balancing; lower-latency and higher-quality throughput
        - A Content Distribution Network (CDN) is a collection of different content that a website may display, distributed across geographical regions. A CDN allows website creators to improve performance by providing a website’s content in a geographical region closest to the client. This reduces latency and download times.
    - Client-based CDN is often referred to as P2P (peer-to-peer)
    - BitTorrent is an example of a peer-to-peer (P2P) content delivery network. It is commonly used for legitimate purposes to distribute large files like Linux ISOs and other freely distributed software packages and files in addition to its less legitimate uses. CloudFlare, CloudFront, and Akamai's Edge are all hosted CDNs.
    -Thus a content delivery network, or CDN, run by a major provider can handle large-scale DDoS attacks more easily than local server implementations.

- 4.1.12 🔴**Edge Networks**
    - Distributed networks that bring compute and storage resources physically closer to end users and devices on the edge of the network.
    - **Ingress/Egress**: Entry point for traffic entering an edge network, usually from an end user device or an external network. Important for security monitoring and traffic shaping.
    - **Peering**: Direct interconnection between edge network locations to allow traffic exchange without travelling through a central hub. reduces latency and bottle necks which are problems in a hub-and-spoke topology. Peering allows you to connect directly to a Cloud Service provider's network at a peering location where they provide edge facilities. This can reduce ingress/egress costs as well as provide direct paths to their networks and services. Peering can be either public peering, a connection through an Internet Exchange Point via a network connection, or private peering done directly with another entity in a colocation facility. 
    - **Caching**: Caching popular contents like video, audio and web pages. Provides better user experience in SaaS subscriber scenarios. eg CDNs.
    - **Compute**: Granular compute functions, containarized, to provide low-latency processing near end users and devices. Also known as Edge Computing. Edge computing is a technology that processes data near the source of data generation, such as IoT devices or local servers, rather than sending it to a central data center or cloud for processing.
    - **Storage**: Multiple edge locations to reduce latency for accessing data and updating data. E.g file servers that are synchronized across location like DFS.
- 🛠️**Grid computing** is a form of distributed computing where multiple computers work together to solve complex problems or process large amounts of data. In simple terms, it's like combining the power of many computers to achieve a task more efficiently than a single computer could alone.
     - In many grid computing implementations, grid members can access the contents of the distributed work segments or divisions.
     - Grid computing over the internet is not usually the best platform for sensitive operations.
     - Grid computing is able to handle and compensate for latency of communications, duplicate work, and capacity fluctuation.
     - Grid computing involves Parallel processing where nodes may join and leave at will
     - Grid computing is similar to clustering, however, individual nodes do not trust each other and can join and leave at will.
     - Grid computing is generally distributed across hundreds and thousands of nodes across the internet. Nodes check in when they have available system resources and contribute to grid processing.
     - Grid computing is used for Bitcoin mining, the creation of rainbow tables, and predicting weather patterns, among many other things.
       
- 4.1.17 🔴Virtual Private Cloud (VPC)
    - Virtual networks, public and private subnets, segmentation and API inspection and integration are important elements of cloud security.
    - VPC is a virtual network that consists of cloud resources, where the VM of one company is isolated from the resources of another company.
    - A VPC, or virtual private cloud, is the environment many organizations operate inside of public clouds. They provide on-demand access to configurable, shared resources operated by the cloud provider inside of their isolated boundaries.
    - Seperate VPCs can be isolated using public or private networks or segmentation. This concept exists in all major public clouds. It is refered to as VPC in AWS & Google Cloud Platforms. It is referred to as Virtual Networks (VNET) in Azure.
    - Virtual private clouds (VPCs) run on cloud-hosted infrastructure providing a secure, isolated pool of resources to be used by organizations to meet their needs.
 
- 4.1.18 🔴Monitoring and Management
    - **Network Observability:** Invloves collecting data and gaining visibility into the status and performance of network components and traffic flows. Supports issue identificaton and troubleshooting. Observability focuses on the ability to see how an entire system, service, or environment is performing and behaving based on its external outputs. That means that telemetry data—information about what components are doing—is critical and will be gathered using logs, metrics, and real-time analysis. This means that centralizing and aggregating data, enabling alerts for critical errors, and implementing logging using standardized formats are all common practices.
        - 💻Real-time fault monitoring for network devices and connections often relies on ☑️SNMP and ☑️ICMP-based monitoring capabilities.  
    - **Traffic FLow/Traffic Shapping:** Managing and controlling the volume and priorities of different types of traffic. E,g QOS (priority to certain traffic such as real-time traffic), rate limitting (example API limiting to number of API requests that can be made by a single user in a specific period of time), throttling.
    - **Capacity Management:** Tracking network utilization and planning capcity expansion to meet future demands.
    - **Fault Detection and Handling:** Discovering, diagnosing and responding to problems like failed devices, connectivity losses, performance slow downs. includes alerting and automatic failover. Feedback loops are also important, allowing administrators and others to take action when problems or issues are detected.
        - 💻diagnostic and analysis tasks often relies on ☑️Netflow and ☑️syslog.

[4.2](#4.2) Secure network components (OSG-9 Chpt 11)
The components of a network make up the backbone of the logical infrastructure for an organization; these components are often critical to day-to-day operations, and an outage or security issue can be very costly
- 4.2.1 Operation of hardware (e.g. redundant, power, warranty, support)
    - Modems provide modulation/demodulation of binary data into analog signals for transmission; modems are a type of Channel Service Unit/Data Service Unit (CSU/DSU) typically used for converting analog signals into digital;  the CSU handles communication to the provider network, the DSU handles communication with the internal digital equipment (in most cases, a router)
        - modems typically operate at Layer 2 
        - routers operate at Layer 3, and make the connection from a modem available to multiple devices in a network, including switches, access points and endpoint devices 
        - switches are typically connected to a router to enable multiple devices to use the connection
        - switches help provide internal connectivity, as well as create separate broadcast domains when configured with VLANs 
        - switches typically operate at Layer 2 of the OSI model, but many switches can operate at both Layer 2 and Layer 3
        - access points can be configured in the network topology to provide wireless access using one of the protocols and encryption algorithms
    - Redundant power: most home equipment use a single power supply, if that supply fails, the device loses power
        - redundant power is typically used with components such as servers, routers, and firewalls
        - redundant power is usually paired with other types of redundancies to provide high availability

- 4.2.2 🔴Transmission media
    - Transmission Media: comes in many forms, not just cables
        - includes wireless, LiFi, Bluetooth, Zigbee, satellites
        - most common cause of network failure (i.e. violations of availability) are cable failures or misconfigurations
        - wired transmission media can typically be described in three categories: coaxial, Ethernet, fiber
        - 🍖Coaxial is typically used with cable modem installations to provide connectivity to an ISP, and requires a modem to convert the analog signals to digital
            - fairly resistent to EMI
            - longer lengths than twisted pair
            - requires segment terminators
            - two main types:
                - 🔨**thinnet (10Base2)**: used to connect systems to backbond trunks of thicknet cabling (185m, 10Mbps)
                - 🔨**thicknet (10Base5)**: can span 500 meters and provide up to 10Mbps. 10Base5 and coaxial cables have a low susceptibility to EMI, but they are not completely resistant.
        - 🍖Ethernet (Copper) can be used to describe many mediums, it is typically associated with Category 5/6 unshielded twisted-pair (UTP) or shielded twisted pair (STP), and can be plenum-rated
            - Unshielded Twisted Pair (UTP) is susceptible to Electromagnetic Interference (EMI) and should not be used in environments known to have large amounts of EMI.
            - Shielded Twisted Pair (STP) is protected with a thin foil that helps protect against EMI. It does not absolutely contain or reflect electrical signals, but it does help.  
        - 📝A repeater, switch, or concentrator can be used to amplify signals, ensuring that the 100-meter (328 Feet) distance limitation of 1000BaseT or CAT 6 is not an issue.
        -  STP cable is limited to 155 Mbps and 100 meters (328 Feet)
        - 🍖fiber typically comes in two options: single-mode or multi-mode
            - 🥑Single-mode is typically used for long-distance communication, over several kilometers or miles
            - 🥑Multi-mode fiber is typically used for faster transmission, but with a distance limit depending on the desired speed
            - Fiber is most often used in the datacenter for backend components
            - it is not affected by electromagnetic interference (EMI)

        | Medium | Speed/Distance | Standard |
        |----------|------------|--------|
        | Cat 3 or higher    |   10 Mbps Ethernet over twisted pair copper cables   |    10Base-T    |
        | Multi-mode fiber (10Base-FL is the common variant)   |  10 Mbps Ethernet over fiber optic cables.  |   10Base-F     |
        | Cat5 or higher twisted pair cables.   |  100 Mbps Ethernet over twisted pair cables. Up to 100 meters (328 feet |  100Base-TX      |
        | Multi-mode fiber.   |   100 Mbps Ethernet over fiber optic cables Up to 2 kilometers  |      100Base-FX  |
        | Cat5e or higher twisted pair cables  |  1 Gbps Ethernet over twisted pair cables. Up to 100 meters |   1000Base-T (1 Gbps)     |
        | Multi-mode fiber.  |   1 Gbps Ethernet over short-wavelength fiber optic cables Up to 550 meters (1804 feet) on OM2 fiber  |    1000Base-SX    |
        | Single-mode fiber.   |   1 Gbps Ethernet over long-wavelength fiber optic cables Up to 10 kilometers  |   1000Base-LX     |
        | Shielded twisted pair cables (STP)  |  1 Gbps Ethernet over very short-distance copper cables Up to 25 meters |   1000Base-CX     |
        | Single-mode fiber   |   An extended range version of 1000Base-LX. Up to 70 kilometers |    1000Base-ZX    |


-Common  fiber optic connectors and their uses:
| Connector    | Uses      |Design               |
|--------|---------------| -------------------|
| SC (Subscriber Connector)  | single-mode and multi-mode        | square-shaped, push-pull connector |
| LC (Lucent Connector)  | single-mode and multi-mode (high-density applications)       | small, compact connector with a latch |
| ST (Straight Tip)  | multi-mode fiber (legacy systems)       | bayonet-style coupling mechanism |
| MTP/MPO (Multi-Fiber Push-On/Pull-Off) |  multiple fibers (e.g., 12, 24, 48 fibers) high-density and high-bandwidth applications.      | multiple fibers are terminated in a single connector.|
| FC (Ferrule Connector)  | single-mode fiber (high precision and minimal signal loss)      | screw-on mechanism |
| LC/APC and SC/APC | single-mode fiber applications where low signal loss and high performance are critical     | Angled Physical Contact) connectors are designed to reduce back-reflection.|
| LC/UPC and SC/UPC  |  single-mode and multi-mode fibers,  low insertion/signal loss | polished UPC (Ultra Physical Contact) connectors .|

- 4.2.3 Network Access Control (NAC) devices
- Port security can refer to several concepts, including network access control (NAC), Transport layer ports, and RJ-­45 jack ports. Port security is generally a MAC address–based security feature that can only restrict which systems or devices can connect to a given port. 📝NAC requires authentication before devices can communicate on the network. 📝Transport-­layer port security involves using firewalls to grant or deny communications to TCP and UDP ports. 📝physical control of all connection points. RJ-­45 jacks should be managed so that unused ports are disabled and that when a cable is disconnected, the port is disabled. This approach prevents the connection of unauthorized devices, cam table flooding etc.
    - **Network Access Control (NAC)**: the concept of controlling access to an environment through strict adherence to and enforcement of security policy
    - NAC is meant to be an automated detection and response system that can react in real time, ensuring all monitored systems are patched/updated and have current security configurations, as well as keep unauthorized devices out of the network. 📝 Note that it cannot reduce social engineering threats.
    - Network Access Control (NAC) systems can be used to authenticate users and then validate their system's compliance with a security standard before they are allowed to connect to the network. Enforcing security profiles can help reduce zero-day attacks, making NAC a useful solution
    - NAC goals:
        - prevent/reduce known attacks directly (and zero-day attacks indirectly)
        - enforce security policy throughout the network
        - use identities to perform access control
        - detect/block rogue devices
    - NAC can be implemented with a preadmission or postadmission philosophy:
        - 🍮**pre-admission philosohpy**: requires a system to meet all current security requirements (such as patch application and malware scanner updates) before it is allowed to communicate with the network. A pre-admit, client-based NAC system will test systems before they are allowed on the network using a client that can determine more about a system than a clientless model can.
        - 🍮**post-admission philosophy**: allows and denies access based on user activity after connection, which is based on a predefined authorization matrix. It doesn't check the status of a machine before it connects.
    - ✴️Agentless NAC: An agentless NAC performs port scans, service queries, and vulnerability scans against networked systems to determine whether devices are authorized and baseline compliant. 
    - ✴️Agent-based NAC: installed on each management system, checks config files regularly, and can quarantine for non-compliance. Agent-based NACs can quarantine noncompliant devices and implement updates automatically.
        - 🍈Dissolvable: usually written in a web/mobile language and is executed on each local machine when the specific management web page is accessed (such as captive portal). A dissolvable NAC agent can be set to run once and then terminate.
        - 🍈Permanent: installed on the monitored system as a persistent background service
    - Just as you need to control physical access to equipment and wiring, you need to use logical controls to protect a network; there are a variety of devices that provide this type of protection, including:
        - 💥**Stateful and Stateless firewalls** can perform inspection of the network packets and use rules, signatures and patterns to determine whether the packet should be delivered. Circuit-level firewalls (aka circuit proxies) are used to establish communication sessions between trusted partners. In theory, they operate at the Session layer (layer 5) of the OSI model.
            - reasons for dropping a packet could include addresses that don’t exist on the network, ports or addresses that are blocked, or the content of the packet (e.g malicious packets blocked by admin policy)
            - ⚒️Tier 1 Firewall - One protected Zone e.g Internet 
            - ⚒️Tier 2 Firewall - Two Protected Zones e.g Internet and DMZ and so on.
        - IDP devices, which monitor the network for unusual network traffic and MAC or IP address spoofing, and then either alert on or actively stop this type of traffic
        - **Proxy/Reverse proxies:**
            - proxy servers can be used to proxy internet-bound traffic, instead of letting clients talk directly
            - Proxy servers can act to anonymize web requests by hiding their true source IP addresses and removing identifying information. 
            - reverse proxies are often deployed to a perimeter network; they proxy communication from the internet to an internal host, such as a web server
            - like a firewall, a reverse proxy can use rules and policies to block certain types of communication
- 4.2.4 Endpoint security
    - **Endpoint security**: each individual device must maintain local security
        - any weakness in a network, whether border, server, or client-based presents a risk to all elements of the org
        - client/Server model is distributed architecture, meaning that security must be addressed everywhere instead of at a single centralized host
        - processing, storage on clients and servers, network links, communication equipment all must be secured
        - clients must be subjected to policies that impose safeguards on their content and users’ activities including:
            - email
            - upload/download policies and screening
            - subject to robust access controls (e.g. MFA)
            - file encryption
            - screen savers
            - isolated processes for user/supervisor modes
            - local files should be backed up
            - protection domains/network segments
            - security awareness training
            - desktop env should be included in org DR
            - EDR/MDR should be considered
- 📂**Endpoint detection and response (EDR)** is a security mechanism that is an evolution of traditional antimalware products. EDR seeks to detect, record, evaluate, and respond to suspicious activities and events, which may be caused by problematic software or by valid and invalid users.
    - It is a natural extension of continuous monitoring, focusing on both the endpoint device itself and network communications reaching the local interface.
    - Some EDR solutions employ an on-­device analysis engine whereas others report events back to a central analysis server or to a cloud solution.
    - The goal of EDR is to detect abuses that are potentially more advanced than what can be detected by traditional antivirus or HIDSs, while optimizing the response time of incident response, discarding false positives, implementing blocking for advanced threats, and protecting against multiple threats occurring simulta neously and via various threat vectors.
    - The most common features of EDR systems are
        - 🔨analyzing endpoint memory, filesystem, and network activity for signs of malicious activity;
        - 🔨isolating possible malicious activity to contain the potential damage;
        - 🔨integrating with threat intelligence sources;
        - 🔨integrating with other incident response mechanisms
- 📂**Managed detection and response (MDR)**: focuses on threat detection and mediation but is not limited to the scope of endpoints. MDR is a service that attempts to monitor an IT environment in real-time to quickly detect and resolve threats. Often an MDR solution is a combination and integration of numerous technologies, including SIEM, network traffic analysis (NTA), EDR, and IDS.
- 📂**Endpoint protection platform (EPP)**: is a variation of EDR much like IPS is a variation of IDS. The focus on EPP is on four main security functions: predict, prevent, detect, and respond. Thus, EPP is the more active prevent and predict variation of the more passive EDR concept.
- 📂**Extended detection and response (XDR)**: components often include EDR, MDR, and EPP elements. Also, XDR is not solely focused on endpoints, but often includes NTA, NIDS, and NIPS functions as well. Managed security service provider (MSSP) can provide XDR solutions that are centrally controlled and managed.
- 📂**Managed security service provider MSSP**: solutions can be deployed fully on-premise, fully in the cloud, or as a hybrid structure, and can be overseen through a SOC which is itself local or remote. Typically, working with an MSSP to provide EDR, MDR, EPP, or XDR services can allow an organization to gain the benefits of these advanced security products and leverage the experience and expertise of the MSSP's staff of security management and response professionals. MDR combines antimalware capabilities with a managed service that reduces the burden on the IT team.

[4.3](#4.3) Implement secure communication channels according to design ((OSG-9 Chpt 12))
- Protocols that provide security services for application-specific communication channels are called secure communication protocols
- 4.3.1 Voice
    - 📗**Voice of Internet Protocol (VoIP)**: set of technologies that enables voice to be sent over a packet network
        - Multipoint Control Units (MCUs) are used in the ITU-TSS (or ITU-T) H.323 Voice Over Internet Protocol (VoIP) to allow conference calls to be created. The endpoint is the device plugged into the network and would be the VoIP phones or video conferencing systems, etc. H.323 gatekeepers are used to bridge the world of phone numbers and Internet Protocol (IP) addresses. H.323 devices are given an H.323 number (or alias). The gatekeeper has the ability to map that to the current IP address that the device has. This allows users to continue to use traditional phone numbers on the data network with VoIP. While both H.323 and SIP are used for VoIP, SIP is the preferred and more commonly used protocol today for voice and multimedia communications over IP networks due to its simplicity, flexibility, and widespread adoption.
    - As more orgs switch to VoIP, protocols like SIP become more common, and introducing additional management, either via dedicated voice VLANs, or by establishing quality of service (QoS) levels to ensure voice traffic priority
    - 🔥SIPS, the secure version of the Session Initialization Protocol for VoIP, adds TLS encryption to keep the session initialization process secure. 📝SIPS and 📝SRTP are appropriate for a VoIP environment, but are not generally a complete solution for a modern multimedia collaboration platform like Microsoft Teams, Zoom, or WebEx. (Modern collaboration platforms support TLS throughout their communications allowing clients to securely connect to the service and to encrypt communications.) Media packets can be encrypted by using the Secure Real-time Transport Protocol (SRTP). When SRTP is used, keys are generally exchanged by the SIP protocol.
         - 🍉SIP is primarily used for initiating, maintaining, and terminating real-time communication sessions. It handles the setup and teardown of calls or sessions.  It deals with the signaling aspect of a communication session, including establishing session parameters. It does not carry the actual media between each endpoint. SIP is what is used to set up the telephone ‘call’ by notifying each party how to reach each other. We still use phone numbers to place ‘calls’ on the data network even though the data network does not use phone numbers. It is necessary to resolve the address difference by linking the phone number to the IP (Internet Protocol) address. 
         - 🍉RTP is used for the actual transmission of media streams (like audio and video) once the session has been established. The media traffic is the actual audio broken up into packets. By default, media traffic uses the Real-Time Transport Protocol (RTP). If the media traffic needs to be encrypted, Secure Real-Time Transport Protocol (SRTP) can be used. After the SIP protocol has established a VoIP call, RTP is used to carry the audio data between the caller and receiver during the call. RTP settings are negotiated between endpoints by Session Initiation Protocol (SIP)
    - Web-based voice apps can be more difficult to manage, causing additional unplanned bandwidth consumption
    - In most cases, VoIP is only able to be encrypted between 📝compatible VoIP solutions, which is usually only those products provided by the same VoIP vendor, or VoIP endpoints that are from the same VoIP vendor or provider
    - VoIP is at risk for 📝caller ID spoofing, 📝vishing, call manager 📝software/firmware attacks, phone 📝hardware attacks, 📝DoS, 📝MitM/on-path attacks, 📝spoofing, and 📝switch hopping.
        - 💰DOS: Call managers and VoIP phones can be thought of as servers or appliances and embedded or network devices. That means that the most likely threats that they will face are denial-of-service (DoS) attacks and attacks against the host operating system.
        - 💰Phreaking is a specific type of attack in which various types of technology are used to circumvent the telephone system to make free long-distance calls by generating signaling tones, to alter the function of telephone service, to steal specialized services, or to cause service disruptions. A phreaker is an attacker who performs phreaking. Phreaking is incorrect because it targets a specific PBX and tries to manipulate menu options or make free calls. Phreaking also includes using blue boxes on public pay phones to trick the system into thinking that coins were added to place phone calls
        - 💰Vishing: Anyone who can receive a call, whether using a traditional PSTN landline, a PBX business line, a mobile phone, or a VoIP solution, can be the target of a VoIP-originated voice-based social engineering attack. This type of attack is known as voice-based phishing.
        - 💰Caller ID falsification: This refers to the practice of altering or spoofing the Caller ID information that is displayed to the recipient of a phone call. This can be used to disguise the caller's true identity or to mislead the recipient.
        - 💰War dialing: Calling a block of numbers looking for modems is called war dialing. War dialing is when an attacker calls each number in a given range. The attacker is looking for modems or fax machines to use for future attacks. When a modem or a fax machine answers a call, it makes unique tones to identify itself as a modem or fax machine. Modems are still used for backup communication or management communication for network equipment.
        - 💰Remote dialing:  It can refer to the use of remote dialing features to place calls from a distance, such as using a phone system's remote access codes. Remote dialing, especially if not properly secured, can be a vector for unauthorized access or abuse. Remote dialing is a VoIP PBX concern.
    -  Countermeasures must be deployed to protect against interception, eavesdropping, tapping, and other types of exploitation.
    -   Countermeasures to PBX fraud and abuse include Changing default passwords on PBX systems and it provides the most effective increase in security since PBX systems typically ⛔do not support encryption, although some VoIP PBX systems may support encryption in specific conditions.
    -   PBX and PSTN voice communications are vulnerable to 🔏interception, 🔏eavesdropping, 🔏tapping, and other exploitations. Often, physical security is required to maintain control over voice communications within the confines of your organization’s physical locations.
    -   Many PBX systems can be exploited by malicious individuals to avoid toll charges and hide their identity. Phreakers may be able to gain unauthorized access to personal voice mailboxes, redirect messages, block access, and redirect inbound and outbound calls.
    - 💙Countermeasures to PBX fraud include:
        - 🎶Consider replacing remote access or long-distance calling through the PBX with a credit card or calling card system.
        - 🎶Restrict dial-in and dial-out features to authorized individuals who require such functionality for their work tasks.
        - 🎶If you still have dial-in modems, use unpublished phone numbers that are outside the prefix block range of your voice numbers.
        - 🎶Protect administrative interfaces for the PBX.
        - 🎶Block or disable any unassigned access codes or accounts.
        - 🎶Define an acceptable use policy and train users on how to properly use the system.
        - 🎶Log and audit all activities on the PBX and review the audit trails for security and use violations.
        - 🎶Disable maintenance modems (i.e., remote access modems used by the vendor to remotely manage, update, and tune a deployed product) and/or any form of remote administrative access.
        - 🎶Change all default configurations, especially passwords and capabilities related to administrative or privileged features.
        - 🎶Block remote dialing.
        - 🎶Keep the system current with vendor/service provider updates.
        - 🎶Deploy direct inward system access (DISA) technologies to reduce PBX fraud by external parties. Direct inward system access (DISA), like any other security feature, must be properly installed, configured, and monitored in order to obtain the desired security improvement. DISA adds authentication requirements to all external connections to the PBX. 
    -  💙Securing VoIP communications often involves specific application of many common security concepts:
        - 🎽Use strong passwords and two-factor authentication.
        - 🎽Record call logs and inspect for unusual activity.
        - 🎽consider the use of a dedicated VLAN for VoIP devices to help separate them from other networked devices
        - 🎽Block international calling.
        - 🎽Outsource VoIP to a trusted SaaS.
        - 🎽Update VoIP equipment firmware.
        - 🎽Restrict physical access to VoIP-related networking equipment.
        - 🎽Train users on VoIP security best practices.
        - 🎽Prevent ghost or phantom calls on IP phones by blocking nonexistent or invalid-origin numbers.
        - 🎽Implement NIPS with VoIP evaluation features.

-📘 **Switching Technologies**

| Circuit Switching      | Packet Switching      | 
|------------------------|-----------------------|
| Constant traffic   | Bursty traffic   |
| Fixed known delays | Variable Delays |
| Connection oriented | Connectionless*️ |
| Sensitive to connection loss | Sensitive to data loss |
| Used primarily for voice | Used for any type of traffic |
| Outdated | Modern |

- 🍊Packet Switching: Packet switching protocols include the order protocol of X.25, Frame Relay, and Asynchronous Transfer Mode (ATM) which incur variable delays and are ideal for bursty traffic. It breaks down communication into small segments which are known as packets, frames, and cells, respectively. Each segment has its own header which includes source and destination address information.
    - Data is broken into smaller packets. Packets travel independently across the network, taking different paths. More efficient use of network resources. Common in data networks like the Internet.
        - Connectionless: No dedicated path is established between sender and receiver.
        - Variable delays: Packets can take different routes and may arrive out of order, causing delays.
        - Sensitive to data loss: Packets may be lost during transmission due to network congestion or errors.
    - Packet-switched networks include X.25, Frame Relay, Aysnchronous Transport Mode (ATM), and Multi-Protocol Label System (MPLS), for example. When data is sent across these networks, each packet takes its own path. This is also how ethernet networks operate. Data packets can, therefore, arrive out of order. If the packets (frames or cells) are numbered, they can be placed back in the correct order before delivery to the user. Some protocols will even request a retransmission for any missing packets (frames or cells). 
- 🍊Circuit Switch: A dedicated communication path (circuit) is established between two parties. The path remains reserved for the entire session. Less efficient but provides consistent communication quality. Common in traditional phone networks.
    - circuit switching is connection-oriented and less sensitive to data loss. Circuit Switching protocols establish a dedicated communication path for the duration of a session. Here are examples: PSTN (Public Switched Telephone Network), ISDN (Integrated Services Digital Network):
    - It provides digital transmission of voice and data over traditional circuit-switched telephone networks.
        - Voice networks were originally circuit-switched. This meant that when a call was placed from a phone on the traditional network (that can be found in homes that have had a phone number for a very long time) a connection was built and established across the network. Once the path of that connection was established, the telephone call would use that path until the phone call ended. This process happens every time a phone call is established on that type of network.
- ❄️**Virtual Circuit**: (also called a communication path) is a logical pathway or circuit created over a packet-switched network between two specific endpoints. Within packet-switching systems are two types of virtual circuits: Permanent Virtual Circuit (PVC) and Switched Virtual Circuit (SVC) refer to the logical connection that is built across many WAN technologies like X.25, frame relay, and Asynchronous Transfer Mode (ATM).
    - 🍊Permanent virtual circuits (PVCs): A PVC is like a dedicated leased line; the logical circuit 📝always exists and is waiting for the customer to send data. A PVC is a predefined virtual circuit that is always available. The virtual circuit may be closed down when not in use, but it can be instantly reopened whenever needed.  A PVC is like a two-way radio or walkie-talkie. Whenever communication is needed, you press the button and start talking; the radio reopens the predefined frequency automatically (that is, the virtual circuit). A PVC reestablishes a link using the same basic parameters or virtual pathway each time it connects.
        - A PVC is a logical connection that is planned across a network then set up and left in place. These connections have been seen in places like a phone to call a taxi from the taxi stand at the airport. All you have to do is pick up the phone and it then rings the phone on the other end of the connection so the taxi company will pick up the phone. 
    - 🍊Switched virtual circuits (SVCs): An SVC has to be 📝created each time it is needed using the best paths currently available before it can be used and then disassembled after the transmission is complete. An SVC is more like a shortwave or ham radio. You must tune the transmitter and receiver to a new frequency every time you want to communicate with someone.  SVCs use unique settings, parameters or virtual pathway each time.
        - An SVC is seen in the traditional Plain Old Telephone System (POTS) as well as 📝X.25, 📝frame relay, and 📝ATM. In the POTS network, if someone picks up a phone they then have to dial a phone number. That number is used to navigate the network, set up a connection, and ring the phone on the other end. Once the call is finished and someone hangs up their phone, the connection is dropped. 
    - In either type of virtual circuit, when a data packet enters point A of a virtual circuit connection, that packet is sent directly to point B or the other end of the virtual circuit. However, the actual path of one packet may be different from the path of another packet from the same transmission. In other words, multiple paths may exist between point A and point B as the ends of the virtual circuit, but any packet entering at point A will end up at point B.
- 📘**WAN Technologies**
    - 🟢**Dedicated line (also called a leased line or point-to-point link)** is one that is continually reserved for use by a specific customer. A dedicated line is always on and waiting for traffic to be transmitted over it. The link between the customer’s LAN and the dedicated WAN link is always open and established. A dedicated line connects two specific endpoints and only those two endpoints. This type of connection is often used between multiple business locations, so they can effectively communicate as a single entity.
     - There have been numerous types of dedicated lines over the years, ranging from the T1 (telephone line 1 with 1.54 Mbps capacity) to T3 or DS3 (Digital Service 3 with 44.7 Mbps capacity). Other options included X.25, Asynchronous Transfer Mode (ATM), and Frame Relay. These technologies have mostly been replaced by fiber optic–based solutions.
     - For long-term connections like backhaul networks, a point-to-point VPN that is connected at all times is the most common choice to ensure all traffic is secured. 
    - 🟢**Nondedicated line** is one that requires a connection to be established before data transmission can occur. A nondedicated line can be used to connect with any remote system that uses the same type of nondedicated line. Standard classic modems and DSL modems are examples of nondedicated lines. Digital subscriber line (DSL) is a technology that exploits the upgraded telephone network to grant consumers speeds from 144 Kbps to 20 Mbps (or more). There are numerous formats of DSL, such as ADSL, xDSL, CDSL, HDSL, SDSL, RASDSL, IDSL, and VDSL. SoGEA is intended for general broadband access. It is more similar to traditional ADSL or FTTC (Fibre to the Cabinet) services in that it shares bandwidth with other users on the same network. Each format varies as to the specific downstream and upstream bandwidth provided.
    - 🟢**Cable TV–based internet service** does not fit well into either the dedicated or the nondedicated classification. Cable internet is an always-on system, but not between two client locations. Instead, it is a link from your premises to an internet gateway. Thus, it can be labeled as a point-to-multipoint connection. 
    - 🟢**X.25** is a 📝packet-switched technology. It was one of the earlier protocols for Wide Area Networks (WANs) and is used for transmitting data across Public Data Networks (PDNs). Packet switching breaks data into smaller units (packets), which are then transmitted individually and can take different paths to reach the destination.
    - 🟢**ATM** Asynchronous Transfer Mode (ATM) is a 📝cell-switching technology. It is a high-speed networking technology designed to support the simultaneous transmission of various types of traffic, such as voice, video, and data, over the same network.
        - Unlike traditional packet-switched networks (like IP networks) that use variable-length packets, ATM uses fixed-length cells. Each ATM cell is 53 bytes in size, with 5 bytes allocated for the header and 48 bytes for the payload.
        - cell switching is used in technologies like Asynchronous Transfer Mode (ATM), where data is transmitted in fixed-size cells. It fragments communications into fixed-length 53-byte cells. The use of fixed-length cells allows ATMs to be very efficient and offer a guaranteed bandwidth.
        - ATM is capable of multiplexing, meaning it can combine multiple data streams into a single transmission.
        - ATM is a connection-oriented protocol, meaning that a virtual circuit (a logical connection) is established between the sender and receiver before data transmission begins.
    - 🟢**Frame Relay** Frame Relay is a type of 📝packet-switched network, which means it breaks down data into packets, called "frames," that are then transmitted across the network. Each frame is independently routed based on its destination address. Frame Relay uses a connection-oriented approach. It establishes a logical connection called a Permanent Virtual Circuit (PVC) between endpoints before any data transmission occurs. PVCs are pre-configured paths through the network, which remain established as long as the connection exists, even when no data is being transmitted.
        - Frame Relay operates primarily at the Data Link Layer 📝(Layer 2) of the OSI model. It encapsulates data inside a frame with a header that contains addressing and control information.
        - Unlike technologies that use fixed-length cells (like ATM), Frame Relay uses variable-length frames, which allows it to handle a wider range of traffic types and makes it more flexible.
        - Frame relay uses virtual circuits and a Data Link Connection Identifier (DLCI) address to connect routers
        - Frame Relay was replaced mostly by Asynchronous Transfer Mode (ATM) which was then mostly replaced by Multi-Protocol Label Switching (MPLS).
        - It uses packet-switching technology to connect different Wide Area Networking (WAN) connections together. Frame relay uses virtual circuits and Data Link Connection Identifier (DLCI) addresses to connect routers.
        - 🛎️Data Terminal Equipment (DTE) is a term for the interface a 📝customer will connect to when using older serial-based Wide Area Network (WAN) connections. This is common in frame relay and Asynchronous Transfer Mode (ATM) connections. In a Frame Relay network, the DTE is typically a router, computer, or terminal that connects to the network. The DTE sends data to and receives data from the network.
        - 🛎️The Data Circuit-terminating Equipment (DCE) end connects to the provider.  DCE is the device that provides the physical connection to the Frame Relay network. It is typically owned and operated by the 📝network service provider. Examples of DCE devices include modems, CSU/DSUs (Channel Service Unit/Data Service Unit), or network termination equipment. The DCE is responsible for establishing, maintaining, and terminating the physical connection to the network. It also provides clocking signals to the DTE to synchronize data transmission. The DCE connects the DTE to the Frame Relay network, acting as an intermediary that passes data between the DTE and the network.
   - 🟢**Multiprotocol Label Switching MPLS**: MPLS is a technique used to speed up and shape traffic flows across enterprise-wide area networks (WANs) and service provider networks. Unlike traditional IP routing, which makes forwarding decisions based on the destination IP address, MPLS uses short path labels rather than long network addresses to direct data packets. These labels determine the next hop for packets as they travel through the network.
       - Labels are inserted between Layer 2 (data link) and Layer 3 (network) headers, so MPLS is often described as operating between these layers, sometimes referred to as 📝"Layer 2.5."
       - By using labels, MPLS can make forwarding decisions faster than traditional routing, improving the performance of data transmission, especially for large-scale networks.
       - traffic engineering capability
       - supports different levels of QoS by allowing service providers to define and guarantee specific levels of performance for different types of traffic (e.g., voice, video, data).
       - MPLS can carry a wide variety of network protocols, not just IP. This flexibility makes it useful for integrating different types of network services, such as Ethernet, Frame Relay, and ATM, into a single cohesive network.
       - MPLS supports VPNs, allowing different customers' traffic to be isolated from each other even while sharing the same network infrastructure. This is typically achieved through the use of MPLS Layer 3 VPNs
       - One specific attack in MPLS networks is 📝label spoofing, where an attacker might insert or modify labels to reroute or intercept traffic. Implementing security measures such as label integrity checks can mitigate this risk.
- 4.3.2 🔴Multimedia collaboration
    - There are a variety of new technologies that allow instant organizational collaboration, including smartboards, and products that enhance on-site, hybrid, or virutal meetings
    - Mobile communication apps are a huge market, and will continue to grow, increasing the complexity of mobile security
    - Most questions that relate to the security of the multimedia collaboration product would be relevant to supporting business objectives. This includes the following questions:
         - 🗞️Does the communication occur across an open protocol or an encrypted tunnel?
         - 🗞️Does the service use strong authentication techniques? Are activities of users audited and logged?
         - 🗞️What tracking mechanisms are used, can the tracking be disabled?
         - 🗞️What is the data collected for? 
- 4.3.3 🔴Remote access
    - 4 main types of remote access:
        - 🥑**service specific**: gives users the ability to remotely connect to and manipulate or interact with a single service (e.g. email)
        - 🥑**remote-control**: grants a remote user the ability to fully control another system that is physically distant
        - 🥑**remote node operation**: AKA remote client connecting directly to a LAN
        - 🥑**screen scraping**: refers to 1) remote control, remote access, or remote desktop services or 2) technology that allows an automated tool to interact with a human interface
    - Remote access include modem, VPN, WAP, thin-client, remote desktop service, and cloud-based desktop solutions
    - VPN (virtual private network) is a traditional remote access technology
    - WAP (wireless access point) - local env treats as remote access
    - VDI (virtual desktop infrastructure) / VMI (virtual mobile interface)
    - Jumpbox: a jump server/jumpbox is a remote access system deployed to make accessing a specific system or network easier or more secure
        - often deployed in extranets, screened subnets, or cloud networks where a standard direct link or private channel is not available
    - RDS (Remote Desktop Service) such as RD, Teamviewer, VNC etc can provide in-office experience while remote
    - Using cloud-based desktop solutions such as Amazon Workspaces, Amazon AppStream, V2 Cloud, and Microsoft Azure
    - Security must be considered to provide protection for your private network against remote access complications:
        - stringent auth before granting access
        - grant permission only for specific need
        - remote comm protected via encryption
    - Create a remote access security policy, addressing:
        - remote connectivity technology
        - transmission protection
        - authentication protection
        - remote user assistance

- 4.3.4 🔴Data communications   
    - Whether workers are physically in an office or working remotely, communication between devices should be encrypted to prevent any unauthorized device or person from openly reading the contents of packets as they are sent across a network
    - Corporate networks can be segmented into multiple VLANs to separate different types of resources
    - Communications should be encrypted using TLS or IPSec
- 4.3.5 🔴Virtualized networks
    - A virtualized network, or network virtualization, is the combination of hardware and software networking components into a single integrated entity. The resultant system allows for software control over all network functions, management, traffic shaping, address assignment, and so on. A single management console or interface can be used to oversee every aspect of the network, a task requiring physical presence at each hardware component in the past. 
    - Allow adopting things like software-defined networks (SDNs), VLANs, virtual switches, virtual SANs, guest OSs, port isolation etc
    - Many orgs are moving to the cloud, and not continuing to build out local or on-site server infrastructure
        - however, organizations still use hypervisors to virtualize servers and desktops for increased density and reliability
            - to host multiple servers on a single hypervisor, the Ethernet and storage networks must also be virtualized 
            - VMware vSphere and Microsoft Hyper-V both use virtual network and storage switches to allow communication between virtual machines and the physical network; guest OSs running in the VMs use a synthetic network or storage adapter, which is relayed to the physical adapter on the host
            - Securing virtual machine images and snapshots is a key consideration when designing secure virtualization environments. Virtual machines can be easily copied or cloned, potentially exposing sensitive data or allowing unauthorized access. Proper security measures must be taken to secure virtual machine images and snapshots.
            - SDN on the hypervisor can control the VLANs, port isolation, bandwidth and other aspects just as if it was a physical port
- 4.3.6 Third-party connectivity
    - Any time an org’s network is connected directly to another entity’s network, their local threats and risks affect each other
        - 🏔️**Memorandum of Understanding (MOU)** or **memorandum of agreement (MOA)**: (Note: MOU = letter of intent) an expression of agreement or aligned intent, will, or purpose between two entities.  it is only a statement of intentions and not a legal contract.  A memorandum of understanding (MOU) or memorandum of agreement (MOA) is an expression of agreement or aligned intent, will, or purpose between two entities. It is not typically a legal agreement or commitment but rather a more formal form of a reciprocal agreement or handshake.
        - 🏔️**Interconnection Security Agreement (ISA)**: a formal declaration of the security stance, risk, and technical requirements of a link between two organizations’ IT infrastructures. An interconnection security agreement (ISA) is a formal declaration of the security stance, risks, and technical requirements of a link between two organizations' IT infrastructures. The goal of an ISA is to define the expectations and 📝responsibilities of maintaining security over a communications path between two networks. Connecting networks can be mutually beneficial, but it also raises additional risks that are related to third-party connectivity. 
    - Remote workers are another form of third-party connectivity
    - Vendors (like IT auditing firms) may need to connect to your network, and attackers are routinely looking for creative ways to gain organizational access -- third-party connectivity is one option
    - As organizations evaluate third-party connectivity, they need to look carefully at the principle of least privilege and at methods of monitoring use and misuse
    - The potential areas of concern related to third-party connectivity are those in which an actual outsider is to be directly connected to on-premises networks; these situations include 📝business partnerships, 📝cloud services, and 📝telecommuting. 

- 📁**Email Security**: The email infrastructure employed on the internet primarily consists of email servers using Simple Mail Transfer Protocol (SMTP) (TCP port 25) to accept messages from clients, transport those messages to other servers, and deposit them into a user’s server-based inbox.
     - In addition to email servers, the email infrastructure includes email clients.
     - Clients retrieve email from their server-based inboxes using Post Office Protocol version 3 (POP3) (TCP port 110) or Internet Message Access Protocol (IMAP) (technically version 4) (TCP port 143).
         - 🔮**Post Office Protocol (POP) 3**  POP3 is a basic protocol that enables a user to access their emails. It works by downloading the messages off of the server onto the local device. That provides little security because the email is not on the central email server. However, the emails are sent in the clear and are not encrypted. There is 📝no confidentiality. Anyone listening will see the text of your email. Post Office Protocol version 3 (POP3) (TCP port 📝110). With POP3, the email is generally deleted from the server after it's downloaded to the local inbox
         - 🔮**Internet Message Access Protocol (IMAP)** changes the older logic of POP and SMTP by leaving the emails on the server. This is what allows the same emails to show on a mobile phone, a desktop computer, and a tablet all at the same time. It too sends emails in the clear. It is possible to use Transport Layer Security (TLS) (formerly SSL. SSL was developed by Netscape) to encrypt the sent and received, which is technically known as IMAPS. Internet Message Access Protocol (IMAP) (technically version 4) (TCP port 📝143). Unlike POP3 which is designed to delete the email after being retrieved, IMAP 📝stores email on the server.
     - Internet-compatible email systems rely on the X.400 standard for addressing and message handling.
     - Sendmail is the most common SMTP server for Unix systems, and Exchange is the most common SMTP server for Microsoft systems.
     - ❄️**SMTP**: Simple Mail Transfer Protocol (SMTP) is a protocol that enables the sending of emails. It transmits from the email client to the server. It  is  it is primarily used to transfer emails between servers. It is designed to be a mail relay system. This means it relays mail from sender to intended recipient. However, you want to avoid turning your SMTP server into an open relay (also known as an open relay agent or relay agent).
         - ✴️Open Relay: is an SMTP server that does not authenticate senders before accepting and relaying mail.
         - Open relays are prime targets for spammers because they allow spammers to send out floods of emails by piggybacking on an insecure email infrastructure. As open relays are locked down—becoming closed relays or authenticated relays—adversaries are often resorting to hijacking authenticated user accounts through social engineering or credential stuffing/spraying/guessing attacks.
     - Email Security goals include:
         - Restrict access to messages to their intended recipients (i.e., privacy and confidentiality)
         - Maintain the integrity of messages
         - Authenticate and verify the source of messages
         - Provide for nonrepudiation
         - Verify the delivery of messages
         - Classify sensitive content within or attached to messages
         - Essential email concepts, which local systems can enforce and protect, include nonrepudiation, message integrity, and access restrictions.
         - 📝Mail-bombing is the use of email as an attack mechanism by flooding a system with messages, causing a denial of service.
     - ❄️**Secure Multipurpose Internet Mail Extensions (S/MIME)**  offers authentication and confidentiality to email through public key encryption, digital envelopes, and digital signatures.
         - S/MIME are used to encrypt and digitally sign emails.
         - S/MIME uses the 📝RSA encryption algorithm and has been incorporated into many commercial products, such as Microsoft Outlook, Mozilla Thunderbird, and MAC OS X Mail.
         - S/MIME relies on the use of the 📝X.509 certificates for exchanging cryptographic keys.
         - Authentication is provided through X.509 digital certificates issued by trusted third-party CAs.
         - Privacy is provided through the use of Public Key Cryptography Standard (PKCS) standards-compliant encryption.
         - Two types of messages can be formed using S/MIME: signed messages and secured enveloped messages.
             - 🐌A signed message provides integrity, sender authentication, and nonrepudiation.
             - 🐌An enveloped message provides recipient authentication and confidentiality.
     - ❄️**Pretty Good Privacy (PGP)**  is a peer-to-peer public-private key–based email system that uses a variety of encryption algorithms to encrypt files and email messages. PGP is not a standard but rather Open Source.
         - Pretty Good Privacy (PGP) is a hybrid cryptosystem that uses the International Data Encryption Algorithm 📝(IDEA), a symmetric block algorithm, to encrypt the data. PGP uses a 📝web of trust. The commercial version uses the asymmetric algorithms of 📝RSA and the free version uses the Diffie-Hellman key exchange. Symmetric algorithms are used to encrypt and protect the confidentiality of data.
         - Pretty Good Privacy (PGP) is a software program that was developed to secure email communications in 1991. It is still used today in applications where only basic security is required. PGP is similar to a Public Key Infrastructure (PKI) because each user is given a public and private key. However, PGP uses a community-driven web of trust instead of a predefined trusted certificate authorities list.
         - PGP uses a mix of cryptographic techniques and tools. It uses symmetric encryption for confidentiality, asymmetric encryption for digital signatures, and hashing algorithms for integrity proof.
     - ❄️**DomainKeys Identified Mail (DKIM)** is a means to assert that valid mail is sent by an organization through 📝verification of 📝domain name identity. Domain Key Infrastructure Management (DKIM) is the use of a digital signature by e-mail servers to provide authentication and integrity of email messages. See dkim.org.
     - ❄️**Sender Policy Framework (SPF)** To protect against spam and email spoofing, it operates by checking that inbound messages originate from a host authorized to send messages by the owners of the SMTP origin domain. A Sender Policy Framework (SPF) record is a 📝list of e-mails associated with a domain to reduce spam. 
     - ❄️**Domain Message Authentication Reporting and Conformance (DMARC)** DMARC is a 📝DNS-based email authentication system. It is intended to protect against business email compromise (BEC), phishing, and other email scams. Email servers can verify if a received message is valid by following the DNS-based instructions; if invalid, the email can be discarded, quarantined, or delivered anyway.
     - ❄️**STARTTLS** using Secure SMTP over TLS. STARTTLS (aka explicit TLS or opportunistic TLS for SMTP) will attempt to set up an encrypted connection with the target email server. STARTTLS is not a protocol but instead an SMTP command. Once the initial SMTP connection is made to the email server, the STARTTLS command will be used if the target server supports it. Otherwise, it will remain as plaintext. STARTTLS’s secure session will take place on TCP port 587. STARTTLS can also be used with IMAP connections, whereas POP3 connections use the STLS command to perform a similar function.
     - ❄️**Implicit SMTPS** This is the TLS-encrypted form of SMTP, which assumes the target server supports TLS. If accurate, then an encrypted session is negotiated. If not, then the connection is terminated because plaintext is not accepted. SMTPS communications are initiated against TCP port 465.

🍏IEEE 802.1 - Bridging and Network Management
- 802.1Q: VLAN Tagging - Defines VLANs and the tagging protocol used to identify VLAN traffic.
- 802.1X: Port-Based Network Access Control - Provides an authentication mechanism for devices wishing to attach to a LAN or WLAN.
- 802.1D: Spanning Tree Protocol (STP) - Provides loop-free topology for Ethernet networks.
- 802.1w: Rapid Spanning Tree Protocol (RSTP) - An evolution of STP providing faster convergence.
- 802.1s: Multiple Spanning Tree Protocol (MSTP) - Extends RSTP to support multiple spanning trees.
- 802.1ad: Provider Bridges (Q-in-Q) - Extends VLANs for use in provider networks.

🍏IEEE 802.1AE - MACsec
- MACsec is an Institute of Electrical and Electronics Engineers (IEEE) standard that provides confidentiality and integrity at the data link layer of the Open Systems Interconnection (OSI) model.

🍏IEEE 802.3 - Ethernet
- 802.3i: 10BASE-T - 10 Mbps over twisted pair cabling.
- 802.3u: 100BASE-TX - Fast Ethernet, 100 Mbps over twisted pair cabling.
- 802.3ab: 1000BASE-T - Gigabit Ethernet over twisted pair cabling.
- 802.3ae: 10GBASE-SR/LR - 10 Gigabit Ethernet over fiber.
- 802.3af: Power over Ethernet (PoE) - Provides power over Ethernet cabling.
- 802.3at: Power over Ethernet Plus (PoE+) - Enhanced version of PoE with higher power delivery.
🍏IEEE 802.4: Fiber Distributed Data Interface (FDDI) is derived from IEEE 802.4. Fiber Distributed Data Interface (FDDI) is a high-speed token-passing technology that employs two rings with traffic flowing in opposite directions and is designed for the Metropolitan Area Network (MAN)
🍏IEEE 802.5: A token ring is IEEE 802.5. Token passing is used by the token ring technology (IEEE 802.5). Collisions are avoided because there is a single token on the ring and a device/host cannot transmit unless it is in possession of that token. 
🍏IEEE 802.11 - Wireless LAN (Wi-Fi)
- 802.11a: 5 GHz, up to 54 Mbps.
- 802.11b: 2.4 GHz, up to 11 Mbps.
- 802.11g: 2.4 GHz, up to 54 Mbps.
- 802.11n: 2.4/5 GHz, up to 600 Mbps with MIMO.
- 802.11ac: 5 GHz, up to several Gbps with wider channels and more MIMO streams.
- 802.11ax: Wi-Fi 6, improvements in throughput and efficiency.
    - 🎈Wi-Fi 6 operates at the 2.4 Gbps and 5Ghz frequency but allows for the same data rate as the Wi-Fi 6 and 6E standards. Wi-Fi 5 is an old Wi-Fi standard, allowing for only a fraction of the data transfer rate Wi-Fi 6 and 6E allow for.
    - 🎈Wi-Fi 6E is the latest Wi-Fi standard to be released yet, allowing a maximum data rate of 9.6 Gbps under the 6Ghz frequency. Like Wi-Fi 6, it falls under the IEEE 802.11ax standard. Wi-Fi 6E is currently the only 6Ghz standard in the U.S., with the release of Wi-Fi 7 to occur shortly.
    - 🎈Wi-Fi 7 is available as of January 8, 2024. The current exam outline, as of writing, is Wi-Fi 6e. The exam update in 2024 would make Wi-Fi 7 a valid question.

🍏IEEE 802.15 - Wireless Personal Area Networks (WPAN)
- 802.15.1: Bluetooth.
- 802.15.4: Low-Rate WPAN (used by protocols like Zigbee).

🍏IEEE 802.16 - Broadband Wireless Access (MAN)
- 802.16: WiMAX - Provides wireless metropolitan area network (MAN) connectivity.

🍏IEEE 802.17 - Resilient Packet Ring (RPR)
- 802.17: RPR - Optimizes the transport of data traffic over fiber ring networks.
- **UTP categories**

| UTP    | Throuput      |Notes               |
|--------|---------------| -------------------|
| Cat 1  | 1 Mbps        | Primarily used for voice. Not suitable for networks, but usable by modems |
| Cat 2  | 4 Mbps        | Original Token Ring networks and host-to-terminal connections on mainframes |
| Cat 3  | 10 Mbps       | Primarily used in Ethernet networks and as telephone cables.|
| Cat 4  | 16 Mbps       | Primarily used in Token Ring networks.|
| Cat 5  | 100 Mbps      | Used in 100BaseTX, FDDI, and ATM networks.|
| Cat 5e | 1 Gbps        | Gigabit Ethernet (1000BaseT).|
| Cat 6  | 1 Gbps        | Gigabit Ethernet (10G Ethernet with 55-meter distance limit).|
| Cat 6a | 10 Gbps       | Gigabit Ethernet, 10G Ethernet.|
| Cat 7  | 10 Gbps       | Gigabit Ethernet, 10G Ethernet.|
| Cat 8  | 40 Gbps       | 10G+ Ethernet.|

- Maximum distance to deploy twisted-pair cable (1000BaseT) should not be longer than 100 meters
- Attenuation is the loss of signal as it travels through a medium. Ethernet connections should not exceed the recommended length of 100 meters. Excessive length can cause the signal to degrade as it travels through the cable. This can lead to packet loss or excessive latency.
- 📘**Coax**
- There are two main types of coaxial cable: thinnet and thicknet. 
    - Thinnet (10Base2) was commonly used to connect systems to backbone trunks of thicknet cabling. Thinnet can span
        distances of 185 meters and provide throughput up to 10 Mbps. 
    - Thicknet (10Base5) can span 500 meters and provide throughput up to 10 Mbps.
    
Bending the coax cable past its maximum arc radius may break the center conductor and Deploying the coax cable in a length greater than its maximum recommended may cause isses.
- 📘**Fibre Optics**
- Fiber can be deployed as single-mode (supporting a single light signal) or multimode (supporting multiple light signals).  
    - 💢Single-mode fiber has a thinner optical core, lower attenuation over distance, and potentially unlimited bandwidth. It uses a 1310 nm or 1550 nm wavelength laser, can be deployed in runs up to 10 km without repeaters, and is typically sheathed in yellow.
        - Single mode cables are typically rated for between 1 and 10 Gigabits per second over these incredible lengths. It’s theoretically possible that they can run at much higher bandwidths, but typical specifications limit them to 10 Gbps at the top end. 
        - Single mode cables are typically made with a single strand of glass at their core, leading to a narrower core of the cabling, and more robust signal integrity over greater distances. They can be further divided into
        - 🐍OS1 cables: commonly used in campus data networks, telecommunication networks, and TV transmission networks. Generally designed for a minimum attenuation of 0.35 dB/km at 1310 nm and 0.22 dB/km at 1550 nm. Supports distances up to 10 kilometers at 10 Gbps and up to 40 kilometers or more at 1 Gbps, depending on the specific network equipment and conditions. Used for long-distance communication, such as in telecommunications networks and long-haul connections.
        - 🐍OS2 cables: which are designed for indoor and outdoor uses, respectively, with OS2 cables offering greater cable lengths and bandwidth. Designed for lower attenuation compared to OS1, with minimum attenuation of 0.35 dB/km at 1310 nm and 0.20 dB/km at 1550 nm. Supports longer distances than OS1, up to 40 kilometers at 10 Gbps and 80 kilometers or more at 1 Gbps. Suitable for high-performance, long-distance communications, including high-speed backbone connections and metropolitan area networks (MANs).
    - 💢Multimode fiber has a larger optical core, higher attenuation over distance, and bandwidth limitations (inversely related to distance), and it uses 850 nm or 1300 nm wavelength LEDs or lasers, has a maximum run length of 400m, and is typically sheathed in blue.
        - Multimode cables have multiple glass strands in the core, making them larger and more versatile since they can handle multiple data streams at a time. However, that broader core means there’s more light refraction throughout the cable, weakening the signal faster, and making multimode cables less suitable for longer runs. They too are divided into more cable types:
        - 🐍OM1: Legacy OM1 cables are limited to just 100ft. 300 meters for 1 Gbps (Gigabit Ethernet) and 33 meters for 10 Gbps (10-Gigabit Ethernet).
        - 🐍OM2: OM2 provides a higher quality connection and can stretch to 260ft. OM2 bandwith is relatively comparable to single mode cables, delivering between 1Gbps and 10 Gbps depending on cable length. Supports up to 550 meters for 1 Gbps and 82 meters for 10 Gbps.
        - 🐍OM3: OM3 multimode fiber optic cables can manage longer cable runs at up to 1,000ft. Supports up to 300 meters for 10 Gbps and 100 meters for 40 Gbps and 100 Gbps.
        - 🐍OM4: OM4 and OM5 are capable of 1,300ft cable runs at up to 10 Gbps. OM4 Supports up to 400 meters for 10 Gbps, 150 meters for 40 Gbps, and 150 meters for 100 Gbps.
        - 🐍OM5: OM4 and OM5 are capable of 1,300ft cable runs at up to 10 Gbps. Designed for high-speed data centers and enterprise networks, supports wavelength division multiplexing (WDM) to increase data capacity. OM3, OM4, and OM5 are also capable of transmitting at a much higher bandwidth: up to 100 Gbps in some cases. However, offering such throughput requires a shorter cable run, with even the most capable OM4 and OM5 cables limited to just 500ft at the maximum bandwidth.
- 🟦SONET (Synchronous Optical Network) is a standardized protocol that transfers multiple digital bit streams over optical fiber. SONET defines a hierarchy of data transmission rates, known as Optical Carrier (OC) levels. Each OC level corresponds to a different data rate.
- SONET standardizes the optical interfaces between different network equipment, enabling seamless integration and communication between different vendors' devices in a network. Each of the SONET levels represents a multiple of the OC-1 base rate and is used to match the data rate requirements of different applications.
- While SONET is primarily used in North America, SDH (Synchronous Digital Hierarchy) is the international equivalent used in the rest of the world.
- In SDH, data transmission rates are categorized into different levels called STMs (Synchronous Transport Modules). Each STM level represents a specific data rate, similar to how SONET categorizes data rates using OC (Optical Carrier) levels.

| SONET         | SDH        |DATA RATE               |
|---------------|-----------------| -------------------|
|STS-1/OC-1     | STM-0           | 51.84 Mbps        | 
|STS-3/OC-3     | STM-1      | 155.52 Mbps |
|STS-12/OC-12   | STM-4      | 622.08 Mbps |
|STS-48/OC-48   | STM-16      | 2.488 Gbps |
|STS-96/OC-96   | STM-32      | 4.876 Gbps |
|STS-192/OC-192 | STM-64      | 9.953 Gbps |
|STS-768/OC-768 | STM-256      | 39.813 Gbps |

- Synchronous Digital Hierarchy (SDH) and Synchronous Optical Network (SONET) are fiber-optic high-speed networking standards. SDH was standardized by the International Telecommunications Union (ITU) and SONET by the American National Standards Institute (ANSI). SDH and SONET are mostly hardware or physical layer standards defining infrastructure and line speed requirements. SDH and SONET use synchronous time-division multiplexing (TDM) to high-speed duplex communications with minimal need for control and management overhead.

- 📁**Common VPN Protocols**: VPNs can be implemented using software or hardware solutions. In either case, there are several common VPN protocols: PPTP, L2TP, L2F (Cisco), SSH, OpenVPN (i.e., TLS), and IPsec.
  - ⚓Tunnel Mode: encrypts the entire IP packet, including both the header and the payload, and then encapsulates it within a new IP packet. This mode is commonly used for VPNs that connect entire networks or provide secure communication over untrusted networks. Tunnel mode VPNs are used to connect networks to networks or hosts to networks. It is applied in Site-to-Site VPNs and remote access VPNs
  - ⚓Transport Mode: encrypts only the payload of the IP packet, leaving the original IP header intact. This mode is typically used for end-to-end communications between individual devices. Transport mode is used to connect hosts to hosts. 
    - ⚒️**TLS**:  TLS is also used for an increasingly large percentage of VPN connections and may appear at some point in the CISSP exam.
        - An HTML-based VPN, often referred to as a web-based VPN, is a type of VPN solution that allows users to securely connect to a private network via a web browser. Instead of installing dedicated VPN client software, users access the VPN through a web interface.  the web-based VPN creates a secure connection between the user’s browser and the VPN server. This connection might use technologies like WebVPN or SSL/TLS.
        - TLS allows for use of TCP port 443;
        - prevents tampering, spoofing, and eavesdropping; and can be used as a VPN solution.
        - TLS supports both one-way and two-way authentication.
        - TLS and SSL are not interoperable or backward compatible.
    - ⚒️**Point-to-Point Tunneling Protocol (PPTP)**: is an obsolete encapsulation protocol developed from the dial-up Point-to-Point Protocol.
        - 🎈**Point-to-Point Protocol (PPP)** was developed to support multiple network layer protocols (such as IP, IPX, and others) and provides features like login, password authentication, and error correction. PPP is widely used for establishing direct connections over serial links such as dial-up or VPN connections, offering robust functionality for authentication and error handling.
            - It's commonly used for connecting end-user systems (like a computer) to an ISP (Internet Service Provider).
            - Encapsulation: Wraps network layer packets (like IP packets) in a data link frame, allowing them to travel across various physical media
            - Supports various authentication protocols, such as PAP (Password Authentication Protocol) and CHAP (Challenge Handshake Authentication Protocol) and EAP.
            - It's commonly used for connecting end-user systems (like a computer) to an ISP (Internet Service Provider).
        - PPTP is a Layer 2 tunneling protocol used to implement VPNs (Virtual Private Networks). It encapsulates **PPP** frames into IP datagrams so they can be transmitted over an IP-based network (like the Internet).
        - It operates at the Data Link layer (layer 2) of the OSI model and is used on IP networks.
        - PPTP uses TCP port 1723.
        - PPTP offers protection for authentication traffic through the same authentication protocols supported by PPP: Password Authentication Protocol (PAP), CHAP, EAP, Microsoft Challenge Handshake Authentication Protocol (MS-CHAPv2).
        - Initial tunnel negotiation process used by PPTP is not encrypted.
        - Most modern uses of PPTP have adopted the Microsoft customized implementation(MS-CHAPv2), which supports data encryption using Microsoft Point-to-Point Encryption MPPE and which supports various secure authentication options.
    - ⚒️**Layer 2 Tunneling Protocol (L2TP)** L2TP  was developed by combining features of PPTP and Cisco’s Layer 2 Forwarding (L2F) VPN protocol.
        - Since its development, L2TP has become an internet standard (RFC 2661).
        - Obviously, L2TP operates at layer 2 and thus can support just about any layer 3 networking protocol.
        - L2TP uses UDP port 1701. L2TP can rely on PPP’s supported authentication protocols, specifically IEEE 802.1X, which is a derivative of EAP from PPP.
        - IEEE 802.1X enables L2TP to leverage or borrow authentication services from any available AAA server on the network, such as RADIUS or TACACS+.
        - L2TP does not offer native encryption, but it supports the use of payload encryption protocols.
        - Although it isn’t required, L2TP is most often deployed using IPsec’s ESP for payload encryption. 
    - ⚒️**Generic Routing Encapsulation (GRE)** is also a proprietary Cisco tunneling protocol that can be used to establish VPNs.
        - GRE provides encapsulation but not encryption.
    - ⚒️**SSH**: Secure Shell (SSH) is a secure replacement for Telnet (TCP port 23) and many of the Unix “r” tools, such as rlogin, rsh, rexec, and rcp.
        - While Telnet provides plaintext remote access to a system, all SSH transmissions (both authentication and data exchange) are encrypted.
        - SSH operates over TCP port 22.
        - it can be used to encrypt protocols (such as SFTP, SEXEC, SLOGIN, and SCP) similar to how TLS operates; and it can be used as a VPN protocol.
        - However, as a VPN, SSH is limited to transport mode (i.e., end-to-end encryption between individual hosts, aka link encryption and host-to-host VPN).
        - The tool OpenSSH is a means to implement SSH VPNs. For most secure protocols, if the S in the name is a prefix, like with SFTP, then the encryption is provided by SSH (which has an S as its first letter).
        - If the S in the name is a suffix, like with HTTPS, then the encryption is provided by TLS (which has S as its last letter).
        - Secure Shell (SSH) provides end-to-end encryption and exchange keys using the Diffie-Hellman algorithm. The encryption is negotiated between the client and server and does not rely on lower-layer encryption methods to protect the payload.
    - ⚒️**OpenVPN**: OpenVPN is based on TLS (formally SSL) and provides an easy-to-configure but robustly secured VPN option.
        - OpenVPN is an open source implementation that can use either pre-shared passwords or certificates for authentication.
        - Many WAPs support OpenVPN, which is a native VPN option for using a home or business WAP as a VPN gateway.
    - ⚒️**Internet Protocol Security (IPsec)** is a standard of IP security extensions used as an add-on for IPv4 and integrated into IPv6.
        - IPsec is sometimes paired with L2TP as L2TP/IPsec.
        - IPsec isn’t a single protocol but rather a 📝collection of protocols, including AH, ESP, HMAC, IPComp, and IKE.
            - 🐍Authentication Header (AH) provides assurances of message integrity and nonrepudiation. AH also provides the primary authentication function for IPsec, implements session access control, and prevents replay attacks. The Authentication Header provides authentication, integrity, and nonrepudiation for IPsec connections. 
            - 🐍Encapsulating Security Payload (ESP) provides confidentiality and integrity of payload contents, hence confidentiality. It provides encryption, offers limited authentication, and prevents replay attacks. Modern IPsec ESP typically uses advanced encryption standard (AES) encryption. The limited authentication allows ESP to either establish its own links without using AH and perform periodic mid-session reauthentication to detect and respond to session hijacking. ESP can operate in either transport mode or tunnel mode.
            - 🐍Hash-based Message Authentication Code (HMAC) is the primary hashing or integrity mechanism used by IPsec.
            - 🐍IP Payload Compression (IPComp) is a compression tool used by IPsec to compress data prior to ESP encrypting it in order to attempt to keep up with wire speed transmission.
            - 🐍Internet Key Exchange (IKE) is the mechanism of IPsec that manages cryptography keys and is composed of three elements: OAKLEY, SKEME, and ISAKMP. The mechanism of IPsec that manages cryptography keys is Internet Key Exchange (IKE).  It is used to exchange the symmetric key for encryption/confidentiality purposes. IKE is composed of three elements: OAKLEY, SKEME, and ISAKMP. 
                - ✏️OAKLEY is a 📝key generation and exchange protocol similar to Diffie–Hellman.
                - ✏️Secure Key Exchange Mechanism (SKEME) is a means to 📝exchange keys securely, similar to a digital envelope. Modern IKE implementations may also use ECDHE for key exchange.
                - ✏️Internet Security Association and Key Management Protocol (ISAKMP) is used to organize and manage the encryption keys that have been generated and exchanged by OAKLEY and SKEME. A security association is the agreed-on method of authentication and encryption used by two entities (a bit like a digital keyring).  ISAKMP is used to negotiate and provide authenticated keying material (a common method of authentication) for security associations in a secured manner. Each IPsec VPN uses two security associations, one for encrypted transmission and the other for encrypted reception. Thus, each IPsec VPN is composed of two simplex communication channels that are independently encrypted. ISAKMP’s use of 📝two security associations per VPN is what enables IPsec to support 📝multiple simultaneous VPNs from each host.
                    - IKE has two modes:
                        - ⚒️Main Mode uses a six-way handshake where parameters are exchanged in multiple rounds with encrypted key exchange. This is more secure than Aggressive Mode. A key exchange using a Diffie-Hellman (DH) or DH-like algorithm is always preferred over using a pre-shared key.
                        - ⚒️Aggressive Mode uses a three-way handshake where the hashed Pre-Shared Key (PSK) is sent unencrypted.
                    - Internet Key Exchange (IKE) is used to negotiate parameters and ultimately establish Security Associations (SAs) for Internet Protocol Security (IPsec). IKE operates in two phases:
                        - 🎈Phase 1: Negotiates a single bi-directional SA by exchanging a generated secret key using the Diffie-Hellman key exchange.
                        - 🎈Phase 2: Negotiates unidirectional SAs using the SA established during phase 1. 
        - IPsec uses public-key cryptography and symmetric cryptography to provide encryption (aka hybrid cryptography), secure key exchange, access control, nonrepudiation, and message authentication, all using standard internet protocols and algorithms.
        - IPsec, or Internet Protocol Security, using public key cryptography, can provide
            - encryption, access control
            - nonrepudiation
            - message authentication .
         - 📝Replay Attacks are where the attacker stole an authentication token and used it to impersonate the user
         - IPsec has always offered native data encryption. Generic Routing Encapsulation (GRE) is a proprietary Cisco tunneling protocol that can be used to establish VPNs. GRE provides encapsulation but not encryption. L2TP does not offer native data encryption, but it can support IPsec's ESP to provide encryption. PPTP did not originally provide native data encryption, but with the adoption of MS-CHAPv2 that feature was added.
- 🔴**PRIVATE IP**: These IPv4 addresses, commonly called the private IPv4 addresses, are defined in RFC 1918. They are as follows:
    - 10.0.0.0–10.255.255.255 (a full Class A range)./8
        - Example: 10.0.0.1 in binary: 00001010.00000000.00000000.00000001
        - Class A: Maximum number of addresses: 16,777,214
    - 172.16.0.0–172.31.255.255 (16 Class B ranges)./12
        - Example: 172.16.0.1 in binary: 10101100.00010000.00000000.00000001
        - Class B: Maximum number of addresses: 65,534
    - 192.168.0.0–192.168.255.255 (256 Class C ranges)./16
        - Example: 192.168.1.1 in binary: 11000000.10101000.00000001.00000001
        - Class C: Maximum number of addresses: 254
- 🌲**Well-known ports**: Well-known ports  are assigned by the Internet Assigned Numbers Authority (IANA) and range from 0 to 1023. These ports are used by widely used protocols and services, such as HTTP (port 80), FTP (port 21), and SSH (port 22).
- 🌲**Registered\User Ports 1,024-49,151**: registered ports used with non-system applications associated with vendors and devs
- 🌲**Dynamic\Private\Ephemeral Ports 49,152-65,535**: dynamic ports (AKA private or non-reserved ports) used as temporary ports, often in association when a service is requested via a well-known port
- 🔴**Centralized Remote Authentication Services**
    - RADIUS: Users pass login credentials to a RADIUS server for authentication. By default, RADIUS uses UDP and only encrypts passwords. RADIUS supports TCP and TLS, but this is not a default setting.
    - Diameter: is essentially the successor to RADIUS. One significant improvement Diameter provides is added reliability. Diameter is often used in prepaid and credit-­based usage models in mobile device services, and similar applications.
    - TACACS: available in three versions: original TACACS, Extended TACACS (XTACACS), and TACACS+. TACACS integrates the authentication and authorization processes. XTACACS keeps the authentication, authorization, and accounting processes separate. TACACS+ improves XTACACS by adding two-­factor authentication.
