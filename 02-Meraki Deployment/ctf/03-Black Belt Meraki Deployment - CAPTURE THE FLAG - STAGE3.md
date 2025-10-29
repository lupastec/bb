# Black Belt - Meraki Deployment - CAPTURE THE FLAG (CTF)


## 1. CISCO SECURE CONNECT USE CASES?

### Cisco Secure Connect securely connects users working anywhere to any application, including private applications hosted in your data center, private cloud, or public SaaS applications.

### What are the 3 major use cases for Cisco Secure Connect?

### Expected Flag Format: Use Case 1/Use Case 2/Use Case X

* ***secure internet access/secure private access/interconnect*** 


## 2. SASE PACKAGE

### Cisco Secure Connect is offered in two packages that make it easy for customers to choose the right level of protection and coverage for their organizational needs so they can SASE their way.

### Select all that apply from the below choices:

* ***Cisco Secure Connect Complete***
* ***Cisco Secure Connect Foundation***


## 3. AUTHENTICATING USERS

### To address the "Secure Remote Access" use case using Secure Connect, and IdP is required. For the services, listed below Cisco Secure Connect must integrate with an IdP to provide end-user Single Sign-on (SSO) for:

### Client-based remote access
### Clientless-based (ZTNA) remote access
### Enforcement of User-based internet access policies

### How many users are registered and can have security policies applied in this organization?

* ***4***


## 5. CONFIGURING REMOTE ACCESS

### Cisco Secure Connect enables remote users to securely access private applications from anywhere through the Secure Connect fabric. One of the ways to securely access private applications is using the Cisco Secure Client (formerly the Cisco AnyConnect client). When using Cisco Secure Client with a VPN tunnel you can select the traffic inside or outside the tunnel. Which configuration you must customize to accomplish this?

### Select all that apply from the below choices:

* ***não sei a resposta!!!! Se alguém souber, favor enviar, que eu atualizo aqui***


## 6. SECURING ACCESS TO PRIVATE APPLICATIONS

### Cisco Secure Connect secures access to private network destinations and applications via site-to-site VPN tunnels, client-based tunnels (Cisco Secure Client VPN) with identity-based control, and clientless per-app access using any browser. A private application is an application that is hosted within a private datacenter or private cloud. Cisco Secure Connect enables organizations to control access to an application to users connecting via client-based remote access or clientless remote access (ZTNA). How many private applications are currently configured in this organization?


* ***2***


## 7. CLIENTLESS REMOTE ACCESS (ZTNA)

### Clientless Remote Access or Browser Access allows you to leverage a web browser for user authentication and application access without requiring users to install the client on their devices. Clientless remote access can simplify how users access private applications while working remotely.

### Each user and device is verified and validated by a Browser Access Policy before access is permitted to an application or resource.

### When configuring a Browser Based Access Posture what are the 2 items you can add to the Endpoint Posture profile?

* ***operating system/browsers***


## 8. CONFIGURING BROWSER ACCESS POLICIES 

### Once you have 1-defined your applications and 2-configured your posture profile configuration, you can start to create your Zero Trust Access policies.

### There are currently 2 browser access policies configured. Doctors who don´t have the Secure client installed will fall under what endpoint posture profile?

* ***browser requirements*** 


## 9. CISCO SECURE CONNECT INTERNET ACCESS

### Cisco Secure Connect has four main policy categories for internet access that allow you to apply granular access control while maximizing performance.

### What are they?

* ***DNS***
* ***Cloud Firewall***
* ***WEB***
* ***DLP***


## 10. INTERNET ACCESS POLICIES DNS PROTECTION

### Domain Name System (DNS) protection is your first line of defense. Nothing stops attacks earlier than DNS-layer security. Secure Connect has implemented a pre-defined DNS access policy. Each policy can contain multiple settings.
### How many settings does the Default DNS policy currently contain?

* ***5***


## 11. CLOUD FIREWALL 

### Secure Connect’s Cloud Firewall provides firewall services without the need to deploy, maintain, and upgrade physical or virtual appliances at a site. The cloud firewall supports visibility and control of internet traffic, branch-to-branch traffic, and Remote users to internet or branch traffic. Secure Connect logs all network activity and blocks unwanted traffic using IP, port, protocol, or Applications (public and private) rule criteria.
### This organization has multiple Cloud firewall rules configured. One of them is called "App_access_allow". The source is configured to the users within 2 groups and the destination is configured to the resources and application group "ABC HCC".

### What resources or applications define the ABC HCC destination?

### The answer can be input in numerical IP or FQDN format.

### Expected Flag Format: use the format 1.1.1.1/2.2.2.2 or 1.1.1.1/fqdn.abc.com

* ***não sei a resposta!!!! Se alguém souber, favor enviar, que eu atualizo aqui***


## 12. SECURE WEB GATEWAY

### The Secure Web Gateway (SWG) specifically protects web traffic over ports 80/443. SWG proxies all of your web traffic for greater visibility and control. It enables you to log all activity, inspect web traffic to protect against viruses and malware, and enforce acceptable internet use policies.

### Currently, there is a Web policy called "Block Social Networking". What is the status of the HTTPS inspection feature?

* ***enabled***


## 13. DATA LOSS PREVENTION

### Data Loss Prevention (DLP) is part of CASB. The DLP function scans in all outbound web traffic and blocks sensitive data in it from leaving your organization or being exposed to malicious attackers in the cloud.

### What destination are configured to be evaluated against the "DLP block demo" DLP rule?

### Expected Flag Format: use the format option1/option2

* ***all destinations***


## 14. SEARCHING

### You received a request to assist in an investigation related to a car incident that happened some time ago and was recorded by your MV72x smart camera. You are not sure when it happened but you know where it happened. Instead of going back and forth reviewing footage, the MV provides a great feature in which you can select a specific area of the camera and all the events in that area will be promptly filtered.

### What's the name of this feature?

* ***motion search***


## 15. AUTOMATE YOUR WORLD

### As networks evolve, engineers are required to quickly adapt to new technologies. Programmability is a hot topic in the network world and Cisco Meraki provides great APIs which you can consume in many different ways.

### What is the collective name given to the group of Cisco Meraki APIs that you can use to automate administrative tasks in your network?

* ***dashboard API***


## 16. RESPONSIVE ALERTING

### For many years, network engineers relied on event logs (syslogs) to track information on the network. Now, with Cisco Meraki API technology, you can send alerts in a JSON formatted message that is sent to a unique URL where it can be processed, stored, or used to trigger powerful automations or playbooks.

### What is the name of the Cisco Meraki programmable function that can perform this kind of action?

* ***webhooks***


## 17. TRACKING USERS WITH APIs

### One of the most used Cisco Meraki MR APIs has the capability to "track" users and send raw information like MAC Address, IP Address, RSSI, floor, x/y location, etc.

### What is the name of the Cisco Meraki APIs that can provide this information in a streaming fashion?

* ***scanning API***