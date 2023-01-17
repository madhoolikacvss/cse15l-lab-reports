# **Working our way to remote access - CSE 15L**
## **Task 1 -Installing Visual Studio Code (VScode)**
VS code is an IDE (Integrated DevelopmentEnvironment) we eill be using for our class. So evidently, out first task is to install and set up VScode.
Click on the following that will take you to the official VScode website: [VScode website](https://code.visualstudio.com/). Select the most latest version of VScode that suits your OS and install it on to your computer. 
In case you are hesitant to download VScode and other imporant files onto your personal computer, you could use UCSD's lab computers - you'll find them at CSE building.
After it is done, open it up and you'll find a window looking like such: ![VScode window](https://github.com/madhoolikacvss/cse15l-lab-reports/blob/main/VScode%20window.jpg)

**NOTE:**You will not be able to see the Recent files when you install VScode afresh as you have not created any files on it for VScode to display them.

## **Task 2 - Remotely connecting**

For you to connect to the remote server from yoru computer, you'll need to activate your course-specific account.

**Task 2.1** - Actiavting your CSE 15L account

Follow [this link](https://sdacs.ucsd.edu/~icc/index.php) that will take you to UCSD'sIT sercives website, and follow the steps below.
  1. Select the account that startes with 'cs'. It will look something like cs15lfa22zz.
  2. Enter your current password and then enter the new password you'd like the CSE 15L account to have.
  3. Select No for the question - 'Change MyTritonLink password?'
  4. *Instead* of click on 'Check', just press enter on your keyboard.
  5. Wait for about 15 mins for the system to reset your password
  You will know if you have successfully changed your password if you see the following on the website.
  ![After password change window](https://github.com/madhoolikacvss/cse15l-lab-reports/blob/main/After%20password%20reset.jpg)
  
**Task 2.2 - Accessing the account**
Closely follow the steps below to connect to the remote server:

1. Download Git using this [this link](https://gitforwindows.org/)
2. Go onto VScode and type *ctrl + shift + p*
3. Type 'Select Default Profile' onto the search bar and select select Git Bash
4. Open VScode terminal or just press *ctrl + `*
5. Type in ssh cs15lwi23XXX@ieng6.ucsd.edu, but replace'XXX' with your username. 
   For example, if your username is cs15lfa22abc, replace 'XXX' with 'abc'
6. When the computer prompts you for the password, type your password that you recently set, and press *enter*

**NOTE:** If you are having troubles with logging in, and your terminal looks something similar to below, please wait for a while longer and retry
          (UCSD's servers might be in the process of resetting your passsword). Make sure you are typing in the correct password.
          ![Login issue](https://github.com/madhoolikacvss/cse15l-lab-reports/blob/main/login%20issue.jpg)

7. After successfully logging in, you terminal will look something like below:
![After successful login](https://github.com/madhoolikacvss/cse15l-lab-reports/blob/main/After%20login.jpg)
8. Try out some commands to see how they work differently int he clinet computer and the remote server.
   eg: cd ~, cd, ls -lat, ls -a


