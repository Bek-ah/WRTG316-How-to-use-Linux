# How to use the Linux Terminal
This instruction guide will help you learn some command-line basics!

Knowing how to use the command line is a powerful skill. It provides you with fast, efficient file management that you can use in complicated tasks, like moving thousands of specific files at once from one folder to another. You can also log into another computer remotely, or install, run and edit software. And it works on almost any computer!

Note for using these instructions: Throughout these instructions there are dropdown menus that contain tips or helpful information. To view these, simply click the triangle icon. If you are in split screen, you may have to click on the triangle icon twice. 

<details>
   <summary>Example Dropdown Menu</summary>
      Good work! If you are stuck on a step, these tips can help.
   </details>

## Requirements
<body>
   <img align="right" src="/screenshots/Terminal_icon.jpg" style="height: 6em; vertical-align: middle" />
   A charged laptop with a Linux Terminal open<br/>
</body>

*See [Troubleshooting](#troubleshooting) for computers without Linux Terminal support*
<br>
<br>

## Caution
Do not use spaces, ```-```, or ```*``` when naming files or when using the command ```rm``` to remove your file.

This can make it difficult to modify the right file, and may cause you delete other important files.

<br>


## Steps
### 1\. Make a directory
   1. Type ```mkdir ```, a name for your folder you are creating, then press ```enter``` <br>
      If I wanted to name my folder "recipes" I would type ```mkdir recipes```

      *```mkdir```: stands for "make directory", and is used to create folders*

      <img src="screenshots/colored mkdir.png" width="50%"/>
      <br>
      <br>
      
      <details>
      <summary>Using ls to check directory contents</summary>

      Type ```ls``` then press ```enter``` <br>
      You can use this command at any time to ensure files are created or moved correctly.

      *```ls```: displays the files in your current directory/folder.* <br>
   
      <img src="screenshots/colored ls.png" width="33%"/>
      </details>
      <br>
      <br>
   
   
### 2\. Move in and out of directory
   1. Type ```cd ```, and then the name of the directory you created, then press ```enter``` <br>
      If my directory was named "example" I would type ```cd example``` <br>
      Your new directory is now displayed next to the username. 

      *```cd```: stands for "change directory", and is used to navigate through directories* <br>

      <img src="screenshots/colored cd.png" width="50%"/>   

   2. To go back into the parent directory, type ```cd ..``` then press ```enter```

      *```..``` is the shortcut for "parent directory", or the directory containing the one you are in currently*

      <img src="screenshots/colored cd ...png" width="44%"/>   

   3. Move back into your directory to get ready for the next step

      <br>
      <br>
   
### 3\. Create and Move Into a File using the Nano command
   1. Type ```nano ```, a file name of your choice (ending in .txt to ensure it is a text file) then press ```enter```<br>
      If I were to name the file "shopping list" I would type ```nano "shopping list.txt" <br>
      
      <img src="screenshots/colored nano create and open file.png" width="55%"/>   
   
   2. Type the following text: ```print("Hello, World!")``` <br>

      *nano: a simple text editor you can use to create, view or modify files.* <br>
      *If ```nano "file name"``` doesn't exist, nano will create a new file and open it* <br>
      *If it does exist, nano will just open the file.*

      <img src="screenshots/colored nano ide.png" width ="75%"/>
      <br>
      <br>
      
   
### 4\. Save and Exit Nano File
   1. Save with ```WriteOut``` by pressing ```ctrl + o``` (not zero.) <br>
      Terminal is now giving you the option to save it with the same file name      
      Press ```enter``` again to replace the file. 

      <img src="screenshots/colored nano writeOut.png" width ="75%"/>   
      
   2. Exit by pressing ```ctrl + x``` (think e**x**it)
      <br>
      <br>

### 5\. Run the Code
   1. Type the command ```python "filename.txt"```, filename.txt being whatever you named your text file previously, and press enter <br>

      *python: this tells the terminal to run the text file like a python script. <br>
      It works here because the ```print("Hello World")``` from earlier is a python command*

      <img src="screenshots/colored python command.png" width ="50%"/>
      <br>
      <br>
      
      <details>
      <summary>Finding your filename</summary>
   
      If you are concerned whether your file saved or forgot the name, use the ```ls``` command from the first step. 
      *```ls```: stands for "list" and is used to list the file directory*
      </details>

      *See [Troubleshooting](#troubleshooting) for help with error messages such as ```command not found``` or ```syntax error```*
      <br>
      <br>
   
### 6\. Editing the File to Create Your Own Message
   1. Type ```nano "filename.txt"```, again replacing "filename.txt" with whatever your filename is, then press ```enter```<br>
      Use the arrow keys to navigate into the end of the phrase “Hello World”.<br>
      Delete Hello World, and then type any message of your choice. <br>
      Ensure your message stays within the quotation marks that contained Hello World.
   
      <img src="screenshots/colored new text nano ide.png" width ="75%"/>
      <br>
      <br>

### 7\. Save and Run New Message
   1. Repeat steps 4 and 5

      <img src="screenshots/colored python command updated text.png" width ="75%"/>
      <br>
      <br>

### 8\. Moving directories and Files
   1. Exit current directory with the ```cd ..``` command
         
      <img src="screenshots/colored cd ...png" width ="45%"/>   

   2. Create a new directory with the ```mkdir ``` command from step 1.

      <img src="screenshots/colored mkdir second folder.png" width ="55%"/>   

   3. Move the old directory into the new one by typing ```mv oldfoldername newfoldername```, replacing oldfoldername and newfolder name with the       respective new and old folders

      *```mv```: stands for "move" and is used to move files and folders around. It is always the item to be moved, followed by where it should be            moved to.*

      <img src="screenshots/colored mv.png" width ="70%"/>
      
      <details>
      <summary>Renaming your files</summary>
         Move command can also be used to rename files

         *insert colored screenshot here*
      </details>
      <br>
      <br>

## Conclusion
You have now learned basic file manipulation in Linux! <br>
There is a lot to explore, and if you would like to learn more then you can try playing this game: [linuxsurvival.com](https://linuxsurvival.com/)
<br>
<br>

## Troubleshooting
#### Problem: No Linux Terminal on your computer
Solution: If you do not have a linux terminal on your computer, you can go to this website: [cylabacademy](https://learn.cylabacademy.org/) <br>
Log in with "writing316" as your username and password. <br>
Once you are logged in you can click the ```>_``` icon in the top right. <br>
You should now be able to practice with the terminal!
<br>
<br>
#### Problem: ```python``` keyword from step 5 isn't working
Solution: For certain machines, like a macbook pro, the ```python``` command is outdated. Try ```python3``` instead. <br>
<img alt="image" src="https://github.com/user-attachments/assets/65337764-4538-4f17-a921-66179d447133" />
<br>
<br>
#### Problem: Syntax or name error after using the command outlined in step 5
Solution: If you get a syntax error or name error after using the command ```python3 name_of_your_file.txt```, <br>
make sure you typed out the sentence exactly as shown in step 3. You may not have typed ```print``` correctly or <br>
forgot symbols like these: ```()""```
<br>
<br>

#### Problem: can't open file '/Users/sbennion/Desktop/writing316/test/helloworld.txt': [Errno 2] No such file or directory
Make sure you spelled the name of your file correctly. To see what it's spelled, try using the ```ls``` command
<br>
<br>

## Survey
How did we do?

[![Survey Link](SurveyQR.png)](https://forms.gle/Uyh9GfeSEtA6TSXHA)  
https://forms.gle/Uyh9GfeSEtA6TSXHA
