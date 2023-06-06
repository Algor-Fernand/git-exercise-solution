##Bundle 4
#Exercise 2
´´´´bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/footer)
$ git add footer.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/footer)
$ git commit -m "add a footer page"
[ft/footer c2a2247] add a footer page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/footer)
$     git push --set-upstream origin ft/footer
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 274 bytes | 137.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/footer
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/footer)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git merge --squash ft/footer
Updating 8e25831..c2a2247
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git log
commit 8e2583189e6daeda35443a4dc10d55b53ab2a573 (HEAD -> ft/squashing, origin/main, main)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 14:55:39 2023 +0200

    added home icon

commit 0f5c00750d1967ae7d9c5db1d242617efc9a2d8d
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 14:13:41 2023 +0200

    add  home page content

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git commit -m "footer changes squashing"
[ft/squashing e2d1205] footer changes squashing
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git log
commit e2d1205d2e3a5d093d7840f2c0bb01cf819bf7bb (HEAD -> ft/squashing)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 15:29:16 2023 +0200

    footer changes squashing

commit 8e2583189e6daeda35443a4dc10d55b53ab2a573 (origin/main, main)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 14:55:39 2023 +0200

    added home icon

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git push 
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git push --set-upstream origin ft/squashing [201~
fatal: invalid refspec '[201~'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$ git push --set-upstream origin ft/squashing 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 281.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/squashing
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/squashing)
$
´´´´