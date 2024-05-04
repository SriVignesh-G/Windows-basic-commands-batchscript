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
mkdir ~/Desktop/MyLab
```
![WhatsApp Image 2024-05-04 at 11 16 42_229e91bd](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/71acafbd-1471-481d-9a68-6282a4e10d82)


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
```
cd MyLab
touch MyFile.txt
```

![WhatsApp Image 2024-05-04 at 11 16 42_61f496ae](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/54aa02c4-ff20-424d-9f33-c1fbd9ac2226)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
```
ls ~/Desktop/MyLab
```

![WhatsApp Image 2024-05-04 at 11 16 42_808017ed](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/6713a70d-1a2d-4d3f-b39e-da14159cdc01)


Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir ~/Desktop/Backup
cp MyFile.txt ~/Desktop/Backup
```

![WhatsApp Image 2024-05-04 at 11 16 42_4b35f6c7](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/38eb3e69-b676-46aa-816c-0a929509ab00)


Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT
```
mv ~/Desktop/MyLab/ ~/Documents
```
![WhatsApp Image 2024-05-04 at 11 16 43_fff03fea](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/fe865691-e79e-42e8-89a1-19123e333f6c)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir ~/Desktop/DocBackup
cp ~/Documents/*.docx ~/Desktop/DocBackup
rm ~/Documents/*.docx
echo Backup and Deletion completed successfully
```

## OUTPUT
![WhatsApp Image 2024-05-04 at 11 16 43_16c3794a](https://github.com/SriVignesh-G/Windows-basic-commands-batchscript/assets/147576510/9bb00c1d-63c0-4130-a181-6551db9ebe4e)


# RESULT:
The commands/batch files are executed successfully.

