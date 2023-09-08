# Network types and topologies:
### What is network?
A network is a collection of network-enabled devices, typically made up of computers, switches, routers, printers, and servers. Networks allow all types of network-enabled devices to communicate.

**Network types:** 
-  Personal area network
-  Local area networks
-  Metorpolitian area networks
-  Wide area networks

### What is Personal area network?
A personal area network (PAN) provides networking needs around an individual. An example of a PAN is where a smartphone, smartwatch, tablet and laptop all connect and share data without the need to connect to an access point or other third-party network services. PAN networks typically use Bluetooth to communicate because it provides a low-power, short-range data-sharing capability. The network standards associated with a PAN are Bluetooth and IEEE 802.15.
### What is Local area network?
A local area network (LAN) provides networking needs around a single location. This location might be an organization's office, a school or many others. Typically, a LAN is privately owned and needs authentication and autorization to access. Of the different classifications of a network, a LAN is by far the most commonly used.
### What is Metropolitan area network?
A metropolitan area network (MAN) provides networking capabilities between two different locations within a city or metropolitan area to provide a single extensive network. Typically, a MAN requires a dedicated and secure connection between each LAN joined to the MAN.
### What is Wide area network?
A wide area network (WAN) provides networking capabilities between two different geographical locations locally or worldwide. For example, a WAN is used to connect an organization's head office with branch offices all over the region. A WAN links multiple LANs together to create one super network. With a WAN, we use a virtual private network (VPN) to manage the connection between different LANs.
### Difference between LAN and WAN networks
|LAN    |WAN    |
|----   |----   |
|A LAN is a privately operated network typically contained in a single building. |A WAN is used to connect geographically separate offices to each other. Multiple organizations might operate WANs.|
|A LAN operates at speeds of 10 Gbps or higher.|A WAN typically operates at speeds of less than 1 Gbps.|
|A LAN is less congested compared to other network types.|A WAN is more congested compared to other network types.|
|A LAN can be managed and administrated in-house.|A WAN typically requires the use of a third party to configure and set up, which increases const.|

### Network topologies
A network topology describes the physical composition of a network. There are four topologies from which we can choose when we design a LAN. They are:
-  Bus: In a bus topology, each network device is connected to a single network cable. The limitations include the length of the main cable or bus. The longer the bus gets, the higher the chance of signal dropout. The limitation constrains the physcial layout of the network. All devices have to be physically located near each other. Also if there is a break in the bus cable, the whole network fails.
  
![image](https://github.com/legion-abhisar/fundamental_network_security/assets/37869095/5a8ec4e1-cade-462e-b3c7-14615fac70ca)
-  Ring: In a ring topology, each network device is connected to its neighbour to form a ring. This form of network is more resilient than the bus topology. A break in the cable ring also affects the performance of the network.

![image](https://github.com/legion-abhisar/fundamental_network_security/assets/37869095/b515e4d7-e830-49eb-ac18-1fea1a851690)
-  Mesh: The mesh topology is described as either a physcial mesh or a logical mesh. In a physical mesh, each network device connects to every other network device in the network.

![image](https://github.com/legion-abhisar/fundamental_network_security/assets/37869095/a2fb94b0-0a8f-4afc-be9f-e0f3dddc4885)
-  Star: The star topology is the most commonly used network topology. Each network device connects to a centralized hub or switch. Switches and hubs can be linked together to extend and build more extensive networks. This type of topology is the most robust and scalable.

![image](https://github.com/legion-abhisar/fundamental_network_security/assets/37869095/ebe58caf-ad86-48d0-ac1e-535da3e69b8c)

### Ethernet
Ethernet is a networking standard that's synonymous with wire-based LAN networks, and also used in MAN and WAN networks. Ethernet standard defines a framework for data transmission, error handling and performance threshold. It describes the rules for configuring an Ethernet network and how each element in the network interacts with each other.

Ethernet is used in the OSI model at the data link and physical layers. It formed the basis for the IEEE 802.3 Standard. This standard helped to unify network and hardware development.
