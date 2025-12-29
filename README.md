--------------------------------------------------------------------------
                           PYTHON KEYLOGGER
--------------------------------------------------------------------------

[ DESCRIPTION ]
This repository contains a Python-based keylogger designed to capture and 
record keystrokes from the target system. The script runs in the background 
and logs keys to a local text file. It demonstrates the use of the `pynput` 
library for monitoring keyboard input events.

[ FEATURES ]
- Captures all alphanumeric keys and special characters.
- Handles special keys (Space, Enter, Backspace) for readable logs.
- Saves logs locally to a specified text file (e.g., `keylog.txt`).
- Lightweight and minimal resource usage.
- (Optional) Can be extended to send logs via email.

[ PREREQUISITES ]
Ensure you have the following installed on your system:
- Python 3.x
- pip (Python Package Installer)

[ DEPENDENCIES ]
This project relies on the following external libraries:
- pynput: To control and monitor input devices.

[ INSTALLATION ]
1. Clone the repository:
   git clone https://github.com/Gauravpatel44/Python-Keylogger.git

2. Navigate to the project directory:
   cd Python-Keylogger

3. Install the required dependencies:
   pip install pynput

[ USAGE ]
1. Open the terminal or command prompt in the project directory.
2. Run the keylogger script (ensure you have appropriate permissions):
   python keylogger.py
   
   (Note: Replace 'keylogger.py' with the actual filename if different, 
   e.g., 'main.py')

3. To stop the keylogger, typically use the interrupt command (Ctrl+C) 
   in the terminal, or terminate the process via Task Manager.

4. Check the generated log file (e.g., `keylog.txt`) in the same directory 
   to view the captured keystrokes.

[ DISCLAIMER ]
This software is provided for EDUCATIONAL PURPOSES ONLY. The author assumes 
no liability and is not responsible for any misuse or damage caused by this 
program. Using keyloggers on systems without the explicit permission of the 
owner is illegal and a violation of privacy laws. 

Use responsibly.
--------------------------------------------------------------------------
