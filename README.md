# Training-MSOfficeOffensiveTradecraft
Info related to the Outflank training: Microsoft Office Offensive Tradecraft

_work in progress - you can start already but more information will follow shortly_

# Virtual Machine prep
We recommend you to prepare a virtual machine before the training starts. Having a VM with the proper tools allows you to do the assignments during the training.

Prepping your VM:
- Take a x64 Windows VM as base, we tested on Server 2022 but any recent version might be ok
- Install Office 64 bit, we tested with version 2016 but any recent version might be ok
    - You can find an installer config xml in the ```Office-install``` directory that may help in some cases. To use, run your Office installer as following: ```setup.exe /configure Config.xml``` - if this fails (could be many reasons to), just run the Office installer manually.
- Install .Net 3.5 (https://learn.microsoft.com/en-us/dotnet/framework/install/dotnet-35-windows)
- Install .Net 4.8 (https://go.microsoft.com/fwlink/?linkid=2088631)
- Disable built-in Defender: For example with powershell to remove: ```Uninstall-WindowsFeature -Name Windows-Defender``` or click through the configuration settings to leave installed but disabled.
- Install Python version 3.8.10 (https://www.python.org/downloads/release/python-3810/) 
- Install python PIP (```py -m ensurepip --upgrade```)
- Install python pip packages oletools and olefile (```py -m pip install oletools olefile```)
- Install 7zip (https://www.7-zip.org/download.html)
- Install your favorite text editor, can be VS Code, Notepad++, etc 
- Install Google Chrome (https://www.google.com/chrome/)
- Install Process Hacker (https://processhacker.sourceforge.io/downloads.php)
- Install PE Studio Free version (https://www.winitor.com/download)
- Install The Systinternals Suite (https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite)
- Install Flexhex (http://www.heaventools.com/flexhex-hex-editor.htm)
- Download assignments from *follows later*
