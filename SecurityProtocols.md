# Security Protocols

### IpSec

- Encrypts Data during comms. 
- Both sender and receiver must use pub key. 
- Verifies Data was received and not altered
- ISAKMP = SA Security Association

    > Transport mode

        > Only message portion is enc.

    > Tunnel mode

        > Entire packed enc. 

-Authentication Header is part of the IPSec standard. Note that it does not provide encryption. 

### L2Tp 

- Combo of ciscos layer 2 forwarding and PPTP
- Uses digital certs to authenticate. 
- Prevents 'man in the middle' attacks. 

### SSL 

- Provides security over internet. 
- Uses pub key enc. 
- Works with HTTP to secure site with certificate. 

    > Provides Protection in three ways

        >  Auth Server
        >  Auth Client
        >  Encrypts Data

### TLS

- Successor to SSL 
- 2 Layers

    > TLS Record Protocol 

        > Provides connection security by making sure the connection is private and reliable. 

    > TLS Handshake Protocol

        > Allows server and client to auth each eother and negotiate an encryption algorithm and crypto keys. 

### 802.1x

- Wired and Wireless
- Controls network access by ports


## IDS/IPS notes

- Primary Method : Signature-based detection

    > Could be a string of bytes

- Policy-based detection : 

    > needs very speciffic declaration of the security policy.

- Statistical anomaly detection : 

    > Watches traffic patterns over time and dynamically builds baseline

        > If traffic patterns significantly vary from baseline, alarm will trigger. 

- Non-Statistical anomaly detection : 

    > Allows an admin to define what normal traffic patterns are supposed to look like. 


