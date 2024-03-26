# Learn-Java-NIO
A series to learn Java's new IO model

## Exploring NIO

``NIO stands for New I/O``

NIO provides enhanced support for file-handling. NIO supports; 

- Buffer-oriented
- Channel-based approach to I/O operations

NIO is built on 2 foundational items

- Buffers
- Channels

`` A buffer holds data``

``A channel represents an open connection to an I/O device like a file or a socket``

How it works is 
1. You obtain a channel to an I/O device 
2. A buffer to hold data.
3. Operate on the buffer, inputting and outputting data as needed.