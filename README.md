# windows sub system
Windows10 provide sub system in which linux can be installed and used

Installation :
  Requirement : 
    In order to use, Developer mode need to be turned on.
  How to :
    Open setting search for "Use developer settings"
    Select "Developer mode" radio button
    Next, Search "Turn Windows Featurs on or off" in start menu.
    Find Windows subsystem for Linux. Check / Select this.
    
    We are done with the setup. Next step is install linux. 
    For that, we need to go to Microsoft Store. And search for "Linux" or "Ubuntu". And get the app.

  Access :
    To access open powershell or command prompt. 
    type bash. You are all set. 
    It will ask you to set password and uses. Once set you would be in unix system without use of docker or VM / Virtualbox.
    
  Windows Filestore : 
    Windows FS is mounted in /mnt/.. So you can access c drive by cd /mnt/c/
    
