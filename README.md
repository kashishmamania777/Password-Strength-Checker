# Password-Strength-Checker
A Tkinter-based GUI tool to check password strength based on length and character diversity criteria.

Password Strength Checker Tool

Description
This is a simple password strength checker tool implemented in Python using the `tkinter` library for the GUI. It evaluates the strength of passwords based on several common criteria and provides real-time feedback to the user.

Features
*   Graphical User Interface (GUI) built with `tkinter`.
*   Checks password strength based on:
    *   Minimum length
    *   Presence of uppercase letters
    *   Presence of lowercase letters
    *   Presence of special characters
    *   Presence of digits
*   Provides visual feedback on strength level (Weak, Okay, Good, Strong).
*   Lists the criteria that are met and missing.
*   Includes a progress bar to visually represent password strength.

Usage

1.  **Install Python:** Make sure you have Python 3.x installed on your system.
2.  **Install tkinter:** You may need to install tkinter if it's not already included in your Python installation. On some systems, you can do this with:
    ```
    sudo apt-get install python3-tk  # For Debian/Ubuntu
    ```
3.  **Run the script:**  Execute the `pass_check.py` script from the command line:
    ```
    python pass_check.py
    ```
4.  **Use the GUI:**
    *   Enter a password in the "Enter Password" field.
    *   Click the "Check Strength" button.
    *   View the results displayed in the GUI, including the strength level, criteria met/missing, and the progress bar.

Code Overview
*   `pass_check.py`: Contains the main Python code for the password strength checker.

