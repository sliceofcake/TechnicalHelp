# TechnicalHelp  
General Technical Help Write-Up For My Projects  
  
  
  
  
***JavaScript Console Help***  
A modern browser will almost certainly have a tool called a JavaScript Console built into it. This console shows textual output and accepts textual input. It is frequently used by web developers in order to print out debug statement to make sure JavaScript programs running on the page are running correctly. The name of this console may be slightly different. For example, it may be called "Web Console".  
The location of this console can change over the years. New browsers are developed. New versions of existing browsers are constantly released.  
You'll be able to find this console through your browser's menus. For illustrative purposes, here are two example Operating Systems and browsers and how to reach the console on each:  
For one version of Chrome running on Apple OS, it can be found at  
View>Developer>JavaScript Console  
from the top menu bar. The shortcut for it is command+option+I.  
For one version of Firefox running on Windows, it can be found at  
[Menu Icon]>Developer>Web Console  
from the in-window menu bar. The shortcut for it is control+shift+K.  
One you're in the JavaScript Console, you'll likely find a thing text input box at the bottom. You can type things in here. When the textbox has focus and you hit the enter/return key on your keyboard, it should run whatever you have in the box as JavaScript. At the time of writing, Firefox disallows pasting into this textbox until you type in "allow pasting".  
  
  
  
  
***Command-Line Help***  
On an Apple OS, it's an application called "Terminal". On Windows, it's called "Command Prompt". You'll have to demonstrate some Operating System prowess in order to find the application, as it could change between major Operating System releases. At one time, for Apple OS, it was located at /Applications/Utilities/Terminal. At one time, for Windows, it was located at C:\Windows\System32\cmd.exe.  
A command prompt is an application in which you type out a line of text and hit enter to run a "command" on your computer. Based on what you type, your Operating System will take a certain action. Each command is an action that you're telling your Operating System to do. On a basic level, you can use the command-line to move around to various folders, as you normally do every day with the graphical interface. There are three basic commands that you need to know to get around your file system from the command-line.  
  
"what folder am I current looking at?"  
Apple OS : pwd  
Windows : cd  
  
"show me the files in the current folder"  
Apple OS : ls  
Windows : dir  
  
"go to a different folder"  
Apple OS : cd name_of_folder_here  
Windows : cd name_of_folder_here  
If, for the name, you type in two dots together, "..", then it's a special command meaning to go up/back to the folder that your current folder is inside of. If I'm in the "sliceofcake" folder on my "Desktop", and I issue  
cd ..  
then I'll now be in my "Desktop".  
A single dot for a filename is used to refer to the current folder, and is sometimes used in more advanced cases.  
Assume that uppercase/lowercase ~matters~ everywhere in the command prompt. If you see a folder named "Desktop" and you try to go to it, you'll need to type that first letter as a capital "D" and the rest as lowercase "esktop".  
  
To help you understand the command-line, imagine that every graphical way that you interact with your computer is translated to commands as though they were typed in for you in a command-line. When you get a listing of the contents of a folder, you could imagine that there's actually an ls/dir command being run out there, where you can't see it, and the results are being prettied up for you and put on the screen in an appealing format.  
  
A semicolon between commands is a useful feature to run the commands back-to-back. So if you see something like  
cd ~/Desktop;ls  
for Terminal on an Apple OS, that means to change directory to the Desktop, and then list out all the filenames that can be found there.  