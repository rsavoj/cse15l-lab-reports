## Tutorial on how to log into your course specific account ieng6 c for ucsd CSE15L students!
1. Download visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
![Image](DownloadingVS.png)
2. The application interface should resemble the one below 
![Image](openingVS.png)
3. Go to [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php) to access course specific account. To activate the account change the password and wait ~15 minutes.
4. Open a new terminal in VS code using + ` or opening a new terminal from the menu 

5. Enter ssh cs15lwi22zz@ieng6.ucsd.edu replacing the zz with your course specific ID. A password will be prompted. Enter in the one made when the account was activated. When logged in ther terminal should look like the one below.
![Image](login.png)
> **Example Input** $ ssh cs15lwi22ahd@ieng6.ucsd.edu

6. Run Some Commands 
* cd~ 
![Image](cd~.png)


* ls -a
![Image](lsa.png)

* ls -lat 
![Image](lslat.png)

* along with additional commands 

7. Leave the server by typing exit into the command line or pushing Ctrl-d
8. You can use the command scp "fileName" cs15lwi22zz@ieng6.ucsd.edu:~/ To add a file to your home directory on the server. Note you will be asked for a password if you have not implemented a key.
 
> **Example Input** WhereAmI.java cs15lwi22ahd@ieng.ucsd.edu:~/

9. Log into ssh account and use the command ls to check that the file was uploaded. If it was uploaded you can use java and javac commands.
 ![Image](AddFile2.png)
 10. One can create a key to avoid using a passcode every time they


![Image](ScreenShotToAddLabSession.png)

