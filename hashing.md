- Hashing is the cryptographic operation that produces a relatively small and unique yet repeatable representational value from some input data. It is a [trap door function](trap-door.md) so the original data cannot easily be recovered from the hash value. Re-running the hash algorithm can be done in order to detect any violation of the original data's [integrity](integrity.md) without having to do a byte for byte comparison of the two copies of the original data. #ref/2023/12/09/130055 #glossary 

- Anti-malware researchers publish malware hash value details as indicators of compromise. If a file hash value for a file on a victim’s system matches one of the published hashes then the malware is present and can be identified. #ref/2023/12/09/120659
- There is a very small possibility that two files could have the same hash value, this is called [hash collision](hash-collision.md). #ref/2023/12/09/120659
- Frequently used hash functions are [MD5](md5.md) and [SHA1](sha1.md). #ref/2023/12/09/101428
- All Hash Functions are [one-way](trap-door.md) by definition. #ref/2023/12/09/095245
- [Message Digest](message-digest.md)
## My Notes
[Notes](mynotes/hashing-notes.md)
