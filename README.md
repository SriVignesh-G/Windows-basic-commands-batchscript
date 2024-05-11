# Name: Sri Vignesh G
# Reg No: 212223040204
# Ex No:08 Windows basic commands batchscript

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
```
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/ed3866ca-3d90-477e-aa52-b0bfff5750cc)



Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```

![image](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/ed3866ca-3d90-477e-aa52-b0bfff5750cc)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```

![image](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/92186753-27ee-44e0-a4bf-6c10be494a80)



Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup
```
![image](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/8be31297-c25a-47bc-babc-452c3b565d26)




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```

## OUTPUT
![image](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/08c1ca6e-7389-4e30-bd43-91b2ec03f936)



# RESULT:
The commands/batch files are executed successfully.

