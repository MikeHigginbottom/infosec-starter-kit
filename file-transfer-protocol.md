# File Transfer Protocol
- A TCP/IP protocol specifying the transfer of text or binary files across the network. [^1] #glossary

- The File Transfer Protocol (IETF RFC 114, 765, 959, 1579, 2228 and 2428) is a client-server network-layer protocol for transferring files across a network over TCP. [^2]
- Uses port 20 (active mode data) and port 21 (control).
- [ftp](notes/infosec/ftp.md) was developed at a time when security was not considered when designing protocols. Data transmitted using FTP is not encrypted and can be intercepted by an attacker with access to the network. It's also vulnerable to several attacks including brute-forcing, spoofing or FTP bounce attacks. [^2]
- Can use username/password authentication but depending on server configuration you may be able to use [Anonymous FTP](anonymous-ftp.md)
- Can list, add, delete etc. files
## My Notes
[Notes](mynotes/file-transfer-protocol-notes.md)

[^1]: [ref20231209T101428](references.md#20231209T101428)
[^2]: [ref20231209T120659](references.md#20231209T120659)