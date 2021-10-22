# Silent installer for Python version 2 and 3

### Supported OS:
Windows x64

<br>

### For installation:
* Download Python_Installer.exe
* Run and select the python version you want.

### Silent Installation:
```cmd
Python_Installer.exe --install 3.10.0 --library
```

<br>  

### Silent switches:
Python_Installer.exe

-h, --help            show this help message and exit  
-i INSTALL, --install INSTALL
                      install Python  
-r, --reset           reset Python environment variables  
-l, --library         install Python library  
-d, --download        download Python binaries  

<br>  

### Examples:  
| Package |Version |
| ---          |     ---      |
| To install Python 3.10.0 | `Python_Installer.exe --install 3.10.0` |
| To install Python Library | `Python_Installer.exe --library` |
| To install Python 3.10.0 + libraries | `Python_Installer.exe --install 3.10.0 --library` |
| To reset environment variables | `Python_Installer.exe --reset` |
| To download Python binaries | `Python_Installer.exe --download` |
