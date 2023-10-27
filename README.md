# Project 2

This is second git project using init.
below are the commands to execute.

# steps for remote to local machine

step1: git clone [URL] <br />
step2: go to the directory <br />
step3: git add [file name]/ .(to add all the file together) <br />
step4: git commit -m "enter your message". [if we need to add only one file then we can skip step3 and we can write `git commit -am "add message"` to add and commint at the same time] <br />
step5: git push origin main [if we need to write origin main frequently then we can use this command `git push -u origine main` after this command every time we need to push just execute the command `git push`] <br />

# steps for local to remote

step1: go to the directory where we need git <br />
step2: `git init` <br />
step3: `git add .` or `git add filename`<br />
step4: `git commit -m "message"` [`git commit -am "add message"` also applicable]<br />
step5: create a repo in github and copy the repo url <br />
step6: `git remote add origin [URL]` (URL is copied in step5)<br />
step7: `git remote -v` <br />
step8: git branch
step9: git branch -M main (to rename the branch to main)
step10: git push origin main [`git push -u origine main` also applicable]
