# Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
```
NAME:Tarunika.D
REG.NO:212223040227
```
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab

![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/20b91359-5d35-41c8-9d4c-1e3091469e46)




## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab

![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/f43c7942-b126-4c2b-b605-b214d28a10ab)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab


![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/6d31e34c-9c15-42ce-9b40-f319861080f5)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup


![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/eb15a0a0-c82d-4fa5-b8db-f6c7205d48de)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents


![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/53d0d253-0f3d-4f0c-b580-991d52ce19e4)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT

![image](https://github.com/mounika2005/Windows-basic-commands-batchscript/assets/145633112/94bfcc21-bdc4-4bbf-a67d-6bc5ad345d8b)


# RESULT:
The commands/batch files are executed successfully.

