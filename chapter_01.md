# Chapter 1: The Termux Foundation

> This chapter covers the absolute essentials for managing the Termux environment itself, installing tools, and performing basic file system navigation. Mastering these commands is the first and most critical step.

| Command                       | Explanation                                                              |
| ----------------------------- | ------------------------------------------------------------------------ |
| `pkg update`                  | Updates the list of available packages from your subscribed repositories.  |
| `pkg upgrade`                 | Upgrades all installed packages to their latest versions.                |
| `pkg install <package>`       | Installs a specific package, like `termux-api`.                          |
| `pkg uninstall <package>`     | Removes a package from your system.                                      |
| `pkg reinstall <package>`     | Reinstalls a package, which can fix broken installations.                |
| `pkg list-installed`          | Shows a list of all packages you have installed.                         |
| `pkg search <query>`          | Searches for available packages.                                         |
| `pkg show <package>`          | Displays detailed information about a specific package.                  |
| `pkg files <package>`         | Lists all files that a specific package installed.                       |
| `termux-setup-storage`        | Prompts for permission to access the device's shared storage.            |
| `pwd`                         | Displays the full path of your current directory.                        |
| `ls`                          | Lists the files and folders in your current location.                    |
| `cd`                          | Changes your current directory (`cd ..` goes up, `cd ~` goes home).      |
| `clear`                       | Wipes the terminal screen clean.                                         |
| `exit`                        | Closes the current Termux session.                                       |
| `mkdir <name>`                | Creates a new directory.                                                 |
| `touch <filename>`            | Creates a new, empty file.                                               |
| `rm <filename>`               | Deletes a file. Use `rm -r <directory>` to delete a directory.           |
| `cp <source> <destination>`   | Copies a file or directory.                                              |
| `mv <source> <destination>`   | Moves or renames a file or directory.                                    |
| `whoami`                      | Displays the current username (e.g., `u0_a123`).                         |
| `uname -o`                    | Displays the operating system (Android).                                 |
| `df -h`                       | Shows disk space usage in a human-readable format.                       |
| `top`                         | Displays a live view of running processes and system resource usage.     |
| `ping <host>`                 | Checks network connectivity to a server (e.g., `ping google.com`).       |
| `ifconfig`                    | Displays your device's network interface information and IP address.     |

---
<p align="center">
  <a href="./README.md">Home</a> | <a href="./chapter_02.md">Next ></a>
</p>
