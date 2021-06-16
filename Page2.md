# **What Makes The Internet Work?**
---
## **Things You Cannot See or Touch**
The things you cannot see or touch are the concepts and ideas that have are used to develope how the devices in a network communicate. The internet is a global network which allows communication across the globe.

### **Binary**

Binary is a base in the number system containing only ones and zeros. Also known as base 2. It is used mainly to represent high and low, on and off, true and false. A sequence of the ones and zeros can be used to represent a message. Messages sent from an electronic device are made up of bits. A bit is either a one or a zero.

    4 bits = Nibble 

    8 bits = Byte

    16 bits = Half Word

    32 bits = Word

    64 bits = Double Word


### **Hexadecimal**
Base 16 is called hexadecimal and is made of 16 characters that each represent a numerical value. A hexadecimal value is mostly used to represent a nibble.

Example :
* A nibble with the value 0010 in binary is 0x2 in hex  
* A byte with the value 10000001 in binary is 0x81 in hex

|Decimal   |Hexadecimal| Binary|
|---------:|----------:|------:|
|0         |0          |0      |
|1         |1          |1      |
|2         |2          |10     |
|3         |3          |11     |
|4         |4          |100    |
|5         |5          |101    |
|6         |6          |110    |
|7         |7          |111    |
|8         |8          |1000   |
|9         |9          |1001   |
|10        |A          |1010   |
|11        |B          |1011   |
|12        |C          |1100   |
|13        |D          |1101   |
|14        |E          |1110   |
|15        |F          |1111   |

_Table 1: Showing the representation of 0 to 15 in decimal, hexadecimal, and binary_

### **Transporting Bits**
* Electricity
* Light
* Radio Waves

### **Protocols**
Protocols are the rules and procedures used to establish a standard. The internet being a global collection of individual networks need standards so that everyone knows the rules that need to be followed so that messages can be sent between devices irrespective of the manufacturer or model.

* TCP/IP and UDP
  * Transfer Control Prototcol (TCP)
  : The most widely used protocol for communicating over a network. This protocol divides the the message being sent into packets and checks the packets when they arrive at the destination. 
  * Internet Protocol (IP)
  : This protocol is used with TCP or UDP when packets are being sent over a network. It is the protocol that is used to assign addresses to the devices on a network. There are different factors that determine an IP address including the address type and the subnet.
      * IPv4 
      : A 32 bit address that is typically represented using decimal. Ranges from 0.0.0.0 to 255.255.255.255.
      * IPv6 
      : A 128 bit address that is typically represented using hexadecimal. Ranges from 0:0:0:0:0:0:0:0 to FFFF:FFFF:FFFF:FFFF:FFFF:FFFF:FFFF:FFFF.
  * User Datagram Protocol (UDP)
  : Unlike TCP, UDP does not error check packets when they arrive at the destination.

* HTTP, HTTPS, SSL
  * Hypertext Transfer Protocol (HTTP) and Hypertext Transfer Protocol Secure (HTTPS)
  : HTTP transfers data between the client browser and the web server in hypertext format. HTTPS does that same in an encrypted format.
* DNS
* POP, IMAP, SMTP
: These protocols are used for emails. POP and IMAP are used to retrieve emails from the server and 
  * Post Office Protocol (POP)
  : The latest verion of POP is version 3 (POP3). 
  * IMAP
  * SMTP

| Protocol | Port |
|---       |---   |
| FTP      | 20 and 21|
| HTTP     | 80       |
| HTTPS    | 443      |
| IMAP     | 143/993  |
| POP3     | 110/995  |
| SMTP     | 25/465   |

_Table 2: Showing the respective port numbers for each protocol. xxx/yyy represent the port for unencrypted/encrypted traffic._ 

---
## **Things You Can See or Touch**

### **Cables and Wires**
* Ethernet
* Fiber Optic : Uses light pulses to represent bits and traonsport messages between the sender and the receiver.
### **Devices**
* Modem
* Router
* Switch
---
## **Security**
In our lives we use locks, alarms, and surveillance to keep physical properties protected. Security is important because not everyone has good intentions.  
### **Cryptography**

### **Public Key Infrastructure (PKI)**
 
#### **Certificate Authority (CA)**

### **Firewall**
The purpose of a firewall is to block unwanted network traffic from travelling in a specific direction. This means that it can prevent attackers from penetrating a private network. Firewalls can either be a software or a combination of hardware and software. They are used to protect individual computers or networks.

Types of firewall:
  * Proxy firewall
  * Stateful inspection firewall
  * Unified threat management firewall (UTM)
  * Next-generation firewall (NGFW)
  * Threat-focused NGFW
  * Virtual firewall

### **Virtual Private Network (VPN)**
---
## **The Organizations Maintaining Order**
### **The World Wide Web Consortium (W3C)**
### **Internet Corporation For Assigned Names and NUmbers (ICANN)**
---
### **References**
[1] https://www.cisco.com/c/en/us/products/security/firewalls/what-is-a-firewall.html

[2] https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols

[3] https://www.educba.com/types-of-networking-protocols/

---
Footer Menu






