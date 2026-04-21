# Whois
- An IP for finding information about resources on networks. [^1] #glossary
- An Internet program which allows users to query a database of people and other Internet entities, such as domains, networks, and hosts. The primary database is kept at the InterNIC. The information stored includes a person's company name, address, phone number and email address. The latest version of the protocol, WHOIS++, is defined in RFCs 1834 and 1835. See also: InterNIC, white pages, Knowbot, netfind, X.500. [^2] #glossary
- Used to check ownership of IPs
- Many ISPs now sub-delegate customer ranges using Shared Whois (SWIP) or Referral Whois (RWhois). If the ISP has done this, you can learn the customer's exact netblock size.
- On Linux you can use the `whois` command

`whois -h whois.arin.net \?` gives the ARIN query syntax.
`whois -h whois.arin.net @<targetdomain>` shows all the ARIN contacts with email addresses at `<targetdomain>`
`whois -h whois.arin.net "n <target>*"` shows all the netblock handles starting with `<target>`
`whois -h whois.arin.net "o <target>*"` shows all of the organizational names starting with `<target>`

On Windows, need to use online tools such as:
- [RIPE Network](https://www.ripe.net/)
- [Networksolutions.com](https://www.networksolutions.com/domains/whois)
- [Whois Lookup - DomainTools](https://whois.domaintools.com/)
## My Notes
[Notes](mynotes/whois-notes.md)

[^1]: [ref20231209T101428](references.md#20231209T101428)
[^2]: [ref20240211T163156](references.md#20240211T163156)
