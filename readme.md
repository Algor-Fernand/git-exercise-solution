#Git Exercise Projects

This project will be used for a series of git exercises.
#Bundle 1
##Exercise 1
´´´bash
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git init
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.md

PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git add readme.md
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git status
On branch main

Changes to be committed:
        new file:   readme.md

PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git commit -m "init project"
[main (root-commit) 51b8605] init project
 1 file changed, 3 insertions(+)
 create mode 100644 readme.md
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git remote add origin https://github.com/Algor-Fernand/git-exercise-solution.git  
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git status
nothing to commit, working tree clean
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

info: please complete authentication in your browser...
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 287 bytes | 143.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      main -> main
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git checkout -b dev
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/dev
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git checkout -b test
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git push origin test
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/test
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      test -> test
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git checkout dev
Switched to branch 'dev'
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git branch -D test
Deleted branch test (was 51b8605).
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> git push origin --delete test
To https://github.com/Algor-Fernand/git-exercise-solution.git
 - [deleted]         test
PS C:\Users\DOLPHIX ELECTRONICS\OneDrive\Documents\GitHub\git-exercise-solution> 
´´´

