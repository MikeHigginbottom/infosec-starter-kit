# File Transfer Protocol
- A TCP/IP protocol specifying the transfer of text or binary files across the network. #ref/2023/12/09/101428 #glossary

- The File Transfer Protocol (IETF RFC 114, 765, 959, 1579, 2228 and 2428) is a client-server network-layer protocol for transferring files across a network over TCP. #ref/2023/12/09/120659
- Uses port 20 (active mode data) and port 21 (control).
- FTP was developed at a time when security was not considered when designing protocols. Data transmitted using FTP is not encrypted and can be intercepted by an attacker with access to the network. It's also vulnerable to several attacks including brute-forcing, spoofing or FTP bounce attacks. #ref/2023/12/09/120659
- Can use username/password authentication but depending on server configuration you may be able to use [Anonymous FTP](anonymous-ftp.md)
- Can list, add, delete etc. files
## My Notes
[Notes](mynotes/file-transfer-protocol-notes.md)
