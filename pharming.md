- This is a more sophisticated form of [MitM](man-in-the-middle.md) attack where a user’s session is redirected to a [masquerading](masquerade.md) website. #ref/2023/12/09/101428 #glossary

- This can be achieved by corrupting a DNS server on the Internet and pointing a URL to the masquerading website’s IP. Almost all users use a URL like www.worldbank.com instead of the real IP (192.86.99.140) of the website. Changing the pointers on a DNS server, the URL can be redirected to send traffic to the IP of the pseudo website. At the pseudo website, transactions can be mimicked and information like login credentials can be gathered. With this the attacker can access the real www.worldbank.com site and conduct transactions using the credentials of a valid user on that website. #ref/2023/12/09/101428
## My Notes
[Notes](mynotes/pharming-notes.md)
