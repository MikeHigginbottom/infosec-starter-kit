# Buffer Overflow
- A buffer overflow occurs when a program or process tries to store more data in a buffer (temporary data storage area) than it was intended to hold. Since buffers are created to contain a finite amount of data, the extra information - which has to go somewhere - can overflow into adjacent buffers, corrupting or overwriting the valid data held in them. #ref/2023/12/09/101428 Carefully crafting this overflow can allow force the target to behave in a way desired by the hacker. #glossary

- Buffer Overflow attacks are generally possible because of poor design and coding techniques when systems are built. #ref/2023/12/09/095245
- [Stack Mashing](stack-mashing.md)
## My Notes
[Notes](mynotes/buffer-overflow-notes.md)
