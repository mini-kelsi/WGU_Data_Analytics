# Networking Foundations: Networking Basics

https://www.linkedin.com/learning/networking-foundations-networking-basics/wireless-access-points-25000815?autoSkip=true&resume=false&u=2045532

### A Network's Purpose in Life

- 2 ways to connect to the internet

    - Wired with an ethnernet cable (CAT 5 / CAT 6 cables)
    - Wifi (wireless land)

--------------------

- Networks are categorized by their scope.

- **PAN** *Personsal Area Network* ~ Ex. the controller connected (either by bluetooth or wifi) to a gaming console

- **LAN** *Local Area Network* ~ Usually local to a building or within a building

- **CAN** *Campus Area Network* ~ Can connect to multiple local buildings

- **MAN** *Metropolitan Area Network* ~ Can connect multiple offices around a large city (ie multiple business across the city)

- **WAN** *Wide Area Network* ~ Can connect business around the world

----------------

  - **VPN** *Virtual Private Network*
 
--------------

Networks allos us to share items & communication.

- **IoT** *Internet of Things* ~ the interconnection via the internet of computing devices embedded in everyday objects, enabling them to send & recieve data.

- Monitoring Connected Devices

   - Equipment can send an alert
   - Motion alert from a security camera
   - Allows the use of an *Admin* to control from a central location
 
----------------------

### Networks Addresses

- **Physical addresses** are assigned at manufacturing, also called *burned in addresses*

- **Media Access Control** *MAC* **Address**

- **Network Interface Card** *NIC* ~ Each NIC has a unique MAC address ~ MAC address are unique vendor codes

- Vendor code makes up half of the MAC address

MAC Address Format ~ made up of 48 bits

**24 bits** -------**24 bits**

First 24 bits are unique to the manufactor. Known as Vender Code or **Organizationally Unique Identifier** *OUI*

- **Logical Address** is IPv4(Or IPv6) adress

- Logical address is assigned to a device and is codded into the hardware by the manufactor

- **IPv4 Address** is 32-bits and written with '.'  in 4 groups

**172.16.** *10.5*
First 16 bits is **Network** and the last 16 bits are the *Host*.  *16-bit Subnet Mask*

------------------------

IPv4 Address  ~ Bits in Address: 32 bits
              ~ Total Addresses: 2 ^32 possible addresses

IPv6 Address  ~ Bits in Address: 128 bits
              ~ Total Address: 2 ^128 possible addresses

- IPv4 address are full

- IPv6 has a prefix included in the address

- **Quartet** is the grouping of four hexadecimal digits

- IPv6 address have eight quartets

IPv6 Address Structure

**Prefix** *Host*

- 32 hexadecimal numbers
      - Using 1 - 9 and A - F

- 8 quartets of 4 hexadecimal digits separated by a colon

- EXAMPLE: 23A0:201A:00B2:0000:0000:0000:0400:0001/64

----------------------------

### Pieces and Parts of a Network

- Can have NIC that are internal or external

Enthernet Switch

- Learns which port has a MAC address

![Screenshot 2025-05-14 111100](https://github.com/user-attachments/assets/4af1683f-fe59-4319-a194-69a98bd88547)

-------------------------


- The device that connects all the networks is a router, which gives an IP address.

Twisted pair wiring

  - Unshielded twisted pair (UTP)
  - Shielded twisted pair (STP)

- RJ - 45 is the name of the connector for connecting wire to enthernet ports

![image](https://github.com/user-attachments/assets/60c3739f-7c16-4ada-b437-04f721d82e73)

----------------

- **Open Systems Interconnection** *(OSI)* **Model**

- The name of data at the physical layer is "bits." *Layer 1*

    - Where we have things like network cabling or radio waves being sent from wireless access points.
  

- The data link layer *Layer 2*

    - Where the switch makes their decisions based on those MAC addresses
 
    - We name give ata at this layer "Frames"

- Next is the network layer. *Layer 3*

    - routers operate at the 3rd layer of the OSI Model
 
    - Data is called "Packets" here

- *Layer 4* is the transporter layer

    - is concerned with logical connections
 
    - might be considered reliable where we confirm that transmitted information was recieved
      
    - or these connections could be considered unreliable, where we send the data and hope that it reaches its destination
 
    - Two main protocols that operate here at layer 4:

        - Transmission Control Protocol *TCP*
            - considered to one of those responsible transport protocols
     
        - User Datagram Protocol *UDP*
            - is considered to be unreliable

      - data is called "data segments"
     
  *Layers 5-7 do not have special names for data*

  - *Layer 5* is the session layer
 
     - conscered with establishing, monitoring, and then tearing down communication sessions between our hosts.
   
     - **Application Programming Interfaces** *API* let one's piece of software on one device talk to another piece of software on another device.
   
- *Layer 6* is the presentation layer

    - this is all about how we present data
 
    - we might encrypt data for security reasons, so some of our encryption protocols, they live at this layer.
 
    - We format a picture as a JPEG image.  That's a format of how that picture is represented, so we say JPEG fromatting lives at layer 6.
 
- *Layer 7* is the application layer

    - these layer that users typically interact with.
 
    - If you're surfing the web, you are using a protocol like HTTP or HTTPS.
 
    - If we know the name of a website, but not its IP address, what we can do is ask a DNS server and that DNS server will take the name that we provide and it's going to give us back the IP address corresponding to that name, and the protocol that makes that possible is domain name system, or DNS
 
    - DNS is an example of something that lives here at layer 7.
 
-------------------------------

We can memorize these layers from the bottom up using **Please Do Not Throw Sausage Pizza Away**

P ~ physical    *Bits*

D ~ Data Link    *Frames*

N ~ Network     *Packets*

T ~ Transporter     *Segments*

S ~ Session 

P ~ Presentation 

A ~ Application

Or from top to bottom **All People Seem To Need Data Processing**

A way to remember the data names is **Back Frying Produces Salivation**, which is bits, frames, packets, and segments.

The names in general are called protocol data units or *PDUs*.

This is a *reference model* and not a one fits all model.

--------------------------------

**TCP/IP Model**

![image](https://github.com/user-attachments/assets/238c502f-e4fc-4f37-9d32-19a519f3cdd8)

---------------------------

![image](https://github.com/user-attachments/assets/fc7c000a-fedf-4f11-bab8-0cabbfac413f)

HTTPS is more secure than HTTP, like for using card data

![image](https://github.com/user-attachments/assets/d90a4c95-468b-4d8d-8d7f-b837f8da761a)

------------------------------------------------------

- **Dynamic Host Configuration Protocol** *DHCP* ~ server that can hand out IP address information to all of our different network devices

![image](https://github.com/user-attachments/assets/33dcb190-e4e9-4b3f-bb0e-ad6577f721ce)


