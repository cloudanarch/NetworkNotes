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

### Session
- Controls dialog during comms.
- Establishes, manages and terminates connections between remote and local apps. 
- "traffic cop" directs network traffic. 

### Transport
- Provides xfer of data between end users.
- Resends any packets that don't get acknowledged by destinations
- Guarantees that packets are received. 

### Network
- Routes data packet based on logical IP 
- Fragements and reassembles packets. 
- Instructs how to find ultimate destination. 

### Data Link
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
