# Chapter 2: Interacting with the Android UI

> These commands, primarily from the `termux-api` package, allow your scripts to break out of the terminal and interact directly with the Android user interface, creating a bridge between the command line and the graphical environment.

| Command                                             | Explanation                                                              |
| --------------------------------------------------- | ------------------------------------------------------------------------ |
| `termux-toast "message"`                            | Shows a small, temporary pop-up message (a "toast").                     |
| `termux-dialog`                                     | Creates a pop-up dialog box to get text input from the user.               |
| `termux-dialog checkbox -v "Option1,Option2"`       | Creates a dialog with selectable checkboxes.                               |
| `termux-dialog confirm -t "Question?"`              | Creates a pop-up with "Yes" and "No" buttons.                              |
| `termux-dialog counter -r "1,10,5"`                 | Creates a dialog to select a number within a range (min, max, start).      |
| `termux-dialog date`                                | Creates a dialog with a date picker.                                     |
| `termux-dialog radio -v "Choice1,Choice2"`          | Creates a dialog with radio button options (only one can be selected).     |
| `termux-dialog sheet -v "Item1,Item2"`              | Creates a bottom sheet with selectable items.                              |
| `termux-dialog spinner -v "Value1,Value2"`          | Creates a dialog with a dropdown spinner menu.                             |
| `termux-dialog speech -t "Say something"`           | Opens a dialog to get voice input from the user.                           |
| `termux-dialog time`                                | Creates a dialog with a time picker.                                     |
| `termux-notification --title "Alert"`               | Posts a notification to the Android notification drawer.                   |
| `termux-notification-remove <id>`                   | Removes a notification that was created by Termux.                         |
| `termux-clipboard-get`                              | Prints the current content of the system clipboard.                        |
| `termux-clipboard-set "text"`                       | Sets the system clipboard to the specified text.                           |
| `termux-open <URL>`                                 | Opens a URL in the default web browser.                                    |
| `termux-open <file>`                                | Opens a file with its default Android application.                         |
| `termux-share <file>`                               | Opens the Android share dialog for a specific file.                        |
| `termux-wallpaper -f <image_file>`                  | Sets the device's home screen wallpaper from a local file.                 |
| `termux-wallpaper -u <image_url>`                   | Sets the wallpaper from an image URL.                                      |
| `termux-get-prop <property>`                        | Gets an Android system property value.                                     |
| `termux-vibrate`                                    | Vibrates the device for a short period.                                    |
| `termux-vibrate -d <milliseconds>`                  | Vibrates the device for a specified duration.                              |
| `termux-vibrate -f`                                 | Forces vibration even if the device is in silent mode.                     |
| `termux-job-scheduler`                              | Schedules a script to be run at a later time, even if Termux is closed.    |
| `logcat -d`                                         | Dumps the Android system log to the console and exits.                     |

---
<p align="center">
  <a href="./chapter_01.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_03.md">Next ></a>
</p>
