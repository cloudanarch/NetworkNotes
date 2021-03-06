# Routing Protocols

## Loopback Interface

- Virtual interface created on router
- Assigned IP of your choice
- for testing and admin purposes. 

## Routing Table

- Set of rules on data packet paths
- Routers use routing tables
- As packets come in, it decides best path via tables

- Contains

    > Network Destination

    > Subnet Mask

    > Gateway

    > Interface

    > Nexthop (ip being forwarded to)

    > Metric (best route)

## Three Types of Routing Protocols

### Distance Vector

- factors distance via hops
- hop is how many routers data packet must pass thru to destination. 
- RIP cannot be used in large networks due to a maximum hop count of 15. 
- RIP: Routing information protocol 

        > oldest
        > broadcasts to others every 30 sec regardless if info has changes
        > as networks got larger it created unnecessary traffic on network

- RIP v2 :

        > solved problem of excess traffic
- BGP : Border Gateway Protocol 

        > Standard for internet
        > based on Paths and Policies
        > routing protocol that is used for moving prefixes back and forth between different autonomous systems
        > Based on a variety of parameters 


### Link State

- shares info independently map out best path on network. 

    > OSPF

            > Open Shortest Path First
            > Determines correct routes using IP and creates topology map of network 
            > Determined by "cost" / Bandwidth 

    > IS-IS (intermediate system to intermediate system)
        
            > Organized into domains (groups)
            > Primarily functions within these domains
            > Uses CLNS to communitate (connectionless network services)

### Hybrid 

    > EIGRP (Enhanced interior gateway routing protocol)

            > Only runs on cisco
            > fast less overhead
            > many network layer protocols
            > combines both
    
## SIP Session Initiation Protocol 

- Establishes comms sessions over internet. 

    > VOIP

    > Instant messaging

    > Confrencing

- Works at application layer of OSI

## RTP

- Internet standard for transporting real time data.
- UDP
- Used also with RTCP

        > can monitor quality of data delivered

- both unicast and multicast. 

## BGP 

- External protocol 
- Uses complex set of metrics called path vectors. 
- BGP is the protocol that makes the Internet a reality. 


#### Administrative Distances

- RIP 120

- OSPF 110

- Internal BGP 200

- External EIGRP 170

- EIGRP 90

### Routing Protocol Charactaristics 

- The better the administrative distance, the more believable the protocol. Lower is better for the AD score. 

- nonoverlapping channels should have a 10-15% overlap coverage. 

### MISC 

- The client-to-router protocol in multicast is IGMP. 

