# Black Belt - Meraki Deployment - CAPTURE THE FLAG (CTF)


## 1. SFO Modus operandi?
### Q. Review the "San Francisco" site and determine the following:
### 1- What mode is the branch MX deployed in?
### 2- What is the typical MX default tracking client mode?

### [Please input your flag in x/y format to unlock this challenge - where x is the operational mode and y the client tracking mode.]

* ***routed/unique client identifier*** 


## 2. KNOW YOUR NETWORK - SFO

### Review the "San Francisco" site and determine what VLAN IDs are configured for that branch.

### [Please input your flag in x/y format to unlock this challenge, where each of the letters corresponds to a configured VLAN, from lowest to highest; eg - 1/2/3/4]

* ***1/50***


## 3. THE SFO BRANCH CONNECTIVITY 

### The San Francisco network includes a Meraki Cloud-Managed MX Security and SD-WAN device, which has VPN functionality enabled. This can be checked under Security & SD-WAN -> Site-to-site VPN. It allows you to connect to data centers and remote peers using Cisco Meraki’s Auto-VPN. Additionally, an SD-WAN setup is configured for all connected sites.

### How many sites is the San Francisco location connected to via Cisco Non-Meraki Site-to-Site VPN?
### If there are connected sites, please list their names in answer. If there are no connections, enter 'None'.

### [Please submit your flag in the format location1/location2/location3/location5/etc., ordered alphabetically. If there are no connections, simply submit the answer 'None' to unlock this challenge.]

* ***None***


## 4. LET'S TAlK TO SFO

### When you first enabled the SD-WAN overlay, your branch MX automatically started learning routes from its peers. From which peer location is the San Francisco MX learning the route 172.17.5.0/24?

### Please input your flag in the format peer1.

* ***não sei a resposta!!!! Se alguém souber, favor enviar, que eu atualizo aqui***


## 5. ENFORCE COMPANY POLICY

### The MX device comes with many security features. One of the most common and important is content filtering which allows you to block undesired traffic to specific pre-configured categories of URLs. Navigate to the "London" site and check which content categories the MX is configured to block.
### Please enter your flag with the names of the categories.

### Please input your flag in the format category1/category2/category3/etc. in alphabetical order

* ***adult/child abuse content/pornography***


## 6. PATH OF LEAST RESISTANCE

### User experience improvement is one of your goals as network admin. You must configure your network to choose traffic paths based on link performance metrics for some of the applications hosted in the Data Centers. Those applications do not accept link latency higher than 50ms, jitter higher than 10ms, and loss higher than 1%.

### What is the name of the custom performance class configured at London's MX which matches the metrics described?

* ***high quality real time services***


## 7. INSTALL ME WI-FE

### In this Capture the Flag mission you will navigate the Catalyst Center Trends and Insights of AI-Network Analytics. Become a seasoned wireless engineer and analyze RF data relative to referenced radios operation under optimal conditions through the eyes of Catalyst Center AI Endpoint Analytics. You will also assess the impacted clients to understand the scope of a poor performing access point. To Capture this flag, what is the number of clients that are impacted by the high co-channel interference on access point SFO15-C9136-01?

* ***access points***


## 8. CAPTIVE WI-FI - SFO 

### You need to figure out what is the SSID configured to use a captive portal and no authentication in San Francisco office.

* ***CMP-CAMPUS-SFO-Lobby*** 


## 9. OPEN FOR BUSINESS

### You need to make the SSID advertised by your AP functional only during business hours every single day. What is the schedule template name you should apply on it?

* ***available 8-5 daily***


## 10. CUSTOMIZE MY SIGNAL 

### Now that you have basic AP info, you will need to configure RF profiles for your Wi-Fi network. In what section of the dashboard would you configure RF profiles?

* ***radio settings***


## 11. NEEDLE IN A HAYSTACK - WI-FI EDITION 

### Users are having a bad WI-FI experience (i.e., high delay to load web pages, connectivity issues, sticky clients).

### As a System administrator, you need to get information to start troubleshooting the environment.

### What is the name of the Report in dashboard that can show, all at once, the most common Wi-Fi problems (e.g., # of failed connections, # of devices with problems, # of failed connections per problematic client) in a given network?

* ***health***


## 12. VISION 2020

### The MV family brings Meraki magic to the enterprise video security world.
### Centralized cloud management, "everything’s" in the box, super-secure, and bandwidth-conscious are some of the benefits of the solution.
### Your first task related to the cameras is to check how many you have in the London. Enter the flag with the number of cameras installed in the London office.

* ***2***


## 13. WALLED VISION

### One useful capability of the MV solution is to build a video wall, where you can verify multiple cameras simultaneously. You can create multiple video walls where you can put together groups of cameras with the same interest or target area.

### What is the name of the video wall in London which includes all the MVs installed at the venue?

* ***video wall - london***


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