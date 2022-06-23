# Persistence_AND_Anti_Sandbox
This reposiorty contain the code which is using latest persistence techniques and multiple anti-vm, anti-sandboxes techniques. In this program, I am using 4 anti-vm and anti-sanboxe techniques, I am also using persistence technique using powershell and task scheduler.


# Persistence
1) Downloading a Exe from webserver using webclient in WindowsApps Folder.
2) Exe is downloading with the name Get-Variable.exe in WindowsApps Folder.
3) Creating a task in scheduler execute Get-Variable command in powershell which is legitimate cmdlet gets the PowerShell variables in the current console.
4) After executing this our downloaded binary will execute rathar than powereshell cmdlet.
5) This is because when we place any exe in windowsapps folder with name Get-variable, Poweshell will execute this exe rather than kegit command.


# Anti-Vm and Anti-Sandbox
1) I am getting Ram size if it is less than 4 gb program will terminate.
2) I am checking if the exe is running in VMware or VirtualBox it will terminate.
3) I am checking the debuger is present, it will terminate.
4) I am checking if the exe is running in sandbox it will terminate.


# Assignment
1) You can add memory insertion technique to bypass sandboxes.
2) You cam add human interaction techniques to bypass sndboxes.




## Just for educational purpose.............. I am not responsible for misuse

