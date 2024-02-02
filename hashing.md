# Hashing
- Hashing is the cryptographic operation that produces a relatively small and unique yet repeatable representational value from some input data. It is a [trap door function](trap-door.md) so the original data cannot easily be recovered from the hash value. Re-running the hash algorithm can be done in order to detect any violation of the original data's [integrity](integrity.md) without having to do a byte for byte comparison of the two copies of the original data. #ref/2023/12/09/130055 #glossary 

- See also [Checksum](checksum.md) and [Cyclic Redundancy Check](crc.md)
- A hash is calculated before an event, and another hash is calculated after the event (an event can be a time frame of storage (i.e. data-at-rest) or an occurrence of transmission (i.e. data-in-transit); the two hashes are then compared using an XOR Boolean operation. If the two hashes exactly match (i.e. the XOR result is zero), then the data has retained its integrity. However, if the two hashes do not match exactly (i.e. the XOR result is a non-zero value), then something about the data changed during the event. #ref/2023/12/09/130055
- Hashing differs from what we usually think of as encryption in that it cannot be undone.
- Anti-malware researchers publish malware hash value details as indicators of compromise. If a file hash value for a file on a victim’s system matches one of the published hashes then the malware is present and can be identified. #ref/2023/12/09/120659
- There is a very small possibility that two files could have the same hash value, this is called [hash collision](hash-collision.md). #ref/2023/12/09/120659
- Frequently used hash functions are [MD5](md5.md) and [SHA1](sha1.md). #ref/2023/12/09/101428
- All Hash Functions are [one-way](trap-door.md) by definition. #ref/2023/12/09/095245
- [Message Digest](message-digest.md)
## My Notes
[Notes](mynotes/hashing-notes.md)
