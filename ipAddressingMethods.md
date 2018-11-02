# IP Addressing Methods

## Dynamic IP (best)
- Gets IP auto from DHCP
- DHCP assigns computer with IP
- can also assign subnet mask, default gateway, and DNS server

## Static IP (manual)
- User manually assigns.
- Doesn't need DHCP
- Permanent, won't change automatically

### Other Notes
- 98 or later
    > will assign own IP Address
    > 169.254.0.0 = APIPA 

- APIPA allows to connect to other computers on same network.
- Assigns from SCOPE

### Scope

- Group and a range of consecutive IPs for comps that get their IP from DHCP
- Can be customized. 
- Reservations can be created to reserve IP for specific device (ID'd by MAC address)(Recognized by DHCP)

        > typically given to special devices such as printers. 

### Lease

- DHCP assigns as "lease" 
- Computer doesn't "own" IP 
- Amount of time an IP is addressed. 
- Duration of lease can be set in DHCP Server. 

        > ipconfig /all

            > LEASE OBTAINED
            > LEASE EXPIRED

- Will Automatically Renew 

### Relay

- Will broadcast request to DHCP
- If on same subnet, DHCP will assign computer IP. 
- If on different subnets, DHCP Relay = IP Helper (enabled on router) will forward request.
