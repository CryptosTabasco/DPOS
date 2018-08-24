# DPOS
Descentralized point of sales with a server client architecture for charging cryptocurrency remotely.

## Objective
The main goal of this application is to descentralized the wallet into multiple points to be able to be used by employees in order to create purchase orders without having direct access to the private keys or account from a corporate business account. A server-client configuration that will use quick authentication between clients and parent wallet through QR scan of a temporary QR to authenticate the client with the server. 

### The server 
Will hold the private keys and full wallet, also listeners to be able to send communication through RPC protocol. 
Additional company centric services like connectivity with an address book and a web interface.

### The clientt 
Will hold a calculator POS to insert quantity or programable interface for set products or menus with set price.
Exchange communication and request to the server for charging address and generate a QR with the total amount to charge.
Bring third party data like employee ID and log history through third party server datapoints.

## Contributors
JZA
