# Chapter 7: Scripting & Automation

> Combine individual commands into powerful scripts to automate repetitive tasks. This chapter covers the essential building blocks of shell scripting, from user input and logic to controlling command execution flow.

| Command                             | Explanation                                                              |
| ----------------------------------- | ------------------------------------------------------------------------ |
| `read variable`                     | Pauses a script to wait for user input and stores it in a variable.      |
| `echo "message"`                    | Prints text to the terminal, essential for feedback in scripts.          |
| `printf "format" "text"`            | A more powerful way to print formatted text.                             |
| `sleep <seconds>`                   | Pauses the execution of a script for a specified number of seconds.      |
| `[ -f "file.txt" ]`                 | `test` expression to check for conditions, the basis of `if` statements. |
| `xargs`                             | Builds and executes commands from standard input.                        |
| `$(command)`                         | Command Substitution. Runs a command and substitutes its output.         |
| `>` (Redirect)                      | Redirects command output to a file, overwriting it.                      |
| `>>` (Append)                       | Redirects output and appends it to the end of a file.                    |
| `<` (Redirect Input)                | Uses a file as the input for a command.                                  |
| `2>` (Redirect Error)               | Redirects only the error messages (stderr) to a file.                    |
| `&>` (Redirect All)                 | Redirects both standard output and error to the same file.               |
| `&&` (AND Operator)                 | Executes the second command only if the first command succeeds.          |
| `;` (Separator)                     | Executes commands sequentially, regardless of success or failure.        |
| `basename /path/to/file.txt`        | Strips the directory path, leaving only the filename (`file.txt`).       |
| `dirname /path/to/file.txt`         | Strips the filename, leaving only the directory path (`/path/to`).       |
| `getopt`                            | Parses command-line options in scripts.                                  |
| `termux-job-scheduler -s <script>`  | Schedules a script to run periodically, even when Termux is inactive.    |
| `termux-dialog \| jq '.text'`       | A scripting pattern to get and parse user input.                         |
| `true`                              | A command that does nothing and always succeeds (exit code 0).           |
| `false`                             | A command that does nothing and always fails (exit code 1).              |
| `sh <script.sh>`                    | Executes a shell script.                                                 |
| `chmod +x <script.sh>`              | Makes a script executable, so you can run it directly with `./script.sh`.|
| `seq <start> <end>`                 | Prints a sequence of numbers, useful for `for` loops.                    |

>  `|` (Pipe)                          Connects the output of one command to the input of another.
>
>  `||` (OR Operator)                 Executes the second command only if the first command fails.                       
---
<p align="center">
  <a href="./chapter_06.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_08.md">Next ></a>
</p>
