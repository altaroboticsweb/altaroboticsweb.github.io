---
title: Robotpy installation for Windows
parent: Robotics
---

Linux Version: [[How to setup Robotpy and Driver Station on Linux]]
___
## You should only need to follow this guide if you have already tried the robotpy-installer repository in the github



This will automatically install the python3.12.3 installer, you will need to run this executable so that your system will register python3 commands

Open Command Prompt terminal or your VSCode project terminal

Enter this command into the terminal:
```Terminal
python3 -m pip install robotpy
python3 -m pip install robotpy-commands-v2
python3 -m pip install robotpy[phoenix5]
python3 -m pip install robotpy["commands2","phoenix5"]
```

### Powershell Robotpy Installer

To install robotpy exclusively through powershell (CMD), first make sure that you have python3.12 installed:

Go to your taskbar and search "CMD", this will bring up "command prompt"
#### OPEN IT AS AN ADMINISTRATOR

Once you've done that, install chocolatey by running:
````sql
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
````
That will allow us to install python3
```SQL
choco install -y python3
```
