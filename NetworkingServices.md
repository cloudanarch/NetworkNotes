# Networking Services

## DNS


- Translates name to ip address (like a phone book)

    > i.e Yahoo.com = 68.241.226.32

## WINS

- NETBIOS to IP addresses
- IE computer names to ip addresses

- You communicate to other computers on network by names/WINS

## NAT

- Used usually in routers
- set of IP to set of ip

- Example would be private network using ip internally. Router runs NAT to translate a private IP to internets Public Ip via router
- and reverse, I.E over internet, through router, then translates to YOUR private IP/computer

### PAT

- Translates IP based on port numbers
- each computer is issued unique port number
- that way external packets know which computer to talk to via outside network . 

## SNAT

- Static Network Address Translation
- Private IPs to single Public IP
- SNAT links private to public permanently
- useful for server or pc if needs to be accessesed outside network (ie mail server)

## Proxy

- cached database on proxy server
- much faster because its already there. 
- Proxy server retrieves from internet then stores it for your PC and anyone else on network. 
- saves bandwith 
- provides security by reporting retrieved pages to network admin

## RDP 

- microsoft tech (ew)
- based on terminal services
- type in IP and credentials. 
- can see remote users screen. 

## CSMA/CD
#### Carrier Sense Multiple Access Collision Detection

- Used on ethernet networks
- Each PC senses if wire is idle, if yes sends data  (prevents collision by waiting random time to retry)


## CSMA/CA

- Used on wireless routers
- sends out small data packet to see if channel is clear. 

## BROADCAST

- A single transmitter of data is being recieved by multiple receivers. 

#### UNICAST

- Sent to single destination

#### MULTICAST

- Sent to multiple

