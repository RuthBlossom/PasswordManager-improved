# Password Manager

## Overview
This Python script implements a simple password manager application using Tkinter for the graphical user interface (GUI). The application allows users to securely store login credentials for various websites and provides features for generating strong passwords and retrieving saved passwords.

![password](https://github.com/user-attachments/assets/83f537d3-733a-4b87-ad2e-23e383e371a8)


## Prerequisites
- Python 3.x
- Tkinter (usually included in standard Python installations)
- Pyperclip (`pip install pyperclip`)
- Pillow (PIL) (`pip install Pillow`)

## Usage
1. Ensure that the script file (`password_manager.py`), the `logo.png` file, and the `data.json` file are in the same directory.
2. Run the Python script using your preferred Python interpreter.
3. Use the provided GUI to add, search for, and generate passwords for websites.
4. To add a new password, enter the website URL, your email or username, and the password. Then click the "Add" button to save the credentials.
5. To search for a saved password, enter the website URL and click the "Search" button.
6. To generate a strong password, click the "Generate Password" button, and the generated password will be copied to your clipboard.
7. The application will save the entered data to a JSON file named `data.json` in the same directory.

## Customization
- You can customize the appearance of the GUI by modifying the labels, buttons, and entry widgets' properties in the script.
- To change the logo image displayed in the application, replace the `logo.png` file with your desired image file. Make sure the file name remains the same.
- The application uses Tkinter for the GUI, so you can further customize the layout and design according to your preferences.

## Notes
- This password manager is designed for personal use and may not provide advanced security features found in dedicated password management software.
- It is recommended to use strong, unique passwords for each website to enhance security.
- Please exercise caution when storing sensitive information and ensure that your computer is secure against unauthorized access.

## Disclaimer
This password manager application is for educational and personal use only. T

---

