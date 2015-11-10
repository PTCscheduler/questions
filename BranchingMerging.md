#Branching and Merging

###Here is the step by step process on branching and merging branches. If you have questions on the steps I can try and clearify them. I also listed the links to the videos at the bottom.
####-Cam

1. git checkout -b nameOfBranch (you name it) =     -b is what creates the new branch.
    1. can move between branches by using = git checkout master or git checkout banana or whatever the branch name is.
    2. should push new branch right away before editing. You push the same was as the master except use the name of the branch you are on.
2. If you want to checkout someone else’s branch. 
    1. git fetch github
    2. git checkout nameOfBranchYouWant
3. You can branch a branch by following step 1.
4. When ready to merge:
    1. go to github create a pull request
        1. reminder this is just where others can look at the code you have written and write comments before you merge with the master branch
    2. Want to make sure your master is up to date
        1. git checkout master, git pull github master
    3. merge master branch to your branch
        1. switch back to your branch and then, git merge master
    4. fix any conflicts - view them using git status. After fixing them git add ., git commit on your branch.
    5. after conflicts are fixed, go to master branch and merge branch. git checkout master, git merge branchName, git push github master.
    6. YOUR DONE!

Here are links to the two videos if you want to see Sumeet do it on a project.

https://vimeo.com/channels/ocsdrakon/134749996

https://vimeo.com/channels/ocsdrakon/134749994
