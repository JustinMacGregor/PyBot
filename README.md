# ALFRED - Automated Language Functionality and Recognition Enabled Device
PyBot is a Python-based automation tool that allows users to run pre-written Python scripts using voice commands. The tool is designed to recognize trigger phrases and run the corresponding automation script. PyBot also provides a graphical user interface (GUI) for managing the list of available automations, adding new automations, and deleting existing ones.

<p align="center">
  <img src="https://camo.githubusercontent.com/c8ea1110aab43014bb8d5f86c84f82881f9847f2ea92a6ca6c7e511d06d7339c/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f3733353030382f313834353232392f37373338666530612d373537392d313165332d383466342d3762313261613462323939622e706e67" alt="image" height="300" />
</p>



## Requirements
- Python 3.7 or higher
- `pyttsx3` library
- `sounddevice` library
- `speech_recognition` library
- `tkinter` library
## Installation
Clone the repository or download the source code as a ZIP file.
Install the required libraries by running the following command:
Copy code
```python
pip install -r requirements.txt
```
Run the `PyBot.py` script:
Copy code
```python
python PyBot.py
```
## Usage
1. Start the PyBot program by running the `PyBot.py` script.
2. Use the dropdown menu to select the audio input device.
3. To add a new automation, click the "Add Automation" button and select the Python script you want to run. Enter a trigger phrase for the automation when prompted.
4. To delete an existing automation, select it from the list and click the "Delete Automation" button.
5. Speak the trigger phrase for the desired automation. PyBot will run the corresponding Python script.
## Example Automations
PyBot comes with two example automations:

- `lock_device.py`: locks the Windows device.
- `open_browser.py`: opens the default browser.

To add these automations to PyBot:

Copy the automations folder from the PyBot source code to your project folder.
Open the `PyBot.py` script in your preferred code editor.
In the `add_automation` function, replace the `file_path` variable with the path to the desired automation script (e.g., `"./automations/lock_device.py"`).
When prompted, enter a trigger phrase for the automation (e.g., "lock my device").
Repeat steps 3-4 for each desired automation.
## License
PyBot is released under the MIT license. See the LICENSE file for more details.
