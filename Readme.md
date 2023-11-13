# Github Steps

1. Setup RSA Key
   -  ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
   -  Download and Install Git
   -  Go to the .ssh folder in users/yourcomputername
   -  open the .pub file in note pad or vs code or any editor
   -  Go to github -> settings (Top right corner) -> ssh and GPG keys -> add new ssh key
   -  Remove the extra space when you paste your rsa key
   -  save the rsa key to github.
2. Make a Folder named -> testing-hello
   1. Make a PUBLIC repository in github named testing-hello
   2. make a text file in the folder (testing-hello) in your computer name hello.txt and add some text.
   3. Initialise the a git project in the testing-folder -> git init
   4. Add all the files to git -> git add .
   5. Commit all the code to git -> git commit -m "Your message"
   6. -m stands for message
   7. Make the main branch -> git branch -M main (-M sets the main branch as default), (Only done for the first time, after the first time you have to skip this.)
   8. Add the remote to link your local repo to github -> git remote add origin [given by github] (Only done for the first time, after the first time you have to skip this.)
   9. Push the code to github -> git push -u origin main

- note -> step 2 should be done in the testing-hello folder in your local computer.
- Skip 2.7 and 2.8 after the first time.
