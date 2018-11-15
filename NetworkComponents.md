# Network Components. 

## DOCSIS

- Data Over Cable Service Interface Specifications
- Typical Cable Modem (incoming and outgoing)
- internet video and voice
- 10GB Down, 1GB up. 

### Hub

- Multiple Ports
- Not intelligent. Doesn't filter. 
- Data Copied to all ports. All devices see data packet. 

#### Passive Hub

- Doesn't Require Power

#### Active Hub

- Does require power

###  Switch

- Intelligent, learns addresses into table to know where packet goes
- delivers only to intended destination. 
- Creates collision domains 
- Operates at LAYER 2 of OSI model 

#### Multilayer Switch

- Operates at LAYER 2 AND LAYER 3
- Interprets layer 3 data similar to router

#### Content Switch

- LAYERS 4>7
- Load balancing and Advanced Filtering
- $$$

## PoE

- Gets power through ethernet cable. Doesn't have regular power cable. 

### Spanning Tree (Protocol)

- Multiple switches for fault tolerence.
- Can create broadcast traffic loops with multiple loops.
- Creates excess traffic. 

- Spanning tree prevent traffic loops by allowing switches to communicate to find loops in network. 

### Bridges

- Seperate into seperate collision domains

    > I.e segmented by multiple hubs via bridge. 

- Separates by mac address. 
- Blocks data which fails requirement. 

### Routers

- Routes or forwards data from one network to another via IP address. 
- inspects data packets and makes determinations. 
- "gateway for a network" 

### Gateway

- Device that joins 2 networks together
- Only changes the format of the data. 

### CSU/DSU

- size of modem
- converts from LAN to WAN 
- data formats are different. 

### NIC

- connects computer to network. 
- circuit board with network adapter to PC. 
- Converts serial to parallel. 
- Costant connection.
- UID = MAC Address. 

### Transceiver 

- transmitter and receiver in same package. 

### WAP 

- wireless hub used by wireless devices. 
- relays data between wired network and wireless devices. 

### Dial up Modem

- Can transmit data over normal telephone lines (analog)
- Data in computer is digital so it converts. 
- Maximum Speed is 56kbps. 

