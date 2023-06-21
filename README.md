# Python Installation Guide

This repository provides step-by-step instructions on how to install Python and add it to the system path. The instructions are intended for beginners and cover various operating systems.

## Installation Instructions

### Windows

1. Visit the [Python official website](https://www.python.org/downloads/) and download the latest Python installer for Windows.

2. Run the installer and select the option to add Python to the system PATH during the installation process.

3. Follow the on-screen instructions and complete the installation.

### macOS

1. Open a web browser and navigate to the [Python official website](https://www.python.org/downloads/).

2. Download the latest Python installer for macOS.

3. Run the installer and follow the on-screen instructions to complete the installation.

### Linux

1. Open a terminal and enter the following command to install Python using the package manager:
   ```
     sudo apt-get install python3
   ``` 
   Note: The package manager command may vary depending on the Linux distribution. Use the appropriate package manager for your system.

2. Once the installation is complete, you can verify the installation by running the following command:
   ```
      python3 --version
   ```
   This should display the Python version installed on your system.

## Adding Python to System Path
### Windows
1. Press Win + X and select "System" from the menu.
2. Click on "Advanced system settings" on the left side of the System window.
3. In the System Properties window, click on the "Environment Variables" button.
4. Under the "System variables" section, locate the "Path" variable and click "Edit".
5. Add the Python installation path to the "Path" variable. Typically, the path will be something like `C:\PythonXX\` or `C:\PythonXX\Scripts\`, where XX represents the Python version.
6. Click "OK" to save the changes.
7. Open a new command prompt window and type python to verify that Python is added to the system path.

### macOS and Linux

1. Open a terminal window.

2. Depending on your preferred shell, open the corresponding configuration file:

   - For Bash, open `~/.bashrc` or `~/.bash_profile`.
   - For Zsh, open `~/.zshrc`.

3. Add the following line to the configuration file:

   ```bash
   export PATH="/usr/local/bin:$PATH"```
  If Python is installed in a different directory, modify the path accordingly.

4. To apply the changes, run the following command in the terminal:
   ```
   source ~/.bashrc
   ```
   or
   ```
   source ~/.zshrc
   ```
5. Open a new terminal window and type `python` to verify that Python is added to the system path.   
  




