# Windows-basic-commands-batchscript

## Ex08-Windows-basic-commands-batchscript

## AIM:
To execute Windows basic commands and batch scripting

## DESIGN STEPS:

### Step 1:
Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:
Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.

### Step 3:
Execute the necessary commands/batch file for the desired output. 

## WINDOWS COMMANDS:

### Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

###### COMMAND AND OUTPUT


<img width="975" height="115" alt="Screenshot 2026-03-28 132743" src="https://github.com/user-attachments/assets/e1254a68-8d2f-40d5-8ff0-2621f6880b07" />

Remove the directory "my-folder"

##### COMMAND AND OUTPUT


<img width="1018" height="124" alt="Screenshot 2026-03-28 132828" src="https://github.com/user-attachments/assets/d2cb51a9-c156-4c02-a945-6e518e22bbdf" />


Create the file Rose.txt

##### COMMAND AND OUTPUT

<img width="1127" height="469" alt="Screenshot 2026-03-28 133202" src="https://github.com/user-attachments/assets/ae4c42a8-9706-422a-9723-48afca94099d" />


Create the file hello.txt using echo and redirection

##### COMMAND AND OUTPUT

<img width="1178" height="188" alt="Screenshot 2026-03-28 133305" src="https://github.com/user-attachments/assets/b242d4b8-00c5-4db6-87dc-8066c554458c" />



Copy the file hello.txt into the file hello1.txt

##### COMMAND AND OUTPUT

<img width="1158" height="194" alt="Screenshot 2026-03-28 133348" src="https://github.com/user-attachments/assets/f5677866-1f6d-4ee7-ad90-a37ce3b38150" />



Remove the file hello1.txt & list out the file hello1.txt in the current directory

##### COMMAND AND OUTPUT


<img width="921" height="218" alt="Screenshot 2026-03-28 133431" src="https://github.com/user-attachments/assets/234c294c-fe22-4ae2-8e4a-a40a7126170c" />


List out all the associated file extensions 

##### COMMAND AND OUTPUT
<img width="997" height="286" alt="Screenshot 2026-03-28 133445" src="https://github.com/user-attachments/assets/48df7484-5090-4262-80a3-7fdd097337c0" />




Compare the file hello.txt and rose.txt

##### COMMAND AND OUTPUT

<img width="937" height="856" alt="Screenshot 2026-03-28 133635" src="https://github.com/user-attachments/assets/88f6d7c8-2524-4287-bac4-9d64310b862f" />



### Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

#### OUTPUT
<img width="1120" height="257" alt="Screenshot 2026-03-28 133757" src="https://github.com/user-attachments/assets/54901c05-7d2e-4cc7-b89b-059ed8ad1cf5" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

#### OUTPUT

<img width="958" height="228" alt="Screenshot 2026-03-28 133955" src="https://github.com/user-attachments/assets/90f1f11c-1837-4df2-b8b5-56bc634df445" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

#### OUTPUT

<img width="937" height="229" alt="Screenshot 2026-03-28 134004" src="https://github.com/user-attachments/assets/0d77e8bb-61cb-491f-b067-d8f05c46706d" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

#### OUTPUT
<img width="878" height="120" alt="Screenshot 2026-03-28 134036" src="https://github.com/user-attachments/assets/dfc1fbd1-7bd0-4212-9ba3-be50a7f64fc0" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

#### OUTPUT
<img width="937" height="454" alt="Screenshot 2026-03-28 134128" src="https://github.com/user-attachments/assets/5cdf5864-d94b-4bd2-b018-422bfdaaaa66" />



## RESULT:
The commands/batch files are executed successfully.
