# Keylogger Application

This is a simple keylogger application built using Python, `tkinter` for the GUI, and `pynput` to capture keyboard events. The keylogger records keystrokes and saves them in both a text file (`key_log.txt`) and a JSON file (`key_log.json`).

## Features

- Captures and logs keystrokes.
- Saves keystrokes to a text file and a JSON file.
- Simple GUI to start and stop the keylogger.

## Requirements

- Python 3.x
- `tkinter` (usually comes pre-installed with Python)
- `pynput` (install using `pip install pynput`)

## Installation

1. Clone the repository or download the code files.

   ```sh
   git clone https://github.com/yourusername/keylogger.git
   cd keylogger
**Install the required Python packages.**
pip install pynput
Usage
**Run the keylogger.py script.**
python keylogger.py
Use the GUI to start and stop the keylogger.

Click "Start" to begin keylogging.
Click "Stop" to stop keylogging.
Code Explanation
Keylogging Functions:

generate_text_log(key): Saves the captured keys to key_log.txt.
generate_json_file(keys_used): Saves the captured keys to key_log.json in JSON format.
on_press(key): Handles key press events.
on_release(key): Handles key release events.
GUI Functions:

start_keylogger(): Starts the keylogger and updates the GUI.
stop_keylogger(): Stops the keylogger and updates the GUI.
GUI Setup:

A simple tkinter GUI with start and stop buttons.
Note
This keylogger is intended for educational purposes only. Use it responsibly and ensure you have permission to log keystrokes on any device.

**This `README.md` provides an overview of the project, including its features, requirements, installation instructions, usage, code explanation, and a note on responsible use. Remember to replace the GitHub repository link with your actual repository URL.
**
