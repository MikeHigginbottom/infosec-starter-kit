# Checksum
- A calculation that's used to confirm the Integrity of a collection of data: a calculation is performed on all the individual bytes of data and the result is the checksum. Checksums are good for checking for corruption but less so for ensuring that the data has not been tampered with, because it's often possible to change the data so that the checksum works out correctly; use a Hash Function instead in the latter case. [^1] #glossary
- A computed value which is dependent upon the contents of a packet. This value is sent along with the packet when it is transmitted. The receiving system computes a new checksum based upon the received data and compares this value with the one sent with the packet. If the two values are the same, the receiver has a high degree of confidence that the data was received correctly. See also: Cyclic Redundancy Check. [^2] #glossary
## My Notes
[Notes](mynotes/checksum-notes.md)

[^1]: [ref20231209T095245](references.md#20231209T095245)
[^2]: [ref20240211T163156](references.md#20240211T163156)
