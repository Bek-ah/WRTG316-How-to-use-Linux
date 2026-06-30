# How to use the Linux Terminal
This instruction guide will help you learn some command-line basics!

Knowing how to use the command line is a powerful skill. It provides you with fast, efficient file management that you can use in complicated tasks, like moving thousands of specific files at once from one folder to another. You can also log into another computer remotely, or install, run and edit software. And it works on almost any computer!

## Requirements
<body>
   <img align="right" src="https://github.com/user-attachments/assets/68d50096-b81d-4940-9117-503db9d2982a" style="height: 6em; vertical-align: middle" />
   A charged laptop with a Linux Terminal open<br/>
   See <i>Troubleshooting</i> for computers without Linux Terminal support
</body>

## Steps
1. Make the folder
   1. Type ```mkdir foldername``` then press ```enter```
   1. Type ```ls``` then press ```enter``` <br>
   <details>
   <summary>What does ls do?</summary>
   ls lets you see the directory. You can use this command at any time to ensure that files and folders are created
   </details>
   
   ![error](screenshots/Screenshot1.png)
1. Move into folder
   1. Type ```cd foldername``` (it should now show the folder name next to the username) <br>
   <details>
   <summary>How to return to the parent folder?</summary>
   To return to the parent folder, in this case the previous layer use ```cd ..```
   </details>

   ![error](screenshots/Screenshot2.png)

1. Create and Move Into a File
   1. Type ```nano filename.txt``` and press enter.
   1. Type the following text: ```print("Hello, World!")``` <br>
   <summary>What does nano do?</summary>
   The command nano creates the file, and opens it automatically. If a file with that name has already been created, it opens the file.
   </details>

   ![error](screenshots/Screenshot3.png)

1. Save and Exit
   1. Save with Write Out by pressing ```ctrl``` then ```O``` (not 0) <br>
      Press enter when terminal asks if you want to save it to keep the file name
   1. Exit by pressing ctrl then X

       ![error](screenshots/Screenshot4.png)

1. Run the Code
   1. Type the command ```python filename``` and press enter <br>
   <summary>How to find the file name?</summary>
   If you are concerned if your file saved, or forgot the name, type ```ls```
   </details>
   
   ![error](screenshots/Screenshot5.png)

   If the file didn't run this may be a good spot to link to troubleshooting, teaching them how to edit the file. Or! Optional steps below: editing the file
   
1. Editing the File to Create Your Own Message
   1. Enter ```nano filename.txt```. Use the arrow keys to navigate into the end of the phrase “Hello World”. Delete Hello World, and then type any message of your choice <br>
   <summary>What does nano do?</summary>
   The command nano creates the file, and opens it automatically. Since a file with that name has already been created, it opens the file.
   </details>
   
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

   1. Move the old folder into the new one by entering ```mv /path/to/source_folder /path/to/destination/``` <br>
      Since in this example both folders are in the same file, the path is just ```mv oldfoldername newfoldername```
      
      ![error](screenshots/Screenshot10.png)




## Conclusion
You have now learned basic file manipulation in Linux! <br>
There is a lot to explore, and if you would like to learn more then you can try playing this game: [linuxsurvival.com](https://linuxsurvival.com/)
## Troubleshooting
writing316 username and password for cylabacademy

If you do not have a linux terminal on your computer, you can also go to this website: [cylabacademy](https://learn.cylabacademy.org/) <br>
Once you are logged in you can click the ```>_``` icon in the top right.

"The webshell is intended only for solving CyLab Security Academy
 challenges. Any other usage is a violation of our terms and conditions."
python filename doesn't work

## Caution
Do not use spaces, -, or * for file names or when using the command ```rm``` to remove your file.
## Survey
[![Survey Link](SurveyQR.png)](https://forms.gle/Uyh9GfeSEtA6TSXHA)  
https://forms.gle/Uyh9GfeSEtA6TSXHA
