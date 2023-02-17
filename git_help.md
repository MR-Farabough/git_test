# Commands related to a remote repository
> git clone {SSH URL} (copy to local machine)
> git push | git push origin main (push to GitHub)
# Commands related to the workflow
> git add . (adds all files in current working directory to staging)
> git commit -m "{descriptive message of edits}" (-m for message)
# Commands related to checking status or log
> git status (check status of staging)
> git log (check the commit log)
# The basic git syntax is
program | action | destination
# EX
git add .
git | add | .
# EX_2
git commit -m "message"
git | commit -m | "message"
# git best practices
>Atomic commits
Changes related to only one feature or task of your program 
#ATTENTION
> If you use `git commit` rather than `git commit -m` revist
https://www.theodinproject.com/lessons/foundations-git-basics
