# WRTG316-How-to-use-Linux
## Welcome to the Linux Terminal!
## Requirements
## Steps
1. Make the folder
   1. Type ```mkdir foldername``` then press enter
   1. Type ```ls``` then press enter
   Note: ls lets you see the directory, this can be done at any time to ensure things are created
   ![error](screenshots/Screenshot1.png)
1. Move into folder
   1. Type ```cd foldername``` (it should now show the folder name next to the username)
   Note: to return to the previous layer ```cd ..```
   ![error](screenshots/Screenshot2.png)

1. Create and Move Into a File
   1. Type ```nano filename.txt``` and press enter.
   1. Type the following text: ```print("Hello, World!")```
   Note: typing Nano creates the file, and opens it automatically
   ![error](screenshots/Screenshot3.png)

1. Save and Exit
   1. Save with write out by pressing ctrl then O (not 0)
      Note: press enter when terminal asks if you want to save it to keep the file name
   1. Exit by pressing ctrl then X
      ![error](screenshots/Screenshot4.png)

1. Run the Code
   1. Type the command ```python filename``` and press enter
   Note: if you are concerned if your file saved, or forgot the name, type ```ls```
   ![error](screenshots/Screenshot5.png)
   If the file didn't run this may be a good spot to link to troubleshooting, teaching them how to edit the file. Or! Optional steps below: editing the file 
1. Editing the File to Create Your Own Message
   1. Enter ```nano filename.txt```. Use the arrow keys to navigate into the end of the phrase “Hello World”. Delete Hello World, and type any message of your choice
   Note: running Nano on an existing file will not create a new one, rather edit the existing one
   ![error](screenshots/Screenshot6.png)

1. Save and Run
   1. Repeat steps 4 and 5
      ![error](screenshots/Screenshot7.png)

1. Moving Folders and Files
   1. Exit current folder by entering
   ```cd ..```
      1. Enter ```ls``` to see the folder you have just exited
   ![error](screenshots/Screenshot8.png)

   1. Create new folder by entering ```mkdir newfoldername```
   ![error](screenshots/Screenshot9.png)

   1. Move the old folder into the new one by entering ```mv /path/to/source_folder /path/to/destination/```
      Note: since in this example both folders are in the same file, the path is just ```mv oldfoldername newfoldername```
   ![error](screenshots/Screenshot10.png)




## Comments, notes, and examples
## Conclusion
## Troubleshooting
## Hazards Statements
Do not use spaces, -, or * for file names or when using the command rm to remove your file.
## Survey
[![Survey Link](SurveyQR.png)](https://forms.gle/Uyh9GfeSEtA6TSXHA)  
https://forms.gle/Uyh9GfeSEtA6TSXHA
