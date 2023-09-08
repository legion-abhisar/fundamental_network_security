# Network protocols
A network protocol is a set of conditions and rules that specify how network devices communication on a given network. It provides a common framework for establishing and maintaining a communications channel and how to handle errors or faults should they occur. Network protocols allow communication between different network-enabled devices.

**Network address**: 
A network address is a unique identifier that identifies a network-enabled device. A network-enabled device might have more than one address type. Among several network address, two address types include:

-  Media access control (MAC) address that identifies the network interface on the hardware level.
-  Internet Protocol (IP) address identifies the network interface on a software level.

**Data packet**: 
A data packet is a unit that's used to describe the message that two devices on a network send each other. A data packet consists of raw data, headers and potentially a trailer. The header contains several information items like it includes the sender and destination device addresses, the size of the packet, the protocol used and the packet number. The trailer in a data packet deals with error checking.

**Datagram**:
A datagram is considered the same as a data packet. Datagrams commonly refer to data packets of an unreliable service, where delivery can't be guaranteed.

**Routing**:
Routing refers to the mechanism used to make sure that data packets follow the correct delivery path between the sending and receiving devices on different networks.

## Protocol categories
Protocol fall into three categories:

-  Network communication protocols
-  Network security protocols
-  Network management protocols

### Network communication protocols
Communication protocols focus on establishing and maintaining a connection between devices. As we work with different devices and network services, we make use of various network communication protocols.

The three foundational protocols of all internet-based networks are Transmission Control Protocol (TCP), Internet Protocol (IP) and User Datagram Protocol (UDP). These protocols are concerned with the logical transmission of data over the network.

-  **Transmission Control Protocol (TCP)**: TCP chunks up data into data packets that can be sent securely and quickly while minimizing the chance of data loss. It provides a stable and reliable mechanism for the delivery of data packets across an IP-based network.
-  **Internet Protocol (IP)**: IP is responsible for the addressing of a data packet. IP encapsulates the data packet to be delivered and adds an address header. The header contains infomartion on the sender and recipient IP addresses. This protocol isn't concerned about the order in which the packets are sent or received. It also doesn't guarantee that a packet is delivered, only the address.
-  **User Datagram Protocol (UDP)**: UDP is a connectionless protocol that offers a low-latency and loss-tolerant implementation. UDP is used with processes that don't need to verify that the receipient device received a datagram.

The most commonly used network communication protocols that are based on a type of application are:

-  **Hypertext Transfer Protocol (HTTP)**: The HTTP protocol used TCP/IP to deliver web page content from a server to our browser. HTTP can also handle the download and upload of files from remote servers.
-  **File Transfer Protocol (FTP)**: FTP is used to transfer files between different computers on a network. Typically, we'd use FTP to upload files to a server from a remote location. While we can use FTP to download files, web-based downloads are typically handled through HTTP.
-  **Post Office Protocol 3 (POP3)**: POP3 is one of three email protocols. It's most commonly used by an email client to allow you to receive emails. This protocol uses TCP for the management and delivery of an email.
-  **Simple Mail Transfer Protocol (SMTP)**: SMTP is another one of the three email protocols. It's most commonly used to send emails from an email client via an email server. This protocol uses TCP for management and transmission of the email.
-  **Interactive Mail Access Protocol (IMAP)**: IMAP is the most powerful of the three email protocols. With IMAP and an email client, we can manage a single mailbox on an email server in our organization.

### Network security protocols
Network security protocols are designed to maintain the security of data across our network. These protocols encrypt in-transmission messages between users, services and applications.

Following list explores leading network security protocols:

-  **Secure Socket Layer (SSL)**: SSL is a standard encryption and security protocol. It provides a secure and encrypted connection between our computer and the target server or device that we accessed over the internet.
-  **Transport Layer Security (TLS)**: TLS is the successor to SSL, and provides a stronger and more robust security encryption protocol. Based on the Internet Engineering Task Force (IETF) standard, it's designed to stop message forgery and tampering and eavesdropping. It's typically used to protect web browser communication, email, VoIP and instant messaging.
-  **Hypertext Transfer Protocol Secure (HTTPS)**: HTTPS provides a more secure version of the standard HTTP protocol by using the TLS or SSL encryption standard. This combination of protocols ensures that all data transmitted between the server and the web browser is encrypted and secure from eavesdropping or data packet sniffing.
-  **Secure Shell (SSH)**: SSH is a cryptographic network security protocol that provides a secure data connection across a network. SSH is designed to support command-line execution of instructions, which includes remote authentication to servers. FTP uses many of the SSH functions to provide a secure file transfer mechanism.
-  **Kerberos**: This validation protocol provides a robust authentication for client-server-based applications through secret-key cryptography. Kerberos assumes that all endpoints in the network are insecure. It constantly enforces strong encryption for all communications and data.

### Network management protocols
Management protocols look at faults and performance of the network. Each device in the our network exposes some indicators about the state and health of the device. The network administrator tool requests these indicators and uses them for monitoring and reporting.

Two network management protocols are:

-  **Simple Network Management Protocol (SNMP)**: SNMP is an internet protocol that allows for the collection of data from devices on our network and the management of those devices. Devices that support SNMP typically include switches, routes, servers, laptops, desktops and printers.
-  **Internet Control Message Protocol (ICMP)**: ICMP is one of the protocols included within the Internet Protocol suite (IPS). It allows network-connected devices to send warning and error messages along with operation information about the success or failure of a connection request, or if a service is unavailable. 

## Ports
A port is a logical construct that allows the routing of incoming messages to specific processes. A port is an unsigned 16-bit number in the range 0 to 65535 and is also known as a port number. Based on the communications protocol used, the sending TCP or UDP layer assigns the ports.

There are specific port numbers reserved for every service. The first 1024 ports, called the well-known port numbers, are reserved for the commonly used services. The high-numbered ports, called the ephemeral ports, are unreserved and used by dedicated applications.

Every port links to a specific service or communications protocol. It means that the target network device, say a server, can receive multiple requests on each port and service each of them without conflict.

### Well-known port numbers
Ports are split into three ranges:

-  Well-known ports
-  Registered ports
-  Dynamic/private ports

Table listing some of the well-known port numbers:
|Port number|Assignment|
|----|----|
|20|File Transfer Protocol for data transfer.|
|21|File Transfer Protocol for command control.|
|22|Secure Shell for secure authentication.|
|23|Telnet remote authentication service for unencrypted text messages.|
|25|Simple Mail Transfer Protocol for email routing.|
|53|Domain Name System service.|
|80|Hypertext Transfer Protocol for use in the web.|
|110|Post Office Protocol|
|119|Network News Transfer Protocol (NNTP)|
|123|Network Time Protocol (NTP)|
|143|Internet Message Access Protocol fro management of digital mail.|
|161|Simple Network Management Protocol.|
|194|Internet Relay Chat (IRC)|
|443|HTTP Secure HTTP over TLS/SSL|

### Internet Protocol suite
The Internet Protocol suite is a collection of communication protocols, also called a protocol stack. It's also sometimes referred to as the TCP/IP protocol suite, because both TCP and IP are primary protocols used in the suite.

The IPS describes the different layered protocols used to send and receive data on the internet and similar networks. The IPS model is one of several similar networking models that of OSI networking reference models.
![image](https://github.com/legion-abhisar/fundamental_network_security/assets/37869095/a514df11-e8ba-4354-91c2-f9edfbcbe08c)

- **Application layer**: The top layer of this stack is concerend with application or process communication. The application layer is responsible for determining which communication protocols to use based on what type of message is transmitted. For example, the layer assigns the correct email protocols such as POP, SMTP or IMAP if the message is email content.
- **Transport layer**: This layer is responsible for host-to-host communication on the network. The protocols associated with this layer are TCP and UDP. TCP is responsible for flow control. UDP is responsible for providing a datagram service.
- **Internet layer**: This layer is responsible for exchanging datagrams. A datagram contains the data from the transport layer and adds in the origin and recipient IP addresses. The protocols associated with this layer are IP, ICMP and the Internet Protocl Security (IPsec) suite.
- **Network access layer**: The bottom layer of this stack is responsible for defining how the data is sent across the network. The protocols associated with this layer are ARP, MAC, Ethernet, DSL and ISDN.















