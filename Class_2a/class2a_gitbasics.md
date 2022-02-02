Class 2 - git basics

git is the version control system eveybody is using today. It is a beautiful system, not only for not losing work, but also for collaboration and sharing.



SSH access

To make it easier to read and write to your repo, it's useful to add a key without a password, so you don't have to type each time.

Create local SSH key

Add to your github settings

Make sure you ONLY ADD THE PUBLIC KEY (~/.ssh/id_rsa.pub)
Workflow

Create new repo
Download and install Fork-UI or use CLI
Clone the repo
Create a README.md file in the folder
Add new file to stage
Commit file with a message
Push change to master/main repo
When working with others, pull changes before you start working, and before you push your changes.

If you make a mess

If you had a nice working commit when you started working, but now nothing works -> Throw away all staged and unstaged changes, forget everything on your current local branch and make it exactly the same as origin/master.

git reset --hard origin/master
General advice

Don't commit large files