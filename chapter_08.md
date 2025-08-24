# Chapter 8: Storage & Archive Management

> Effectively manage files, archives, and permissions. This chapter covers essential tools for compressing and decompressing data, understanding disk usage, and controlling access to your files.

| Command                           | Explanation                                                              |
| --------------------------------- | ------------------------------------------------------------------------ |
| `chmod <permissions> <file>`      | Changes the access permissions of a file (read, write, execute).         |
| `chmod 755 <file>`                | A common permission set for executables (owner: rwx, group/others: r-x). |
| `chown <user>:<group> <file>`     | Changes the owner and group of a file (useful in proot environments).    |
| `du -h`                           | Displays disk usage of files and directories in a human-readable format. |
| `du -sh <directory>`              | Shows the total size of a single directory (`-s` for summary).           |
| `tar -czvf <archive.tar.gz> <dir>`| Creates a compressed archive (c: create, z: gzip, v: verbose, f: file).  |
| `tar -xzvf <archive.tar.gz>`      | Extracts a compressed archive (x: extract).                              |
| `tar -tvf <archive.tar.gz>`       | Lists the contents of an archive without extracting it (t: list).        |
| `gzip <file>`                     | Compresses a file, replacing it with a `.gz` version.                    |
| `gunzip <file.gz>`                | Decompresses a `.gz` file.                                               |
| `zip <archive.zip> <files>`       | Creates a `.zip` archive.                                                |
| `unzip <archive.zip>`             | Extracts files from a `.zip` archive.                                    |
| `bzip2 <file>`                    | Compresses a file using the bzip2 algorithm.                             |
| `bunzip2 <file.bz2>`              | Decompresses a `.bz2` file.                                              |
| `xz <file>`                       | Compresses a file using the xz algorithm (high compression).             |
| `unxz <file.xz>`                  | Decompresses an `.xz` file.                                              |
| `termux-storage-get <file>`       | Uses the system's file picker to copy a file into the current directory. |
| `ls -l`                           | Long listing format, shows permissions, ownership, size, and date.       |
| `ls -a`                           | Lists all files, including hidden files (starting with a dot).           |
| `ls -lh`                          | Combines long listing with human-readable file sizes.                    |
| `df -hT`                          | Shows disk space usage for filesystems, including their type (`-T`).     |
| `mount`                           | Displays all mounted filesystems.                                        |
| `readlink -f <file>`              | Follows a symbolic link to find the real path of the original file.      |
| `dd if=/dev/zero of=dummy bs=1M`  | A low-level command to create a file of a specific size for testing.     |
| `shred <file>`                    | Securely deletes a file by overwriting it multiple times.                |
| `pwd -L`                          | Prints the logical current working directory (respecting symlinks).      |

---
<p align="center">
  <a href="./chapter_07.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_09.md">Next ></a>
</p>
