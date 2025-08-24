# Chapter 9: Advanced Networking & Secure Connections

> Go beyond `ping`. This chapter covers the tools for secure remote access, robust file transfers, and in-depth network diagnostics, transforming Termux into a fully-featured network administration client.

| Command                                   | Explanation                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------ |
| `ssh <user@host>`                         | Secure Shell client for logging into a remote server securely.           |
| `sshd`                                    | The OpenSSH server daemon; run this to `ssh` into your Termux device.    |
| `ssh-keygen`                              | Generates a pair of cryptographic keys for passwordless SSH login.       |
| `ssh-copy-id <user@host>`                 | Copies your public key to a server to enable passwordless login.         |
| `scp <user@host:remote/file> <local>`     | Securely copies files over SSH.                                          |
| `sftp <user@host>`                        | An interactive secure file transfer program over an SSH connection.      |
| `rsync -avh <source> <dest>`              | A powerful tool for efficiently synchronizing files and directories.     |
| `curl <URL>`                              | A versatile tool to transfer data from or to a server (download, test APIs). |
| `curl -L <URL>`                           | Tells curl to follow any HTTP redirects.                                 |
| `curl -o <filename> <URL>`                | Saves the output to a specific file.                                     |
| `wget <URL>`                              | A simple, non-interactive utility for downloading files from the web.    |
| `wget -c <URL>`                           | Continues a partially downloaded file.                                   |
| `wget -r <URL>`                           | Downloads a website recursively.                                         |
| `telnet <host> <port>`                    | An unencrypted tool for testing if a network port is open.               |
| `hostname`                                | Displays the device's network hostname.                                  |
| `ip -s link`                              | Shows detailed statistics for your network interfaces (bytes, errors).   |
| `arp`                                     | Displays the system's Address Resolution Protocol (ARP) cache.           |
| `termux-contact-list \| jq`               | API pattern to get and parse data (e.g., scripting contact lookups).     |
| `termux-wifi-scaninfo \| jq`              | API pattern to get and parse info on nearby Wi-Fi networks.              |
| `ping -c 5 google.com`                    | Pings a host 5 times (`-c 5`) and then stops.                            |
| `whois <domain.com>`                      | Retrieves registration information for a domain name.                    |
| `dig <domain.com>`                        | A powerful DNS lookup utility.                                           |
| `nslookup <domain.com>`                   | Another command for querying DNS servers.                                |
| `netstat -r`                              | Displays the kernel routing table.                                       |
| `netstat -i`                              | Displays a table of all network interfaces.                              |
| `lsof -i`                                 | Lists processes that are using the network.                              |

---
<p align="center">
  <a href="./chapter_08.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_10.md">Next ></a>
</p>
