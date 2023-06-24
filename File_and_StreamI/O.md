# File and Stream I/O
 File and Stream I/O in C# and .NET involves reading/writing files and streams. System.IO provides classes for file operations, while streams handle byte-level data. It is also an ordered and named collection of bytes that has persistent storage. When you work with files, you work with directory paths, disk storage, and file and directory names. In contrast, a stream is a sequence of bytes that you can use to read from and write to a backing store, which can be one of several storage mediums (for example, disks or memory).
 
 Reader and writer classes convert characters to/from bytes. Asynchronous I/O improves responsiveness. Compression classes handle file compression. Exception handling is important.

 # How to: Write text to a file
 The following classes and methods are typically used to write text to a file:

StreamWriter contains methods to write to a file synchronously (Write and WriteLine) or asynchronously (WriteAsync and WriteLineAsync).

File provides static methods to write text to a file such as WriteAllLines and WriteAllText, or to append text to a file such as AppendAllLines, AppendAllText, and AppendText.

Path is for strings that have file or directory path information. It contains the Combine method and in .NET Core 2.1 and later, the Join and TryJoin methods. These methods let you concatenate strings for building a file or directory path.

# How to: Read and write to a newly created data file

The System.IO.BinaryWriter and System.IO.BinaryReader classes are used for writing and reading data other than character strings. The following example shows how to create an empty file stream, write data to it, and read data from it.
