# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="649" height="184" alt="Screenshot 2026-05-26 185257" src="https://github.com/user-attachments/assets/b344e5c7-49b1-49f8-a2de-f5f071ef19bc" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="413" height="35" alt="Screenshot 2026-05-26 185329" src="https://github.com/user-attachments/assets/1fd5e34a-2d6d-4d9a-a561-8e996ec3c691" />



## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="697" height="389" alt="Screenshot 2026-05-26 185613" src="https://github.com/user-attachments/assets/e2758800-1235-45d5-ac54-28850866d9d7" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="592" height="199" alt="Screenshot 2026-05-26 185702" src="https://github.com/user-attachments/assets/3aa4bf19-6ac0-4d26-82c1-d0f5b7a48cdf" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="592" height="199" alt="Screenshot 2026-05-26 185702" src="https://github.com/user-attachments/assets/bc21df9d-bca1-4bdc-a4bf-53f5672f9226" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="509" height="322" alt="Screenshot 2026-05-26 185746" src="https://github.com/user-attachments/assets/1765870e-ada6-486e-aaa6-52d6514dbfef" />



## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="620" height="904" alt="Screenshot 2026-05-26 185808" src="https://github.com/user-attachments/assets/7b6d29cf-cac5-428a-b11f-9dc3da73f537" />




## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="524" height="193" alt="Screenshot 2026-05-26 190045" src="https://github.com/user-attachments/assets/5c17a0eb-4bf5-415a-848c-a4ac0c6cfd83" />




## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="558" height="98" alt="Screenshot 2026-05-26 192712" src="https://github.com/user-attachments/assets/98800f49-47fc-481b-9c11-733e655d2855" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="617" height="166" alt="Screenshot 2026-05-26 192725" src="https://github.com/user-attachments/assets/5df7f3b2-10cb-4dd5-9604-c32ebbd7ae39" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="619" height="171" alt="Screenshot 2026-05-26 192734" src="https://github.com/user-attachments/assets/b154f217-fc07-4970-8001-ffb967958aff" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="547" height="93" alt="Screenshot 2026-05-26 192745" src="https://github.com/user-attachments/assets/d832329e-e358-427f-a891-e40d0ac7cf4e" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="512" height="217" alt="Screenshot 2026-05-26 192806" src="https://github.com/user-attachments/assets/c5d14320-bd69-466b-abb3-98766b019409" />




# RESULT:
The commands/batch files are executed successfully.

