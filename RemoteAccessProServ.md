# Remote Access Protocols & Services 

## RAS Remote Access Service

- Allows to connect from remote location 
- Access over Dialup connection 
- Built by microsoft
- put into windows NT software
- works with TCP/IP NETBEUI and IPX

## SLIP (serial line internet protocol)

- two computers connect via serial connection like phone line
- not used anymore
- insecure, no encryption/clear text.
- no error checking
- only uses TCP/IP

## PPP (point to point protocol)

- standard remote access protocol used today
- has error checking
- has security
- uses serial 
- used thru dial-up

## PPPoE (point to point over ethernet)

- encapulates PPP frames in ethernet frames.
- DSL, cable, wireless
- multiple uses on lan to remote site using common device

## PPTP (point to point tunneling)

- default protocol for VPN
- creates secure tunnel between two points  
- USES MICROSOFT !

## GRE (generic route encapsulation)

- uses PPTP in creating a VPN
- creates the tunnel 

## VPN 

- uses public network to establish a secure remote connection. 
- encrypted when sent
- decrypted when received. 
- dedicated

### VPN concentrator

- creates the vpn connection and manages, 
- authenticates
- encrypts/decrypts
- not always needed to manage and create
- mainly used in orgs that use a lot of them. 
- handles heavy traffic if using lots. 

#### VPN - Site to Site

- to connect building to building across range
- decrypts at private network 
- no need of internet leased line == cheaper

#### VPN - Host to Site

- Can connect to office from home
- Doesn't require home hardware to connect. 
- Can just use OS to connect to office hardware. 

#### VPN - Host to Host

- Two computers over internet
- No need for hardware at either end
- Both clients need software. 