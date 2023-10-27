# Project 2

This is second git project using init.
below are the commands to execute.

# steps for remote to local machine

step1: git clone [URL]
step2: go to the directory
step3: git add [file name]/ .(to add all the file together)
step4: git commit -m "enter your message". [if we need to add only one file then we can skip step3 and we can write `git commit -am "add message"` to add and commint at the same time]
step5: git push origin main [if we need to write origin main frequently then we can use this command `git push -u origine main` after this command every time we need to push just execute the command `git push`]

# steps for local to remote

step1: go to the directory where we need git
step2: git init
step3: git add .
step4: git commit -m "message" [`git commit -am "add message"` also applicable]
step5: create a repo in github and copy the repo url
step6: git remote add origin [URL] // copied in step5
step7: git remote -v
step8: git branch
step9: git branch -M main (to rename the branch to main)
step10: git push origin main [`git push -u origine main` also applicable]
