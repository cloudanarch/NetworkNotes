# OSI MODEL

## OPEN SYSTEMS INTERCONNECT

- describes how info in software moves within network to other computer in network
- breaks down into seven different layers. 
- 1-7 from bottom 

## Data flows DOWN from Top to Bottom > Then back up to its destination 
1 2
|_|

### Application

- Manage comms between apps
- Supports protocols such as Email, HTTP, and FTP
- Resembles readable Data

### Presentation

- First converted to form that can be sent over network
- compressed or decompressed
- encrypted or decrypted
- ASCII

### Session

- Controls dialog during comms.
- Establishes, manages and terminates connections between remote and local apps. 
- "traffic cop" directs network traffic. 

### Transport

- Provides xfer of data between end users.
- Resends any packets that don't get acknowledged by destinations
- Guarantees that packets are received. 
- TCP / UDP

    > The transport layer offers TCP and UDP. With TCP, a connection-oriented protocol, windowing can be used to dictate how much data is sent at one time.


### Network

- Routes data packet based on logical IP 
- Fragements and reassembles packets. 
- Instructs how to find ultimate destination. 


### Data Link

ARP BETWEEN LAYER 2 AND 3


- Sending data to physical layer
- encoded and decoded to bits. 
- handles flow control and frame sync.
- Divided into two sub layers

    > MAA/ Mac 
    > Logical link layer/LCC


### Physical 

- defines network standards and physical chars of network 
- such as network, media types, cables, volts, etc
- defines topology. 


### Misc Notes About OSI 

- QoS mechanism that can compress Layer 3 and Layer 4 Headers of a voice over IP Packet

    > cRTP

        > RTP Header Compression 

    > LFI

        > Link Fragmentation and Interleaving

- STP Spanning Tree Protocol Prevents broadcast storm at Layer 2 topological loop. 

- ICMP is a layer 4 protocol 

### MISC

- The DoD TCP/IP model features just four layers. From the bottom up they are network interface, Internet, transport, and application.

- Baseband technology uses the entire medium to transmit. You should contrast this to broadband technology, which can divide the medium up into different channels. A great example of broadband is the use of the coaxial cable you might have in your home, which carries cable television signaling as well as high-speed Internet.

