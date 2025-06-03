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

![1](https://github.com/user-attachments/assets/a88bf22e-5a7d-4027-b9b4-68a4d1df8eef)

## COMMAND AND OUTPUT

Remove the directory "my-folder"

![2](https://github.com/user-attachments/assets/2d5243ae-dc3a-4b92-96e7-9b7eb61869a0)

## COMMAND AND OUTPUT

Create the file Rose.txt

![3](https://github.com/user-attachments/assets/80deeaaf-87bf-490e-857c-aa79e9879cb2)

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

![4](https://github.com/user-attachments/assets/149030eb-71cc-4df5-ba1a-502ac1043680)

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

![5](https://github.com/user-attachments/assets/1375be9e-d5e9-455e-a794-9bfe9ca10cba)


## COMMAND AND OUTPUT

Remove the file hello1.txt

![6](https://github.com/user-attachments/assets/a66806b9-263e-41b7-9c73-3911de73bc40)


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

![8](https://github.com/user-attachments/assets/cf1b58ba-1512-4efa-b6a4-5c36dd715388)


## COMMAND AND OUTPUT

List out all the associated file extensions 

![9](https://github.com/user-attachments/assets/d0ce7143-a1c1-41e5-9d15-086b961361f8)

![10](https://github.com/user-attachments/assets/34b2accf-cbd1-40c5-be2a-f62f101154c0)

![11](https://github.com/user-attachments/assets/815a83b9-7c46-454e-82cf-c5c598b4d79a)

![12](https://github.com/user-attachments/assets/6f145e91-a65d-42b3-bcc0-72973d3ff0f4)

![13](https://github.com/user-attachments/assets/06cad828-6a2f-4875-9403-989495392310)

![14](https://github.com/user-attachments/assets/655e232d-2d56-455c-a9d9-935788cc6d7d)

![15](https://github.com/user-attachments/assets/c4e77592-6465-4527-8989-304f4a0c729b)


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

![16](https://github.com/user-attachments/assets/1458de2e-0e18-48dc-964b-2473e501fca4)


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

![image (1)](https://github.com/user-attachments/assets/18ea3add-63be-4594-aa9d-8d92c05fe6ac)

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

![18](https://github.com/user-attachments/assets/cdf0cc88-e9c9-4099-bc71-c6c16ca6b5ec)

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

![19](https://github.com/user-attachments/assets/e96404fd-c0aa-49e0-b473-84a7b3ea750b)

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

![20](https://github.com/user-attachments/assets/2dac5214-08bd-462a-9dbf-c18a42326e49)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT

![21](https://github.com/user-attachments/assets/34f838aa-d9c3-4a67-8079-18a370f84994)

![22](https://github.com/user-attachments/assets/e79a5aa9-24ce-458f-9750-bb70ebc192b3)

![23](https://github.com/user-attachments/assets/744350ef-1048-4717-9481-1da3aaee8655)

# RESULT:
The commands/batch files are executed successfully.
