# Chapter 6: Advanced File & Text Manipulation

> Unlock the true power of the shell by learning to process data. These native utilities are the cornerstone of the command line, allowing you to search, filter, and transform text and files with precision and speed.

| Command                             | Explanation                                                              |
| ----------------------------------- | ------------------------------------------------------------------------ |
| `grep <"pattern"> <file>`           | Searches for a specific pattern of text within a file.                   |
| `grep -r <"pattern"> <directory>`   | Recursively searches for a pattern in all files within a directory.      |
| `grep -i <"pattern"> <file>`        | Performs a case-insensitive search.                                      |
| `find <dir> -name "<filename>"`     | Searches for files by name within a directory hierarchy.                 |
| `find . -type f -mtime -1`          | Finds files (`-type f`) in the current directory (`.`) modified in the last day. |
| `sed 's/old/new/g' <file>`          | A stream editor that can find and replace text.                          |
| `awk '{print $1}' <file>`           | A pattern-scanning language. This prints the first word of every line.   |
| `cut -c 1-10 <file>`                | Cuts out and prints the first 10 characters of each line.                |
| `cut -d',' -f2 <file.csv>`          | Extracts the second field (`-f2`) from a CSV file using a comma delimiter. |
| `tr 'a-z' 'A-Z' < <file>`           | Translates characters. This converts a file's content to uppercase.      |
| `sort <file>`                       | Sorts the lines of a text file alphabetically.                           |
| `sort -n <file>`                    | Sorts lines numerically.                                                 |
| `uniq <file>`                       | Discards all but one of successive identical lines (use after `sort`).   |
| `wc <file>`                         | Counts the number of lines, words, and characters in a file.             |
| `diff <file1> <file2>`              | Compares two files line by line and shows the differences.               |
| `head -n 20 <file>`                 | Displays the first 20 lines of a file.                                   |
| `tail -n 20 <file>`                 | Displays the last 20 lines of a file.                                    |
| `tail -f <logfile>`                 | "Follows" a file, showing new lines as they are added in real time.      |
| `tee <filename>`                    | Reads input and writes it to both the screen and a file simultaneously.  |
| `ln -s <target> <link>`             | Creates a symbolic link (a shortcut) to a file or directory.             |
| `stat <file>`                       | Displays detailed information about a file (size, permissions, etc.).    |
| `file <file>`                       | Determines and prints the type of a file (e.g., ASCII text, JPEG image). |
| `strings <binary_file>`             | Prints the printable character sequences from a binary file.             |
| `hexdump -C <file>`                 | Displays file content in hexadecimal and ASCII format.                   |
| `base64 <file>`                     | Encodes a file to Base64 text.                                           |
| `base64 -d <file.b64>`              | Decodes a Base64 file back to its original binary form.                  |

---
<p align="center">
  <a href="./chapter_05.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_07.md">Next ></a>
</p>
