# Black Belt - Switching Deployment - STAGE 1 QUIZ


## 1. A network administrator wants to prevent employees from accessing social media applications during work hours by blocking them at the network level. Which Cisco Catalyst Center feature, leveraging NBAR/CBAR, could be used to achieve this?

* ***Port Security***
* DHCP Snooping
* QoS policy with application fingerprinting
* Dynamic ARP Inspection (DAI)


## 2.  In an 802.1X (dot1x) deployment, what is the role of the AAA server (e.g., Cisco ISE) after a user provides credentials?

* To act as the physical authenticator device.
* ***To verify the user's identity (authentication) and determine their network access privileges (authorization).***
* To forward all user traffic to the internet.
* None of the above


## 3. WWhat is the recommended soft oversubscription ratio for the uplink from the access layer to the distribution layer?

* Below 5:1
* Below 10:1
* ***Below 20:1***
* Below 50:1


## 4. Cisco Umbrella provides security at which layer of the network, primarily by inspecting and validating queries to prevent users from accessing malicious sites?

* Physical Layer
* Data Link Layer
* ***DNS Layer***
* Network Layer


## 5. To prevent current ARP attacks by validating ARP packets, what global configuration command is used to enable Dynamic ARP Inspection (DAI) for specific VLANs?

* ip arp inspection enable
* ip arp inspection trust
* ***ip arp inspection vlan [data vlan], [voice vlan]***
* ip arp inspection limit rate


## 6. What technology is recommended for simplifying the Distribution Layer design by creating a "Single Box Design" from a deployment perspective?

* First Hop Redundancy Protocols (FHRPs) like HSRP or VRRP
* Spanning Tree Protocol (STP) for loop avoidance
* ***Virtual Switching System (VSS) or StackWise Virtual (SWV)***
* A fully meshed Layer 2 topology


## 7. What is the primary role of the Distribution Layer in a campus network design?

* To provide direct access to end-user devices.
* To serve as the high-speed backbone for the entire network.
* To connect the campus network to the internet.
* ***To act as an aggregation point, provide Layer 2 boundary, introduce Layer 3, and manage congestion with QoS.***


## 8. WWhich of the following is NOT listed as an attribute of the Access Layer in the design fundamentals?

* Provides endpoints and users direct access to the network.
* Supports Wireless LAN access APs.
* ***Provides IP Routing summarization to the rest of the network***
* Supports advanced technologies like PoE services.


## 9. What is the primary purpose of Port Security (limiting the maximum number of MAC addresses) on a switch port, as described in the script?

* To allow only specific VLANs to pass through the port
* To enable Power over Ethernet (PoE) functionality.
* To increase the speed of data transfer on the port.
* ***To prevent a Cam overflow attack by a malicious device spamming MAC addresses.***


## 10. What is the key distinction between the E-100 and K-100 variants in the new Silicon One lineup?

* E-100 supports more slices than K-100
* E-100 has built-in encryption; K-100 does not
* ***K-100 includes high bandwidth memory (HBM), while E-100 does not***
* K-100 is for fixed switches, E-100 is for modular switches


## 11. What is the primary benefit of a Virtual Output Queue (VOQ) system in Cisco Silicon One-based switches?

* It increases the maximum cable length between switches
* It simplifies MAC address learning
* It reduces power consumption in the ASIC
* ***It eliminates head-of-line blocking by providing per-destination queuing***


## 12. What stacking or virtualization method is supported for Catalyst 9610 high-availability configurations?

* StackWise-480 only
* ***StackWise Virtual with NG Stacking architecture***
* No stacking supported
* Cisco Fabric Interconnect


## 13. What is the Cisco Application Framework (CAF) used for in IOS XE?

* Hosting Docker containers on unused CPU cores
* Storing user configurations
* Managing hardware ASIC drivers
* ***Running virtual machines on the control plane***


## 14. A customer is designing a high-capacity network infrastructure and requires a line card that supports 400 Gigabit Ethernet (400G) speed for connectivity in their Cisco Catalyst 9606R chassis. Which of the following line cards should the customer select to meet this requirement?

* C9600-LC-24C
* C9600-LC-48YL
* ***C9600X-LC-32CD***
* C9600-LC-48TX


## 15. A customer is designing a high-performance enterprise network and requires a Cisco Catalyst 9350 switch that supports all 48 ports at 10 Gigabit Ethernet speed. Additionally, the customer needs each port to provide up to 90W of power using Cisco's Universal Power over Ethernet Plus (UPOE+) technology to support high-power devices such as advanced IP cameras, wireless access points, and smart building IoT devices. Which model should they choose?

* Cisco C9350-48P
* Cisco C9350-48U
* ***Cisco C9350-48HX***
* Cisco C9350-48T


## Assesment Result - 1300/1500 points (87%) - required 1200 points (80%) for approvation

* **`CVD`** - Total questions 69 - **800/900 (89%)**
* **`Silicon One`** - Total questions 2 - **200/200 (100%)**
* **`IOS XE`** - Total questions 2    - **100/200 (50%)**
* **`Smart Switches`** - Total questions 2 - **200/200 (100%)**