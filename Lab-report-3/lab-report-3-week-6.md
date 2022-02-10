# Lab 3: Streamlining ssh Configuration
## ssh/config file
![image](SSHConfigFile.png)
I created the config file by entering the `\.ssh` directory on my local computer. I created the config file. Then used the `vim config` command to edit the file.I pressed the `i` key to allow insertions. I coppied and pasted the code from Lab report 5. Then changed the email to the correct course specific email. After that I exited the insert mode using esc. The pressed typed `:wq`.

## ssh command being used 
![image](sshLoginShortCut.png)
Instead of typing `ssh cs15lwi22ahd@ieng6.ucsd.edu` we can type `ssh ieng6`, (replacing ieng6 with whatever Host the user chose).The number of keystrokes is reduced by 22 strokes.
## scp command 
![image](scpcommand.png)

The key can also be used to copy files to the ieng6 account. The command `scp fileName ieng6:~\` can be used to copy files. This is much shorter than the command `scp fileName cs15lwi22ahd@ieng6.ucsd.edu:~\` The number of keystrokes is reduced by 22 strokes.

![image](fileAdded.png)

This image shows the file added to the ieng6 account.