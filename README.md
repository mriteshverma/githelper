# githelper

<h4>Global git config:</h4>
git config --global user.name "username"
<br>
git config --global user.email "myemail@gmail.com"
<br>
git config --list # Check config list on system

<h4>Clone command:</h4>
Git have 2 sides: Local and remote
<br/>
To copy data from remote git we use clone command
<br>
To copy most easy way is https to clone command
<br>
Copy code to local machine cammand with global config: git clone <http_link.git>
<br>
Project will copy inside the folder in which you run command.

<h4>Status cammand:</h4>
This shows status of repo and also shows current branch
<br>
command is : git status
<br>
<h4>Status have 4 types:</h4>
<h5>untracked</h5>
new file which git don't know the file
<h5>modified</h5>
changes are done in file.
<h5>staged</h5>
Whenever file is "untracked" or "modified" we need to run command for staged:
<br/>
command is: git add . or git add <file>
<h5>unmodified</h5>
nothing is changed in files
<br>
In starting or after commit it shows unmodified. because all code updated on remote.
<h4>Push command:</h4>
This is used to push all the commited changes to remote.
command is: git push origin main # to uploa changes in main branch