# Guide line For developer
The main objective of this document is to install the necessary tools for developing automatic test scripts.


## Requirements

1- Python (version 3.6 or higher) & PIP :
    - Dowlowd python from https://www.python.org/downloads/
    - Run the setup program.
    - Check the "Add python.exe to PATH" window and choose the Customize installation option.
    - After Next -> Check all icons except Install python for all users "verify that PIP is checked" -> Install

    -> "When installing Python, you typically get pip installed automatically".


NB : under windows the python command is not recognized as an internal command.
    -> You will have to use the "py" command instead of python.


1.1- check the Installation of "Python (version 3.

6 or higher)": 
    - open a command prompt "Cmd" and run the following command :
        C:\>py --version
        Python 3.9.0

1.2- check the Installation of " PIP " :
- open a command prompt "Cmd" and run the following command :
    C:\> py -m pip --version
    pip 22.3.1 from C:\Users\srzigui\AppData\Roaming\Python\Python39\site-packages\pip (python 3.9)


2- PyCharm : 
    - Dowlowd PyCharm from https://www.jetbrains.com/pycharm/download/ -> section=windows
    - Run the setup program 
    - Check the icons "Add launchers dir to the PATH" and "64-bit launcher" -> follow the installation instructions.

    -> Once the installation is complete, you will find the PyCharm Ide on the desktop. 
    

## Installation of the Automation framework

1- Robot Framework 

    How to use it ?
        Robot Framework is a generic open source automation framework. We will be used for test automation 
   ![Robot](https://user-images.githubusercontent.com/113591126/211787530-9f7381b0-b89d-4d3d-99d3-9719b75547fb.PNG)
    

    Note: As you start the Robot Framework installation, you will get an error which is the Proxy error since the ACTIA network is protected.
        -> The solution to this problem is to define the @ proxy " 172.18.3.180 : Port 3128 " as a global environment variable.



To install Robot Framework, you will need to follow these steps: 


C: \> py -3.10 -m robot --version 
Robot Framework 5 .0 ( Python 3 .10.3 sur win32 )
