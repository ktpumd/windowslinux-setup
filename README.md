# Windows Subsystem Linux Setup

## Getting Started

These instructions will get you started with setting up a linux subsytem as well as installing python and visual studio code.

### Prerequisites

Windows Machine with Windows 10 and Admin Access

### Installing Windows Subsystem Linux Setup

1. Open Settings
2. Click on Apps
3. Under the "Related settings" section, click the Programs and Features option

![Related Settings](apps-features-programsfeatures-option.jpg)

4. Click the Turn Windows features on or off

![Windows Features](controlpanel-turn-windows-features-option.jpg)

5. Check the Windows Subsystem for Linux option

![Check WSL](enable-windows-subsystem-linux-windows-10.jpg)

6. Click the OK button
7. Restart your windows machine

After restart
1. Open Microsoft Store
2. Search for Ubuntu 18.04
3. Click the install button

![install ubuntu](install-ubuntu-microsoftstore.jpg)

4. Click the launch button
5. Create a username (I usually do first name)
6. Set a password (make sure you remember you will need it for any adminstrator operations) 

![setup ubuntu](setup-ubuntu-wsl-windows10.jpg)

### Installing Git on Linux

1. sudo apt-get update (type sudo password after)
2. sudo apt install git-all
3. Follow [Git Started](https://github.com/ktpumd/git-started) Tutorial from KTP

### Installing Visual Studio Code on Linux

I highly recommend using Visual Studio Code for development on a windows machine. 
It interacts well with linux and there are a lot of extensions to make development easier!

1. Install Windows 10 Visual Studio Code here [Windows 10 Download](https://code.visualstudio.com/download)
2. Once installed 

![Visual Studio Code Extension Download](download-extensions.jpg)

### How to Use Visual Studio Code

1. Type cmd in your windows search bar and go to the directory with your programming folders
2. Type bash and enter. The terminal should change and become username@computer-name:(directory)
3. If you want to open visual studio code in your current directory type code .
4. If you want to open visual studio code in a sub directory type code (directory name)
