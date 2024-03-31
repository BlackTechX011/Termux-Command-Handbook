### Chapter 1: Basic Commands
___
#### Part 1:

1. **pkg update**: This command updates the package lists for upgrades and installs.
   
2. **pkg upgrade**: Upgrades all installed packages to their latest version.
   
3. **pkg install [package_name]**: Installs a package. Replace `[package_name]` with the name of the package you want to install.
   
4. **pkg uninstall [package_name]**: Uninstalls a package. Replace `[package_name]` with the name of the package you want to uninstall.
   
5. **pkg search [keyword]**: Searches for packages containing the specified keyword.
   
6. **pkg list-all**: Lists all available packages.
   
7. **termux-setup-storage**: Sets up storage in Termux to access files on your device.
   
8. **pkg info [package_name]**: Displays information about a specific package.
   
9. **pkg list-installed**: Lists all installed packages.
   
10. **termux-wake-lock**: Keeps the device awake while Termux is running.
   
11. **termux-wake-unlock**: Allows the device to sleep normally.
   
12. **termux-open [file/path]**: Opens a file or directory with the default app.
   
13. **termux-open-url [URL]**: Opens the specified URL in the default browser.
   
14. **termux-toast [message]**: Displays a toast message on the screen.
   
15. **termux-volume [option]**: Adjusts the volume. Options include `music`, `ring`, `alarm`, `notification`, and `system`.

16. **termux-vibrate**: Vibrates the device for a specified duration.

17. **termux-share**: Shares files or text using the Android share menu.

18. **termux-clipboard-get**: Retrieves the current contents of the clipboard.

19. **termux-clipboard-set [text]**: Sets the clipboard contents to the specified text.

20. **termux-dialog**: Opens a dialog box with various options.

21. **termux-notification**: Sends a notification with the specified title and text.

22. **termux-sms-inbox**: Lists received SMS messages.

23. **termux-sms-send -n [number] [message]**: Sends an SMS to the specified number with the given message.

24. **termux-contact-list**: Lists all contacts stored on the device.

25. **termux-contact-get [contact_name]**: Retrieves information about the specified contact.

26. **termux-sms-list**: Lists all SMS messages.

27. **termux-tts-speak [text]**: Converts text to speech and speaks it aloud.

28. **termux-camera-photo [output_file]**: Takes a photo using the device's camera and saves it to the specified file.

29. **termux-camera-record [output_file]**: Records a video using the device's camera and saves it to the specified file.

30. **termux-media-player play [file]**: Plays the specified audio or video file.

31. **termux-media-player pause**: Pauses the currently playing media.

32. **termux-media-player stop**: Stops the currently playing media.

33. **termux-media-player seek [time]**: Seeks to the specified time in the currently playing media.

34. **termux-media-player playlist [file]**: Loads a playlist file.

35. **termux-download [URL]**: Downloads a file from the specified URL.

36. **termux-upload [source_file] [destination_directory]**: Uploads a file to the specified directory.

37. **termux-fix-shebang [file]**: Fixes the shebang of a script file to make it executable.

38. **termux-info**: Displays system information.

39. **termux-open-settings**: Opens the Termux settings menu.

40. **termux-wifi-enable [true/false]**: Enables or disables Wi-Fi.

41. **termux-battery-status**: Shows the current battery status.

42. **termux-telephony-cellinfo**: Shows information about the current cellular network.

43. **termux-telephony-deviceinfo**: Shows device-specific information.

44. **termux-telephony-imei**: Shows the IMEI number of the device.

45. **termux-telephony-signalstrength**: Shows information about the signal strength of the cellular network.

46. **termux-dialog**: Displays a dialog box with customizable options.

47. **termux-notification**: Sends a notification to the notification bar.

48. **termux-vibrate**: Vibrates the device.

49. **termux-toast**: Displays a toast message on the screen.

50. **termux-wifi-connectioninfo**: Shows information about the current Wi-Fi connection.

#### Part 2:

1. **termux-wifi-ipinfo**: Displays information about the device's IP address.

2. **termux-wifi-scaninfo**: Scans for Wi-Fi networks and displays information about them.

3. **termux-clipboard-get**: Retrieves the current contents of the clipboard.

4. **termux-clipboard-set [text]**: Sets the clipboard contents to the specified text.

5. **termux-dialog**: Displays a dialog box with customizable options.

6. **termux-notification**: Sends a notification to the notification bar.

7. **termux-vibrate**: Vibrates the device.

8. **termux-toast**: Displays a toast message on the screen.

9. **termux-battery-status**: Shows the current battery status.

10. **termux-camera-info**: Shows information about the device's camera(s).

11. **termux-camera-photo [output_file]**: Takes a photo using the device's camera and saves it to the specified file.

12. **termux-camera-record [output_file]**: Records a video using the device's camera and saves it to the specified file.

13. **termux-camera-snapshot [output_file]**: Takes a snapshot using the device's camera and saves it to the specified file.

14. **termux-camera-view**: Opens a live preview from the device's camera.

15. **termux-contact-get [contact_name]**: Retrieves information about the specified contact.

16. **termux-contact-list**: Lists all contacts stored on the device.

17. **termux-dialog**: Displays a dialog box with customizable options.

18. **termux-download [URL]**: Downloads a file from the specified URL.

19. **termux-fix-shebang [file]**: Fixes the shebang of a script file to make it executable.

20. **termux-info**: Displays system information.

21. **termux-location**: Shows the current device location.

22. **termux-media-player**: Controls media playback.

23. **termux-media-scan [path]**: Scans the specified path for media files.

24. **termux-microphone-record [output_file]**: Records audio using the device's microphone and saves it to the specified file.

25. **termux-notification**: Sends a notification to the notification bar.

26. **termux-open [file/path]**: Opens a file or directory with the default app.

27. **termux-open-url [URL]**: Opens the specified URL in the default browser.

28. **termux-share**: Shares files or text using the Android

 share menu.

29. **termux-sms-list**: Lists all SMS messages.

30. **termux-sms-inbox**: Lists received SMS messages.

31. **termux-sms-send -n [number] [message]**: Sends an SMS to the specified number with the given message.

32. **termux-sms-view [message_id]**: Displays the contents of the specified SMS message.

33. **termux-storage-get [path]**: Retrieves information about the specified storage path.

34. **termux-storage-list**: Lists all available storage volumes.

35. **termux-telephony-cellinfo**: Shows information about the current cellular network.

36. **termux-telephony-deviceinfo**: Shows device-specific information.

37. **termux-telephony-imei**: Shows the IMEI number of the device.

38. **termux-telephony-signalstrength**: Shows information about the signal strength of the cellular network.

39. **termux-torch [true/false]**: Turns the device's flashlight on or off.

40. **termux-tts-engines**: Lists available text-to-speech engines.

41. **termux-tts-speak [text]**: Converts text to speech and speaks it aloud.

42. **termux-upload [source_file] [destination_directory]**: Uploads a file to the specified directory.

43. **termux-url-opener [URL]**: Opens the specified URL in the default app.

44. **termux-volume**: Controls volume settings.

45. **termux-wallpaper [file]**: Sets the device's wallpaper to the specified image file.

46. **termux-wifi-connect [SSID] [password]**: Connects to the specified Wi-Fi network.

47. **termux-wifi-enable [true/false]**: Enables or disables Wi-Fi.

48. **termux-wifi-ipinfo**: Displays information about the device's IP address.

49. **termux-wifi-scaninfo**: Scans for Wi-Fi networks and displays information about them.

50. **termux-wifi-scaninfo**: Scans for Wi-Fi networks and displays information about them.
___
___

These commands cover a wide range of functionalities within Termux, allowing users to perform various tasks and operations directly from the command line interface.
___
