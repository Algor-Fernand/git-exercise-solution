#Git Exercise Projects

This project will be used for a series of git exercises.
## BUNDLE1
## EXERCISE 1
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
´´´
## Exercise 2
´´´bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git add home.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash
Saved working directory and index state WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git add about.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash
Saved working directory and index state WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash list
stash@{0}: WIP on dev: 51b8605 init project
stash@{1}: WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git add team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash
Saved working directory and index state WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash list
stash@{0}: WIP on dev: 51b8605 init project
stash@{1}: WIP on dev: 51b8605 init project
stash@{2}: WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (83ea12bfaa12c5660d2347051a3c43f42d12b35b)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (89a22adf1f7fe27d08719b060735e93cfdc5fcab)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 431 bytes | 143.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Algor-Fernand/git-exercise-solution.git
   786fec1..bade3d7  dev -> dev

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash list
stash@{0}: WIP on dev: 51b8605 init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (406e3bde1a58ae530d8af4e773b50f32e08a4bcc)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git reset --hard
HEAD is now at bade3d7 html pages added

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$
´´´