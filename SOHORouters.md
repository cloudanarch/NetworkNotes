# SOHO Routers

#### Small Office / Home Office

- Use built in router config webpage on router

        > Type in routers ip
        > Usually has DHCP built in. 
        > SSID == Router Network Name
        > Use different Channels in case nearby router is using same channel. 
        > Can choose type of security (WPA2)

#### WEP

- 40 bit key insecure
- Super easy to hack
- RC4

#### WPA

- Uses stronger enc (TKIP) (changes keys during use == data integrity)
- Uses EAP (verifies network users)

#### WPA2 

- Stronger than WPA (CCMP > TKIP) (encapsulated crypto mechanism)
- AES

#### WPS 

- Easy for noobs. 
- Press button
- Recently hacked and now garbage. 

#### Mac Filter

- hexadecimal address
- prevent or permit specific MACs

#### DMZ 

- allows designated computer to be exposed to internet
- router forwards all ports to DMZ
- used for testing purposes
- Must use static IP (should)

#### Port Forwarding

- Customize for certain apps to forward to certain computers from outside network (ie RDP from outside PC to your network chooses which comp on your Network to forward to.)

#### Guest Network

- Seperate wireless network on router. 
- Has own SSID

### MISC

- Troubleshooting 

        > A black-hole router drops a packet exceeding a router interface's MTU size, when that packet has its "don't fragment" bit set.

- Convergence is the amount of time required for a routing protocol to failover from a previously active route to a backup route.

- Split horizon is a feature that prevents a route learned on a router interface from being advertised back out of that same interface. 

- Poison reverse is a feature that causes a route received on an interface to be advertised back out of that same interface with a metric considered to be infinite. 

- Time-to-live (TTL) is a value in an IP packet's header that is decremented by one each time the packet is routed. When the TTL reaches zero, the packet is discarded.

