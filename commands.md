# Git Commands
1. Git Initialization
These commands are for setting up a new Git repository.

mkdir git-for-devops: Creates a new directory called git-for-devops.
cd git-for-devops: Navigates into the git-for-devops directory.
pwd: Prints the current directory’s path.
git init: Initializes an empty Git repository in the current directory.
2. File Operations
These commands manage files within the Git repository.

vim git.txt: Opens or creates a file named git.txt in the Vim text editor.
cat git.txt: Displays the content of the git.txt file.
rm git.txt: Removes the git.txt file from the directory.
git add amit.txt: Stages amit.txt for commit, adding it to the Git index.
git add devops.txt: Stages devops.txt for commit.
git rm --cached amit.txt: Removes amit.txt from the staging area but keeps the file in the working directory.
3. Commit Changes
These commands save your changes to the Git history.

git commit -m "adding amit devops": Commits the changes in the staging area with a message "adding amit devops".
git commit -m "adding virat anushka": Commits the changes with the message "adding virat anushka".
git commit -m "adding february.month january.month": Commits changes related to february.month and january.month.
git commit -m "added new changes to virat": Commits changes made to virat file.
git commit -m "adding rohit radha": Commits changes made to rohit and radha.
4. Git Status and Logs
These commands give you an overview of your repository's status and history.

git status: Shows the current state of the working directory and staging area (modified, added, or removed files).
git log: Displays the commit history of the repository.
git log --oneline: Shows a condensed version of the commit history in a single line per commit.
5. Restoring Files
These commands are used to revert changes to files.

git restore devops.txt: Restores the devops.txt file to its state from the last commit.
git restore virat: Restores the virat file to its state from the last commit.
git restore anushka: Restores the anushka file to its state from the last commit.
git restore january.month: Restores the january.month file to its state from the last commit.
6. Git Branching and Checkout
These commands help you work with Git branches.

git branch: Lists all branches in your repository.
git checkout -b update3.5: Creates a new branch named update3.5 and checks it out.
git checkout master: Switches to the master branch.
git checkout -b update3.6: Creates a new branch update3.6 and checks it out.
git checkout -b from-master: Creates and checks out a new branch from master.
git checkout -b from-pubg: Creates and checks out a new branch from pubg.
git checkout pubg: Switches to the pubg branch.
7. File and Directory Listing
These commands help you view files and directories in your repository.

ls: Lists files in the current directory.
ls -a: Lists all files, including hidden ones (files starting with a dot).
clear: Clears the terminal screen.
8. Git Configurations
These commands set up Git configuration options.

git config --global user.name "CHAUHANAMIT009": Sets your global Git username.
git config --global user.email "chauhanamit3639@gmail.com": Sets your global Git email address.
9. Git File Operations
These commands create files in the repository.

touch amit.txt: Creates an empty file named amit.txt.
touch devops.txt: Creates an empty file named devops.txt.
touch virat: Creates an empty file named virat.
touch anushka: Creates an empty file named anushka.
touch rohit: Creates an empty file named rohit.
touch radha: Creates an empty file named radha.
10. Cleaning up Files
These commands remove files from the repository.

rm virat: Removes the virat file.
rm anushka: Removes the anushka file.
rm rohit: Removes the rohit file.
rm radha: Removes the radha file.
rm january.month: Removes the january.month file.
11. Miscellaneous
Additional miscellaneous commands.

git checkout pubg: Switches to the pubg branch.
git checkout from-master: Switches to the from-master branch.
git branch: Lists branches in your repository.
