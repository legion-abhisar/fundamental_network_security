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













