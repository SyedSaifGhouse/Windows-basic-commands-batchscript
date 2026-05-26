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

%userprofile%\Desktop\MyLab

![Screenshot 2024-05-09 113508](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/acf6eee7-7d51-4189-b22e-565658efe2a9)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

%userprofile%\Desktop\MyLab

![Screenshot 2024-05-09 113558](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/b4a62ce6-28d4-4866-87bd-06234088fb28)

![Screenshot 2024-05-09 113628](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/12d6bfa3-167d-40cc-bd31-17db465b03cb)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

%userprofile%\Desktop\MyLab

![Screenshot 2024-05-09 113802](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/e2c9595a-b88a-49da-94fb-c156125d3059)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

mkdir %userprofile%\Desktop\Backup

mkdir %userprofile%\Desktop\Backup

![Screenshot 2024-05-09 113839](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/5f2dcf54-92b0-4433-9bec-6de7404bbfd9)

![Screenshot 2024-05-09 113909](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/812199af-2ab1-4f75-bda2-44f3d7baac59)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![Screenshot 2024-05-09 114000](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/a4471ead-62e7-49cd-8305-319d4a51a1bd)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx

%userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT

![Screenshot 2024-05-09 114051](https://github.com/23005529/Windows-basic-commands-batchscript/assets/139842207/37b02a9e-0852-48b2-9146-d922f77df7de)




# RESULT:
The commands/batch files are executed successfully.

