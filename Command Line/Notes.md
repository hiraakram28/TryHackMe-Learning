
ipconfig /all --> to get your device ip address and more information

netstat --> established connections 

taskkill ==> to kill any command

chkdsk--> checks file system for any errors

------------Power SHell----------------
Power Shell is a tool from microsoft for task automation. It is object-oriented 

Uses object, properties and methods. An object in powershell can include file names and sizes (properties) and functions like copying a process (method).

commands in powershell are verb-noun
get-content -> gets content of file

Something like Get-Help Get-Date will give you information about the Get-Date command

Alias
cd -> Set-Location
cat -> Get-Content
ls ->Get-ChildItem

TO create a new item in powershell we use New-Item -Path ".\..." -ItemType "File"
To delete we use Remove-Item. We can remove the file and directory at the same time just like creating a file and directory at the same time.

Copy-Item -Path .\... -Destination .\...

Powershell is able to pass objects through piping |
-Where-Object is used to filter 
Select-String used to search for text patterns in files

---------------------------------------------System and network--------------
Get-ComputerInfo--> gets operating system information
systeminfo for less details
Get-LocalUser --> tells you all the accounts
Get-NetIPConfiguration == ipconfig


