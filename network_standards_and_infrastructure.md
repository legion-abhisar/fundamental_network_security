## Network standards
While network protocols provide a unified method for communication, network standards govern the hardware and software that used them. Netowrk standards provide a framework that enables the interoperability between devices. Network standards improve the interoperability of different network-enabled devices and provide backward compatibility between product revisions and differing vendors.
### The 802 family of standards
The 802 specification covers all the physical networking standard for both Ethernet and wireless.
|802  |Overview  |Basics of physical and logical networking concepts |
|-----|------    |--------  |
|802.1|Bridging|LAN/MAN briding and management of the lower sublayers of OSI Layer 2|
|802.2|Logical Link|Commonly referred to as the logical link control (LLC) specification|
|802.3|**Ethernet**|Provides asynchronous networking by using carrier sense multiple accesses with collision detect (CSMA/CD) over coaxial cable, twisted-pair copper cable and fiber media.|
|802.5|Token ring|The token-passing standard for shielded copper cables and twisted-pair cable.|
|802.11|Wi-Fi|Wireless local area network (WLAN) media access control (MAC) and physical layer (PHY) specification.|
|802.11a|Wi-Fi|Specifies a PHY that operates in 5 GHz.|
|802.11b|Wi-Fi|Enhances 802.11, adds higher data rate modes.|
|802.11d|Wi-Fi|Enhances 802.11a/b, allows for global roaming.|
|802.11e|Wi-Fi|Enhances 802.11, adds Quality of Service (QoS) features.|
|802.11g|Wi-Fi|Extends WLAN maximum data rate.|
|802.11h|Wi-Fi|Extends 802.11a, now resolves interference issues.|
|802.11i|Wi-Fi|Enhances 802.11, adds security for WLAN applications.|
|802.11j|Wi-Fi|Enhances 802.11a for Japanese regulatory extensions.|
|802.11n|Wi-Fi|Higher-speed standards.|
|802.12|Demand Priority|Ethernet data rate increased to 100 Mbps.|
|802.15|Wireless personal area networks|Support for wireless personal area networks (WPANs).|
|802.15.1|Bluetooth|Short-range (10m) wireless technology.|
|802.15.3a|UWB|Short-range, high-band-width ultra-wideband (UWB) link.|
|802.15.4|ZigBee|Short-range wireless sensor networks.|
|802.16|Wireless metropolitan area networks|Covers mobile and wireless broadband access in wireless metropolitan area networks (WMANs).|

## Network infrastructure
There are several network standard-compliant devices that make-up the structure of our networks. These devices are:
-  Repeaters
-  Hubs
-  Bridges
-  Switches
-  Routers

**Media access control address**: It is a unique identifier assigned to every network-enabled device at the time of manufacture. It's sometimes referred to as the burned-in address, the Ethernet hardware address or a physical address.

The MAC address has standard composition of six hexadecimal numbers separated by a colo or dash. The first three numbers of the MAC address define the manufacturer's organizationally unique identifier (OUI) and the remaining three numbers uniquely identify the device.

For example, if the MAC address is AA-6A-BA-2B-68-C1 then the OUI is AA-6A-BA and 2B-68-C1 is the device ID.

**Repeater**: A repeater is a two-port device that repeats network signals. Repeaters are used when network devices are some distance from each other. The repeaters doesn't modify or interpret data packets before it resends them, and it doesn't amplify the signal. Instead, it regenerates the data packet at the original strength, bit by bit.

**Bridge**: A bridge divides a network into network segments, and can filter and forward data packets between these segments. Bridges use the network device's MAC address to decide the data package's destination. Typically, a bridge is used to improve network performance by reducing unnecessary network traffic on network segments.

**Hub**: A hub acts as a multiport repeater on a network. Hubs are used to connect more than one device and structure the layout of a network. Hubs contain multiple ports that act as an input/output Ethernet connection between the hub and a network device. A hub can operate at only one speed, which is the speed of the slowest network device on the netword. It doesn't interpret or filter data packets and sends copies of each data packet to all attached devices.

**Switch**: A switch combines the functionality of a bridge and a hub. It segments network and can interpret and filter packet data to send it directly to an attached network device. Swithces use the network device's MAC address to decide the data package's destination. A swithc operates in full-duplex mode, which means it can send and receive data to and from network devices at the same time.

**Router**: Router links networks with different ranged addresses together. They can interpret and filter data packets and then forward them to the correct networks. Routers use the network device's IP address information to route the data package to its destination. Most routers can now detect issues with data traffic that flows to any attached network and route or reroute it around the issue. A router is also called a gateway. When we configure network devices, we usually configure them with a default gateway IP address.
