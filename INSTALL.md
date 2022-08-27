Installing Python
==========================

Based on the Operating System of your PC, you can download and install Python's latest as well as older versions. Please find below instructions for the same based on your OS.



## Windows
Download the windows installer for the python version you desire from [Python Downloads](https://www.python.org/downloads/)

Double-click on the downloaded file and follow the instructions as requested.

Once completed, add python in the environment variables of your system settings to enable python compiling from your command line.

You can verify if the Python installation is successful either through the command line or through the IDLE app that gets installed along with the installation. Search for the command prompt and type “python”. You can see that Python "version" is successfully installed.

To check python version, run this command in your CMD or Terminal:

```bash
python --version
```

## Mac OS

MacOS comes with Python pre-installed. But it's Python Version 2.7, which is now deprecated (abandoned by the Python developer community).

To install the latest version of python in your mac, first you need to install [Homebrew](https://brew.sh/), a powerful package manager for Mac.

Open your terminal and run this command to install Homebrew in your system:
```bash
"$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Your terminal will ask for admin.user access of your system. You will need to type your password to run this command. This is the same password you type when you log into your Mac. Type it and hit enter.

Once you are done with installing the Homebrew package, you can run this command in your terminal to install python with the desired version you want.

```bash
python version 3.6.5
```
Once done, you can run this command to check if you have successfully installed python in your system or its version:
```bash
python3 --version
```





