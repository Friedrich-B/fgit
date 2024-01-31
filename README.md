# fgit
A tool to make your git process a little more fancy. There might be hundreds of these tools out there, I don't know. I just wanted to write it on my own.
# prerequisites
You need to install ```gum```. Otherwise this script will not work.
```brew install gum```
# features
This tool currently has the following features:
## create branches
Using ```fgit new``` you can create a new branch. You will be asked for the type of branch e.g. feature or hotfix. Then you'll be asked about your ticket number. Leave it empty if you do not have a ticket. Finally you can enter the actual branch name.
## commit messages
Using ```fgit commit``` you can enter a commit message for your current branch. If the branch was created using fgit and a ticket number was provided, then the ticket number will be used as the prefix for your commit message.
## delete branches
Using ```fgit delete``` you can get a listing of all branches except for master and develop. You can choose as many branches as you want to delete.
## checkout branch
Use ```fgit checkout``` to show all branches from ```git branch``` except for your current branch.
