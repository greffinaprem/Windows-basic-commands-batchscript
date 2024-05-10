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
```
mkdir %userprofile%\Desktop\MyLab
```

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/36755895-6437-4fcc-880b-b8513c9c6bc4)

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/60d0641f-0104-44a4-a0af-717062f486d9)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/de4831c8-3c42-425e-a268-1b113e305a11)

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/2fe4ab35-88d1-437a-8c00-3f8f9b4629c3)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/0b2e5b33-5ce9-40a5-8aeb-b3c555d6edd3)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/ca245612-87e9-4f85-ae2d-4a01dd992c86)


![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/ec2cb6cb-1e31-4367-9e34-4afd03d7c04c)


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/6a52af6a-2895-4ae7-a05f-3971c793329e)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![image](https://github.com/greffinaprem/Windows-basic-commands-batchscript/assets/119475603/61a0a23c-db27-4a39-b182-22ca09df64f5)

# RESULT:
The commands/batch files are executed successfully.

