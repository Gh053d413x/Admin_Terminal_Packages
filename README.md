# Admin Terminal Packages `v1.0`

This is where you can download packages for Admin Terminal

---

## ℹ️ INFO ℹ️

If a package is required, Admin Terminal will prompt you to install packages or create new ones, you can download already-made packages from here or make new ones yourself

You can upload packages and if it is approved then it will be added to the repository

## Instructions

You can install it as an EXE file or a Python file, you will need to install python to use the python (original) version

Install Python at the [Python Website](https://www.python.org)

#### Steps to install

1. Put the program file into the directory you want to run the terminal
2. Run the program and let the settings file install
3. Create a user then log in and have fun!

---

## Patch Notes:

### Main Line Changes
-   Re-added the legacy logo and can be turned on via the settings
-   Updated to Python 3.13
-   Updated the log in system (You can still log in the same way)
-   Fixed a few bugs
-   Changed the look of constant variables
-   Fixed the wrong color bug - Some pages had the Blue Hue for input for the main page
-   Fixed the Settings Wipe bug - Changing a user's password and/or enable/disable-ing the legacy logo would wipe the settings file

### Technical Changes
-   Added the TYPE_COMMAND variable - Use this to type file contents into the terminal at will
-   Updated `text_decor.style.END` to `text_decor.RESET`
-   Renamed `adminPassword` to `master_password`
-   Added `NoReturn` from the `typing` package
-   Renamed py_command, clear_command, pause_command and remove_command to PY_COMMAND, CLEAR_COMMAND, PAUSE_COMMAND and REMOVE_COMMAND
-   Changed all constant variables from this format `const_var` to `CONST_VAR`


---

## User System Information

The users are stored in the settings file with a custom made API

The password is encrypted which means if you want to change your user's password then you have to do it within the settings menu in the terminal

Accounts can be disabled

Accounts can be set as admins

---

## Master Password Information

The Master password is stored in the settings file with a custom made API

The password is encrypted which means if you want to change the master password then you have to do it within the settings menu in the terminal

it is used if a regular user is escalating to admin like changing a user's password

---
## File and Folder Information

The program file is going wherever you put it, for example: `D:\Admin_Terminal.py` or `D:\Admin_Terminal.exe`

The settings file backups will go in the "backups" directory in the same directory you put the admin terminal in, for example: `D:\backups\settings_backup_2024-05-04_20-55.json`

The settings file will go in the same directory you put the admin terminal in, for example: `D:\settings.json`

---

## Installing Information

When opening Admin Terminal for the first time, it will prompt you to install the settings file.
