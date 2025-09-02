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

A company uses its on-premises data center to store sensitive data while running some customer-facing applications in a public cloud environment. They have integrated both environments, enabling data and applications to move between them seamlessly.

Which type of virtual and cloud computing solution does this scenario desvribe?

*- Hybrid Cloud*

**A hybrid cloud combines a private cloud (the on-premises data center) with a public cloud service, allowing seamless data and application movement between both environments. This matches the scenario where sensitive data stays on-premises, and customer-facing applications fun in the public cloud.**

------------------------

# Unit 2

## Lesson 1

An employee recieves an email from an unknown sender with a suspicious attachment.

What is the fundamental network security principle that should be applied?

*- Anti-malware*

**Anti-maleware software helps detect and remove malicious software, such as viruses or malware, which may be contrained within suspicious email attachements.**

---------------------------

A company regularly updates its software and patches vulnerabilities in its systems. 

Which fundamental network security principle is being followed?

*- Patch Management*

**Patch management involves regualrly updating software and applying patches to address known vulnerabilities, thereby enhancing the security of network systems and infrastructure.**

----------

A company's wireless network does not require authentication for access.

Which network security vulnerability is present?

*- Unauthorized Access*

**The absence of authentication on a wireless networks allows unauthorized individuals to gain access, representing a vulnerability in network security.**

----------------

An individual uses pre-written scripts and tools to exploit known vulnerabilites without understanding the underlying mechanisms.

Which type of attacker is involved?

*- Script kiddie*

**Script Kiddies are individuals who use readily available tools and scripts to launch attachs without understanding the technology behind them.**

---------------

A group of security professionals simulates attachs on a company's network to indentify vulnerabilities and improve defenses.

Which type of team is involved?

*- Red team*

**Read teams are groups that simulate attacks on a company's netwrok to identify vulnerabilities and test defenses, often providing valuable insights for imporving security.**

--------------------

An attacker intercepts sensitive information, such as log-in credenticals or financial data, that is transmitted between a user and a legitimate website.

Which type of threat is this?

*- Man-in-the-middle attack*

**A man-in-the-middle (MitM) attack occurs when an attacker intercepts and possibly alters communication between two parties, allowing them to eavesdrop on or mainpulate the data being transmitted.**

-----------------------

An employee recieves an email with a link that appears to be from a colleague but leads to a malicious website designed to steal log-in credentials.

Which type of cyber-attack is this?

*- Phishing Attack*

**Phishing attacks involve deceptive emails or messages designed to trick recipients into providing sensitive information, such as usernames and passwords.**

-------------------

## Lesson 2

When ensuring that data remains accurate and unaltered during transmission or storage, which category of the CIA triad is being addressed?

*- Integrity*

**Integrity is the category of the CIA triad that focuses on ensuring that data remains accurate, complete, and unaltered during transmission or storage, thereby maintaining its integrity.**

---------------

### Section 2 Test

An attacker initates a distrubted denial-of-service (DDoS) attack on a corporate web server.

Which type of risk is being exploited?

*- Availability risk*

**Availability risk affects the ability to access resources. A DDoS attack is designed to make the web server unavailable.**

----------

A company's IT department discovers malware that is logging keystrokers and transmitting them to an external server.

Which threat describes this situation?

*- Data exfiltration*

**Data exfiltration involves unauthorized data transmission, such as keystrokes, to an external server.**

-----------

Which situation is classified as a physical security risk to a network?

*- Power Outage*

**A power outage is a physical security risk that can interrupt network functionality.**

-------------

An attacker uses an organization's poorly secured Wi-Fi network to access internal resources. 

Which term describes the Wi-Fi netowrk in this scenario?

*- Vulnerability*

**A vulnerability is a weakness that allows threats to exploit a system, as in the case of poorly secured Wi-Fi.**

---------------

A user recives an email inpersonating the IT department and asking login credentials.

Which type of attack is this?

*- Phishing*

**Phishing involves deceptive communication to gather sensitive information like login credentials.**

---------

A network scan reveals that a company's database server is running outdated software with known vulnerabilites.

Which type of risk does this scenario describe?

*- Vulnerability*

------------

An attacker intercepts unencrypted data being transmitted over a network.

What is the attacker exploiting in this scenario?

*- Data Confidentiality*

**Dataa confidentiality is compromised when unauthorized parites intercept sensitive information.**

---------------

Which situation is an example of social engineering attack?

*- A phishing email requesting login credentials*

**Phishing is a social engineering attack that manipulates individuals into revealing sensitive information.**

-------

Employees use personal devices to access the corporate network without adequate security measures.

Which type of risk does this pose?

*- BYOD*

**The risk of bringing your own device (BYOD) arises when personal devices introduce potential vulnerabilities or lack security controls.**

------------

A company uses a firewall to block unauthorized traffic from reaching its internal network.

Which role does the firewall serve in this scenario?

*- Safeguard*

**A safeguard is a security control implemented to prevent risks like unauthorized access.**

-----------

Which aspect of the CIA triad is addressed by encrypting sensitive emails before transmission to ensure only the inteded recipient can read them?

*- Confidentiality*

**Confidentiality ensures that information is protected from unauthorized access, and encryption is a key method of achieving this.**

--------------

A hosptial implements digital signatures to verify that electronic health records are not altered during transmission. 

Which part of the CIA triad does thi saction address?

*- Integrity*

**Integrity ensures data remains accurate and unaltered; digital signatures help verify this.**

----------

A disaster recovery system is installed ensure that data can be quickly restored in case of a failure.

Which part of the CIA triad does this primarily address?

*- Availability*

**Availability ensures resources remain accessible, and disaster recovery systems help achieve this.**

--------

Which aspect of the CIA triad is addressed by restricting access to sensitive customer information using role-based access control?

*- Confidentiality*

**Role-based access control protects senstitive information from unauthorized access, ensuring confidentiality.**

----------

A software development company employs hash functions to ensure that code deployed to clients has been tampered with.

Which category of the CIA triad is this ensuring?

*- Itegrity*

**Itegrity ensures data remains unaltered, and has functions are a method to verify data authenticity.**

-----------------

An organization deploys multifactor authentication (MFA) to ensure only authorized users can log in to its systems.

Which CIA triad component does this primarily support?

*- Confidentiality*

**Confidentiality protects data from unauthorized access, which MFA supports by requiring additional verification.**

----------------------------

A company schedules regular backups of its critical systems to mitigate the impace of hardware failure.

Whic CIA triad component does this action support?

*- Availability*

**Availability ensures resources remain accessible, and backups are key to maintaining availability.**

--------------

An organization has decided to encrypt sensitive emails before sending them, ensuring only the inteded rrecipient can read their contents.

Which aspect of the CIA triad does this practice address?

*- Confidentiality*

**Encrypting data ensures condifentiality by protecting iti from unauthorized access.**

----------

A bank employs a hashing algorithm to verify that transaction logs have not been altered.

Which CIA triad category does this measure support?

*- Integrity*

**Integrity ensures data is accurate and unaltered, which is the purpose of hashing algorithms.**

-----------

A government agency ensures that emergency response systems are operational 24/7 to guarantee service access during a crisis.

Which CIA triad component does this support?

*- Availability*

**Availability ensures that resources are accessible when needed, which is critical during emergencies.**

-------

# Unit 3

## Lesson 1

In network security design, which principle advocates for the use of cryptographic techniques to secure senstive data and communications?

*- Security*

**The Security principle advocates for the use of cryptographic techniques to secure sensitive data and communications, ensuring confidentiality, integrity, and authenticity.**

-------------------------

When designing a network security system, wheich principle ensures that users are only granted the minimum level of access necessary to preform their task?

*- Least Privilege*

**The least privilege principle ensures that users are granted only the minimum level of access required to perform their tasks, reducing the potential impact of security breaches.**

---------

Indesigning a network security system, which principle focuses on ensuring that the system remains secure even if individual components fail?

*- Fail-safe*

**The fail-safe principle focuses on ensuring that a system defaults to a secure state in the event of component failure, thereby minimizing the impace of such failures on overall security.**

--------------

In network security design, which principle ensures that access to resources is checked against the security policy, even after initial authentication?

*- Complete mediation*

**The complete mediation principle ensures that access to resources is checked against the security policy, even after initial authentication, to prevent unauthorized access.**

---------------

Which principle of network security design emphasizes the importance of keeping security mechanisms transparent and understandable?

*- Open Design*

**The open design principle advocates for transparency and understandability of security mechanisms to faciliate scrutiny and testing by security experts.**

--------

When designing network security, which principle emphasizes the need to verify the identity of users and restrict access based on their roles or permissions?

*- Separation of privilege*

**Separation of privilege involves dividing system function among mulitple components to enhance security and restrict access based on users' roles or permissions.**

--------------

In network security design, which principle suggests that security mechanisms should be easy to understand and use by users to encourage compliance?

*- Psych acceptability*

**The psych acceptability principle suggests that security mechanisms should be easy to understand and use by users to encourage compliance and adherence to security policies.**

----------

### Lesson 2

A company suspects that an insider is attempting to access sensitive information without authorization. Which solution can help detect and prevent such unauthorized activities?

*- IDS and IPS*

**Intrusion dection systems (IDS) and intrusion prevention systems (IPS) are designed to monitor network or system activites for malicious actions or policy violations. They can detect and prevent unauthorized access attempts, making them effecting for identifying and responding to insider threats.**

---------------------

An organization's confidential data is intercepted during transmission over the internet. Which solution can provide protection for data in transit?

*- Encryption*

**Encryption is the appropriate solution to protect data during transmission over the internet. It encodes the data into a secure format that can only be decrypted by authorized parties, ensuring confidentiality and security.**

------------

A company's network is under a distributed denial-of-service (DDoS) attack, causing significant disruption. Which solution can hlep mitigate this attack?

*- Device hardware*

**Device hardware specifically designed to handle DDoS attacks, such as dedicated DDoS mitigation applicances, can effectively filter out malicious traffic and ensure the availability of network services.  These devices are built to manage high traffic volumes and protect against the impact of DDoS attacks.**

--------------

### Lesson 3

A company is migrating its sensitive data to the cloud and wants to ensure that it is securely stored.

Which solution can helpt secure data in the cloud?

*- Using strong encryption algorithms*

**Strong encryption algorithms can helpt secure data stored in the cloud by encoding it in a format that can only be accessed with the appropriate decryption key, ensuring the confidentiality and integrity of the data.**

--------------------

An organization is deploying applications to the cloud and is concerned about unauthorized access.

Which approach can help secure cloud-based applications?

*- Implementing multi-factor authentication (MFA)*

**Implementing multi-factor authentication (MFA) adds an extra layer of security by requiring users to provide multiple forms of verification before accessing cloud-based applications, significantly reducing the risk of unauthorized access.**

-------------

A company is using cloud-based storage for its critical business documents and wants to prevent data breaches.

Which measure can help enhance the security of cloud storage?

*- Enabling access control mechanisms*

**Enabling access control mechanisms allows organizations to define and enforce policies governing who can access specific data stored in the cloud, helping to prevent unauthorized access and data breaches.**

--------------------

A company is setting up a wireless network in its offic
