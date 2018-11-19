# Optimization & Fault Tolerance

### Bandwith Shaped

- Control network traffic

    > Set upload and dl limits on types of data
    > Can prioritize data

### Traffic Shapin

- Prioritizes applications 

### Load Balancer

- Used to evenly dist. data across network. 

        > If one server gets more activity, it will spread it across to other server evenly. 

### Content Engine

- A content engine is typically a network appliance, which can receive a copy of content stored elsewhere (for example, a video presentation located on a server at a corporate headquarters) and serves that content to local clients, thus reducing the bandwidth burden on an IP WAN.

### QoS Quality of Service 

- Provides guarantee of data delivery within certain period of time

### Port Blocking

- Provides security of ports from firewall.

        > IE Block 80 to block HTTP traffic

### High Availability

- Guarantees period of uptime for continual operation

### Power Fault Tolerance

- UPS Battery to keep things going during possible power outages. 

    > Uninterrupted Power Supply. 

- Surge and spike protection

### Link Redundancy 

- ISDN can be a backup incase broadband fails
- Can have secondary network card. 

### Backup Services

- Can have standby server with exact config as primary in case primary goes down. 
- Server Clustering : When a company has a group of servers for load balancing and fault tolerance. 

    > works best in different geographical locations. \

### Disaster Recovery

- Rebuilding organizations data in case of data loss. 

    > 3 Types of Data Backups

        > Full: all data backed up on one tape. Simpliest form of backup
        > Incremental : Only backs up data that has been changed since last full/incremental backup.
            > Restore : Full + Incrementals (in correct order)
        > Differential : Data that has been changed since last full backup. (stacking M-F from previous days)
            > Does not clear archive bit. 
            > Restore : Restore last full + Last differential. 

### Offsite Storage

- Have stored somewhere else. 

### Hot Spares

- Can be swapped out without turning off power : 'hot swapping' 

### Cold Spare

- Must turn off power first to replace. 



### MISC 

- RSVP is an Integrated Services (IntServ) type of protocol.

- A delay of 150 ms is often considered the worst acceptable one-way delay for voice. 

- 99.999%  = 5 Minutes downtime per year. 

- Random early detection seeks to avoid congestion before it becomes a major issue on the network. 

- Class of Service (CoS) implements packet tagging in a local area network (LAN). It tags the different types of traffic, such as video streaming or VoIP. The tag is a value between 0 and 8, with 0 being the highest priority. Quality of Service (QoS) uses the CoS tag to determine which traffic gets priority. 

- One approach to providing Layer 3 redundancy is to have multiple links between devices and select a routing protocol that load balances over the links. Additionally, Link Aggregation Control Protocol (LACP) lets you assign multiple physical links to a logical interface, which appears as a single link to a route processor.

- VRRP is an IETF open standard that operates almost identically to HSRP from Cisco Systems. 

- Link Fragmentation and Interleaving (LFI) and RTP Header Compression (cRTP) are both link efficiency mechanisms, which attempt to make a more efficient use of relatively limited WAN bandwidth. LFI can fragment large packets and interleave smaller packets (for example, voice over IP packets) in amongst the fr