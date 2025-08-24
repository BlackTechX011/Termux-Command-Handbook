# Chapter 4: Communication & Connectivity

> Automate and manage your device's core communication features. These API commands allow you to send SMS, initiate calls, query contacts, and control Wi-Fi connections, all from your scripts.

| Command                               | Explanation                                                              |
| ------------------------------------- | ------------------------------------------------------------------------ |
| `termux-telephony-call <number>`      | Initiates a phone call to the specified number.                          |
| `termux-telephony-cellinfo`           | Returns JSON data about neighboring cell towers.                         |
| `termux-telephony-deviceinfo`         | Returns JSON data about the device's telephony capabilities.             |
| `termux-contact-list`                 | Returns a JSON list of all contacts on the device.                       |
| `termux-sms-list`                     | Returns a JSON list of recent SMS messages.                              |
| `termux-sms-list -l 50`               | Lists the last 50 SMS messages.                                          |
| `termux-sms-send -n <number> "Msg"`   | Sends an SMS to a specific number.                                       |
| `termux-sms-send -n <num1,num2> "Hi"` | Sends an SMS to multiple numbers at once.                                |
| `termux-wifi-connectioninfo`          | Returns JSON data about the current Wi-Fi connection (SSID, IP, etc.).   |
| `termux-wifi-scaninfo`                | Returns a JSON list of nearby Wi-Fi networks.                            |
| `termux-wifi-enable true`             | Turns Wi-Fi on.                                                          |
| `termux-wifi-enable false`            | Turns Wi-Fi off.                                                         |
| `termux-location`                     | Returns JSON data with the device's last known GPS location.             |
| `termux-location -p <provider>`       | Gets location from a specific provider (`gps`, `network`, or `passive`). |
| `termux-location -r <request_type>`   | Specifies a single (`once`) or continuous (`last`) update.               |
| `termux-download <URL>`               | Downloads a file using the Android system download manager.              |
| `termux-download -t "Title" <URL>`    | Downloads a file with a custom title in the notification.                |
| `netstat`                             | Shows network connections, routing tables, and interface statistics.     |
| `ip addr`                             | A modern command to show IP addresses and network interface information. |
| `ip route`                            | Displays the current IP routing table.                                   |
| `ss`                                  | A utility to investigate sockets (a modern replacement for `netstat`).   |
| `proot`                               | Emulates `chroot`, allowing you to run programs with a different root directory. |
| `proot-distro install <alias>`        | Installs a full Linux distribution (like Ubuntu) inside Termux.          |
| `proot-distro login <alias>`          | Starts a shell inside the installed Linux distribution.                  |
| `proot-distro list`                   | Shows available and installed distributions.                             |
| `wget <URL>`                          | A non-interactive tool for downloading files from the web.               |

---
<p align="center">
  <a href="./chapter_03.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_05.md">Next ></a>
</p>
