 # Call#1

## Section 1 Lesson 1

 

### Network devices:

 

**WAP**
  - Wireless Access Point
  -  Device used to connect devices to a newtwork by wireless means
  -  typically, will connect to a network switch as an extention of the LAN creating a WLAN

**Router**
  - Layer 3
  - interconnect different networks like multiple LAN buildings or LAN to WAN network.
  - uses IP address to determine how to route network gtraffic to the destination.

 **Switch**
   - Layer 2
   - central device in a star topology
   - the switch learns the MAC addresses that come from the devices that are connected to the switch's ports. the switch creates a table using the MAC addresses to forward frames to the correct device.
   - if the switch does not know the destination MAC address then it will send a broadcast (ARP) to find out the MAC address

**Hub**
  - Layer 1
  - hubs send the signal to all connected devices regardless of destination.
  


### Topologies:

 

**Star**
  - network where devices are all connected to a centeral point

**Ring**
  - Also referred to by Token Ring
  - passes data from one device to another using their directly connected neighbor
  - each device has a neighboring device connected on each side

**Bus**
  - a signle cable connects all of the computers and other network devices together

**Mesh** 
  - has a connection to every device and will provide the best option for redundancy in case of a device failure

 

### Network Types:

 

**LAN**
  - local area network
  - could be a building, house or room that connects mulitple computer and devices together

**MAN**
  - Metropolitan Area Network
  - may connect several different LANs together that may 

**CAN**
  - campus area network
  - mutliple buildings connected to a network.

**WLAN**
  - Wireless Local Area Network
  - the wireless portioin of the LAN
  - provides wireless network connectivity to mobile devices

**WAN**
  - could connect to a server across the contry or across the world.

 

### Cables

**Coaxial Cable**
  -

**Cat 5**
  -

**Cat 5e**
  -

**Cat 6**
  -

**Cat 6A**
  -

**Single Mode Fiber**
  -

**Multi Mode Fiber**
  -

 

---------------------------------------

 

# Call#2

## OSI Model

 

### List and describe what happens at each layer of the OSI model, the network devices at each layer and protocols at those layers.


 **Application**
   - This layer is responsible for network applications (like HTTP or FTP) and their production of data to be transferred over the network. This is what is displayed for the end user to see on the computer screen.

**Presentation**
   - This layer is responsible for translating data from the application layer into the format required to transmit the data over the network as well as encrypting the data for security if encryption is used.

 **Session**
   - This layer is responsible for connection establishment, session maintenance, and authentication.


 **Transport**
   -The transport layer is responsible for end-to-end communication between devices. It is responsible for the reliable delivery of data. It segments and reassembles data in the correct order for it to be sentg ot the receiving device. It may also handle the reliable delivery of data and any retries of data that are lost or corrupted. This layer is often called the heart of the OSI. The protocls *TCP* and *UDP*.

  - **TCP**
     - Considered connection-oriented and reliable
     - ensures all data has been delivered and checks for errors during data transmission
  - **UDP**
     - Connectionless, does not first establish a connection before sending data like TCP.
     - Does not guarantee delivery.
     - Best used for real time applications like online gaming, voice applications and video conferencing.

 **Network Layer**
   - This layer is responsible for the transmission of data between hosts in different networks as well as routing of data packets. This layer is implemented through the use of devices usch as *routers* and some switches.

 **Data Link**
   - This layer is implemented through the use of devices such as *switches* and *bridge devices*, as well as anything with a netwrok interface, like wireless or wired network cards. This layer uses MAC addresses to forward frames to the destination. Ensures the frames are free from errors before sending data.

 **Physical Layer**
   - This layer is responsible for the physical connections of the devices in the network. This layer is implemented through the use of devices such as *hubs*, *repeaters*, *modem devices*, and *physical cabling*.
 

### Network Commands

 

### Describe the network commands:

 

**Ping**
  - tests connectivity to other hosts
  - sends an ICMP echo request to a host and listens for the reply
  - measures latency between two devices

**Traceroute**
  - Linux command
  - will show you the path your network traffic is taking to a destination
  - can test latency for how long it takes a packet to reach destination and back
  - shows "hops"

**Tracert**
   - Microsoft Windows
   - same input as Traceroute

**Netstat**
  - See what connections are active on the local computer
  - useful for troubleshooting and capacity management
  - displays routing information for network adapters

**Nslookup**
  - can be used to find IP address to host name or host name to IP address using a DNS server

**Dig**
  - Linux
  - basically same as Nslookup but more detailed

**Ipconfig**
  - Microsoft Windows command
  - will display our IP address information on our local computer.
  - includes IP address, subnet Mask and Default Gateway

**Ifconfig**
  - Linux Command
  - will display the IP address information on your network adapter. Similar to Ipconfig

**Telnet**
  - unencrypted and username, password, and data is sent in clear text for anyone to see
  - good for video calls

**SSH**
  - encrypted so the username, password and data is protected by encrypted

 

------------

# Call#3

## Section 1 Lesson 4

 

### Cloud Service Models:

 

**IaaS** 
  - Service provider gives you on-demand access to infrastructure services, including compute, storage, networking, and virtualization. You manage evertyhing else i.e. the virtual machines, operating systems, middleware, apps and your data.
  - no need to maintain or update your own data center infrastructure.

**PaaS**
  - The service provider delivers and amnages all the hardware and software resources needed for application development. You write the code and manage all the apps and data but you do not have to manage or maintain the software development platform. 

**SaaS**
  - Service provider delivers and manages the entire application stack (from the hardware infrastructure all the way to the application itself) throught the internet.
  - All updates, bug fixes and other general maintenance to all components are handled by the provider. All you have to do is connect to the app.

 

### Cloud deployment models:

 
**Private cloud**
  - Cloud model is used by only one organization or tenant and is not shared with other organizations.

**Public cloud**
  - This model is available over the internet and for public use. You share the same hardware like storage and netwrok with other organizations. The cloud provider is responsible for the network infratsture.

**Hybrid cloud**
  - Combines the features of using both private and public cloud. This model with store and uses applications in both models.

**Multi cloud**
  - Uses different cloud services from more than one cloud provider. 

**Community cloud**
  - This model is shared between different organizations. Usually these organizations will be in the same industry or share a common goal.


### Types of Hypervisor 

**Type 1**
  - Bare Metal
  - loaded directly on the server hardeare with no underlying operating system
  - usually found in large data centers to provide performance and large-scale virtualization

**Type 2**
  - Has an underlying operating system already installed.
  - Best suited for smaller scal virtual environments like school, home or lab environments.
  - download and install the hypervisor like you would any other applicaiton. runs on top of an existin operating system.

 
--------

# Call #4

 

## Section 2

 



**CIA**
  - Confidentiality
     - helps limit access to information, preventing an unauthorized user from accessing, copying, or transmitting the information
  - Integrity
     - Helps maintain the accuracy of data to identify the trustworthiness of the information
  - Availability
     - Ensures the data is always accessible by its authorized user

**White hat**
  - IT professionals who specialize in penetrating and compromising network security to help an organization

**Black hat**
  - have malicious intent and breach systems for profits

**Grey hat**
  - has no malicious intent but often break laws by not having permission

**Blue team**
  - Team to try and defend during simulation attacks

**Red team**
  - Team to attack during simulation attacks

**White team**
  - Team to observed red and blue teams during simulation attacks

**Purple team**
  - Red and Blue team when they debrief and cross-train each other 

**Zero day**
  - The exploit or vulnerability is not knnown yet

**Script kiddie**
  - Someone that has no understanding of the coding they are using
  - uses tools and scripts developed by more advanced hackers

**Man in the middle attack**
  - Occurs when an attacker uses spoofing to insert their device between two legitimate endpoints and transparently intercepts, relays or alters the traffic flowing between them

**Phishing**
  - can be done through email, text, voicemail and other methods.
  - goal is to have the target or user disclose personal information

**Vulnerability**
  - A weakness in the system design, implementation, software or software code

**Exploit**
  - refers to software, tools, or technique that takes advantage of an vulnerability that can lead to unauthorized access, denial of service attack or some other type of attack on the network or computer system.

**Social Engineering**
  - Act of manipulating human trust to gain access or information
 

--------------

# Call#5

 

## Section 3 Lesson 1

 

**Data retention policy**
  - A set of guidelines defining what information an organization keeps, how long it is stored, and how it is securely disposed of

**AUP (Acceptable use policy)**
  - A policy that determines how the network will be used by employees and guest. Defines what users ca and cannot do while using the organization's IT resources and systems.

**BYOD policy**
  - Employees are permitted to use their personal mobile devices to access enterprice data and systems.

**Least Privilege**
  - Limits who has access to the data that is being protected by using system file permissions.

**Fails Safe default**
  - Concept stating that when a system, application, or device fails, loses power, or encounters an unkown error, it should revert ot its most restrictive and secure stat.

**Economy of Mechanism**
  - The security mechanisms should be simple helps keep the system simply to understand and maintain will help with security vulnerability within the system and reduce the attack surface for an attacker to exploit.

**Complete Mediation**
  - Every access to an object must be validated and checked. Will not use previous checks or validations.

**Open Design**
  - Model states that the passwords and encryption keys should be kept secret and not the implementation of the system itself. The focus is to protect authentication methods like passwords and encryption keys for securing data. The goal here is not to hide how the system opeates.

**Separation of Privilege/Duties**
  - Concepts does not allow a single person to have complete control over a device or system. This prevents fraud and misuse of the device or system and provides overall acountability.

**Least Common Mechanism**
  - Minimize shared mechanisms between users and processes. In this model, we want to reduce the number of shared resources that are being accessed by multiple users.

**Psychological Acceptability**
  - Relies on the interface between the human and the system to be eaasy to use. This will help with protecting the system security. If the system security methods are too hard, the user will avoid them or try to find a way around the security measure.

**Zero Trust Architecture (ZTA)**
  - Does not assume authomatic trust between devices based on location of where the device is on a network.
  - Operates on the principle of never trust, always verify.

**Stateful Firewall**
  - Keeps track of active connections and uses this information to make, allow, or deny decisions.

**Packet Filtering Firewall**
  - Inspects source IP address, destination IP address, and protocol port numbers.
  - Has a rule table and inspect snetwork traffic and compares the network traffic against the rule table. Table determines if traffic is allowed in or not

**Application Layer Firewall**
  - Does a deep pack inspection of the network traffic
  - inspects the payload to determine what type of application is being used. 

**IDS**
  - Intrustion Detection System
  - will monitor network traffic and look for any pontential threats
  - will log threats and send a message to the admin

**IPS**
  - Intrustion Prevention System
  - Intercepts and prevents threats

**Asymmetric Encryption**
  - Uses 3 keys, private and public key

**Symmetric Encryption**
  - uses the same key to encrypt and decrypt

**DoS**
  - Denial of Service
  - Where the attacker is trying to disrupt network services, or completely bring down the service

**DDoS**
  - Distributed Denial of Service
  - Similar to DoS in style, but has multiple attakers instead of one attacker

**Ping Flood**
  - Network layer 3
  - Attacker sends a large scale amount of ICMP packets to a target eevice. This DoS attack is meant to overwhlm the target and slow it down or crash it.

**Smurf Attack**
  - DDoS attack
  - Attacker uses a spoofed IP address from a real device like a server on the network. The attacker uses the broadcase address and sends ICMP request to the broadcast address, which responds to the real server. This slows and even crashes the system.

**Dictionary Attack**
  - will use a predefined list of common words and phrases to match a passwod to a computer or application.

**Brute Force Attack**
  - Uses every combo of a password to gain access to a device or system

**SQL Injection Attack**
  - happens when the attacker inputs data in a form field that is incorrect. Can potentionally pass a command that could alter the database or give the attacker access to the database.

**Risk Mitigation**
  - Not all risk can be avoided/eliminated
  - the goal is not to elimiate the threat/risk but to emplement security measures to minimize the impact of potential risks to the organization

**Risk Avoidance**
  - occurs when an organizatgion decides not to accept any risk and eliminates anything associated with that risk.
  - goal is to eliminate as many risk as possible that would affect the organization negatively.

------------------------

# Call #6

 

**Discretionary Access Control**
  - The owner of the resource decides how the resource will be shared.
  - best suited for smaller networks

**Role-based Access Control**
  - Model provides access to groups rather than an individual. Permissions will be assigned to groups based on a job role.

**Attribute-Based Access Control**
  - Model can provide more specific access than just using a role-based user. Can combine different attruibutes like the user trying to login,what network, location, time of at or type of computer they are using

**Rule-Based Access Control**
  - This is a predefined set of rules that are in place to portecgt the network. The rules will either allow or deny based on the way the policy is set up. Firewalls us the model to protect the network.

**Context-based Access Control**
  - Does a deeper inspection of the network trraffic to identify any abnormalies in the packets. The network device is looking at how the packets are being used.

**WEP**
  - Wired Equivlent Privacy
  - Developed to add security over wireless networks.
  - legacy wireless encryption protocol

**WPA**
  - Wifi Protected Access
  - was developed to fix security issues with WEP
  - included MIC (Message Integrity Check) to prevent attackers from intercepting or modifying wireless traffic

**WPA2**
  - offers the option to use a pre-share key or enterprise
  - uses AES encryption instead of TKIP (Temporal Key Integrity Protocol)

**WPA3**
  - newest standard and improements over WPA2
  - encryption is unique for each user session
  - uses PMF (protected Management Frames) for wireless connection

**Ad Hoc Mode**
  - Deos not use a central device to connect to the wireless network liek a WAP
  - wireless devices connect directly to each other to send and recieve data

**Infrastructure Mode**
  - Wireless mode is used when the wireless client connects to the wireless network using a WAP

**Evil Twin Attack**
  - One type of rouge AP that is set up with the same SSID as a valid AP. When connected to the evil twin, attacker can see all the data being sent between the user and their destination

**Deauthentiation Attack**
  - Occurs when an attacker sends a wireless frame to the AP, telling the AP  to end the session for the client

**Rouge Access Point**
  - An AP  that has been installed on a secured company network by an eployee without permission.
  - Might also be instealled by a hacker to conduct a man-in-the-middle attack

**AAA Model**
  - Authentication
     - Confirms user is who they claim to be
     - usernames and passwords
     - public key infrastructure (PKI) certificates
   - Authornization
     - Define what the user can access
     - give permissions to a user
     - write and delete / read-only
   - Accounting
     - Report on user's access
     - provides forensic trail after a security breach
     - logs successful and unsuccessful connection attempts

**Separation of Duties**
  - Concept does not allow a single person to have complete control over a device or system. this prvents fraud and misuse of the device or system and provides overall accountagbility. A minimum of two people would be required to oversee a particular task.

**GDPR**
  - General Data Protection Regulation
  - Europena Union Law
  - regulates how organizations handle personal data of indivduals with the European Union.
  - Was created to protect the individiuals' rights to privacy and control over their personal information

**HIPPA**
  - Heatlh Insurance Portability and Accountability Act
  - Passed in 1996
  - requires healthcare organizations to implement security and privacy controls to ensure patient privacy.

**FERPA**
  - Family Education Rights and Privacy Act
  - Passed in th 1974
  - Protects the private data of students and their school record

**GLBA**
  - Gramm-Leach-Bliley Act
  - Passed in 1999
  - requires all types of financial institiutions to protect customers' private financial information
