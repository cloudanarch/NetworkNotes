# Authentication Protocols

### PAP (Password Authentication Protocol)

- Simple Protocol, compatible with almost all
- Not very safe
- SENT IN CLEAR TEXT EW

### CHAP (Challenge Handshake)

- Encrypts
- Server asks/challenges to validate itself (3 way handshake)
- Client sends one way hash. 
- Server checks hash against its own calc. 

### MS-CHAP (Microsoft) 

- Only authenticates client. 
- "basically CHAP" 

### MS-CHAP2

- Both client and server authenticated. 

### RADIUS (remote auth dial in service)

- Enables single server such as domain controller to handle all auth.
- Users log into RADIUS server, which makes a request on the user's behalf after authenticating. 

### KERBEROS

- MIT Made it
- Uses tickets
- AUTHS self with kerberos server
- Client then issues ticket which gives access to various network resources.

### EAP (Extensible auth protocol)

- Extension to PPP
- Supports many uses of auth
- Commonly used with smart cards. 
- Used for 801.11x