# Advance-Keylogger
Introduction
Start with a brief introduction to your project, mentioning that it's an advanced keylogger with additional features.

Libraries Used
Explain the purpose of each library you've used in your project:

pynput:

Purpose: Monitors and controls input devices.
Example: Captures keyboard and mouse activities.
pandasai and pandasai.llm:

Purpose: Used for machine learning predictions.
Example: GPT-3.5 language model predicts next typed letters.
pandas:

Purpose: Handles data in a tabular format.
Example: Manages CSV files for data manipulation.
logging:

Purpose: Records mouse and keyboard activities.
Example: Creates log files for tracking user actions.
platform:

Purpose: Provides information about the computer's OS and hardware.
Example: Retrieves details about the operating system.
psutil:

Purpose: Accesses system details like RAM information.
Example: Gathers information about the computer's memory.
uuid:

Purpose: Generates a unique identifier for the network interface.
Example: Creates a unique MAC address.
ifaddr:

Purpose: Provides network adapter information, including IP addresses.
Example: Retrieves network interface details.
pyautogui:

Purpose: Allows for taking screenshots.
Example: Captures screenshots of the screen.
csv:

Purpose: Reads and writes CSV files.
Example: Manages CSV files for data storage.
Code Structure and Functionality
Briefly explain the structure and functionality of your code:

MouseActivity Class:

Captures and logs mouse activity.
KeyboardActivity Class:

Manages keyboard activity logging.
ComputerInfo Class:

Gathers information about the computer's OS, CPU, and RAM.
NetworkInfo Class:

Collects information about network interfaces.
ScreenshotCapture Class:

Captures a screenshot of the screen.
MachineLearning Class:

Performs machine learning predictions.
Main Section:

Initializes instances of MouseActivity and KeyboardActivity.
Starts and maintains listeners for mouse and keyboard activity.
Handles exceptions and stops listeners on program exit.
Gathers computer and network information, captures a screenshot, and makes a machine learning prediction after listener termination.
Writes computer and network information to text files.
Displays the path to the saved screenshot and the machine learning prediction.
Usage
Provide simple instructions on how to use your keylogger:

Clone the repository.
Install required libraries (pip install -r requirements.txt).
Run the script.
