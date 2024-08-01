[Domain 4](#domain4-top) **Communication and Network Security**

Networking can be one of the more complex exam topics; if you have a networking background, you likely won’t find this domain difficult-- if not, spend extra time in this section and consider diving deeper into topics that are fuzzy

- **ACK**: an acknoledment of a signal being received
- **ARP**: used at the Media Access Control (MAC) layer to provide for direct communication between two devices within the same LAN segment
- **APT**: Advanced Persistent Threat is an agent/org that plans, organizes, and carries out highly sophisticated attacks against a target person, org, or industry over a period of time (months or even years); usually with a strategic goal in mind
- **API**: Application Programming Interface; code mechanisms that provide ways for apps to share data, emthods, or functions over a network (usually implemented in XML or JavaScript Object Notation (JSON))
- **Bandwidth**: amount of information transmitted over a period of time; can be applied to moving bits over a medium, or human processes like learning or education
- **Bluetooth**: wireless personal area network, IEEE 802.15; an open standard for short-range RF communication used primarily with wireless personal area networks (WPANs)
- **Bound networks**: AKA wired/Ethernet networks, where devices are connected by physical cables
- **Boundary routers**: they advertise routes that external hosts can use to reach internal hosts
- **Bridge**: device that aggregates separate network segments into a single network segment, operating at OSI layer 2
- **CSMA/CA**: Carrier Sense Multiple Access with Collission Avoidance is a method of network flow control. 802.11 wireless networking is an example of a network that employs CSMA/CA technologies. CSMA/CA attempts to avoid collisions by granting only a single permission to communicate at any given time.
- **CSMA/CD**: Carrier Sense Multiple Access with Colliion Detection is a method of network flow control, where if > 1 station accesses the network at the same time, other stations detect and re-try their transmission. Ethernet networks employ the CSMA/CD technology. CSMA/CD responds to collisions by having each member of the collision domain wait for a short but random period of time before starting the process over.
- **Circuit-switched network**: network that uses a dedicated circuit between endpoints
- **CDMA**: Code-Division Multiple Access: a method of encoding several sources of data so they can all be transmitted over a single RF carrier by one transmitter, or by using a single RF carrier frequency with multiple transmitters; the data from each call is encoded with a unique key, and calls are transmitted at once
- **Concentrator**: provides communication capability between many low-speed, usually asynchronous channels and one or more high-speed, usually synchronous channels. Usually different speeds, codes, and protocols can be accommodated on the low-speed side; multiplexed into one signal
- **CDN**: Content Distribution Network is a large distributed system of servers deploye in multiple data centers, with a goal of Quality of Service (QoS) and availability requirements
- **Control plane**: part of a network that controls how data packets are forwarded — meaning how data is sent from one place to another; e.g. the process of creating a routing table is considered part of the control plane; control of network functionality and programmability is directly made to devices at this layer
- **Northbound/Southbound interface**: A northbound interface lets a specific component communicate with a higher-level component in the same network; a southbound interface is the opposite — enabling a specific component to communicate with a lower-level component
- **East/West traffic**: network traffic that is within a data, control, or application plane; within a data center or between geo dispersed locations
- **North/South traffic**: in SDN terms, data flowing up (northbound) and down (southbound) the stack of data/control/application planes; data flowing from the organization to external distinations (northbound), or into the org from external sources (southbound)
- **Converged protocol**: combines/converges standard protcols (such as TCP/IP) with proprietary/non-standard ones; they can complicate enterprise-wide security engineering efforts requiring specialist knowledge. eg Fibre Channel over Ethernet (FCoE), Internet Small Computer Systems Interface (iSCSI), and Voice over Internet Protocol (VoIP) are all examples of converged protocols that combine specialized protocols with standard protocols like TCP/IP.
- **DNS**: Domain Name Service is three in interrelated elements: a service, a physical server, and a network protocol
- **DHCP**: Dynamic Host Configuration Protocol is an industry standard used to dynamically assign IP addresses to network devices
- **Ports 1024-4951**: registered ports used with non-system applications associated with vendors and devs
- **Ports 49152-65535**: dynamic ports (AKA private or non-reserved ports) used as temporary ports, often in association when a service is requested via a well-known port
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
- **Port Address Translation**: an extension of NAT (Network Address Translation) translating all addresses to one routable IP address and translate the source port number in the packet to a unique value
- **RPC**: Remote Procedure Call is a protocol that enables one system to execute instructions on other hosts across a network infrastructure
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
    | 7     | Application     | Application |Data               | L7 firewall                                | HTTP/s, DNS, DHCP, FTP,S-HTTP, TPFT, Telnet, SSH, SMTP, POP3, SNMP, PEM, IMAP, NTP, SNMP, TLS/SSL, GBP, RIP, SIP, S/MIME etc. |
    | 6     | Presentation    | Application |Data               | L7 firewall                                | JPEG, ASCII, and MIDI                                                |
    | 5     | Session         | Application| Data               | L7 firewall                                | NFS, SQL, and RPC                                                |
    | 4     | Transport       | Transport (host-to-host) | Segments           | L4 firewall                                | TCP (connection oriented), UDP (connectionless), TLS     |
    | 3     | Network         | Internet/IP | Packets            | Router, Multiplayer Switch, Router         | IPv4, IPv6, IPSec, OSPF, EIGRP                               |
    | 2     | Data Link       | Network Access | Frames             | Switch, Bridge, NIC, Wireless Access Point | MAC, ARP Ethernet 802.3 (Wired), CDP, LLDP, HDLC, PPP, DSL, L2TP, IEEE 802.11 (Wireless), SONET/SDH |
    | 1     | Physical        | Network Access | Bits               | All the above                              | Electrical signal (copper wire), Light signal (optical fibre), Radio signal (air) |

Note: Data streams are associated with the Application, Presentation, and Session layers. Once they reach the Transport layer, they become segments (TCP) or datagrams (UDP). From there, they are converted to packets at the Network layer, frames at the Data Link layer, and bits at the Physical layer.

### OSI layers in detail
- Mnemonics:
        - from top: All People Seem To Need Delicious Pizza
        - from bottom: Please Do Not Throw Sausage Pizza Away
    - Application Layer (7)
        - Responsible for:
            - interfacing user applications, network services, or the operating system with the protocol stack 
            - identifying and establishing availability of communication partners 
            - determining resource availability and 
            - synchronizing communication
    - Presentation Layer (6)
        - Responsible for transforming data into the format that any system following the OSI model can understand
        - Associated tasks:
            - data representation
            - character conversion
            - data compression
            - data encryption
    - Session Layer (5)
        - Responsible for establishing, maintaining, and terminating communication sessions between two computers
        - Three communication session phases: 
            - connection establishment
                - **simplex**: one-way 
                - **half-duplex**: both comm devices can transmit/receive, but not at the same time
                - **full-duplex**: both comm devices can transmit/receive at same time
            - data transfer
            - connection release
    - Transport Layer (4)
        - Responsible for managing the integrity of a connection and controlling the session; providing transparent data transport and end-to-end transmission control
        - Defines session rules like how much data each segment can contain, how to verify message integrity, and how to determine whether data has been lost
        - Protocols that operate at the Transport layer:
            - Transmission Control Protocol (TCP)
                - the major transport protocol in the internet suite of protocols providing reliable, connection-oriented, full-duplex streams
                - emphasizing: full-duplex, connection-oriented protocol
                - uses three-way handshake
            - User Datagram Protocol (UDP)
                - connectionless protocol that provides fast, best-effort delivery of **datagrams** (self-container unit of data)
                - it is also considered a simplex protocol (Typically, there is no acknowledgment or feedback from the receiver to the sender, because the channel only allows data to flow in one direction.)
            - Transport Layer Security (TLS)
    - Network Layer (3)
        - Responsible for logical addressing, and providing routing or delivery guidance (but not necessarily verifying guaranteed delivery), manages error detection and traffic control
        - **routing protocols**: move routed protocol messages across a network
            - includes RIP, OSPF, IS-IS, IGRP, and BGP
            - routing protocols are defined at the Network Layer and specify how routers communicate
            - routing protocols can be static or dynamic, and categorized as interior or exterior
            - **static routing protocol**: requires an admin to create/update routes on the router
            - **dynamic**: can discover routers and determine best route to a given destination; routing table is periodically updated
            - **distance-vector**: (interior) makes routing decisions based on distance (e.g. hop count), and vector (router egress interface); examples:
                - **Routing Information Protocol (RIP)**: a distance-vector protocol that uses hop count as its routing metric
                - Interior Gateway Routing Protocol (IGRP)
                - Enhanced Interior Gateway Routing Protocol (EIGRP). This is Cisco Proprietary.
            - **link state**: (interior) uses router characteristics (e.g. speed, latency, error rates) to make next hop routing decisions; examples:
                - **Open Shortest Path First (OSPF)**: an interior gateway routing protocol developed for IP networks based on shorest path first or link-state algorithm
                - Intermediate System to Intermediate System (IS-IS)
            - interior vs exterior:
                - interior routing protocols ("myopic") make next hop decisions based only on info related to the next immediate hop
                - exterior routing protocols ("far-sighted") make hop decisions based on the entire remaining path (i.e.) vector
                - **Border Gateway Protocol (BGP)**: an exterior/path vector protocol
        - Routed protocols include Internetwork Package Exchange (IPX) and Internet Protocol (IP)  
    - Data Link Layer (2)
        - Responsible for formatting a packet for transmission
        - Adds the source and destination hardware addresses to the frame
        - Media Access Control (MAC) - (hardware-based) address/AKA NIC address
            - MAC address is a 6-byte (48-bit) binary address written in hex
                - first 3b/24-bits: Organizationally Unique Identifier (OUI) - denotes manufacturer
                - last 3b/24-bits: unique to that interface
        - **Address Resolution Protocol (ARP)**: operates at layer 2
        - Switches & bridges function at this layer
        - Logical Link Control (LLC) is one of two sublayers that make up the Data Link Layer
        - **ARP Poisoning**: also known as ARP spoofing, is a type of cyber attack in which an attacker sends falsified Address Resolution Protocol (ARP) messages over a local network. 
            - ARP poisoning can use unsolicited or gratuitous replies—­specifically, ARP replies for which the local device did not transmit an ARP broadcast request.
            - in ARP poisoning,  an attacker sends malicious ARP replies to the network. These replies contain incorrect mappings of IP addresses to MAC addresses. Devices on the network, upon receiving these forged ARP replies, update their ARP tables with the incorrect information.
            - It can be used for Man-in-the-Middle (MitM) Attacks, Denial of Service (DoS), and Session Hijacking.

    - Physical Layer (1)
        - Converts a frame into bits for transmission/receiving over the physical connection medium
        - Network hardware devices that function at layer 1 include NICs, hubs, repeaters, concentrators, amplifiers
        - Know four basic network topologies:
            - **star**: each individual node on the network is directly connect to a switch/hub/concentrator
            - **mesh**: all systems are interconnected; partial mesh can be created by adding multiple NICs or server clustering
            - **ring**: closed loop that connects end devices in a continuous ring (all communication travels in a single direction around the ring);
                - **Multistation Access Unit** (MSAU or MAU) connects individual devices
                - used in token ring and FDDI networks
            - **bus**: all devices are connected to a single cable (backbone) terminated on both ends
        - Know commonly used twisted-pair cable categories
        - Know cable types & characteristics
     
**DNP3 (Distributed Network Protocol 3)** is primarily used in the electric and water utility and management industries. It is used to support communications between data acquisition systems and the system control equipment. This includes substation computers, remote terminal units (RTUs) (i.e., devices controlled by an embedded microprocessor), intelligent electronic devices (IEDs), and SCADA primary stations (i.e., control centers). DNP3 is an open and public standard. It is a multilayer protocol that functions similarly to TCP/IP in that it has link, transport, and transportation layers. It utilizes the **Data Link Layer** for reliable node-to-node data transfer. and at the **Trasnsport layer**, DNP3 uses this layer to provide end-to-end communication, ensuring that data packets are transmitted across the network reliably and in the correct sequence. And At the **Application Layer**, DNP3 defines the format of messages, the functions that can be requested (e.g., reading or writing data points), and the way in which data points are represented. At the **Network layer**, DNP3 messages can be encapsulated within IP packets for transmission over IP networks.

***TCP/IP Model***
        - Application layer
        - Transport layer
        - Internet layer
        - Network Access layer

- 4.1.2 Internet Protocol (IP) networking (e.g., Internet Protocol Security (IPSec), Internet Protocol (IP) v4/6)
     - IP is part of the TCP/IP (Transmission Control Protocol/Internet Protocol) suite
        - TCP/IP is the name of IETF's four-layer networking model, and its protocol stack; the four layers are link (physical), internet (network-to-network), transport (channels for connection/connectionless data exchange) and application (where apps make use of network services)
        - IP provides the foundation for other protocols to be able to communicate; IP itself is a connectionless protocol
        - IPv4: dominant protocol that operates at layer 3; IP is responsible for addressing packets, uses 32-bit addresses
        - IPv6: modernization of IPv4, uses 128-bit addresses, supporting 2128 hosts
        - TCP or UDP is used to communicate over IP 
        - IPSec provides data authentication, integrity and confidentiality
    - **Logical address**: occurs when an address is assigned and used by software or a protocol rather than being provided/controlled by hardware
    - Network layer’s packet header includes the source and destination IP addresses
    - Network Access Layer: defines the protocols and hardware required to deliver data across a physical network
    - Internet Layer: defines the protocols for logically transmitting packets over the network
    - Transport Layer: defines protocols for setting up the level of transmission service for applications; this layer is responsible for the reliable transmission of data and the error-free delivery of packets
    - Application Layer: defines protocols for node-to-node application communication and provides services to the application software running on a computer

- **IPv4**: 
 - Format: IPv4 addresses are 32-bit numerical labels written in decimal format as four octets separated by periods (e.g., 192.168.1.1).
 - Size: The IPv4 header is 20 to 60 bytes in length.
 - Fragmentation: Routers can fragment IPv4 packets to accommodate the maximum transmission unit (MTU) of the network path.
 - Built-in Security: IPv4 does not have built-in security features, but it can use IPsec (Internet Protocol Security) for encryption and authentication.

- **IPv6**:
 - Format: IPv6 addresses are 128-bit hexadecimal labels written in eight groups of four hexadecimal digits separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
 - Size: The IPv6 header is 40 bytes in length.
 - Fragmentation: IPv6 requires fragmentation to be handled by the sending host rather than by routers, improving efficiency.
 - Built-in Security: IPv6 was designed with IPsec as a mandatory component, providing native support for encryption and authentication.

- **Multicast:** One to Many. Supported by both IPv4 and IPv6.
- **Broadcast:** One to all. Not Supported by IPv6. IPv6 replaces broadcast with multicast and anycast to improve network efficiency and reduce unnecessary traffic.
- **Unicast:** One to One communication. Supported by bothIPv4 and IPv6.
- **Anycast:** From single source to the nearest or optimal recipient or group of recipients. Supported natively by IPv6. Used for CDN and for streaming.
- The means by which IPv6 and IPv4 can coexist on the same network is to use one or more of three primary options: dual stack, tunneling, or NAT-­PT.
    - Dual stack is to have most systems operate both IPv4 and IPv6 and use the appropriate protocol for each conversation.
    - Tunneling allows most systems to operate a single stack of either IPv4 or IPv6 and use an encapsulation tunnel to access systems of the other protocol.
    - Network Address Translation-­Protocol Translation (NAT-­PT) (RFC-­2766) can be used to convert between IPv4 and IPv6 network segments similar to how NAT converts between internal and external addresses.

- 4.1.3 Secure protocols
    - **Kerberos**: standards-based network authentication protocol, used in many products (most notably Microsoft Active Directory Domain Services or AD DS)     
        - Kerberos is mostly used on LANs for organization-wide authentication, single sign-on (SSO) and authorization

    - SSL and TLS: data protection used for protecting website transactions (e.g. banking, ecommerce)
        - SSL and TLS both offer data encryption, integrity and authentication 
        - TLS has supplanted SSL (the original protocol, considered legacy/insecure) 
        - TLS was initially introduced in 1999 but didn’t gain widespread use until years later
        - The original versions of TLS (1.0 and 1.1) are considered deprecated and organizations should be relying on TLS 1.2 or TLS 1.3
        - TLS supports both one-­way and two-­way authentication.
        - TLS and SSL are not interoperable or backward compatible.
    - **SFTP**: a version of FTP that includes encryption and is used for transferring files between two devices (often a client / server)
    - **SSH**: remote management protocol, which operates over TCP/IP
        - all communications are encrypted
        - primarily used by IT administrators to manage devices such as servers and network devices
    - **IPSec**: an IETF standard suite of protocols that is used to connect nodes (e.g. computers or office locations) together
        - widely used in virtual private networks (VPNs)
        - IPSec provides encryption, authentication and data integrity

- 4.1.4 Implications of multilayer protocols
    - TCP/IP is a multilayer protocol, and derives several associated benefits
        - this means that protocols can be encapsulated within others (e.g. HTTP is encapsulated within TCP, which is in turn encapsulated in IP, which is in Ethernet), and additional security protocols can also be encapsulated in this chain (e.g. TLS between HTTP and TCP, which is HTTPS)
        - note that VPNs use encapsulation to enclose (or tunnel) one protocol inside another
    - Multilayer benefits:
        - many different protocols can be used at higher layers
        - encryption can be incorporated (at various layers)
        - it provides flexibility and resiliiency in complex networks
    Multilayer disadvantages:
        - nothing stops an added layer from being covert
        - encapsulating can be used to bypass filters: Encapsulation is both a benefit and a potentially harmful implication of multilayer protocols. Encapsulation allows for encryption, flexibility, and resiliency, while also enabling covert channels, filter bypass, and overstepping network segmentation boundaries.
        - logical network segments can be traversed
        - Generally, Multilayer protocols include the risk of VLAN hopping, multiple encapsulation, and filter evasion using tunneling.

- 4.1.5 Converged protocols (e.g., Fiber Channel Over Ethernet (FCoE), Internet Small Computer Sysetms Interface (iSCSI), Voice over Internet Protocol (VoIP))
    - **Converged protocols**: merged specialty or proprietary with standard protocols, such as those from the TCP/IP suite
        - converged protocols provide the ability to use existing TCP/IP supporting network infrastructure to host special or proprietary services without the need to deploy different hardware
    - Examples of converged protocols:
        - **Storage Area Network (SAN)**: a secondary network (distinct from the primary network) used to consolidate/manage various storage devices into single network-accessible storage
           -  In some instances, a SAN may implement deduplication in order to save space by not retaining multiple copies of the same file. However, this can sometimes result in data loss if the one retained original is corrupted.
           -  ✏️Deduplication replaces multiple copies of a file with a pointer to one copy. If the one remaining file is damaged, then all of the linked copies are damaged or inaccessible as well.
           -  Deduplication: is particularly effective when an organization is dealing with a large amount of redundant data, as it ensures that only unique instances of data are stored, thereby optimizing storage utilization and improving overall efficiency.
           -  Compression: While compression reduces the size of data, it does not specifically address the problem of redundant data. Compression can help save space but may not be as effective in cases where the primary issue is data redundancy.
           -  Caching: Caching improves performance by temporarily storing frequently accessed data in a faster storage medium, but it does not address storage issues related to redundant data. It’s more about speeding up access rather than optimizing storage space.
        - **Fibre Channel over Ethernet (FCoE)**: operating at 🧠Data Link Layer (layer 2), Fibre Channel is a network data-storage solution (SAN or network-attached storage (NAS)) that allows for high-speed file transfers of (up to) 🧠128 Gbps
        - designed to be operated over fiber-optic cables support for copper cables was added later to offer less expensive options. Fibre Channel typically requires its own dedicated infrastructure (separate cables). However, Fibre Channel over Ethernet (FCoE) can be used to support it over the existing network infrastructure. 
            - FCoE can be used over existing network infrastructure
            - FCoE typically requires 🧠10 Gbps Ethernet in order to support the Fibre Channel protocol.
            - FCoE used to encapsulate Fibre Channel over Ethernet networks
            - with this technology, FCoE operates at Layer 2, but the Fibre Channel operates as a Network layer (OSI layer 3) protocol, replacing IP as the payload of a standard Ethernet network. So FCoE often relies on an underlying Layer 3 infrastructure (such as IP) to handle network routing and management tasks. 
        - **Internet Small Computer Sysetms Interface (iSCSI)**: operating at 🧠Network Layer (OSI layer 3), iSCSI is a network storage standard based on IP, used to enable location-independent file storage, transmission, and retrieval over LAN, WAN, or public internet connections. It encapsulates SCSI commands and responses within TCP/IP packets, which means it operates over IP networks at the transport layer (Layer 4) but leverages the network's Layer 3 capabilities for addressing and routing.
        - **Multiprotocol Label Switching (MPLS)**: a WAN protocol that operates at both layer 2 and 3 and does label switching; MPLS is a high-throughput/high-performance network technology that directs data across a network based on 🧠short path labels rather than longer network addresses. It requires the first router in the path to determine the full path the packet will travel, removing the need for other routers in the path to make independent determinations.
        - **Voice over Internet Protocol (VoIP)**: a tunneling mechanism that encapsulates audio, video, and other data into IP packets to support voice calls and multimedia collab
            - VoIP is considered a converged protocol because it combines audio and video encapsulation technology (operating as application layer protocols) with the protocol stack of TCP/IP
        - **Infini Band Over Ethernet**: a network protocol that allows remote direct memory access (RDMA) over ethernet network. It is a low-latency high throughput networking technology commonly used in high-performance computing (HPC), data centers, and enterprise environments. Supports speeds of up to 🧠200Gbps per link.
        - **Compute Express Link (CXL)**: is an open standard interconnect designed to improve communication between CPUs and other high-speed devices such as accelerators, memory expanders, and smart I/O devices. It is used for high-speed, high-capacity CPU-to-Device and CPU-to-Memory connections.


- 4.1.6 Micro-segmentation:
- **Micro-Segmentation**: involves creating fine-grained, policy-driven segments that can isolate individual workloads or devices. It takes the concept of logical segmentation to a more granular level. The small segments contain specific workload or functionally similar or identical nodes. It limits scope of breach and lateral movement. Cisco Trsutsec is an example of Micro segmentation.
- Microsegmentation can be implemented using internal segmentation firewalls (ISFWs), transactions between zones are filtered, and it can be implemented with virtual systems and virtual networks. (e.g., Software Defined Networks (SDN), Virtual eXtensible Local Area Network (VXLAN),Encapsulation, Software-Defined Wide Area Network (SD-WAN))
    - **Software-defined networks (SDN)**:
        - SDN is a broad range of techniques enabling network management, routing, forwarding, and control functions to be directed by software
        - SDN is effectively network virtualization, and separates the infrastructure layer (aka the data or forwarding plane) - hardware and hardware-based settings, from the control layer - network services of data transmission management
            - NOTE: the **control plane**: uses protocols to decide where to send traffic, and the **data plane**: includes rules that decide whether traffic will be forwarded
        - typically ABAC-based
        - an SDN solution provides the option to handle traffic routing using simpler network devices that accept instructions from the SDN controller
        - SDN offers a network design that is directly programmable from a central location, is flexible, vendor neutral, and based on open standards
        - Allows org to mix/match hardware
    - **Virtual extensible local area network (VXLAN)**:
        - an encapsulation protocol that enables VLANs to be stretched across subnets and geographic distances
        - VLANs allow network admins to use switches to create software-based LAN segments that can be defined based on factors other than physical location
        - Typically restricted to layer 2
        - Allows up to 16 million virtual networks (VLAN limit is 4096)
        - VXLAN can be used as a means to implement microsegmentation without limiting segments to local entities only
        - Defined in RFC 7348

    - Encapsulation:
        - the OSI model represents a protocol stack, or a layered collection of multiple protocols, and communication between protocol layers occurs via encapsulation and deencapsulation (defined above)

    - **Software-defined wide area network (SD-WAN)**: an evolution of SDN that can be used to manage the connectivity and control services between distant data centers, remote locations, and cloud services over WAN links; put another way, SDN-WAN is an extension of SDN practices to connect entities spread across the internet, supporing WAN architecture; espcially related to cloud migration
    - **Transport Architecture**:
     - Management Plane: The management plane is responsible for network administration tasks. It handles configuration, monitoring, security management, and policy enforcement. E.g SNMP, SSH, NETCONF
     - Control Plane: is responsible for making decisions and determine optimal paths about where and how data packets should be forwarded. It manages routing, signaling, and network topology. E.g routing protocols like OSPF, BGP
     - Data Plane: is responsible for the actual movement of packets through the network. It handles the forwarding of data based on the decisions made by the control plane. e.g QOS, packet forwarding by switch or router using mac address table or routing tables respectively, packet filtering e.g firewalls, load balancers
       - Cut-Through Switching:  is a method of forwarding packets in which a switch starts forwarding a frame before the entire frame has been received. There is minimal error checking and it is used in low-latency networks
       - Store-and-forward Switching: is a method where the entire frame is received and error-checked before being forwarded. Used in environements where liability is essential. 

- **Network Segmentation**: Benefits include boosting performance where system that need to communicate are located in the same segment. It reduces communication problems such as broadcast storms to individual segments, and improves security by isolating traffic to segments
  - Intranet: Data traffic that moves between a data center and external networks or clients.
  - Extranet: A controlled private network allowing access to partners, vendors, or clients. This section of the network has been sectioned off to act as as an intranet for the private network but also to serve information to the public internet. A cross between the internet and the intranet.
  - DMZ: A buffer zone between the internal network and the external network, hosting public-facing services. An extranet for public consumption. Typically labelled perimeter network. DMZ is a specific implementation with a focus on isolating external-facing services from the internal network. 
  - Screened subnet: is a type of security zone that can be positioned so that it operates as a buffer network between the secured private network and the internet and can host publicly accessible services. It is often placed between an internal network and an external network and can be seen as a specific type of DMZ.
 - **Physical Segmentation**:
   - Out-of-Band: physically seperating networks into distinct zones using hardware. It is an alternate communication path for different types of traffic.
   - Air Gap: Complete physical isolation of a network by having no wired or wireless communications. Common in high security government networks or critical infrastructures e.g industrial systems and public utilities.
 - **Logical Segmentation**:
   - In-Band: seperate networks by configuring routers, switches, firewalls to control traffic flow e.g subnets, VLANs
        - Switches: switch is a networking device that can be used to create 🔥digital virtual network segments (i.e., VLANs) that can be altered as needed by adjusting the settings internal to the device.
        - Router: Provides connection to disparate networks (i.e., subnets)
        - Proxy and Firewalls: Can be positioned between network segments to control and manage traffic
   - Virtual Routing and Forwarding: facilitates the co-existence of multiple routing table instances on a router simultenously
   - Virtual Domain: Network segments/chunks created through logical segmentation techniques like VRFs. In the VRF context, they are called VRF domains. Virtual domains (often referred to as virtual contexts or virtual systems) allow for the creation of separate, isolated security domains within a single firewall or security device.
- **Firewall Types**: 
   - **Next-­generation firewall (NGFW)** is a unified threat management (UTM) device that is designed to provide advanced security features at the network perimeter and is based on a traditional firewall with numerous other integrated network and security services. It provides a comprehensive range of security features, including perimeter protection, application control, and advanced threat detection.
   - **Internal Segmentation Firewall (ISFW)** is a security device or technology used to enforce security policies and controls within an internal network, particularly to segment different internal network zones. Unlike traditional firewalls that primarily focus on perimeter security, an ISFW operates within the internal network to create additional layers of security. It focuses on internal network segmentation and access control between internal segments.
   - **Application-­level firewall** is able to make access control decisions based on the content of communications as well as the parameters of the associated protocol and software.
   - **Web Application Firewall WAF**: is a software-based app that monitors and filters exchanges between applications and a host; usually inspect and filter conversations like HTTP/S. It is an appliance, server add-­on, virtual service, or system filter that defines a strict set of communication rules for a website
   - **Stateful inspection firewalls** make access control decisions based on the content and context of communications, but are not typically limited to a single application-­layer protocol.
   - **Circuit-­level firewalls** are able to make permit and deny decisions in regard to circuit establishment either based on simple rules for IP and port, using captive portals, requiring port authentication via 802.1X, or more complex elements such as context-­or attribute-­based access control.
   - **Static packet-­filtering firewalls** filter traffic by examining data from a message header. Usually, the rules are concerned with source and destination IP address (layer 3) and port numbers (layer 4).
   - **TCP Wrapper**: is a host-based access control system that can be used to restrict access to Internet services based on IP address or hostname. It acts as a gateway between network services and the network, allowing administrators to control which hosts can connect to services like SSH, FTP, and others. TCP Wrapper allows administrators to specify which hosts (by IP address or hostname) are allowed or denied access to specific services, such as SSH, FTP, or HTTP, based on the requesting host.

- 4.1.7 Wireless networks (e.g. LiFi, Wi-Fi, Zigbee, satellite)

    - Li-Fi: **light fidelity (Li-Fi)**: a form of wireless communication technology that relies on light to transmit data, with theorectical speeds up to 224Gbits/sec. It is not susceptible to EM interference
    - **Wi-Fi**: Wirless LAN IEEE 802.11x; associated with computer networking, Wi-Fi uses 802.11x spec to create a public or private wireless LAN
        - **Wired Equivalent Privacy (WEP)**:
            - WEP is defined by the original IEEE 802.11 standard
            - WEP uses a predefined shared Rivest Cipher 4 (RC4) secret key for both authentication (SKA) and encryption
            - Shared key is static
            - WEP is weak from RC4 flaws 
        - **Wi-Fi Protected Access II (WPA2)**:
            - IEEE 802.11i WPA2 replaced WEP and WPA.
            - WPA2 enterprise uses 🔥RADIUS authentication for users rather than a preshared key. This means a password attack is more likely to fail as password attempts for a given user may result in account lockout.
            - EAP is an authentication framework used in wireless networks to provide various methods for authenticating users. In WPA2, 🔥EAP is often used in conjunction with the Advanced Encryption Standard (AES) to provide strong encryption and secure authentication for wireless communications.
            - Uses AES-CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol)
        - Frequency table:
            
        | Amendment | Wi-Fi Alliance | Speed | Frequency |
        |-----|---------------| -------------------|------------|
        | 802.11    |   --   | 2 Mbps |2.4 GHz               |
        | 802.11a   |  Wi-Fi 2    | 54 Mbps |5 GHz                |
        | 802.11b   |  Wi-Fi 1    | 11 Mbps |2.4 GHz              |
        | 802.11g   |  Wi-Fi 3    | 54 Mbps |2.4 GHz              |
        | 802.11n   |  Wi-Fi 4    | 200+ Mbps |2.4GHz or 5 GHz    |
        | 802.11ac   | Wi-Fi 5    | 1 Gbps  |5 GHz                |
        | 802.11ax   | Wi-Fi 6/Wi-Fi 6E     |9.5 Gbps |1-5(6)GHz  |

***Wi-Fi Protected Access 3 (WPA3)***: WPA3-ENT uses 192-bit AES CCMP encryption, and WPA3-PER remains at 128-bit AES CCMP. WPA3-PER replaces the preshared key authentication with Simultaneous Authentication of Equals (SAE). SAE performs a zero-knowledge proof process known as Dragonfly Key Exchange, which is itself a derivative of Diffie–Hellman. 

***802.1X/EAP***: WPA, WPA2, and WPA3 support the enterprise (ENT) authentication known as 802.1X/EAP, a standard port-based network access control. Through the use of 802.1X, other solutions such as Remote Authentication Dial-In User Service (RADIUS), Terminal Access Controller Access Control System (TACACS), certificates, smartcards, token devices, and biometrics can be integrated into wireless networks, providing techniques for both mutual and multifactor authentication.

***Extensible Authentication Protocol (EAP)***: is not a specific mechanism of authentication; rather it is an authentication framework. Effectively, EAP allows for new authentication technologies to be compatible with existing wireless or point-to-point connection technologies. More than 40 EAP methods have been defined, including ✏️LEAP, ✏️PEAP, ✏️EAP-­SIM, ✏️EAP-­FAST, ✏️EAP-­MD5, ✏️EAP-­POTP, ✏️EAP-­TLS, and ✏️EAP-­TTLS.

***LEAP***: Lightweight Extensible Authentication Protocol (LEAP) is a Cisco proprietary alternative to TKIP for WPA. This was developed to address deficiencies in TKIP before the 802.11i/WPA2 system was ratified as a standard. An attack tool known as asleap was released in 2004 that could exploit LEAP; use of EAP-TLS as an alternative is recommended, but if LEAP is used, a complex password is strongly recommended.

***PEAP***:Protected Extensible Authentication Protocol (PEAP) encapsulates EAP methods within a TLS tunnel that provides authentication and potentially encryption. Since EAP was originally designed for use over physically isolated channels and hence assumed secured pathways, EAP is usually not encrypted. So PEAP can provide encryption for EAP methods.

***CHAP***:Challenge-Handshake Authentication Protocol, or CHAP, is used by PPP servers to authenticate remote clients. It encrypts both the username and password and performs periodic reauthentication while connected using techniques to prevent replay attacks. 

***Password Authentication Protocol (PAP)***: PAP transmits usernames and passwords in cleartext. It offers no form of encryption; it simply provides a means to transport the logon credentials from the client to the authentication server. Also used by PPP servers.

***Zigbee***: IoT equipment communications concept based on Bluetooth. It requires close proximity of devices and communications are encrypted.
        - Low power/low throughput
        - Requires close proximity
        - Encrypted using 128-bit symmetric algorithm
        - Uses AES to prtect traffic
        
***Satellite***: primarily uses radio waves between terrestrial locations and an orbiting artificial satellite
        - Supports telephone, tv, radio, internet, military communications
        - 3 primary orbits:
            - LEO: low Earth orbit (160-2k km)
                - have stronger signals
                - multiple devices needed to maintain coverage (e.g. Starlink)
            - MEO: medium Earth orbit (2k-35768 km)
                - above a terrestrial location longer than LEO
                - higher orbit, additional delay/weaker signal
            - GEO: geostationary orbit (35768 km)
                - maintain a fixed position above a terrestrial location, and ground stations can use fixed antennas
                - larger transmission footprint than MEO, but higher latency

- **Network Performance Metrics**:
  -  Bandwidth: The maximum amount of data or capacity that can be transmitted over a network in a given amount of time. Theoretical maximum transfer rate. Key: A highway with many lanes can carry more cars than a highway with only one lane.
  -  Throughput: The actual amount of data successfully transferred over the network in a given amount of time. Actual data transfer rate considering factors like latency, packet loss and congestion. Key: How many cars actually pass through a toll booth per hour, not just how many cars the highway can theoretically handle.
  -  Latency: The time it takes for a data packet to travel from the source to the destination. It has an inverse relationship to throughput.
  -  Jitter: The variation in time delay between data packets arriving. Affects QOS for real-time applications. Key: If some cars on a highway arrive faster than others even though they left at the same time.
  -  Signal to Noise Ratio (SNR): A measure of the signal strength relative to background noise. Commonly used in wireless communications. Key: How clearly you can hear someone speaking in a noisy room; higher SNR means a clearer signal and less interferance.


- 4.1.8 Cellular networks (e.g. 4G, 5G)

    - A cellular network or a wireless network is the primary communications technology used by many mobile devices
    - Cells are primary transceiver (cell site/tower)
    - Generally encrypted between mobile device and transmission tower; plaintext over wire; use encryption like TLS/VPN
    - **4G**
        - 4G allows for mobile devices to achieve 100 Mbps, and stationary devices can reach 1 Gbps
        - LTE and WiMAX are common transmission systems
        - **WiMAX**: Broadband Wireless Access IEEE 802.16 is a well-known example of wireless broadband; WiMAX can potentially deliver data rates of > 30 Mbps
    - **5G**
        - 5G uses higher frequencies than previous tech, allowing for higher transmission speeds — up to 10 Gbps, but at reduced distances
        - 5G supports up to 10 Gbps
        - 5G coverage is the most limited since it is the latest technology and still not universally deployed
        - 5G tower covers less area than a 4G tower.
        - Orgs need to enforce security requirements on 5G
    - Security issues with wireless:
        - provider network (voice or data) is not necessarily secure
        - your cell phone can be intercepted
        - provider's towers can be simulated to conduct man-in-the-middle/on-path attack
        - using cell connectivity to access the internet or your office network creates a potential bridge, provider attackers with another avenue
    -  Cellular services, such as 4G and 5G, raise numerous security and operational concerns. Although cellular service is encrypted from device to tower, there is a risk of being fooled by a false or rogue tower. A rogue tower could offer only plaintext connections, but even if it supported encrypted transactions, the encryption only applies to the radio transmissions between the device and the tower. Once the communication is on the tower, it will be decrypted, allowing for eavesdropping and content manipulation. Even without a rogue tower, eavesdropping can occur across the cellular carrier’s interior network as well as across the internet, unless a VPN link is established between the remote mobile device and the network of the organization.
    -  Being able to establish a connection can be unreliable as 3G, 4G, and 5G coverage is not 100 percent available everywhere.
- **Traffic FLows**:
  - East-West Traffic: Data traffic that moves laterally within a data center, between servers or virtual machines. Involves trusted nodes and networks. Traffic remains withing the internal network or cloud. Access controls, micro-segmentation and isolations policies are used here for security.
  - North-South Traffic: Data traffic that moves between a data center and external networks or clients. Traffic moves to/from endpoints on internal network to nodes on the public cloud/internet. Involves untrusted nodes. This brings security concerns like data comprise, DDoS attacks, inadequate authentication. 

- 4.1.9 Content Distribution Networks (CDN)

    - **Content Distribution Network (CDN)**: a collection of resource services deployed in numerous data centers across the internet in order to provide low latency, high performance, and high availability of the hosted content
        - CDNs provide multimedia performance quality through the concept of distributed data hosts, geographically distributed, closer to groups of customers
        - Provides geographic and logical load balancing; lower-latency and higher-quality throughput
    - Client-based CDN is often referred to as P2P (peer-to-peer)

- 4.1.12 Edge Networks 
    - Distributed networks that bring compute and storage resources physically closer to end users and devices on the edge of the network.
    - **Ingress/Egress**: Entry point for traffic entering an edge network, usually from an end user device or an external network. Important for security monitoring and traffic shaping.
    - **Peering**: Direct interconnection between edge network locations to allow traffic exchange without travelling through a central hub. reduces latency and bottle necks which are problems in a hub-and-spoke topology.
    - **Caching**: Caching popular contents like video, audio and web pages. Provides better user experience in SaaS subscriber scenarios. eg CDNs.
    - **Compute**: Granular compute functions, containarized, to provide low-latency processing near end users and devices. Also known as Edge Computing. Edge computing is a technology that processes data near the source of data generation, such as IoT devices or local servers, rather than sending it to a central data center or cloud for processing.
    - **Storage**: Multiple edge locations to reduce latency for accessing data and updating data. E.g file servers that are synchronized across location like DFS.

- **Grid computing** is a form of distributed computing where multiple computers work together to solve complex problems or process large amounts of data. In simple terms, it's like combining the power of many computers to achieve a task more efficiently than a single computer could alone.
     - In many grid computing implementations, grid members can access the contents of the distributed work segments or divisions.
     - Grid computing over the internet is not usually the best platform for sensitive operations.
     - Grid computing is able to handle and compensate for latency of communications, duplicate work, and capacity fluctuation.
       
- 4.1.17 Virtual Private Cloud (VPC)
    - Virtual networks, public and private subnets, segmentation and API inspection and integration are important elements of cloud security.
    - VPC is a virtual network that consists of cloud resources, where the VM of one company is isolated from the resources of another company.
    - Seperate VPCs can be isolated using public or private networks or segmentation. This concept exists in all major public clouds. It is refered to as VPC in AWS & Google Cloud Platforms. It is referred to as Virtual Networks (VNET) in Azure.
 
- 4.1.18 Monitoring and Management
    - Network Observability: Invloves collecting data and gaining visibility into the status and performance of network components and traffic flows. Supports issue identificaton and troubleshooting.
    - Traffic FLow/Traffic Shapping: Managing and controlling the volume and priorities of different types of traffic. E,g QOS (priority to certain traffic such as real-time traffic), rate limitting (example API limiting to number of API requests that can be made by a single user in a specific period of time), throttling.
    - Capacity Management: Tracking network utilization and planning capcity expansion to meet future demands.
    - Fault Detection and Handling: Discovering, diagnosing and responding to problems like failed devices, connectivity losses, performance slow downs. includes alerting and automatic failover. 

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

- 4.2.2 Transmission media
    - Transmission Media: comes in many forms, not just cables
        - includes wireless, LiFi, Bluetooth, Zigbee, satellites
        - most common cause of network failure (i.e. violations of availability) are cable failures or misconfigurations
        - wired transmission media can typically be described in three categories: coaxial, Ethernet, fiber
        - coaxial is typically used with cable modem installations to provide connectivity to an ISP, and requires a modem to convert the analog signals to digital
            - fairly resistent to EMI
            - longer lengths than twisted pair
            - requires segment terminators
            - two main types:
                - **thinnet (10Base2)**: used to connect systems to backbond trunks of thicknet cabling (185m, 10Mbps)
                - **thicknet (10Base5)**: can span 500 meters and provide up to 10Mbps
        - ethernet can be used to describe many mediums, it is typically associated with Category 5/6 unshielded twisted-pair (UTP) or shielded twisted pair (STP), and can be plenum-rated
        - fiber typically comes in two options: single-mode or multi-mode
            - Single-mode is typically used for long-distance communication, over several kilometers or miles
            - Multi-mode fiber is typically used for faster transmission, but with a distance limit depending on the desired speed
            - Fiber is most often used in the datacenter for backend components

        | Category | Throughput | Notes |
        |----------|------------|--------|
        | Cat 1    |   1 Mbps   |        |
        | Cat 2    |   4 Mbps   |        |
        | Cat 3    |   10 Mbps  |        |
        | Cat 4    |   16 Mbps  |        |
        | Cat 5    |   100 Mbps |        |
        | Cat 5e   |   1 Gbps   |        |
        | Cat 6    |   1 Gbps   |        |
        | Cat 6a   |   10 Gbps  |        |
        | Cat 7    |   10 Gbps  |        |
        | Cat 8    |   40 Gbps  |        |

- 4.2.3 Network Access Control (NAC) devices
- Port security can refer to several concepts, including network access control (NAC), Transport layer ports, and RJ-­45 jack ports. 📝NAC requires authentication before devices can communicate on the network. 📝Transport-­layer port security involves using firewalls to grant or deny communications to TCP and UDP ports. 📝physical control of all connection points. RJ-­45 jacks should be managed so that unused ports are disabled and that when a cable is disconnected, the port is disabled. This approach prevents the connection of unauthorized devices.
    - **Network Access Control (NAC)**: the concept of controlling access to an environment through strict adherence to and enforcement of security policy
    - NAC is meant to be an automated detection and response system that can react in real time, ensuring all monitored systems are patched/updated and have current security configurations, as well as keep unauthorized devices out of the network. 📝 Note that it cannot reduce social engineering threats.
    - NAC goals:
        - prevent/reduce known attacks directly (and zero-day attacks indirectly)
        - enforce security policy throughout the network
        - use identities to perform access control
        - detect/block rogue devices
    - NAC can be implemented with a preadmission or postadmission philosophy:
        - **preadmission philosohpy**: requires a system to meet all current security requirements (such as patch application and malware scanner updates) before it is allowed to communicate with the network
        - **postadmission philosophy**: allows and denies access based on user activity, which is based on a predefined authorization matrix
    - Agent-based NAC:
        - installed on each management system, checks config files regularly, and can quarantine for non-compliance
        - dissolvable: usually written in a web/mobile language and is executed on each local machine when the specific management web page is accessed (such as captive portal)
        - permanent: installed on the monitored system as a persistent background service
    - Just as you need to control physical access to equipment and wiring, you need to use logical controls to protect a network; there are a variety of devices that provide this type of protection, including:
        - stateful and stateless firewalls can perform inspection of the network packets and use rules, signatures and patterns to determine whether the packet should be delivered. Circuit-level firewalls (aka circuit proxies) are used to estab-
lish communication sessions between trusted partners. In theory, they operate at the
Session layer (layer 5) of the OSI model.
            - reasons for dropping a packet could include addresses that don’t exist on the network, ports or addresses that are blocked, or the content of the packet (e.g malicious packets blocked by admin policy)
            - Tier 1 Firewall - One protected Zone e.g Internet & Tier 2 Firewall - Two Protected Zones e.g Internet and DMZ and so on.
        - IDP devices, which monitor the network for unusual network traffic and MAC or IP address spoofing, and then either alert on or actively stop this type of traffic
        - proxy/reverse proxies: 
            - proxy servers can be used to proxy internet-bound traffic, instead of letting clients talk directly
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
- **Endpoint detection and response (EDR)** is a security mechanism that is an evolution of traditional antimalware products. EDR seeks to detect, record, evaluate, and respond to suspicious activities and events, which may be caused by problematic software or by valid and invalid users.
    - It is a natural extension of continuous monitoring, focusing on both the endpoint device itself and network communications reaching the local interface.
    - Some EDR solutions employ an on-­device analysis engine whereas others report events back to a central analysis server or to a cloud solution.
    - The goal of EDR is to detect abuses that are potentially more advanced than what can be detected by traditional antivirus or HIDSs, while optimizing the response time of incident response, discarding false positives, implementing blocking for advanced threats, and protecting against multiple threats occurring simulta neously and via various threat vectors.
- **Managed detection and response (MDR)**: focuses on threat detection and mediation but is not limited to the scope of endpoints. MDR is a service that attempts to monitor an IT environment in real-time to quickly detect and resolve threats. Often an MDR solution is a combination and integration of numerous technologies, including SIEM, network traffic analysis (NTA), EDR, and IDS.
- **Endpoint protection platform (EPP)**: is a variation of EDR much like IPS is a variation of IDS. The focus on EPP is on four main security functions: predict, prevent, detect, and respond. Thus, EPP is the more active prevent and predict variation of the more passive EDR concept.
- **Extended detection and response (XDR)**: components often include EDR, MDR, and EPP elements. Also, XDR is not solely focused on endpoints, but often includes NTA, NIDS, and NIPS functions as well. Managed security service provider (MSSP) can provide XDR solutions that are centrally controlled and managed.
- **Managed security service provider MSSP**: solutions can be deployed fully on-premise, fully in the cloud, or as a hybrid structure, and can be overseen through a SOC which is itself local or remote. Typically, working with an MSSP to provide EDR, MDR, EPP, or XDR services can allow an organization to gain the benefits of these advanced security products and leverage the experience and expertise of the MSSP's staff of security management and response professionals. MDR combines antimalware capabilities with a managed service that reduces the burden on the IT team.

[4.3](#4.3) Implement secure communication channels according to design ((OSG-9 Chpt 12))
- Protocols that provide security services for application-specific communication channels are called secure communication protocols
- 4.3.1 Voice
    - **Voice of Internet Protocol (VoIP)**: set of technologies that enables voice to be sent over a packet network
    - As more orgs switch to VoIP, protocols like SIP become more common, and introducing additional management, either via dedicated voice VLANs, or by establishing quality of service (QoS) levels to ensure voice traffic priority
    - Web-based voice apps can be more difficult to manage, causing additional unplanned bandwidth consumption
    - VoIP is at risk for caller ID spoofing, vishing, call manager software/firmware attacks, phone hardware attacks, DoS, MitM/on-path attacks, spoofing, and switch hopping.
    - Phreaking is a specific type of attack in which various types of technology are used to circumvent the telephone system to make free long-distance calls, to alter the function of telephone service, to steal specialized services, or to cause service disruptions. A phreaker is an attacker who performs phreaking. 
    - Vishing: Anyone who can receive a call, whether using a traditional PSTN landline, a PBX business line, a mobile phone, or a VoIP solution, can be the target of a VoIP-originated voice-based social engineering attack. This type of attack is known as voice-based phishing.
    -  Countermeasures must be deployed to protect against interception, eavesdropping, tapping, and other types of exploitation.
    -   Countermeasures to PBX fraud and abuse include Changing default passwords on PBX systems and it provides the most effective increase in security since PBX systems typically do not support encryption, although some VoIP PBX systems may support encryption in specific conditions.
    -   PBX and PSTN voice communications are vulnerable to interception, eavesdropping, tapping, and other exploitations. Often, physical security is required to maintain control over voice communications within the confines of your organization’s physical locations.
    -   Many PBX systems can be exploited by malicious individuals to avoid toll charges and hide their identity. Phreakers may be able to gain unauthorized access to personal voice mailboxes, redirect messages, block access, and redirect inbound and outbound calls.
    -   Countermeasures to PBX fraud include:
        - Consider replacing remote access or long-distance calling through the PBX with a credit card or calling card system.
        - Restrict dial-in and dial-out features to authorized individuals who require such functionality for their work tasks.
        - If you still have dial-in modems, use unpublished phone numbers that are outside the prefix block range of your voice numbers.
        - Protect administrative interfaces for the PBX.
        - Block or disable any unassigned access codes or accounts.
        - Define an acceptable use policy and train users on how to properly use the system.
        - Log and audit all activities on the PBX and review the audit trails for security and use violations.
        - Disable maintenance modems (i.e., remote access modems used by the vendor to remotely manage, update, and tune a deployed product) and/or any form of remote administrative access.
        - Change all default configurations, especially passwords and capabilities related to administrative or privileged features.
        - Block remote dialing.
        - Keep the system current with vendor/service provider updates.
        - Deploy direct inward system access (DISA) technologies to reduce PBX fraud by external parties. Direct inward system access (DISA), like any other security feature, must be properly installed, configured, and monitored in order to obtain the desired security improvement. DISA adds authentication requirements to all external connections to the PBX. 
    -   Securing VoIP communications often involves specific application of many common security concepts:
        - Use strong passwords and two-factor authentication.
        - Record call logs and inspect for unusual activity.
        - Block international calling.
        - Outsource VoIP to a trusted SaaS.
        - Update VoIP equipment firmware.
        - Restrict physical access to VoIP-related networking equipment.
        - Train users on VoIP security best practices.
        - Prevent ghost or phantom calls on IP phones by blocking nonexistent or invalid-origin numbers.
        - Implement NIPS with VoIP evaluation features.

- **Switching Technologies**

| Circuit Switching      | Packet Switching      | 
|------------------------|-----------------------|
| Constant traffic   | Bursty traffic   |
| Fixed known delays | Variable Delays |
| Connection oriented | Connectionless |
| Sensitive to connection loss | Sensitive to data loss |
| Used primarily for voice | Used for any type of traffic |
| Outdated | Modern |

- **A virtual circuit**: (also called a communication path) is a logical pathway or circuit created over a packet-switched network between two specific endpoints. Within packet-switching systems are two types of virtual circuits: 
    - Permanent virtual circuits (PVCs): A PVC is like a dedicated leased line; the logical circuit always exists and is waiting for the customer to send data. A PVC is a predefined virtual circuit that is always available. The virtual circuit may be closed down when not in use, but it can be instantly reopened whenever needed.  A PVC is like a two-way radio or walkie-talkie. Whenever communication is needed, you press the button and start talking; the radio reopens the predefined frequency automatically (that is, the virtual circuit).
    - Switched virtual circuits (SVCs): An SVC has to be created each time it is needed using the best paths currently
available before it can be used and then disassembled after the transmission is complete. An SVC is more like a shortwave or ham radio. You must tune the transmitter and receiver to a new frequency every time you want to communicate with someone.
- In either type of virtual circuit, when a data packet enters point A of a virtual circuit connection, that packet is sent directly to point B or the other end of the virtual circuit. However, the actual path of one packet may be different from the path of another packet from the same transmission. In other words, multiple paths may exist between point A and point B as the ends of the virtual circuit, but any packet entering at point A will end up at point B.

- **WAN Technologies**
    - **A dedicated line (also called a leased line or point-to-point link)** is one that is continually reserved for use by a specific customer. A dedicated line is always on and waiting for traffic to be transmitted over it. The link between the customer’s LAN and the dedicated WAN link is always open and established. A dedicated line connects two specific endpoints and only those two endpoints. This type of connection is often used between multiple business locations, so they can effectively communicate as a single entity.
     - There have been numerous types of dedicated lines over the years, ranging from the T1 (telephone line 1 with 1.54 Mbps capacity) to T3 or DS3 (Digital Service 3 with 44.7 Mbps capacity). Other options included X.25, Asynchronous Transfer Mode (ATM), and Frame Relay. These technologies have mostly been replaced by fiber optic–based solutions.
    - **A nondedicated line** is one that requires a connection to be established before data transmission can occur. A nondedicated line can be used to connect with any remote system that uses the same type of nondedicated line. Standard classic modems and DSL modems are examples of nondedicated lines. Digital subscriber line (DSL) is a technology that exploits the upgraded telephone network to grant consumers speeds from 144 Kbps to 20 Mbps (or more). There are numerous formats of DSL, such as ADSL, xDSL, CDSL, HDSL, SDSL, RASDSL, IDSL, and VDSL. Each format varies as to the specific downstream and upstream bandwidth provided.
    - **Cable TV–based internet service** does not fit well into either the dedicated or the nondedicated classification. Cable internet is an always-on system, but not between two client locations. Instead, it is a link from your premises to an internet gateway. Thus, it can be labeled as a point-to-multipoint connection. 
  
- 4.3.2 Multimedia collaboration
    - There are a variety of new technologies that allow instant organizational collaboration, including smartboards, and products that enhance on-site, hybrid, or virutal meetings
    - Mobile communication apps are a huge market, and will continue to grow, increasing the complexity of mobile security
- 4.3.3 Remote access
    - 4 main types of remote access:
        - **service specific**: gives users the ability to remotely connect to and manipulate or interact with a single service (e.g. email)
        - **remote-control**: grants a remote user the ability to fully control another system that is physically distant
        - **remote node operation**: AKA remote client connecting directly to a LAN
        - **screen scraping**: refers to 1) remote control, remote access, or remote desktop services or 2) technology that allows an automated tool to interact with a human interface
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

- 4.3.4 Data communications   
    - Whether workers are physically in an office or working remotely, communication between devices should be encrypted to prevent any unauthorized device or person from openly reading the contents of packets as they are sent across a network
    - Corporate networks can be segmented into multiple VLANs to separate different types of resources
    - Communications should be encrypted using TLS or IPSec
- 4.3.5 Virtualized networks
    - Allow adopting things like software-defined networks (SDNs), VLANs, virtual switches, virtual SANs, guest OSs, port isolation etc
    - Many orgs are moving to the cloud, and not continuing to build out local or on-site server infrastructure
        - however, organizations still use hypervisors to virtualize servers and desktops for increased density and reliability
            - to host multiple servers on a single hypervisor, the Ethernet and storage networks must also be virtualized 
            - VMware vSphere and Microsoft Hyper-V both use virtual network and storage switches to allow communication between virtual machines and the physical network; guest OSs running in the VMs use a synthetic network or storage adapter, which is relayed to the physical adapter on the host
            - Securing virtual machine images and snapshots is a key consideration when designing secure virtualization environments. Virtual machines can be easily copied or cloned, potentially exposing sensitive data or allowing unauthorized access. Proper security measures must be taken to secure virtual machine images and snapshots.
            - SDN on the hypervisor can control the VLANs, port isolation, bandwidth and other aspects just as if it was a physical port
- 4.3.6 Third-party connectivity
    - Any time an org’s network is connected directly to another entity’s network, their local threats and risks affect each other
        - **memorandum of understanding (MOU)** or **memorandum of agreement (MOA)**: (Note: MOU = letter of intent) an expression of agreement or aligned intent, will, or purpose between two entities
        - **interconnection security agreement (ISA)**: a formal declaration of the security stance, risk, and technical requirements of a link between two organizations’ IT infrastructures
    - Remote workers are another form of third-party connectivity
    - Vendors (like IT auditing firms) may need to connect to your network, and attackers are routinely looking for creative ways to gain organizational access -- third-party connectivity is one option
    - As organizations evaluate third-party connectivity, they need to look carefully at the principle of least privilege and at methods of monitoring use and misuse

- **EMAIL SECURITY**: The email infrastructure employed on the internet primarily consists of email servers using Simple Mail Transfer Protocol (SMTP) (TCP port 25) to accept messages from clients, transport those messages to other servers, and deposit them into a user’s server-based inbox. In addition to email servers, the email infrastructure includes email clients. Clients retrieve email from their server-based inboxes using Post Office Protocol version 3 (POP3) (TCP port 110) or Internet Message Access Protocol (IMAP) (technically version 4) (TCP port 143). Internet-compatible email systems rely on the X.400 standard for addressing and message handling. Sendmail is the most common SMTP server for Unix systems, and Exchange is the most common SMTP server for Microsoft systems.
- SMTP is designed to be a mail relay system. This means it relays mail from sender to intended recipient. However, you want to avoid turning your SMTP server into an open relay (also known as an open relay agent or relay agent), which is an SMTP server that does not authenticate senders before accepting and relaying mail. Open relays are prime targets for spammers because they allow spammers to send out floods of emails by piggybacking on an insecure email infrastructure. As open relays are locked down—becoming closed relays or authenticated relays—adversaries are often resorting to hijacking authenticated user accounts through social engineering or credential stuffing/spraying/guessing attacks.
- Email Security goals include:
    - Restrict access to messages to their intended recipients (i.e., privacy and confidentiality)
    - Maintain the integrity of messages
    - Authenticate and verify the source of messages
    - Provide for nonrepudiation
    - Verify the delivery of messages
    - Classify sensitive content within or attached to messages
- **Secure Multipurpose Internet Mail Extensions (S/MIME)**  offers authentication and confidentiality to email through public key encryption, digital envelopes, and digital signatures. Authentication is provided through X.509 digital certificates issued by trusted third-party CAs. Privacy is provided through the use of Public Key Cryptography Standard (PKCS) standards-compliant encryption. Two types of messages can be formed using S/MIME: signed messages and secured enveloped messages. A signed message provides integrity, sender authentication, and nonrepudiation. An enveloped message provides recipient authentication and confidentiality.
- **Pretty Good Privacy (PGP)**  is a peer-to-peer public-private key–based email system that uses a variety of encryption algorithms to encrypt files and email messages. PGP is not a standard but rather Open Source.
- **DomainKeys Identified Mail (DKIM)** is a means to assert that valid mail is sent by an organization through verification of domain name identity. See dkim.org.
- **Sender Policy Framework (SPF)** To protect against spam and email spoofing, it operates by checking that inbound messages originate from a host authorized to send messages by the owners of the SMTP origin domain.
- **Domain Message Authentication Reporting and Conformance (DMARC)** DMARC is a DNS-based email authentication system. It is intended to protect against business email compromise (BEC), phishing, and other email scams. Email servers can verify if a received message is valid by following the DNS-based instructions; if invalid, the email can be discarded, quarantined, or delivered anyway.
- **STARTTLS** using Secure SMTP over TLS. STARTTLS (aka explicit TLS or opportunistic TLS for SMTP) will attempt to set up an encrypted connection with the target email server. STARTTLS is not a protocol but instead an SMTP command. Once the initial SMTP connection is made to the email server, the STARTTLS command will be used if the target server supports it. Otherwise, it will remain as plaintext. STARTTLS’s secure session will take place on TCP port 587. STARTTLS can also be used with IMAP connections, whereas POP3 connections use the STLS command to perform a similar function.
- **Implicit SMTPS** This is the TLS-encrypted form of SMTP, which assumes the target server supports TLS. If accurate, then an encrypted session is negotiated. If not, then the connection is terminated because plaintext is not accepted. SMTPS communications are initiated against TCP port 465.


IEEE 802.1 - Bridging and Network Management
- 802.1Q: VLAN Tagging - Defines VLANs and the tagging protocol used to identify VLAN traffic.
- 802.1X: Port-Based Network Access Control - Provides an authentication mechanism for devices wishing to attach to a LAN or WLAN.
- 802.1D: Spanning Tree Protocol (STP) - Provides loop-free topology for Ethernet networks.
- 802.1w: Rapid Spanning Tree Protocol (RSTP) - An evolution of STP providing faster convergence.
- 802.1s: Multiple Spanning Tree Protocol (MSTP) - Extends RSTP to support multiple spanning trees.
- 802.1ad: Provider Bridges (Q-in-Q) - Extends VLANs for use in provider networks.
- 
IEEE 802.3 - Ethernet
- 802.3i: 10BASE-T - 10 Mbps over twisted pair cabling.
- 802.3u: 100BASE-TX - Fast Ethernet, 100 Mbps over twisted pair cabling.
- 802.3ab: 1000BASE-T - Gigabit Ethernet over twisted pair cabling.
- 802.3ae: 10GBASE-SR/LR - 10 Gigabit Ethernet over fiber.
- 802.3af: Power over Ethernet (PoE) - Provides power over Ethernet cabling.
- 802.3at: Power over Ethernet Plus (PoE+) - Enhanced version of PoE with higher power delivery.
  
IEEE 802.11 - Wireless LAN (Wi-Fi)
- 802.11a: 5 GHz, up to 54 Mbps.
- 802.11b: 2.4 GHz, up to 11 Mbps.
- 802.11g: 2.4 GHz, up to 54 Mbps.
- 802.11n: 2.4/5 GHz, up to 600 Mbps with MIMO.
- 802.11ac: 5 GHz, up to several Gbps with wider channels and more MIMO streams.
- 802.11ax: Wi-Fi 6, improvements in throughput and efficiency.
  
IEEE 802.15 - Wireless Personal Area Networks (WPAN)
- 802.15.1: Bluetooth.
- 802.15.4: Low-Rate WPAN (used by protocols like Zigbee).
  
IEEE 802.16 - Broadband Wireless Access
- 802.16: WiMAX - Provides wireless metropolitan area network (MAN) connectivity.
  
IEEE 802.17 - Resilient Packet Ring (RPR)
- 802.17: RPR - Optimizes the transport of data traffic over fiber ring networks.

***UTP categories***

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

Maximum distance to deploy twisted-pair cable (1000BaseT) should not be longer than 100 meters

***Coax***

- There are two main types of coaxial cable: thinnet and thicknet. 
    - Thinnet (10Base2) was commonly used to connect systems to backbone trunks of thicknet cabling. Thinnet can span
        distances of 185 meters and provide throughput up to 10 Mbps. 
    - Thicknet (10Base5) can span 500 meters and provide throughput up to 10 Mbps.
    
Bending the coax cable past its maximum arc radius may break the center conductor and Deploying the coax cable in a length greater than its maximum recommended may cause isses.

***Fibre Optics***

- Fiber can be deployed as single-mode (supporting a single light signal) or multimode (supporting multiple light signals).  
    - Single-mode fiber has a thinner optical core, lower attenuation over distance, and potentially unlimited bandwidth. It
uses a 1310 nm or 1550 nm wavelength laser, can be deployed in runs up to 10 km without repeaters, and is typically sheathed in yellow.
    - Multimode fiber has a larger optical core, higher attenuation over distance, and bandwidth limitations (inversely related to distance), and it uses 850 nm or 1300 nm wavelength LEDs or lasers, has a maximum run length of
400m, and is typically sheathed in blue.

| SONET         | SDH        |DATA RATE               |
|---------------|-----------------| -------------------|
|STS-1/OC-1     | STM-0           | 51.84 Mbps        | 
|STS-3/OC-3     | STM-1      | 155.52 Mbps |
|STS-12/OC-12   | STM-4      | 622.08 Mbps |
|STS-48/OC-48   | STM-16      | 2.488 Gbps |
|STS-96/OC-96   | STM-32      | 4.876 Gbps |
|STS-192/OC-192 | STM-64      | 9.953 Gbps |
|STS-768/OC-768 | STM-256      | 39.813 Gbps |

Synchronous Digital Hierarchy (SDH) and Synchronous Optical Network (SONET) are fiber-optic high-speed networking standards. SDH was standardized by the International Telecommunications Union (ITU) and SONET by the American National Standards Institute (ANSI). SDH and SONET are mostly hardware or physical layer standards defining infrastructure and line speed requirements. SDH and SONET use synchronous time-division multiplexing (TDM) to high-speed duplex communications with minimal need for control and management overhead.

***Common VPN Protocols***

VPNs can be implemented using software or hardware solutions. In either case, there are
several common VPN protocols: PPTP, L2TP, SSH, OpenVPN (i.e., TLS), and IPsec.

-**Point-to-Point Tunneling Protocol PPTP)**: is an obsolete encapsulation protocol developed from the dial-up Point-to-Point Protocol. It operates at the Data Link layer (layer 2) of the OSI model and is used on IP networks. PPTP uses TCP port 1723. PPTP offers protection for authentication traffic through the same authentication protocols supported by PPP: Password Authentication Protocol (PAP), CHAP, EAP, Microsoft Challenge Handshake Authentication Protocol (MS-CHAPv2).  initial tunnel negotiation process used by PPTP is not encrypted. Most modern uses of PPTP have adopted the Microsoft customized implementation(MS-CHAPv2), which supports data encryption using Microsoft Point-to-Point Encryption MPPE and which supports various secure authentication options.

-**Layer 2 Tunneling Protocol (L2TP)** L2TP  was developed by combining features of PPTP and Cisco’s Layer 2 Forwarding (L2F) VPN protocol. Since its development, L2TP has become an internet standard (RFC 2661). Obviously, L2TP operates at layer 2 and thus can support just about any layer 3 networking protocol. L2TP uses UDP port 1701. L2TP can rely on PPP’s supported authentication protocols, specifically IEEE 802.1X, which is a derivative of EAP from PPP. IEEE 802.1X enables L2TP to leverage or borrow authentication services from any available AAA server on the network, such as RADIUS or TACACS+. L2TP does not offer native encryption, but it supports the use of payload encryption protocols. Although it isn’t required, L2TP is most often deployed using IPsec’s ESP for payload encryption. 

-**Generic Routing Encapsulation (GRE)** is also a proprietary Cisco tunneling protocol that can be used to establish VPNs. GRE provides encapsulation but not encryption.

-**SSH**: Secure Shell (SSH) is a secure replacement for Telnet (TCP port 23) and many of the Unix “r” tools, such as rlogin, rsh, rexec, and rcp. While Telnet provides plaintext remote access to a system, all SSH transmissions (both authentication and data exchange) are encrypted. SSH operates over TCP port 22. it can be used to encrypt protocols (such as SFTP, SEXEC, SLOGIN, and SCP) similar to how TLS operates; and it can be used as a VPN protocol. However, as a VPN, SSH is limited to transport mode (i.e., end-to-end encryption between individual hosts, aka link encryption and host-to-host VPN). The tool OpenSSH is a means to implement SSH VPNs. For most secure protocols, if the S in the name is a prefix, like with SFTP, then the encryption is provided by SSH (which has an S as its first letter). If the S in the name is a suffix, like with HTTPS, then the encryption is provided by TLS (which has S as its last letter).

-**OpenVPN**: OpenVPN is based on TLS (formally SSL) and provides an easy-to-configure but robustly secured VPN option. OpenVPN is an open source implementation that can use either pre-shared passwords or certificates for authentication. Many WAPs support OpenVPN, which is a native VPN option for using a home or business WAP as a VPN gateway.

-**IP Security Protocol**: Internet Protocol Security (IPsec) is a standard of IP security extensions used as an add-on for IPv4 and integrated into IPv6. IPsec is sometimes paired with L2TP as L2TP/IPsec. IPsec isn’t a single protocol but rather a collection of protocols, including AH, ESP, HMAC, IPComp, and IKE.
- Authentication Header (AH) provides assurances of message integrity and nonrepudiation. AH also provides the primary authentication function for IPsec, implements session access control, and prevents replay attacks.
- Encapsulating Security Payload (ESP) provides confidentiality and integrity of payload contents. It provides encryption, offers limited authentication, and prevents replay attacks. Modern IPsec ESP typically uses advanced encryption standard (AES) encryption. The limited authentication allows ESP to either establish its own links without using AH and per-
form periodic mid-session reauthentication to detect and respond to session hijacking. ESP can operate in either transport mode or tunnel mode.
- Hash-based Message Authentication Code (HMAC) is the primary hashing or integrity mechanism used by IPsec. 
- IP Payload Compression (IPComp) is a compression tool used by IPsec to compress data prior to ESP encrypting it in order to attempt to keep up with wire speed transmission.
- Internet Key Exchange (IKE) is the mechanism of IPsec that manages cryptography keys and is composed of three elements: OAKLEY, SKEME, and ISAKMP.
    
IPsec uses public-key cryptography and symmetric cryptography to provide encryption (aka hybrid cryptography), secure key exchange, access control, nonrepudiation, and message authentication, all using standard internet protocols and algorithms. The mechanism of IPsec that manages cryptography keys is Internet Key Exchange (IKE). IKE is composed of three elements: OAKLEY, SKEME, and ISAKMP. 
- ✏️OAKLEY is a key generation and exchange protocol similar to Diffie–Hellman. 
- ✏️Secure Key Exchange Mechanism (SKEME) is a means to exchange keys securely, similar to a digital envelope. Modern IKE implementations may also use ECDHE for key exchange. 
- ✏️Internet Security Association and Key Management Protocol (ISAKMP) is used to organize and manage the encryption keys that have been generated and exchanged by OAKLEY and SKEME. A security association is the agreed-on method of authentication and encryption used by two entities (a bit like a digital keyring).  ISAKMP is used to negotiate and provide authenticated keying material (a common method of authentication) for security associations in a secured manner. Each IPsec VPN uses two security associations, one for encrypted transmission and the other for encrypted reception. Thus, each IPsec VPN is composed of two simplex communication channels that are independently encrypted. ISAKMP’s use of two security associations per VPN is what enables IPsec to support multiple simultaneous VPNs from each host.

***PRIVATE IP***

These IPv4 addresses, commonly called the private IPv4 addresses, are defined in RFC 1918. They are as follows:
- 10.0.0.0–10.255.255.255 (a full Class A range).
- 172.16.0.0–172.31.255.255 (16 Class B ranges).
- 192.168.0.0–192.168.255.255 (256 Class C ranges).


**4G** has been in use since the early 2000s and most cellular devices support 4G communications. The 4G standard allows for mobile devices to achieve 100 Mbps, whereas stationary devices can reach 1 Gbps. 4G is primarily using IP-based Communications for both voice and data, rather than the traditional circuit-switching telephony services of the past. 4G is provided by various transmission systems, the most common being LTE, followed by WiMAX.

**5G** is the latest mobile service technology that is available for use on some mobile phones, tablets, and other equipment. Many ICS, IoT, and specialty devices may have embedded 5G capabilities. 5G uses higher frequencies than previous cellular technologies, which has allowed for higher transmission speeds (up to 10 Gbps) but at a reduced distance. Organizations need to be aware of when and where 5G is available for use and enforce security requirements on such communications.

***Centralized Remote Authentication Services***
- RADIUS: Users pass login credentials to a RADIUS server for authentication. By default, RADIUS uses UDP and only encrypts passwords. RADIUS supports TCP and TLS, but this is not a default setting.
- Diameter: is essentially the successor to RADIUS. One significant improvement Diameter provides is added reliability. Diameter is often used in prepaid and credit-­based usage models in mobile device services, and similar applications.
- TACACS: available in three versions: original TACACS, Extended TACACS (XTACACS), and TACACS+. TACACS integrates the authentication and authorization processes. XTACACS keeps the authentication, authorization, and accounting processes separate. TACACS+ improves XTACACS by adding two-­factor authentication. 
