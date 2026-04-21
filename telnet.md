# Telnet
- Telnet (IETF RFC 15 & 854), developed in 1969, is an interactive text-based client-server communication protocol. Typically used with a command-line interface to remotely access devices over TCP port 23, Telnet clients are available for almost all operating systems and platforms. However, Telnet was designed at a time when most computer devices were connected on local networks only and every user who connected was trusted, as such it is inherently insecure. By default, Telnet connections are unencrypted, with all data transmitted as plaintext, meaning it is possible for any threat actor with access to the network between the Telnet hosts to intercept all traffic sent between them. This data could then be used by the actor for future attacks. Most Telnet implementations will also not authenticate hosts to ensure communications are sent to the intended recipient. [^1] #glossary 
- Telnet is the Internet standard protocol for remote terminal connection service. It is defined in RFC 854 and extended with options by many other RFCs. [^2] #glossary
## My Notes
[Notes](mynotes/telnet-notes.md)

[^1]: [ref20231209T120659](references.md#20231209T120659)
[^2]: [ref20240211T163156](references.md#20240211T163156)
