# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/2331915f-93a6-431d-9426-045c669af6fd)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/3a948fc5-3881-47b1-9755-7ae0beef5de8)

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/49c55f82-2712-454e-8b1b-573477ba780d)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/d6825945-6ac8-461e-8efb-c73d9741998a)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/b5f3317e-70f4-406c-941d-ae02830275d9)

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/978d5492-0090-404e-9f76-009bc351f85b)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/6a52af6a-2895-4ae7-a05f-3971c793329e)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

## OUTPUT

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/61a0a23c-db27-4a39-b182-22ca09df64f5)

# RESULT:
The commands/batch files are executed successfully.

