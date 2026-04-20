# Fragment Overlap Attack
- A TCP/IP Fragmentation Attack that is possible because IP allows packets to be broken down into fragments for more efficient transport across various media. The TCP packet (and its header) are carried in the IP packet. In this attack the second fragment contains incorrect offset. When packet is reconstructed, the port number will be overwritten. [^1] #glossary 
## My Notes
[Notes](mynotes/fragment-overlap-attack-notes.md)

[^1]: [ref20231209T101428](references.md#20231209T101428)