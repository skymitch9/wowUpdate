# WOW Update

How to update the script with your locations
1. Update these variables in lines 2,3,and 4 by right click editting the script
```$sourceFolder1 = "your WTF folder Location"``` <br>
```$sourceFolder2 = "your interface folder location"``` <br>
```$destinationFolder = "where you want to store your backups"``` <br>

How to Schedule This Script:
1. Save the script as wowBackup.ps1.
2. Open Task Scheduler and create a new task.
3. In the General tab, name your task.
4. In the Triggers tab, click New, set the task to run weekly.
5. In the Actions tab, click New and browse to ```powershell.exe```.
6. In the Add arguments (optional) field, enter: ```-File "C:\Path\To\wowBackup.ps1"```
7. Click OK to save your task.
