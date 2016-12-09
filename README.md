To install the NullSpace Service:
1. Open `NullSpaceVR Service Installer` folder
2. Double click `setup.exe` which will install the service and required dependencies:
	- Microsoft .NET Framework 4.5 
	- Visual C++ 2015 Redistributable (x86)
	- Visual C++ 2015 Redistributable (x64)
	(If the dependencies fail to install, try installing them directly from the relevant folders included with the download. Then double click `NSVRServiceSetup.msi` to install the service)
3. Double click the `NullSpace Service` icon on your Desktop. A small icon will appear in your task tray. Right click the icon to:
    - Enable the service (icon turns green)
    - Disable the service (icon turns grey)
    - Quit (disables the service)

To uninstall:
1. Add/Remove programs --> NSVRServiceSetup -> Uninstall

**Note: the service must be running for the NullSpace SDK to function.**

See the [Wiki](https://github.com/NullSpaceVR/NullSpace-Dev-Kit/wiki) for common issues, quickstart, and SDK usage.

See the [Developer Agreement](http://nullspacevr.com/?wpdmpro=nullspace-developer-agreement) before using the SDK.


If you have questions about how to use the API, or comments, feedback, bugs, crashes, annoyances, or improvements, please email casey@nullspacevr.com

Thanks! 