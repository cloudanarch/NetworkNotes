# IP Address

- Numeric Address
- ID for comp or device on network
- every device on a network needs one 
- Consists of two parts

    > Network Address
    > Host Address

## Two Types of IPs

### IPv4
        > 32bit numeric, four numbers seperated by periods.
        > each group is called an octet
        > number range of octet 0-255
        > 4 billion UIDs
        > 4 sets of octets.
        

### IPv6

    - "Next gen"

        > 128 bit Hexadecimal Address 
        > 8 sets of 16 bits. 
        > separated by colons
        > Each hexadecimal char is 4 bits

            > 4 bit chart [8,4,2,1]
            > Higher than 9 = Letters starting at A
                > A = 10, B = 11 etc...


    - Five Types of NDP messages used by IPv6 Device

            > Router Solicitation (RS)
            > Router Advertisement (RA) (advertises presence along with link info)
            > Neighbor Solicitation (NS) (locates neighbors on network)
            > Neighbor Advertisement(NA)
            > Redirect

## Subnet Mask

- Masks network portion of IP address.

    A   255.0.0.0        
    B   255.255.0.0
    C   255.255.255.0

- First Octet Addresses

    A   1-126       Large Organizations
    B   128-191     Medium Organizations
    C   192-223     Small Organizations

        > 127 - Loopback

## Private IP

- Not public registered
- Can't directly access internet.
- Can use many PC to use 1 Public ISP IP. 
- Translates private to public
- Saves money, saves IP addresses. 
- RFC1918 To prevent shortage. 
- Homes Schools Businesses

    A   10.0.0.0 - 10.255.255.255               255.0.0.0        
    B   172.16.0.0 - 172.31.255.255             255.255.0.0
    C   192.168.0.0 - 192.168.255.255           255.255.255.0

### MISC

- Split horizon and poison reverse are critical loop preventions for early routing protocols. 

- The default route is 0.0.0.0/0.