# Demilitarized Zone
- A demilitarised zone (DMZ) is a physical or logical network used to separate an internal network from other, untrusted networks. Services and resources such as mail and FTP servers are contained within the DMZ in order to be accessible from external networks, such as the internet, but the rest of the internal network is unreachable.  [^1] #glossary

- A DMZ can be deployed in two main configurations. One method is the screened subnet configuration, which has the structure of: internet, then firewall, then the DMZ, then another firewall, then the private LAN. A second method is the multi-homed firewall configuration, which has the structure of a single firewall with three interfaces, one connecting to the Internet, a second to the DMZ, and a third to the private LAN. [^2]
## My Notes
[Notes](mynotes/demilitarized-zone-notes.md)

[^1]: [ref20231209T120659](references.md#20231209T120659)
[^2]: [ref20231209T130055](references.md#20231209T130055)