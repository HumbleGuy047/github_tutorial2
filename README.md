# Demo 2
1. Create new repository:
    >> git init
    >> Initialized empty Git repository in D:/Workspaces/git/demo-repo2/.git/
2. Create remote repo and link it to local machine
    >> git remote add origin https://github.com/HumbleGuy047/github_tutorial2.git
3. Check remote repo associated
    >> git remote -v
origin  https://github.com/HumbleGuy047/github_tutorial2.git (fetch)
origin  https://github.com/HumbleGuy047/github_tutorial2.git (push)
4. Branches
    a) git branch -> show all branches
    b) git checkout branch_name -> switch to which branch
    c) git checkout -b branch_name -> create branch
    d) git diff branch_name-> compare difference between branches
    e) git merge branch_name -> merge branches, but conventionally push branch and then make pull request ti pull branch into the master branch 
8. Shortcuts
    a) Push
        >> git push origin master
        To avoid writing origin master, you set a upstream, push to where by default
        >> git push -u origin master
        subsequent push can just be
        >> git push


