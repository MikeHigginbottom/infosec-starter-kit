# Salt
- A variable passed into a cryptographic algorithm or [Pseudorandom Number Generator](pseudo-random-number-generator.md) to improve randomness/strength. #ref/2023/12/09/095245 #glossary

- [Hashing](hashing.md) a given piece of data using a specific algorithm always produces the same output. This means hashes are prone to dictionary attacks as you can simply hash a list of potential passwords and store the results to check against later. Adding a known, secret string to the end of each piece of plaintext data before hashing mitigates against this. Obtaining access to the salt opens up the possibility of a dictionary attack again though.
## My Notes
[Notes](mynotes/salt-notes.md)
