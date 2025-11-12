# Black Belt - Switching Deployment - STAGE 2 QUIZ


## 1. Scenario: A network engineer is configuring an egress queueing policy on a Silicon One-based switch. They want to set up two priority queues: one for Voice (highest priority) and another for Critical Data. They attempt to configure tc7 as priority level 2 and tc6 as priority level 1. Question: What configuration issue will the engineer encounter, according to Silicon One QoS rules?

* tc7 must always be a normal queue, not a priority queue.
* ***Priority levels must be enabled in sequence, and tc7 must always be priority level 1.***
* Only one priority queue is supported on Silicon One ASICs.
* Custom traffic classes (like tc7 or tc6) cannot be assigned priority levels.


## 2.  In the Cisco Silicon One Q200 ASIC used in Catalyst 9000 switches, what is the maximum number of queues QoS can split traffic into on an interface?

* 4 queuesu200b
* ***8 queuesu200b***
* 16 queuesu200b
* 32 queuesu200b


## 3. Scenario: A network engineer accustomed to configuring QoS on Catalyst 6500 switches is migrating to a Catalyst 9300 switch. They attempt to copy and paste their old Catalyst 6500 QoS configuration directly onto the new switch. Question: What is the most likely outcome of this action ?

* The configuration will be accepted, but some parameters will be automatically adjusted to the new platform.
* The configuration will be accepted, but QoS will not function due to underlying hardware differences.
* ***The switch will reject every line of the old configuration due to syntax differences.***
* Only the wrr-queue bandwidth commands will be rejected, while others will be accepted.


## 4.  Which of the following best describes the queue types supported by Silicon One ASICs in Catalyst 9000 switches?

* Only normal queues with no priority differentiation
* ***Priority queues for critical traffic and normal queues for all other traffic, with a maximum of 7 priority and 7 normal queues***
* Equal priority for all queues with no differentiation
* Only one queue for all traffic


## 5. Scenario: A network engineer wants to implement Weighted Random Early Drop (WRED) on a Silicon One switch to differentiate traffic within the same queue. They have specific requirements to drop 'Yellow' traffic first during congestion, and 'Green' traffic later. Question: How should the engineer configure the ingress policy to achieve this differentiation for WRED on Silicon One ASICs?

* Use set qos-group to assign different QoS groups to 'Yellow' and 'Green' traffic.
* Configure set traffic-class with different values for 'Yellow' and 'Green' traffic within the same queue.
* ***Use set discard-class to mark 'Yellow' traffic with discard-class 1 and 'Green' traffic with discard-class 0.***
* Implement random-detect dscp-based on the ingress policy.


## 6. A network architect is designing the campus core for a large enterprise. The design requires a low-latency, high-availability core with advanced Layer 3 routing capabilities, including BGP for flexible routing and StackWise Virtual for maximum resilience. The access layer will be L3 routed. Which combination of technologies and architectural approach is recommended for this Enterprise Campus Core design, according to the document?

* RPVST+ with VRF segmented access
* Cloud Configuration with Show CLI
* ***StackWise Virtual (SVL) with BGP and L3 Routed Access***
* Device Configuration with Uplink Auto Config


## 7. A network engineer is troubleshooting a newly deployed cloud-managed IOS XE switch that is not appearing in the Meraki Dashboard. The engineer suspects an issue with the Meraki connection or the secure tunnel. Which command should the engineer use on the IOS XE switch to verify if the switch has fetched tunnel configuration, if the tunnel is up, and if packets are being sent/received?

* show meraki config updater
* ***show meraki connect***
* show uac
* show ip interface brief


## 8. A network engineer needs to troubleshoot a cloud-managed IOS XE switch located in a remote branch office. Direct physical access is not possible, but an interactive CLI terminal is required for detailed command execution and audit logging. Which feature provides this capability?

* ***Cloud CLI***
* Packet Capture
* Local Status Page
* Uplink Auto Configuration


## 9. Which feature introduced in IOS XE 17.15 enhances secure remote CLI access for cloud-managed Catalyst switches?

* SSH v1 supportu200b
* ***Cloud CLI via a secure Nextunnel connection***
* Telnet access over VPNu200b
* SNMPv2c community string authentication


## 10. A large campus network requires flexible and open dynamic routing, including support for route reflection, filtering, and AS-path control, with vendor-neutral peering. Which advanced routing protocol, introduced in IOS XE 17.18, best fits these requirements?

* OSPF
* EIGRP
* ***BGP***
* RIP


## 11. A company needs to segment different departments (e.g., Storefront, Warehouse) within their network using a single Catalyst switch, ensuring efficient route handling and forwarding while isolating traffic. Which feature, available in IOS XE 17.18, is ideal for creating scalable macro-segmentation?

* Routed Ports
* BGP
* ***Virtual Routing and Forwarding (VRF) Lite***
* RPVST+


## 12. Which of the following protocols is supported by xFSU to maintain forwarding state during upgrade?

* BGP (IPv4 and IPv6)
* OSPFv2 and OSPFv3
* IEEE 802.1X Port-Based Authentication
* ***All of these***


## 13. What is the primary mechanism by which xFSU reduces traffic downtime during software upgrades on Catalyst 9300 switches?

* Upgrades both control and data planes simultaneously
* ***Keeps the data (forwarding) plane operational while the control plane reloads, using graceful restart principles.***
* Requires a full system reload to ensure consistency
* None of these


## 14. A financial institution operates a core network segment using Cisco Catalyst 9600 series switches, which are configured with dual supervisors to ensure continuous operation. The IT department has scheduled a mandatory software upgrade to implement new security features. Given the extremely high cost of downtime in their environment, the primary objective is to complete the upgrade with minimal traffic interruption, specifically targeting a convergence time of less than 200 milliseconds. Which software upgrade method should the network team employ for the Catalyst 9600 platform to achieve this goal?

* Extended Fast Software Upgrade (xFSU)
* Cold Patching
* ***In-Service Software Upgrade (ISSU)***
* Performing a standard reload after installing the new image


## 15. A network engineer is designing a highly resilient L3 core network and needs to ensure minimal traffic disruption (less than 200ms) in case of an active device failure. The solution should leverage existing Catalyst 9000 series switches and support routing protocols like OSPF and BGP without interruption. Which feature(s) would achieve this goal for a core deployment?

* SSO
* NSF
* ***Both SSO and NS***
* None of these


## Assesment Result - 1500/1500 points (100%) - required 1200 points (80%) for approvation

* **`QoS`** - Total questions 5 - **500/500 (100%)**
* **`IOS XE`** - Total questions 6 - **600/600 (100%)**
* **`xFSU`** - Total questions 2    - **200/200 (100%)**
* **`High Availability (HA)`** - Total questions 2 - **200/200 (100%)**