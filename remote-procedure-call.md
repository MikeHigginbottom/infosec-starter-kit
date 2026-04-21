# Remote Procedure Call
- Remote Procedure Call is a transport and application layer protocol that allows an application to request services from another application running on a separate networked device. [RPC](rpc.md) uses TCP/UDP ports 80, 135, 443, 445 and 593. Port 135 is assigned to the endpoint mapper, used to identify connected devices and the port they are using, and is subject to several well-known vulnerabilities. [^1] #glossary 
- An easy and popular paradigm for implementing the client-server model of distributed computing. In general, a request is sent to a remote system to execute a designated procedure, using arguments supplied, and the result returned to the caller. There are many variations and subtleties in various implementations, resulting in a variety of different (incompatible) RPC protocols. [^2] #glossary
## My Notes
[Notes](mynotes/remote-procedure-call-notes.md)

[^1]: [ref20231209T120659](references.md#20231209T120659)
[^2]: [ref20240211T163156](references.md#20240211T163156)
