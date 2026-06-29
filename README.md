# WRTG316-How-to-use-Linux
## Welcome to the Linux Terminal!
## Requirements
## Steps
1. Make the folder <mkdir foldername>
  Note: ls lets you see the directory, this can be done at any time to ensure things are created <ls>

1. Move into folder (you know you are successful if it now shows the folder name next to the username) <cd foldername>
Note: to return to the previous layer <cd ..>

1. Nano into a file <nano filename.txt> and type the following: print("Hello, World!") 
Note: typing Nano creates the file, and opens it automatically 
1. Save (write out, which is ctrl O, and will open up a new menu ensuring you want to save it to that file name, just hit enter) and exit (ctrl X)
1. Run the code file <python filename>
Note: if you are concerned if your file saved, or forgot the name, type ls
If the file didn't run this may be a good spot to link to troubleshooting, teaching them how to edit the file. Or! Optional steps below: editing the file 
1. Editing the file to create your own message <nano filename.txt>. Use the arrow keys to navigate into the end of the phrase “Hello World”. Delete Hello World, and type any message of your choice
Note: running Nano on an existing file will not create a new one, rather edit the existing one
1. Save (write out), exit the file, and rerun the program, as done in steps 4 and 5 (this step can be broken down more if we want, just bother me (Faith), since I have the setup and can make it look identical to the other screenshots
1. The next few steps handle moving folders and files. Exit current folder (explain why) 
<cd ..> (ls done for demonstration purposes)

1. Create new folder <mkdir newfoldername>

1. Move the old folder into the new one. <mv /path/to/source_folder /path/to/destination/> since in this example both folders are in the same file, the path is just <mv oldfoldername newfoldername> and maybe we just leave the code like that to make it simple



## Comments, notes, and examples
## Conclusion
## Troubleshooting
## Hazards Statements
Do not use spaces, -, or * for file names or when using the command rm to remove your file.
## Survey
**insert QR code**
