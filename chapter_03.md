# Chapter 3: Accessing Device Hardware

> Go beyond software and command your device's physical components. The Termux API provides direct control over the camera, flashlight, sensors, and more, turning your phone into a programmable, real-world tool.

| Command                                       | Explanation                                                              |
| --------------------------------------------- | ------------------------------------------------------------------------ |
| `termux-battery-status`                       | Returns a JSON object with battery level, temperature, and health.       |
| `termux-camera-info`                          | Returns JSON data about the available camera(s) on the device.             |
| `termux-camera-photo -c 0 image.jpg`          | Takes a photo using the specified camera (e.g., camera 0) and saves it.  |
| `termux-torch on`                             | Turns the flashlight on.                                                 |
| `termux-torch off`                            | Turns the flashlight off.                                                |
| `termux-sensor`                               | Dumps a list of all available sensors and their names.                   |
| `termux-sensor -s "accelerometer"`            | Starts streaming live data from a specific sensor.                       |
| `termux-sensor -n 1 -d 500`                   | Gets a single reading from all sensors with a delay.                     |
| `termux-sensor -c`                            | Cleans up (stops) all running sensor listeners.                          |
| `termux-tts-engines`                          | Lists the available Text-To-Speech (TTS) engines on the device.          |
| `termux-tts-speak "Hello from Termux"`        | Uses the default TTS engine to speak text aloud.                         |
| `termux-tts-speak -e <engine> "Text"`         | Speaks text using a specific TTS engine.                                 |
| `termux-tts-speak -p <pitch>`                 | Speaks text with a specified vocal pitch (e.g., `1.5` for higher).       |
| `termux-tts-speak -r <rate>`                  | Speaks text at a specified speech rate (e.g., `0.5` for slower).         |
| `termux-microphone-record`                    | Starts recording audio from the microphone.                              |
| `termux-microphone-record -f rec.wav -l 5`    | Records for 5 seconds and saves to a file.                               |
| `termux-microphone-record -q`                 | Quits the current recording.                                             |
| `termux-media-player play <file>`             | Plays a media file (audio or video).                                     |
| `termux-media-player pause`                   | Pauses the currently playing media.                                      |
| `termux-media-player stop`                    | Stops the currently playing media.                                       |
| `termux-media-player info`                    | Displays information about the currently playing media.                  |
| `termux-volume`                               | Lists all available audio streams and their volume levels.               |
| `termux-volume <stream> <level>`              | Sets the volume for a specific stream (e.g., `termux-volume music 10`).  |
| `termux-fingerprint`                          | Prompts for fingerprint authentication and returns success or failure.   |
| `termux-infrared-frequencies`                 | Gets the available infrared carrier frequencies (on supported devices).  |
| `termux-infrared-transmit -f <freq> <pattern>`| Transmits an infrared pattern.                                           |

---
<p align="center">
  <a href="./chapter_02.md">< Previous</a> | <a href="./README.md">Home</a> | <a href="./chapter_04.md">Next ></a>
</p>
