# Cloud & Virtualization 

## Virtualization

- Traditionally Businesses have different servers on multiple OS

    > Such as

        > Database Server
        > Web Server
        > Email Server
        > etc

    > Requires

        > Space
        > Management 
        > Cost etc

- Virtualization consildates on one physical server in virtual environment. 
- Single server can run multiple OS and applications side by side. 
- Users interact same way. 

    > This saves money on.

        > Hardware
        > Management
        > Maintenence. 

- Also things like Virtual Switches. Created in Virtual Env. 

    > EX

        > You can create a virtual switch to have virtual servers on same hw machine communicate with each other. 

- Virtual Router functions same way. 

- Virtual Firewall: can filter network traffic and monitor for virtual servers same way a physical one does.

## Cloud Computing

- Refers to data and apps being stored and run on remote servers rather than on local PC. 
- Accessed via internet "on the cloud." 
- No need for things like physical email server/exchange/software.

    > Dont have to worry about

        > OS failure
        > HW failure
        > Maintenence. 

    > Now a company will do all this for you
    
        > Gmail
        > Live
        > etc

- Also other services such as databases. 

### Three Types of Cloud Computing

#### IAAS (infastructure)

- let third party vendor manage hardware portion of buisness. 

    > 3rd party manages. 

        > Storage
        > Servers
        > Networking
        > Virtualization

    > You Control Software Portion

        > Applications
        > Data
        > OS
        > Middleware
        > Runtime

- Example : [AWS-Amazon Web Services](https://aws.amazon.com/)


#### PAAS (Platform)

- Third party controls all of above PLUS

    > 3rd Party Manages: 

        > Runtime
        > OS
        > Middleware

- Example : [Azure](https://aws.amazon.com/)

#### SAAS (Service)

- Most common cloud service

    > 3rd Party Manages:

        > Everything

Access cloud service from pc via internet.

Example : [Google Apps](https://gsuite.google.com/)

### NAS (Network Attached Storage)

- Storage Device used strictly for storing data. 
- Centralized
- Multiple HDD in RAID
- Has NIC attached to switch or router

    > Access Data over network from shared folder on: 

        > Laptops
        > PC
        > Other wireless devices. 

### SAN (Storage Area Network)

- Special High Speed Network for large amounts of data
- Multiple disk arrays and servers which access data as if its a local hd. 
- Recognized as local HD rather than shared. 
- Independent of Servers
- Not owned by a single server. Multiple servers usually attached. All data available to all servers simultaneously.
- Redundant and accessible. 
- Shared among several disk arrays. 
- Interconnected via fiber channel / speeds start at over 2000mbps
- Alternative to fiber channel iSCSI (data storage protocol transports SCSI requests over standard TCP/IP)