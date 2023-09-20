# Auto-npm-i-upon-cd
automate npm i (install) and npm t (test) whenever you cd into a new directory! (optionally choose to add a gitignore file)

NOTES: 
This is a script to automate the installation of npm dependencies whenever the user changes the working directory (cd) to a folder containing a package.json file.

Script Features:
- The script should be triggered automatically whenever a user changes directories in a terminal.
- It should check if the new directory contains a package.json file.
- If a package.json file is found, it should run npm install to install the dependencies.

Additional Information:
-  user is using zsh as default shell.
-  user wants to add this automation as a custom function to ~/.zshrc file.


*  STEPS  *

1. Open terminal and type either (I used zshrc):
` nano ~/.bashrc` (for windows its bash)
OR
` nano ~/.zshrc` (mac)

2. Insert: the script provided in the script file in this repo

3. then on keyboard press ` crtl + x ` and then press `Y` and  `enter`

4. source `~/.bashrc` OR `source ~/.zshrc` to reset the terminal to accept your changes


