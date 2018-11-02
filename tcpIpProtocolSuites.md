# TCP/IP Protocol Suites

## TCP Transmission Control Protocol 

- Connection Oriented Protocol 
        > Must first Acknowledge session 
        > 3 way handshake
            > Syn
            > Syn Ack 
            > Ack Received
        > Data then delivered. 

- Guarantees delivery of data.
- Will resend if not delivered. 

## UDP User Datagram Protocol 

- Connectionless
- Doesn't establish session
- Doesn't guarantee delivery 
- "fire and forget" protocol
- less overhead involved (faster)

### FTP File Transfer Protocol

- Standard for users file transfer
- Can download and upload files over internet
- Upload files to FTP server

- Can user broswer, or FTP software. 
- Connection oriented TCP protocol 

### TFTP

- Simple protocol
- Used for within SAME network.
- No security
- Connectionless (UDP)

### SFTP

- Security/Encrypted using Secure Shell. 
- Data not in clear text. 

### SMTP

- Sending email
- TCP (connection oriented) 

### POP3 

- Receiving email
- Only grabs from mail server and downloads it to PC. 
- DOESNT sync email or folders from mail server like IMAP
- Then REMOVED from mail server unless specified. 

### IMAP4

- Receiving email
- Access and manage email on server from PC
- SYNCS email and folders with computer.

### HTTP 

- Most widely used protocol 
- Viewing Web Pages

### HTTPS

- Secured
- Email servers or ecommerce

### Telnet

- access remote servers
- simple, OLD
- only sends commands (fast)
- insecure (clear text)
- used mainly within local networks.

### SSH Secure Shell 

- Better alternative to telnet
- Protects data over network. 
- Secure "tunnel" around data. 

### ARP Address Resolution Protocol

- Resolves IP to MAC 
- Computers use MAC addresses to communicate to each other. 
- Searches ARP cache first to find target MAC address. 
- If not in cache, will broadcast message asking for it. 

### RARP 

- Reverse Address Resolution Protocol
- Opposite of ARP 
- MAC to IP

### NTP

- Network Time Protocol
- US NAVAL observatory Master Clock
- Sends out periodic Requests to server to sync time. 

### SCP

- secure copy protocol
- uses Secure Shell

### SNMP 

- network management
- collects data from various devices, servers, routers, printers etc

