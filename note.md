For each feature
In the shell
git switch -c branchname # create a new branch
git switch branchname # switch branch
git add file # add a file to the stage
git status # check, if everything is ok
git commit -m "message" # commit your changes
git push -u origin branchname # push to GitHub
continue on GitHub
On GitHub
- Create a pull request for that branch (to merge it into main)
- Send a link to the changed files to your team
- Get a code review
- Optional: implement changes, push again to update pull request
- Merge and delete the branch on GitHub
- Continue in the shell