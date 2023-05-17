##Bundle2
#Exercise1
´´´bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$ git add service.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$ git commit -m "service.html added"
[ft/bundle-2 74a95eb] service.html added
 1 file changed, 9 insertions(+)
 create mode 100644 service.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$ git push ft/bundle-2
fatal: 'ft/bundle-2' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$     git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 376 bytes | 376.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:´´
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/bundle-2
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/bundle-2)
$
´´´