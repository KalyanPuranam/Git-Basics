# Git-Basics
Basics of Git Usage
- Do not switch git branch without Committing your changes. Otherwise, you might Loose all changes made
- Open Git Bash in the folder where the main file (Python or any dev file is located) 
$  = (@Dollar Prompt, which is already in Git Bash terminal) 
$ git status - shows which 'branch' the individual user is working on
$ git add . ("add" + "space" + ".") - To add all files individual been working on in that branch, before committing
$ git status again shows which branch you are on (it is also shown on in the parentheses at the end of line)
		○ Once "add ." is done, you can see all changes to be committed when above "git status" is performed
$ git commit -m "Code for Objective A14"
		○ All the above changes are committed with "commit" command
		○ -m is for a comment, which is mandatory when committing changes (for record keeping purposes)
$ git commit -m "blah blah" (without an "add .") can be executed if there are changes that the User is not willing to Commit at that time
$ git fetch to get the 'updates' done on the file from other parallel Users![image](https://user-images.githubusercontent.com/97129756/148125172-d7fc98ae-63b5-4cd8-93ed-ea614dd011d1.png)
