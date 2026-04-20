# S/Key
- A security mechanism that uses a cryptographic hash function to generate a sequence of 64-bit, one-time passwords for remote user login. The client generates a one-time password by applying the MD4 cryptographic hash function multiple times to the user's secret key. For each successive authentication of the user, the number of hash applications is reduced by one. [^1] #glossary
## My Notes
[Notes](mynotes/s-key-notes.md)

[^1]: [ref20231209T101428](references.md#20231209T101428)