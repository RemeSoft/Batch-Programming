# Batch Scripting

Batch Scripting is a simple file, that store command can be executed in a windows environment.  

### Features

-  Using Batch, we can do I/O operations that can be processed further.
- We have various control loops for automatic (For, if, while, etc).
- We can play around with Arrays and Functions, which are the same advanced concepts.
- I support RegEx and we can club this Perl.

### Uses

- Automation of various mundane tasks.
- Automation of various deployment tasks in Windows OS.
- Installing various applications on the system in one go.
- Saving work-hour for the work.



## Creation and Execution

### Creation 

- Using notepad++
- Any editor likes Visual Studio code.

### Execution

- From the same folder
- Via runs the command.



## Printing Hello World

First, create a file with the extension .bat. Bat means **Batch file**.  Now, Right click your batch file and open it on notepad++.

```bash
**Print Command**
echo "Hello world"
```

To run this command you need to open your **cmd** into this folder and  type `filename.bat` 

> If you type **dir** and hit enter cmd will show the Directory.



## Commands

There are a lot of commands in batch scripting. But we will discuss some useful commands.

| Commands     | Explain                                                     |
| ------------ | ----------------------------------------------------------- |
| **ver**      | Version. It shows the windows version.                      |
| **cd**       | Change Directory. It uses to change a directory.            |
| **md**       | Make a Directory. It uses to make a directory.              |
| **rd**       | Remove Directory. It uses to delete a directory.            |
| **cls**      | Clear Screen. It uses to clear the screen.                  |
| **dir**      | Directory. It shows all the content of the directory.       |
| **echo**     | It is used to print something on the screen.                |
| **exit**     | It uses to exit from the command line.                      |
| **ipconfig** | It shows IP configerations.                                 |
| **rem**      | Comments a command.                                         |
| **start**    | Start the program in a new window.                          |
| **time**     | It is used to display the time.                             |
| **pause**    | It pauses whatever running on your console.                 |
| **move**     | It used to move a file one directory to another.            |
| **path**     | It shows which paths are set into the env path.             |
| **ren**      | It is used to rename the file in the directory.             |
| **type**     | This command shows the file type.                           |
| **vol**      | It shows the volume level.                                  |
| **find**     | This command can search a string and output matching lines. |
| **help**     | It shows the list of windows supplied commands.             |
| **sort**     | It is used to sort console outputs.                         |
| **taskkill** | It is used to kill one or more tasks.                       |
| **tasklist** | It shows the list of tasks.                                 |
| **Fc**       | It shows the difference between two files.                  |



### Command : ver

var stands for version. It shows us the current windows version.

------



### Command: cd

cd stands for Change Directory. It uses to change your current directory in the terminal. 

**Example** `C:\Users\DwipSarker> cd Music`

------



### Command: dir

dir stands for the directory. It is used to display all the files and folders available in the directory.

**Example** `C:\Users\DwipSarker> dir`

------



### Command: md

md stands for Make Directory. It is used to create a folder. You have to run this command with the directory name. If you need space for a directory name you **double quote**.  After running this command a directory will create for you.

**Example** `C:\Users\DwipSarker> md new_foler`

You can create multiple directories in a single command. `C:\Users\DwipSarker> md first second`

------



### Command: rd

rd stands for Remove Directory. It is used to remove a directory.

**Example** `C:\Users\DwipSarker> rd newDir`

------



### Command: cls

cls stands for Clear Screen. It will clear the terminal for you. 

**Example** `C:\Users\DwipSarker> cls`

------



### Command: echo

It will show a message in the console.

**Example** `C:\Users\DwipSarker> echo "Hello, World!!"`

------



### Command: exit

exit command is used to close the terminal.

------



