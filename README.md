# DAY-7
I am Jaskiran kaur from department of 'COMPUTER SCIENCE ENGINEERING'.

HOST: 
---
A host is any device connected to a network that can send or receive data.

---
TRAFFIC:
---
It refers to the flow of data across a network. It’s basically the movement of packets or information between devices (hosts) over the network.

---
PROTOCOL:
---
a protocol is a set of rules or standards that define how data is transmitted and received between devices on a network.

---
IP ADDRESS:
---
 An IP address (Internet Protocol address) is a unique string of numbers assigned to each device connected to a computer network that uses the Internet Protocol for communication.
What an IP address does:

    Identifies a device on a network, kind of like a postal address for your house.

    Allows devices to find and communicate with each other over the internet or other networks.

Types of IP addresses:

    IPv4: Most common, looks like this — 192.168.1.1 (four numbers separated by dots, each from 0 to 255).

    IPv6: Newer version to handle more devices, looks like this — 2001:0db8:85a3:0000:0000:8a2e:0370:7334 (longer and uses hexadecimal).

Two kinds of IP addresses for devices:

    Static IP: Stays the same all the time.

    Dynamic IP: Changes periodically, usually assigned by a DHCP server.

    ----
![image](https://github.com/user-attachments/assets/2dbb13ac-5003-44e1-b41e-c43b51dc0d18)
---
# CLASSFUL ADDRESSING:
---
What is Classful Addressing?

    The IPv4 address (32 bits) is divided into five classes: A, B, C, D, and E.

    Each class has a fixed number of bits for the network part and the host part.

    This division helps routers know which part of the IP address identifies the network and which part identifies the host on that network.

Classes and their ranges:
| Class | First Octet Range | Network Bits | Host Bits | Number of Networks | Hosts per Network   | Usage                   |
| ----- | ----------------- | ------------ | --------- | ------------------ | ------------------- | ----------------------- |
| A     | 1 – 126           | 8            | 24        | 128 (2^7)          | \~16 million (2^24) | Large networks          |
| B     | 128 – 191         | 16           | 16        | 16,384 (2^14)      | 65,534 (2^16 - 2)   | Medium-sized networks   |
| C     | 192 – 223         | 24           | 8         | 2,097,152 (2^21)   | 254 (2^8 - 2)       | Small networks          |
| D     | 224 – 239         | N/A          | N/A       | N/A                | N/A                 | Multicast groups        |
| E     | 240 – 255         | N/A          | N/A       | N/A                | N/A                 | Experimental / Research |

Class A: Large networks (e.g., big corporations, governments).

Class B: Medium networks (universities, smaller companies).

Class C: Small networks (small businesses, home networks).

Class D: Used for multicast traffic.

Class E: Reserved for future or experimental use.

----
MAC ADDRESS:
---
A MAC address (Media Access Control address) is a unique identifier assigned to a network interface card (NIC) or device's hardware used to communicate on a local network.
Key points about MAC address:

    It’s a hardware address that identifies a device on the local network segment (like your Wi-Fi or Ethernet network).

    MAC addresses are usually fixed and assigned by the device manufacturer.

    Format: 48 bits long, usually written as six pairs of hexadecimal digits, like:
    00:1A:2B:3C:4D:5E or 00-1A-2B-3C-4D-5E

    The first half (first 3 pairs) identifies the manufacturer (called the OUI — Organizationally Unique Identifier).

    The second half is a unique number assigned by the manufacturer to that specific device.

    ---
CABLES
---
 In computer networking, cables are physical media used to connect devices and allow data transmission between them.
Common types of network cables:

    1. Twisted Pair Cable

        Most widely used for local area networks (LANs).

        Consists of pairs of insulated copper wires twisted together to reduce interference.

    2.  Two types:

            Unshielded Twisted Pair (UTP): Common in Ethernet networks.

            Shielded Twisted Pair (STP): Has extra shielding to reduce electromagnetic interference.

        Examples:

            Cat5e, Cat6, Cat6a cables for Ethernet.

        Used for connecting computers, switches, routers, etc.

    3. Coaxial Cable

        Has a central copper conductor, insulating layer, metallic shield, and outer insulating layer.

        Used in older Ethernet networks (10Base2, 10Base5) and cable TV.

        More resistant to interference than twisted pair but bulkier.

    4. Fiber Optic Cable

        Uses light to transmit data through thin glass or plastic fibers.

        Very high speed and can cover long distances without signal loss.

        Immune to electromagnetic interference.

        Used in backbone networks, internet infrastructure, and long-distance communications.

---
![image](https://github.com/user-attachments/assets/b67db61a-dbdf-4177-b012-a68d37cc4c68)
--
![image](https://github.com/user-attachments/assets/b85b7956-a235-4a75-860f-350f0e97e31c)
---




