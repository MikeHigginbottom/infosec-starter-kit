# Reverse Address Resolution Protocol
- A protocol by which a physical machine in a local area network can request to learn its IP address from a gateway server's Address Resolution Protocol table or cache. A network administrator creates a table in a local area network's gateway router that maps the physical machine (or Media Access Control - MAC address) addresses to corresponding Internet Protocol addresses. When a new machine is set up, its RARP client program requests from the RARP server on the router to be sent its IP address. Assuming that an entry has been set up in the router table, the RARP server will return the IP address to the machine which can store it for future use. [^1] #glossary 
- A protocol, defined in RFC 903, which provides the reverse function of ARP. RARP maps a hardware (MAC) address to an internet address. It is used primarily by diskless nodes when they first initialize to find their internet address. See also: Address Resolution Protocol, BOOTP, internet address, MAC address. [^2] #glossary
## My Notes
[Notes](mynotes/reverse-address-resolution-protocol-notes.md)

[^1]: [ref20231209T101428](references.md#20231209T101428)
[^2]: [ref20240211T163156](references.md#20240211T163156)
