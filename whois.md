- An IP for finding information about resources on networks. #ref/2023/12/09/101428 #glossary

Used to check ownership of IPs

Many ISPs now sub-delegate customer ranges using Shared Whois (SWIP) or Referral Whois (RWhois). If the ISP has done this, you can learn the customer's exact netblock size.

On Linux you can use the `whois` command

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
