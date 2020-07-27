# UDP_HOLE_PUNCHING
This crate is aimed to be rust p2p communication framework.

## What is p2p? 

 When a socket has been "connected" to the other client, the "connection" is directly to the client, not the server. The server is not used to pass through packages, only to pair the two clients together. As you should know, since it's the whole purpose of [UDP hole punching](https://en.wikipedia.org/wiki/UDP_hole_punching).
 To implement a p2p framework, the crate provide 3 sub function:
 - the server: Use this function if you want to run a standard server which waits for two clients to send the same identification packet, then sends the clients' IP address and external port number to each other. It also has some basic protection against someone trying to overload the server by sending multiple packages from the same ip. If you want something more customisable, take a look at `make_match`,
 - the client--callee: to be implemented.
 - the client--caller:to be implemented.

  ## Quick Start 
```
   To be implement
   
    
```

