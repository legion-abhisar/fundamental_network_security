## Address Resolution Protocol
The Address Resolution Protocol (ARP) is a communications protocol within the Internet Protocol suite. It's a request-response protocol used to resolve the media access control (MAC) address for a given IP address. Without ARP, there would be no means to resolve an IP address to a physical device address.

There's also the Reverse Address Resolution Protocol (RARP), which retrieves an IP address based on the given MAC address.

## TCP/IP
The Transmission Control Protocol/Internet Protocol is a collection of different communication protocols that support and define how network-enabled devices interconnect with each other over an IP-based network. At its heart are two key protocols: TCP and IP.

TCP/IP defines the way data is shared between network-enabled devices by defining the end-to-end communication process. It manages how the message is broken down into packets of data, which are sometimes known as datagrams. TCP/IP also determines how the packet is addressed and transmitted, routed and received. TCP/IP can determine the most efficient route across a network.

TCP/IP model is designed to be stateless. This design means the network stack treats each request as new because it isn't related to the precious request. One part of the TCP/IP model isn't stateless. The transport layer operates in a stateful mode because it maintains a connection until all the packets in the message are received.

### TCP/IP model layers
The TCP/IP model is made up of four distinct layers. Each layer uses a different type of protocol.

-  **Application layer**: The application layer is responsible for determining which communication protocols are used. This layer includes Hypertext Transfer Protocol (HTTP), DNS, File Transfer Protocol (FTP), Internet Message Access Protocol (IMAP), Lightweight Directory Access Protocol (LDAP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), Simple Network Management Protocol (SNMP), Secure Shell (SSH), Telnet and TLS/SSL.
-  **Transport layer**: This layer splits the application data into manageable ordered chunks by using the right port for the application protocol that's used. The protocols associated with this layer are TCP and the User Datagram Protocol (UDP).
-  **Internet layer**: Also called the network layer, this layer ensures the data packet gets to its destination. The protocols associated with this layer are IP, IPv4, IPv6, Internet Control Message Protocol (ICMP) and Internet Protocol Security (IPsec).
-  **Network access layer**: This layer is responsible for defining how the data is sent across the network. The protocol associated with this layer are ARP, MAC, Ethernet, digital subscriber line (DSL) and Integrated Services Digital Network (ISDN).

### Internet Protocol Standards
The Internet Protocol only provides a logical addressing system that's used to route and forward messages to their destinations. It is not concerend about the order in which the packets are sent or received. It also doesn't guarantee a packet's delivery.

There are two Internet Protocol versions:

-  IPv4
-  IPv6

**IPv4**: It is the standard for all packet-switch-based networks in use today. IPv4 uses a 32-bit address space that gives an upper limit of 4,29,49,67,296 (4.3 billion) unique logical IP addresses.

The structure of IPv4 address is four decimal numbers in the range of 0 to 255, each separated with a dot. It's also known as the dotted-decimal format. Example 192.168.0.1

Here the 192.168.0 represents the number unique to the network and specifies the class of the network (A, B, C, D, E). The number 1 represents the device and has to be unique within the network to avoid address conflicts. Each device on a network segment must have a unique address.

**IPv6**: It uses a 128-bit address space, which allows 2^128^ addresses. This amount is approximately  7.9x10^28^ times more than IPv4.

The benefits include:

- **Simplified network configuration**: IPv6 has address autoconfiguration built into the protocol. For example, a router broadcasts the network prefix and the network device can append its MAC address to self-assign a unique IPv6 address.
- **Security**: IPsec is built into IPv6.
- **New service support**: IPv6 eliminates the need for NAT, which makes it easier to create peer-to-peer networks.
- **Multicast and anycast functionality**: Multicast allows for the broadcast of messages in a one-to-many fashion. Anycast allows a single destination to have multiple routing paths to two or more endpoint destinations.

The structure of IPv6 is different from IPv4. It uses eight groups of four hexadecimal numbers called hexadectet. Each hexadectet is separated with a colon. A full IPv6 address looks like this: 2001:0db8:0000:0000:0000:8a2e:0370:7334.

The shortened version of IPv6 example is 2001:0db8:8a2e:0370:7334. Here all the instances of 0000 are removed.

## DNS
The Domain Name System is a decentralized lookup service that translates a human-readable domain name or URL into the IP address of the server that's hosting the site or service.

A DNS server serves two purposes. The first is to maintain a cache of recently searched-for domain names, which improves performance and reduces network traffic. The second is to act as the start of authority (SOA) for all the domains under it.

When a DNS server is looking to resolve a domain name that isn't held in its cache. It starts with the highest level, the dot and then works down the subdomains until it finds the DNS server acting as the SOA. Once found, it stores the IP address of the domain in its local cache.

The DNS also holds specific records that relate to the domain. These records include the SOA, IP addressing (A and AAAA), SMTP email (MX), name servers (NS) and domain name alias (CNAME) records.
