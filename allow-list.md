# Allow List
- A list of specifically trusted actions, resources or destinations that a user, system or application can access [^2] [^1] #glossary

- Known in some places as a [whitelist](white-list.md) although this term is falling out of favour.
- The opposite of a [deny list](deny-list.md).
- More secure than deny listing because its default action is to prevent operation - it fails safe
- Typically resource intensive and requires more maintenance than a [deny list](deny-list.md)
- The allow list is often a list of the file name, path, file size and hash value of the approved software. Any code that is not on the list, whether benign or malicious, will not be able to execute on the protected system. [^3]
## My Notes
[Notes](mynotes/allow-list-notes.md)

[^1]: [ref20231209T095245](references.md#20231209T095245)
[^2]: [ref20231209T120659](references.md#20231209T120659)
[^3]: [ref20231209T130055](references.md#20231209T130055)