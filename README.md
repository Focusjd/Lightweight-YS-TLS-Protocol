# Lightweight YS Transport Layer Security Protocol

Transport Layer Security (TLS) protocol is a cryptographic protocol after Secure Sockets Layer (SSL), which aims to provide communication security at the computer network level. This protocol is now widely used in HTTPS protocols. 

However, this protocol lacks in two aspects: long-term authentication security and performance. First, the session key for communication is calculated by long-term key computation, and once the session key is stolen, it can be exploited permanently. Second, the amount of balanced key computation makes the protocol unable to perfectly adapt to the unbalanced client-server performance difference. 

In this project, we first propose an improved balanced protocol to solve the problem of authentication, and on this basis, we design two lightweight protocols to solve the authentication problem between unbalanced devices.

To run the codes, 
First you need to set up two devices with Python3 (Both local VM or remote are OK but need to config the HOST for server)

Then you need to run the client and server side corresponding to the correct protocol model.
1. YS-balanced protocol
2. Weak server – strong client Protocol
3. Strong server – weak client Protocol
4. Original TLS protocol -a python implementation (not needs for this project)

Run the corresponding code (strat server listening frist)

Note: change the congfig ip and port is necessary

For client you need to config the server ip to your traget server

    server_ip = "example.com" or your_server_ip
    server_port = 10005
    
For server you need to make sure the open socket port is in same setting with the server

    HOST = ""
    PORT = 10005
