# Unit 1
## Section 1 

### Q & A

A user connects their laptop to a Wi-Fi network in a coffee shop.

Which Network component is responsible for managing the wireless connection?

*- Access Point*

**Access points managed wireless connections by providing connectivity between wireless devices and the wired network.**

-----------------------

A network campus has multiple buildings connected by underground fiber-optic cables.

Which network component manages the flow of data between these buildiings?

*- Router*

**Routers direct data between different networks, such as those in different buildings, by determining the best path for transmission.**

------------------------

In a network where all computers communicate through a central server, which type of network architecture is being used?

*- Client/Server*

**Client/server architectures involve a central server that provides services to clients, which is not the case in this scenario.**

-------------------

In a network where there is a mainframe computer serving teminals across the organization, which type of network archeitecture is being used?

*- Heirarchical*

**Hierarchial netowrks involve a central mainframe or server providing servies to terminals to lower-level devices, createing a hierarchical.**

--------------------

A user is experiencing network connectivity issues on their Windows computer.

Which command can they sue to display the IIP configuration of their computer?

*- ipconfig*

**Ipconfig is used to display the IP configuration, including IP address, subnet mask, and default gateway.**

-----------------

A user suspects that thwir Windows computer is infected with malware causing network issues.

Which command can they use to display active network connections and processes?

*- netstat*

**Netstat displays active network connections, listening ports, and related information, which can help identify suspicious activity.**

---------------------------

A user is experiencing slow internet speeds and suspects network congestion.

Which command can they used to test the latency and response time to a specific destination?

*- ping*

**Ping sends ICMP echo requests to a specific destination and measures the round-trip time, helping to diagnose latency issuse.**

-------------------

A Linux users wants to view the routing table on their system to troubleshoot routing issues. 

Which command should they use?

*- route*

**The route command is used to display and manipulate the IP routing table on a Linux system.**

----------------

A Linux users wants to view detailed information about their network interfaces, including IP addresses, netmask, and interface status.

Which command should they use?

*- ifconfig*

**Ifconfig is used to configure and display information about network interfaces, including IP addresses, netmask, and interface status.**

------------------------

A Linux user is experiencing slow internet speeds and suspects network congestion. Which command can they use to test network connectivity and measure the round-trip time to a specific destination?

*- traceroute*

**Traceroute is used to trace the route taken by packets to reach a destination and measure the round-trip time to each hop along the path.**

------------------------

### Lesson 2 Summary Notes

- **ipconfig** command in Windows provides details about network adapters and their configurations. **ifconfig** command for Linux.

- IPv6 addresses (128 bits long) use hexadecimal notation separated by colons, while IPv4 addresses are dotted decimals.

- **nslookup** command allows users to query DNS servers to resolve domain names to IP addresses; present in both operating systems.

- In Windows, **arp -a** command reveals the mapping of IP addresses to physical MAC addresses, which is *cruitical for local network communication.*

- **netstat** command provides network statistics and can display active connections, listening ports, and associated addresses; this tool is available in both Linux and Windows.

- Both systems utilize ICMP for tools like **ping** and **traceroute** (or **tracert** in Windows) to test network connectivity and trace newrok paths.

-------------------------------------

## Section 3 

Which layer of the OSI model is primarily responsible for translating network addresses into their physical conunterparts and deciding how to route data from the sender to the reciever?

*- Network Layer*

**The Network Layer is crucial for routing and forwarding packets across different networks by translating logical network addresses into physical addresses, determining the most efficient paht for data to travel between source and destination.**

-------------

~Which OSI layer is responsible for establising, maintaining, and terminating connections between applications?~

*- Session Layer*

**The Session Layer is responsible for establishing, maintaining, and terminating connections between applications.**

--------------------

At which OSI layer does Transmission Control Protocol (TCP) operate?

*- Transport Layer*

**TCP operates at the Transport Layer, providing reliable, connection-oriented communication.**

------------

Which TCP/IP layer is responsible for logical addressing and routing?

*- Internet Layer*

**The Internet Layer is responsible for logical addressing (IP addresses) and routing packets between networks Network Access Layer.**

--------------------

~Where does Hypertext Transfer Protocol (HTTP) operate in the OSI model?~

*- Application Layer*

**HTTP operates at the Application Layer, facilitating communication between web servers and client.**

-------------------

Which layer of the OSI model is responsible for providing error-free data transmission over a network, handling error detection, and error correction?

*- Transport Layer*

**Transport Layer provides reliable, error-checked data transfer, managing flow control, error detection, and error correction to ensure data is recieved exactly as sent.**

---------------

In the TCP/IP model, which layer corresponds to both the session, presentation, and application layers of the OSI model?

*- Application Layer*

**The Application Layer in the TCP/IP model encompansses the functionalities of the OSI model's session, presentation, and application layers, handling high-level protocols, issues of respentation, encoding, and dialog control.**

-------------------

## Lesson 4

When virtualization software is installed directly on the physical hardward of a server, which type of hypervisor is being used?

*- Type 1*

**In this scenario, where virtualization software runs directly on the bare metal, it is a Type 1 Hypervisor.**

-----------------

If a user installs virtualization software on their existing operating system, which type of hypervisor are they using?

*- Type 2*

**Type 2 hypervisors run on top of a host operating system, allowing for virtualization within that environment.**

------------

A company leases physical servers from a third-party provider and manages its own software and applications.

Which type of cloud computing solution is being utilized?

*- Infrastruture as a Service (IaaS)*

**Infrastruture as a service (IaaS) provides virtualized computing resources over the internet, including servers, storage, and networking.**

----------------------

If a company subscribes to a cloud-based email service where the email application is hosted and managed by the service provider, which type of cloud computing solution is this?

*- Software as a service (SaaS)*

**Software as a service (SaaS) delivers applications over the internet, and in this case, it is the email service hosted and managed by the provider.**

------------------

A company uses a cloud provider's infrastucture exclusively for its own use and does not share resources with other organizations. 

Which type of cloud deployment model is beingn utilized?

*- Private Cloud*

**Private clouds offer exclusive use to a single organization, providing greater control and security over data and resources.**

----------------

### Unit 1 Test

A small buisness enables mutliple devices on its private network to share a single public IP address when accessing the internet. This setup hides the internal IP addresses of devices from external networks.

Which network technology concept is being utilized in this scenario?

*- NAT*

**Network address translation (NAT) allows multiple devices on a private network to access the internet using a single public IP address. It translates internal private IP addresses to the public IP address, enabling all devices to share that public address as described in the scenario.**

------------------

A large enterprise uses a network service that automatically assigns IP addresses to client devices, ensuring each device recieves the appropriate network configuration without manual intervention.

Which hnetowrk technology conecpt does this scenario illustrate?

*- DHCP*

**Dynamic host configuration protocol (DHCP) automatically assigns IP addresses and other nework configuation parameters to devices on a network. This process allows each device to connect the  network with the correct settings without manual configuration, exactly as described in the scenario.**

-------------------

Which term desvirbes a configuration where multiple networks are connected over a large geographic area, sharing data and resources efficiently?

*- WAN*

**A wide area network (WAN) connects mulitple networks over large geographic areas, allowing them to communicate and share resources.**

------------------------

Which network topology connects all nodes to a central device, like a switch, to ensure minimal disruption when a single link fails?

*- Star*

**A star topology connects devices to a central device, ensuring localized failure.**

-------------

Which type of device connects different networks and etermines the best path for data transmission?

*- Router*

**Routers connect different networks and manage data routing.**

---------------

A network administrator on a Windows computer wants to test connectivity to a remote server and measure the response time.

Whic network troubleshooting command should the administrator use?

*- ping*

**The ping command in Windows sends ICMP echo requests to a specified host to check connectivity and measure the response time (round-trip time).  This command is exactly what the administrator needs to verify the server's reachability.**

--------------

A Linux system administrator needs to view a server's current network configuration details, such as IP address and subnet mask.

Which command should they use?

*- ifconfig*

**The ifconfig command in Linux displays the current network configuration, including IP addresses, subnet mask, and other interface settings. This command provides exactly the information the administrator needs about the server's network settings.**

-----------------------

An administrator on a Windows machine wants to check how the local DNS server resolves a particular domain name to an IP  address. 

Which ocmmand should the administrator use?

*- nslookup*

**The nslookup command is used to query DNS servers and check DNS resolution. By entering a domain name, it returns the corresponding IP address as resovled by the DNS server, matching the scenario's requirements.**

--------------------

When troubleshooting DNS issues on a Linux system, which command should you use to query DNS servers to resolve domain names?

*- dig*

**Dig is a DNS lookup utility that queries DNS servers to resolve domain names to IP addresses.**

--------------

Which command on Linux provides detailed information about current network connections?

*- netstat*

**netstat provides details on current network connections.**

----------------

Which OSI model layer provides end-to-end data transmission services and ensures complete data transfer?

*- Transport Layer*

**The transport layer is responsbile for end-to-end communication and error recovery, ensuring complete data transfer between the source and destination.**

----------------------

Which OSI layer is responsible for logical addressing and routing packets between devices across different networks?

*- Network Layer*

**The network layer handles logical addressing (IP addresses) and routing packets between different networks.**

----------------

At which OSI layer should you categorize an Ethernet switch that fowards frames based on MAC addresses?

*- Data Link Layer*

**Ethernet switches operate at the data linkl ayer, forwarding frames based on MAC addresses.**

-------------------------

A router determines the best path for data packets to travel across multiple networks. 

At which OSI layer does the router primarily operate?

*- Network Layer*

**Routers operate at the network layer (layer 3), which is responsible for routing data packets between networks.**

---------------------

When a user accesses a website using HTTPS, at which TCP/IP layer does the HTTPS protocol operate?

*- Application Layer*

**HTTPS operates at the application layer, handling secure seb communication.**

-----------------

Which type of cloud service allows users to develop and deploy applications on a plateform without managing the underlying infrastructure?

*- Plateform as a service (PaaS)*

**PaaS provides platforms with preinstalled tools for application development.**

----------------

A company uses an email service that requires no installation or maintenance of the application on local devices.

Which cloud model does this describe?

*- Software as a service (SaaS)*

**SaaS allows users to access applications like email without managing installations.**

---------------------

Which virtualization technology enables multiple operating systems to run on a single physical machine?

*- Hypervisors*

**Hypervisors allow multiple operating systems to run on one physical machine.**

------------------

A business uses a third-party service to host its virtual desktops and provide secure remote access to employees.

Which type of solutin is being used?

*- Virtual desktop infrastructure (VDI)*

**VDI enables remote access to virtual desktops hosted by a third-pary service.**

-------------------------
