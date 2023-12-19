# OpSec
- OpSec (Operational Security) is the process of protecting individual pieces of data that could be grouped together to give the bigger picture (called aggregation) #glossary

- Don't leave fingerprints
- If you have to leave fingerprints don't let them be associable with other fingerprints you've left
- Leave fake fingerprints to make it harder to join the dots
- Set your attacking machine's hostname to something innocuous e.g. `printer`, `DESKJET` when on site or `localhost`, `DESKTOP`, `PC` when remote
- Set username to a user you know exists
- Set your domain name to be the same at the target's
- Set user agent strings to something like Chrome on Windows 10 or Googlebot if you're doing a lot of hits with something like NMAP
- Set user agent in an environment variable and create aliases that use it for your commands so you don't forget to specify it from the command line
## My Notes
[Notes](mynotes/opsec-notes.md)
