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
   - Make a PUBLIC repository in github named testing-hello
   - make a text file in the folder (testing-hello) in your computer name hello.txt and add some text.
   - Initialise the a git project in the testing-folder -> git init
   - Add all the files to git -> git add .
   - Commit all the code to git -> git commit -m "Your message".
   - -m stands for message
   - Make the main branch -> git branch -M main (-M sets the main branch as default), (Only done for the first time, after the first time you have to skip this.)
   - Add the remote to link your local repo to github -> git remote add origin git@github.com:College-Lasalle-Jerry/testing-repo.git (Only done for the first time, after the first time you have to skip this.)
   - Push the code to github -> git push -u origin main

- note -> step 2 should be done in the testing-hello folder in your local computer.