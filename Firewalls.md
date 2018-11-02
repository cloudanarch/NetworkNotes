# Firewalls

- Can be software or hardware
- filters information from internet
- blocks unwanted traffic and permits wanted traffic. 
- filters incoming network data packets and uses access rules. 

- Every business needs one to protect networl

## Access control List (ACL)

- List of rules on what can access network
- Allows OR denies. 
- Can do it on IP > IP basis

### Implicit Deny

- Most firewalls have this
- Will only allow if the ACL specifically allows. 

    > I.e if only 80 is open, you can ONLY allow web pages on network. 

## Host Based

- Software Firewall. 
- Installed on Computer. Only protects computer. 
- I.E Windows Firewall built into PCs

    > Can create exceptions based on application name
    > Can use third party in addition. 

## Network Based 

- Combo of hardware and software.
- works at network layer
- between private network and internet.
- protects entire network
- used management rules that are applied to entire network. 

## Stateful vs Stateless

### Stateful

- Monitors all connections and data streams 
- Keeps a Record
- Allows or denies
- Does a thorough job of protecting dynamically

### Stateless

- Not Thorough
- Uses ACL
- Doesn't Inspect Data Packet

    > Only looks at headers

- Doesn't keep a record

## Content Filtering

- filters data based on content rather than source
- used commonly for email spam. 

## Signiture Identification 

- can detect viruses and malware with common behaviors. 
- can spot behaviors. 
- blocks onces spotted. 

## Intrusion Detection

- hardware tool ( can also be software) 
- alert and prevents network form outside attacks (operates before firewall)
- alrts network admin of possible pending danger

