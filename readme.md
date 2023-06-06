##Bundle 3
#Exercise 2
´´´bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git checkout -b  ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git add --all

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git commit -m "add  home page content"
[main 0f5c007] add  home page content
 1 file changed, 2 insertions(+), 1 deletion(-)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git log
commit 44ae27db49f9f4e5c1728f6abf2aaa470a2691d5 (HEAD -> ft/home-page-redesign, origin/ft/faq-page, ft/faq-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:47:13 2023 +0200

    BUNDLE3 |Exercise 1 work process

commit b1967a31236067c47b0f95f40f045fdda56a084d
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:28:55 2023 +0200

    Revert "add team page"

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git add home.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git commit -m "add home menus"
[ft/home-page-redesign 5e435a1] add home menus
 1 file changed, 6 insertions(+)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$ ^C

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$     git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 4 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (18/18), 4.46 KiB | 761.00 KiB/s, done.
Total 18 (delta 7), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (7/7), done.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/home-page-redesign
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/home-page-redesign)
$
´´´