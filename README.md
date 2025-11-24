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


<img width="478" height="149" alt="Screenshot 2025-11-24 112627" src="https://github.com/user-attachments/assets/273d8b00-0dff-472e-9e37-3148e6509252" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="497" height="37" alt="Screenshot 2025-11-24 112638" src="https://github.com/user-attachments/assets/8ea4d913-0483-4e57-a4c5-2b98be5e4347" />



## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="658" height="362" alt="Screenshot 2025-11-24 112659" src="https://github.com/user-attachments/assets/8a3929ab-a809-41e8-b41c-eeffdc461987" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="658" height="362" alt="Screenshot 2025-11-24 112659" src="https://github.com/user-attachments/assets/aae3b71c-9281-4999-86fe-77a50fc9f525" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="589" height="120" alt="Screenshot 2025-11-24 112730" src="https://github.com/user-attachments/assets/d26082b8-750d-40f5-8bfd-3dc2036f47d8" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="514" height="40" alt="Screenshot 2025-11-24 112849" src="https://github.com/user-attachments/assets/bbc53824-4443-4ebc-a82c-832f1d6ce37f" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="767" height="230" alt="Screenshot 2025-11-24 112911" src="https://github.com/user-attachments/assets/3dd2e8eb-1732-45e0-b0a0-d4bdb5f65418" />

## COMMAND AND OUTPUT

List out all the associated file extensions


<img width="643" height="910" alt="Screenshot 2025-11-24 112959" src="https://github.com/user-attachments/assets/922f275c-d7aa-4f9e-8427-8c0e8865cbb7" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="522" height="167" alt="Screenshot 2025-11-24 113012" src="https://github.com/user-attachments/assets/bc0a2354-660b-4342-b045-1ec48e807f2d" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="422" height="94" alt="Screenshot 2025-11-24 114137" src="https://github.com/user-attachments/assets/0c746b33-d969-4580-a28d-f0c752f62d3e" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT


<img width="520" height="195" alt="Screenshot 2025-11-24 114145" src="https://github.com/user-attachments/assets/52ebbad8-6c7d-4d9d-ba1e-47910269b6b2" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="438" height="250" alt="Screenshot 2025-11-24 114153" src="https://github.com/user-attachments/assets/29306f10-229f-4e2f-861b-74b7d58e887b" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="382" height="93" alt="Screenshot 2025-11-24 114201" src="https://github.com/user-attachments/assets/1113ae63-0318-4541-97c1-7493f7ffd002" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="381" height="338" alt="Screenshot 2025-11-24 114210" src="https://github.com/user-attachments/assets/49a8580d-6c0b-4a15-9cd9-ccaa0cd2772e" />



# RESULT:
The commands/batch files are executed successfully.

