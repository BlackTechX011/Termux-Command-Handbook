# Chapter 10: System Internals & Diagnostics

> For the expert user. These commands let you look under the hood of the Termux environment and the underlying Android system, providing powerful tools for debugging, inspection, and advanced configuration.

| Command                | Explanation                                                              |
| ---------------------- | ------------------------------------------------------------------------ |
| `termux-chroot`        | Sets up a traditional Linux-like chroot environment.                     |
| `login`                | A command that gives you a clean login shell, often used after `termux-chroot`. |
| `id`                   | Displays user and group information.                                     |
| `getprop`              | Displays a huge list of Android system properties.                       |
| `getprop \| grep model`  | A practical example: filtering system properties to find the device model. |
| `logcat`               | Dumps a log of Android system messages, invaluable for debugging.        |
| `logcat -s "TAG"`      | Filters logcat output to show only messages with a specific tag.         |
| `ldd <binary>`         | Prints the shared library dependencies of a program.                     |
| `strace <command>`     | Traces system calls and signals, showing what a program is doing.        |
| `uname -a`             | Prints all available system information (kernel, architecture, etc.).    |
| `arch`                 | Prints the machine's architecture (e.g., `aarch64`).                     |
| `free -h`              | Displays free and used RAM in a human-readable format.                   |
| `vmstat`               | Reports information about processes, memory, paging, and CPU activity.   |
| `termux-api-start`     | A script to ensure the `termux-api` background process is running.       |
| `termux-notification-list` | Retrieves a JSON list of all active notifications posted by Termux.    |
| `pkg policy`           | Displays information about package versions and repository priorities.   |
| `pkg clean`            | Clears out the cache of downloaded package files (`.deb`).               |
| `pkg autoclean`        | Removes old, no-longer-downloadable package files from the cache.        |
| `TERM=xterm-256color`  | Sets the `TERM` variable to enable full color support in console programs. |
| `reset`                | Resets the terminal to its default state, fixing a garbled display.      |
| `stty -a`              | Displays all the settings for the current terminal.                      |
| `set -x`               | Enables debugging mode in a shell script, printing each command.         |
| `set +x`               | Disables debugging mode.                                                 |
| `hash`                 | Shows a list of cached command locations for the current shell session.  |
| `type <command>`       | Indicates how a command would be interpreted (alias, built-in, file).    |
| `bind -p`              | Lists all the keybindings and macros available in your shell.            |

---
<p align="center">
  <a href="./chapter_09.md">< Previous</a> | <a href="./README.md">Home</a>
</p>
