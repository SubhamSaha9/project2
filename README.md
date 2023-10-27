# Project 2

This is second git project using init.
below are the commands to execute.

# steps for remote to local machine

step 1: `git clone [URL]` <br />
step 2: go to the directory <br />
step 3: `git status`<br />
step 4: `git add [file name]` or `git add .` (to add all the file together) <br />
step 5: `git commit -m "enter your message"` (if we need to add only one file then we can skip step3 and we can write <br />&ensp; `git commit -am "add message"` to add and commint at the same time) <br />
step 6: `git push origin main` (if we need to write origin main frequently then we can use this command <br />&ensp;`git push -u origine main` after this command every time we need to push just execute the command `git push`) <br />

# steps for local to remote

step 1: go to the directory where we need git <br />
step 2: `git init` <br />
step 3: `git status`<br />
step 4: `git add .` or `git add filename`<br />
step 5: `git commit -m "message"` (`git commit -am "add message"` also applicable)<br />
step 6: create a repo in github and copy the repo url <br />
step 7: `git remote add origin [URL]` (URL is copied in step5)<br />
step 8: `git remote -v` <br />
step 9: `git branch` <br />
step 10: `git branch -M main` (to rename the branch to main)<br />
step 11: `git push origin main` (`git push -u origine main` also applicable)<br />
