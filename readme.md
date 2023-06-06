##Bundle 3
#Exercise 1
´´´bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git status
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git add team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git commit -m "add team page"
[ft/team-page dff7b23] add team page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$     git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 273 bytes | 273.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/team-page
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git log
commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit b483d1bd87ceb7731fa87ecec32c318863854aa4 (origin/ft/service-redesign, ft/service-redesign)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:36:22 2023 +0200

    read me file with the work process

commit 3de9fbdc620a611b3d7e939a01c261c859be3d4d

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f1~
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1~'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f1
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git log
commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit b483d1bd87ceb7731fa87ecec32c318863854aa4 (origin/ft/service-redesign, ft/service-redesign)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:36:22 2023 +0200

    read me file with the work process

commit 3de9fbdc620a611b3d7e939a01c261c859be3d4d
Merge: 5966d42 4f679af
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:22:37 2023 +0200

    Merge branch 'main' into ft/service-redesign

commit 4f679af1380a73b903df5149cceafd7d70b9b57e (origin/main, main, ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:05:06 2023 +0200

    add old services

commit 5966d42b598b00c3d0b5a5001486e3a8b28a734b
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 11:42:50 2023 +0200
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:05:06 2023 +0200

    add old services

commit 5966d42b598b00c3d0b5a5001486e3a8b28a734b
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 11:42:50 2023 +0200

    add new services

...skipping...
commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit b483d1bd87ceb7731fa87ecec32c318863854aa4 (origin/ft/service-redesign, ft/service-redesign)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:36:22 2023 +0200

commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit b483d1bd87ceb7731fa87ecec32c318863854aa4 (origin/ft/service-redesign, ft/service-redesign)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:36:22 2023 +0200

    read me file with the work process

commit 3de9fbdc620a611b3d7e939a01c261c859be3d4d
Merge: 5966d42 4f679af
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:22:37 2023 +0200

    Merge branch 'main' into ft/service-redesign

commit 4f679af1380a73b903df5149cceafd7d70b9b57e (origin/main, main, ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:05:06 2023 +0200

    add old services

commit 5966d42b598b00c3d0b5a5001486e3a8b28a734b
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 11:42:50 2023 +0200

    add new services

commit 260cd12c303b6e52866af96d1b99457ae4055375
Merge: f9200a2 df05e75
Author: Algor Fernand <131036952+Algor-Fernand@users.noreply.github.com>
Date:   Wed May 17 22:46:32 2023 +0200

    Merge pull request #1 from Algor-Fernand/ft/bundle-2

    Adding html pages to the project to 'Ft/bundle 2' branch

commit df05e75318383d9fd57022c8b1d535c12bfa8b8a
Merge: 74a95eb f9200a2
Author: Algor Fernand <131036952+Algor-Fernand@users.noreply.github.com>
Date:   Wed May 17 15:36:52 2023 +0200

    Merge branch 'main' into ft/bundle-2

commit 74a95eba0581ae0733363b0d2bbbd4b279b3e11d
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed May 17 14:51:21 2023 +0200

    service.html added

commit c1457c7b7d2c698d83c79b065b781ca326cfe415 (origin/dev, dev)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed May 17 13:04:51 2023 +0200

    readme with step by step solution

commit bade3d7a99aad548a991a4d9ea5ce14c977e63ff
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed May 17 12:50:25 2023 +0200

    html pages added

commit 786fec1f0c0bd2ad1fc244f7af25477e6ee5669d
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed May 17 12:37:15 2023 +0200

    home and about page

commit f9200a2bf84d7a728e5ebba4b7cf3652ea978368
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed May 17 12:26:01 2023 +0200

    remove wrong files added

commit b5bffc8c9208f8d11b8219eeef3a2c47d74e1cdb
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue May 16 19:02:47 2023 +0200

    addiing html home and about  pages

commit 3a1dee7a41579adaef7db62bd95ec7708e942be6
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue May 16 18:43:57 2023 +0200

    main

commit 51b86059ee8851da7c65345e3066a4cf8b27ef8d
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue May 16 17:00:06 2023 +0200

    init project

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f1~
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1~'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f1
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1'
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git fetch ft/team-page
fatal: 'ft/team-page' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git fetch add team page
fatal: 'add' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git fetch "add team page"
fatal: 'add team page' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git log
commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit b483d1bd87ceb7731fa87ecec32c318863854aa4 (origin/ft/service-redesign, ft/service-redesign)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:36:22 2023 +0200

    read me file with the work process

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f1 
fatal: bad revision 'dff7b23560312a1b63b7c2733cda4ebcfa85e99f1'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git cherry-pick dff7b23560312a1b63b7c2733cda4ebcfa85e99f
[ft/contact-page 8c074db] add team page
 Date: Tue Jun 6 12:43:53 2023 +0200
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git log
commit 8c074db8e0c02b18d2827e1ef4e761ef3808cfce (HEAD -> ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:43:53 2023 +0200

    add team page

commit 4f679af1380a73b903df5149cceafd7d70b9b57e (origin/main, main)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 12:05:06 2023 +0200

    add old services

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git status
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git add --all

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git commit -m "add contact page"
[ft/contact-page e59f2c0] add contact page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 contact.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$     git push --set-upstream origin ft/contact-page
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 468 bytes | 156.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/contact-page
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git status
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git add --all

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git commit -m "add FAQ page"
[ft/faq-page 115672d] add FAQ page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 faq.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git push 
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$     git push --set-upstream origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise-solution/pull/new/ft/faq-page
remote:
To https://github.com/Algor-Fernand/git-exercise-solution.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git log
commit 115672df4cf1148b6345eded30df33d05edb0726 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:22:36 2023 +0200


Revert "add team page"

    add FAQ page

commit e59f2c0eb73a5a04f5252306cf2e294653f6f36e (origin/ft/contact-page, ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:14:55 2023 +0200

    add contact page

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git revert dff7b23560312a1b63b7c2733cda4ebcfa85e99f
[ft/faq-page b1967a3] Revert "add team page"
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git log
commit b1967a31236067c47b0f95f40f045fdda56a084d (HEAD -> ft/faq-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:28:55 2023 +0200

    Revert "add team page"

    This reverts commit dff7b23560312a1b63b7c2733cda4ebcfa85e99f.

commit 115672df4cf1148b6345eded30df33d05edb0726 (origin/ft/faq-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jun 6 13:22:36 2023 +0200

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 274 bytes | 274.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Algor-Fernand/git-exercise-solution.git
   115672d..b1967a3  ft/faq-page -> ft/faq-page

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Documents/GitHub/git-exercise-solution (ft/faq-page)
$
´´´