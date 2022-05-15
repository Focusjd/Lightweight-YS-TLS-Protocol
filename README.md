# Lightweight Transport Layer Security Protocol
Project abstract - Transport Layer Security (TLS) protocol is a cryptographic protocol after Secure Sockets Layer (SSL), which aims to provide communication security at the computer network level. This protocol is now widely used in HTTPS protocols. However, this protocol lacks in two aspects: long-term authentication security and performance. First, the session key for communication is calculated by long-term key computation, and once the session key is stolen, it can be exploited permanently. Second, the amount of balanced key computation makes the protocol unable to perfectly adapt to the unbalanced client-server performance difference. In this paper, we first propose an improved balanced protocol to solve the problem of authentication, and on this basis, we design two lightweight protocols to solve the authentication problem between unbalanced devices.

To run the codes, You need to run the client and server side corresponding to the correct protocol model.
1. Original TLS (a python implementation) protocol
2. YS-balanced protocol
3. Weak server – strong client Protocol
4. Strong server – weak client Protocol


Note: change the server_ip for clients is necessary
