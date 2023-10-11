# Windows Service Demo

Demonstration of Windows Services

## Steps to run after build



- copy path to the executable file
- open a CMD program in Adminstrative mode
 - go to the Microsoft.Net/framework directory and then to the latest subdirectory version. (for example C:\Windows\Microsoft.NET\Framework\v4.0.30319>)
 - type InstallUtil.exe
- paste the executable path and hit enter


## Run Service

- run services.msc from the windows system command
- find the service according to the Service Name (not the executable name) found in the file ProjectInstaller.Designer.cs which will be this.serviceInstaller1.DisplayName = "Alpha Windows Survice Test";
 - manually right click and press start

## What will happen

- In the Logs directory of where the program started you will see a ServiceLog file for today that was given an entry every 5 seconds.  It will also record every start and stop.
