# Network+ C480 Notes

## Topologies

### Star 

- Most Common 

    Pro

        > one break, the rest are okay.
    
    Con 

        > If hub fails (single point of failure) they all fail.

### Bus 

- Old. No open connections allowed. Terminators can't be loose or else they will bounce back (signal reflection)

    Pro 

        > Cheap and easy to implement

    Con 

        > Requires BNC (t) connectors w/ coaxial and terminators both sides. 

### Ring 

- Ring shape, all connected to each other. All have two neighbors and goes around until it reaches destination.
- Rarely used today

    Pro

        > Easy to install and troubleshoot

    Con 

        > If one computer goes down or a single break would disrupt all dataflow. 

### Mesh

- Connects to every computer. 

    Pro
    
        > Handles failure very well. 
        > Expensive so rarely used on LAN, mostly used on Internet or WAN. 
        > High Redundency level. 

### Hybrid 

- Many businesses use hybrid topologies
- Most common are star/ring and star/bus

        > In star/ring many are linked together using single bus. 
        > In star/bus hubs are created in a ring.

### Point to Point. 

- Directly connected
- Simplist form.

### Client Server

- connect to single server rather than connecting to each other.
- doesn't have to put all resources on each computer (admin can just put on one machine/server)

### Point to Multi-Point

- Commonly used in wireless outdoor networks. 
- Central wireless base station
- Clients around connect to central 
- Clients dont communicate to each other, only to central location (i.e radio tower)
- Central Location is Access Point or Base Station

### Peer to Peer

- Talk to every client on network 
    
    > i.e sharing one printer connected to one computer to every computer in office. 

        > commonly found in homes and small businesses. 