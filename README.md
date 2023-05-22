# GIT Exercise

## Bundle 1 
### Exercise 1

```bash 

H S Sergio@EngDavidprobook MINGW64 ~/Desktop (master)
$ mkdir GIT_Exercise

H S Sergio@EngDavidprobook MINGW64 ~/Desktop (master)
$ cd

H S Sergio@EngDavidprobook MINGW64 ~
$ cd D
DATA visualization/ Doc/                downloadtemp/
DLLs/               Documents/
Desktop/            Downloads/

H S Sergio@EngDavidprobook MINGW64 ~
$ cd Desktop/

H S Sergio@EngDavidprobook MINGW64 ~/Desktop (master)
$ cd GIT_Exercise

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ ls

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ touch README.md index.html style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ ls
README.md  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory
  (commit or discard the untracked or modified content in submodules)
        modified:   ../FLEX Box, GRID/grid (untracked content)
        deleted:    ../Git_Exercise/Git_Exercise
        modified:   ../Git_Exercise/index.html
        modified:   ../Git_Exercise/style.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../3D Objects - Shortcut.lnk
        ../CONTACT US.url
        ../CURRICULUM VITAE abc and application letter.docx
        ../CURRICULUM VITAE abc.docx
        ../CURRICULUM VITAE.docx
        ../Deborah CURRICULUM VITAE.docx
        ../Discord.lnk
        ../Diue merci cv.docx
        ../Edx Harvard/
        ../IT MANA CERTIFICATE.jpg
        ../Internet Download Manager.lnk
        ../L4 NET.pptx - Microsoft PowerPoint Online.lnk
        ../Opera Browser.lnk
        ../PotPlayer.lnk
        ../ScreenRec.lnk
        ../Tech CV.docx
        ../The Room town hall/
        ../YouTube.lnk
        ../consolidated/
        ../consolidated1/
        ../data base/
        ../desktop.ini
        ../django-income-expense-website/
        ../if-else.c
        ../javascript/
        ../learn html/
        ../mcsfp douments.pdf/
        ../new/
        ../programs.c/
        ../project/
        ../python work/
        ../web project-html tutor/
        ../~$BOQ itageretse.xlsx
        ../~$LLEGE OF SCIENCE AND TECHNOLOGY.docx
        ../~$PRESENTATION (1).pptm
        ../~$RRICULUM VITAE abc and application letter.docx
        ../~$RRICULUM VITAE.docx
        ../~$anslated from portigal.docx
        ../~$ar Scholarship Committee.docx
        ../~$borah CURRICULUM VITAE.docx
        ../~$commendation letter 17th February 2023.docx
        ../~$eated ind H S Serge.docx
        ../~$ech CV.docx
        ../~$fsp application letter.docx
        ../~$iko no gufasha urubyiruko.docx
        ../~$nal assays.docx
        ../~$tters ms.docx
        ../~$umba rero yo kumenya never again Rwanda icyo aricyo.docx
        ../~$vised research proposal.doc
        ../~WRL0004.tmp
        ../~WRL0200.tmp
        ../~WRL0812.tmp

no changes added to commit (use "git add" and/or "git commit -a")

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git init
Initialized empty Git repository in C:/Users/H S Sergio/Desktop/GIT_Ext/

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git commit -m "first commit on Git Exercises Bundle 1 Exercise 1"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git commit -m "first commit on Git Exercises Bundle 1 Exercise 1"
[master (root-commit) b2f85fe] first commit on Git Exercises Bundle 1
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 index.html
 create mode 100644 style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git remote add origin https://github.com/DidierShemaGatete/Gym-Git-Elutions..git

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git push --set-upstream origin master

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 269 bytes | 269.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..gi
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (master)
$ git checkout -b dev
Switched to a new branch 'dev'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (test)
$ git checkout dev
Switched to branch 'dev'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git branch -d test
Deleted branch test (was b2f85fe).
```
### Exercise 2

```bash
S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ code .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ touch home.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash save
No local changes to save

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash save
Saved working directory and index state WIP on dev: b2f85fe first commExercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ touch about

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ mv touch touch.html
mv: cannot stat 'touch': No such file or directory

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  about  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ touch about.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  about  about.html  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ rm about

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  about.html  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash save
Saved working directory and index state WIP on dev: b2f85fe first commExercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1
stash@{1}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  index.html  style.css

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ touch team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git add team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ls
README.md  index.html  style.css  team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash save
Saved working directory and index state WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ stash list
bash: stash: command not found

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1
stash@{1}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1
stash@{2}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash pop ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (43e2fe229def9b2eef01707541fca73ffbab46ff)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1
stash@{1}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash pop ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (e10fbf55acd9ecacd2d3a7973384159d7668cb2d)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git commit -m 'stash home and about page '
[dev 4190cce] stash home and about page
 2 files changed, 26 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 600 bytes | 300.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions./pull/new/dev
remote:
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 * [new branch]      dev -> dev

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: b2f85fe first commit on Git Exercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git stash pop stash@{0}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (c287b45a5466c01535726617fe881a6c6a29e63d)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git reset --hard team.html
fatal: Cannot do hard reset with paths.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git reset --hard
HEAD is now at 4190cce stash home and about page

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)
$ git status
On branch dev
nothing to commit, working tree clean

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (dev)

```
## bundle 2 
### Exercise 1
```bash
H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ touch services.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git commit -m "creation and modifocation of service page"
[ft/bundle-2 3df3548] creation and modifocation of service page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 495 bytes | 495.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions./pull/new/ft/bundle-2
remote:
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch -m master main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch
  dev
* ft/bundle-2
  main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch -m main master

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch
  dev
* ft/bundle-2
  master

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch
  dev
* ft/bundle-2
  master

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git branch -m master main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/master'.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git pull
From https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.
 * [new branch]      main       -> origin/main
Your configuration specifies to merge with the ref 'refs/heads/master'
from the remote, but no such ref was fetched.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git branch --set-upstream-to=origin/main
branch 'main' set up to track 'origin/main'.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git pull
Already up to date.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ lgit branch
bash: lgit: command not found

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git branch
  dev
  ft/bundle-2
* main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git branch -d ft/bundle-2
error: The branch 'ft/bundle-2' is not fully merged.
If you are sure you want to delete it, run 'git branch -D ft/bundle-2'.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git branch
  dev
  ft/bundle-2
* main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git restore --staged services.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git commit -m "changes in services page"
[main 08fb554] changes in services page
 1 file changed, 14 insertions(+)
 create mode 100644 services.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git push
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git pull
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 3.97 KiB | 13.00 KiB/s, done.
From https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.
   b2f85fe..743778d  main       -> origin/main
Merge made by the 'ort' strategy.
 README.md | 388 +++++++++++++++++++++++++++++++++++++++++++++++++++++
 ```
 
## bundle 2

### Exercise 2

```bash 
 git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git diff

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git diff

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git diff main
diff --git a/services.html b/services.html
index 10c0fab..2333b83 100644
--- a/services.html
+++ b/services.html
@@ -7,8 +7,9 @@
     <title>services page</title>
 </head>
 <body>
-    <h2> our services online now and everywhere</h2>
-        <p>the new services we offer and on good price</p>
+    <h2> our services online now</h2>
+        <p>the new services we offer</p>
+        <p>we offer these kind of services</p>

 </body>
 </html>
\ No newline at end of file

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git merge
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git switch main
fatal: cannot switch branch while merging
Consider "git merge --quit" or "git worktree add".

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git merge ft/service-redesign
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git diff

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git diff main
diff --git a/services.html b/services.html
index 10c0fab..9af325e 100644
--- a/services.html
+++ b/services.html
@@ -7,8 +7,9 @@
     <title>services page</title>
 </head>
 <body>
-    <h2> our services online now and everywhere</h2>
-        <p>the new services we offer and on good price</p>

+    <h2> our services online now</h2>
+        <p>the new services we offer</p>
+        <p>we offer these kind of services</p>
 </body>
 </html>
\ No newline at end of file

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git status
On branch ft/service-redesign
All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   services.html


H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign|MERGING)
$ git commit -m "resolve merge conflict"
[ft/service-redesign cb781ef] resolve merge conflict

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git status
On branch ft/service-redesign
nothing to commit, working tree clean

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git diff

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git diff main
diff --git a/services.html b/services.html
index 10c0fab..9af325e 100644
--- a/services.html
+++ b/services.html
@@ -7,8 +7,9 @@
     <title>services page</title>
 </head>
 <body>
-    <h2> our services online now and everywhere</h2>
-        <p>the new services we offer and on good price</p>

+    <h2> our services online now</h2>
+        <p>the new services we offer</p>
+        <p>we offer these kind of services</p>
 </body>
 </html>
\ No newline at end of file

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git merge main
Already up to date.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git checkout ^C

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git merge ft/service-redesign
Already up to date.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git push origin
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 666 bytes | 333.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
   0eb6ff1..cb781ef  ft/service-redesign -> ft/service-redesign

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/service-redesign)
$
```

## Bundle 3
### Exercise 1


```bash 

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/team-page)
$ git log
commit 719669546a39d6e13a59c22f0614faba6aefb818 (HEAD -> ft/team-page, origin/ft/team-page)
Merge: 50e295b 321a71c
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Mon May 22 12:19:54 2023 +0300

    deleting services page

commit 50e295bde1ae369305e2a5c3851dbb9d967088de
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:59:16 2023 +0300

    created team page

commit 1aa39746dfb479027d727b55a5123ad3e3d62076
Merge: 2d30dc8 aef25f1
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:56:04 2023 +0300

    Merge branch 'main' into ft/service-redesign

commit 321a71c76b6ae1cfc964b6888c54658d9b48cad4
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:45:59 2023 +0300

    removing services file

commit 556e7c677e6767808c3c9ebeba20b8b0ab7cc202
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 20:49:58 2023 +0300

    new team page

commit aef25f10c1745e140283380a4312422c5608e5d9
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 16:09:18 2023 +0300

    The Gym git Exercise

    Bundle 2 bash commands

commit cb781ef2299a58b0d66d6815f1766a3f16770013 (origin/ft/service-redesign)
Merge: 0eb6ff1 2d30dc8
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:49:55 2023 +0300

    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:18:20 2023 +0300

    inline modification of service page

commit 741c0b735616b4fc674379afcd16c805089ffd5b
Merge: 9985d31 0eb6ff1
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 15:10:50 2023 +0300

    Merge pull request #4 from DidierShemaGatete/ft/service-redesign

    change on services page

commit 0eb6ff1d19230e968c2ba85776e0ebb430fa41ba
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:08:09 2023 +0300

    modification on services page

commit 9985d311f61a0263198b8fa4a0ccc670c8b2e25e
Merge: 0218952 357d631
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 14:58:45 2023 +0300

    Merge pull request #3 from DidierShemaGatete/ft/bundle-2

    html page

commit 357d631b192b8695c1a5e054c9ddbf43d59726d0 (origin/ft/bundle-2, ft/bundle-2)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 14:51:50 2023 +0300

    ceated and modified a service page

commit 021895247b548f0e2f2d503311c0939861035e5c
Merge: 08fb554 743778d
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:33:45 2023 +0300

    Merge branch 'main' of https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.
:
    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:18:20 2023 +0300

    inline modification of service page

commit 741c0b735616b4fc674379afcd16c805089ffd5b
Merge: 9985d31 0eb6ff1
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 15:10:50 2023 +0300

    Merge pull request #4 from DidierShemaGatete/ft/service-redesign

    change on services page

commit 0eb6ff1d19230e968c2ba85776e0ebb430fa41ba
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:08:09 2023 +0300

    modification on services page

commit 9985d311f61a0263198b8fa4a0ccc670c8b2e25e
Merge: 0218952 357d631
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 14:58:45 2023 +0300

    Merge pull request #3 from DidierShemaGatete/ft/bundle-2

    html page

commit 357d631b192b8695c1a5e054c9ddbf43d59726d0 (origin/ft/bundle-2, ft/bundle-2)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 14:51:50 2023 +0300

    ceated and modified a service page

commit 021895247b548f0e2f2d503311c0939861035e5c
Merge: 08fb554 743778d
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:33:45 2023 +0300

    Merge branch 'main' of https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.

commit 08fb55473abaf8a7449b4019e6a36b970ff51b29
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:21:48 2023 +0300
:
    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:18:20 2023 +0300

    inline modification of service page

commit 741c0b735616b4fc674379afcd16c805089ffd5b
Merge: 9985d31 0eb6ff1
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 15:10:50 2023 +0300

    Merge pull request #4 from DidierShemaGatete/ft/service-redesign

    change on services page

commit 0eb6ff1d19230e968c2ba85776e0ebb430fa41ba
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:08:09 2023 +0300

    modification on services page

commit 9985d311f61a0263198b8fa4a0ccc670c8b2e25e
Merge: 0218952 357d631
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 14:58:45 2023 +0300

    Merge pull request #3 from DidierShemaGatete/ft/bundle-2

    html page

commit 357d631b192b8695c1a5e054c9ddbf43d59726d0 (origin/ft/bundle-2, ft/bundle-2)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 14:51:50 2023 +0300

    ceated and modified a service page

commit 021895247b548f0e2f2d503311c0939861035e5c
Merge: 08fb554 743778d
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:33:45 2023 +0300

    Merge branch 'main' of https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.

commit 08fb55473abaf8a7449b4019e6a36b970ff51b29
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:21:48 2023 +0300

    changes in services page

commit 743778d08030d646cefb1f740921d6eb39481af3
:
    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:18:20 2023 +0300

    inline modification of service page

commit 741c0b735616b4fc674379afcd16c805089ffd5b
Merge: 9985d31 0eb6ff1
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 15:10:50 2023 +0300

    Merge pull request #4 from DidierShemaGatete/ft/service-redesign

    change on services page

commit 0eb6ff1d19230e968c2ba85776e0ebb430fa41ba
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:08:09 2023 +0300

    modification on services page

commit 9985d311f61a0263198b8fa4a0ccc670c8b2e25e
Merge: 0218952 357d631
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 14:58:45 2023 +0300

    Merge pull request #3 from DidierShemaGatete/ft/bundle-2

    html page

commit 357d631b192b8695c1a5e054c9ddbf43d59726d0 (origin/ft/bundle-2, ft/bundle-2)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 14:51:50 2023 +0300

    ceated and modified a service page

commit 021895247b548f0e2f2d503311c0939861035e5c
Merge: 08fb554 743778d
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:33:45 2023 +0300

    Merge branch 'main' of https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.

commit 08fb55473abaf8a7449b4019e6a36b970ff51b29
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:21:48 2023 +0300
:
commit 719669546a39d6e13a59c22f0614faba6aefb818 (HEAD -> ft/team-page, origin/ft/team-page)
Merge: 50e295b 321a71c
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Mon May 22 12:19:54 2023 +0300

    deleting services page

commit 50e295bde1ae369305e2a5c3851dbb9d967088de
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:59:16 2023 +0300

    created team page

commit 1aa39746dfb479027d727b55a5123ad3e3d62076
Merge: 2d30dc8 aef25f1
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:56:04 2023 +0300

    Merge branch 'main' into ft/service-redesign

commit 321a71c76b6ae1cfc964b6888c54658d9b48cad4
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:45:59 2023 +0300

    removing services file

commit 556e7c677e6767808c3c9ebeba20b8b0ab7cc202
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 20:49:58 2023 +0300

    new team page

commit aef25f10c1745e140283380a4312422c5608e5d9
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 16:09:18 2023 +0300

    The Gym git Exercise

    Bundle 2 bash commands

commit cb781ef2299a58b0d66d6815f1766a3f16770013 (origin/ft/service-redesign)
Merge: 0eb6ff1 2d30dc8
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:49:55 2023 +0300

    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
:
commit 719669546a39d6e13a59c22f0614faba6aefb818 (HEAD -> ft/team-page, origin/ft/team-page)
Merge: 50e295b 321a71c
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Mon May 22 12:19:54 2023 +0300

    deleting services page

commit 50e295bde1ae369305e2a5c3851dbb9d967088de
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:59:16 2023 +0300

    created team page

commit 1aa39746dfb479027d727b55a5123ad3e3d62076
Merge: 2d30dc8 aef25f1
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:56:04 2023 +0300

    Merge branch 'main' into ft/service-redesign

commit 321a71c76b6ae1cfc964b6888c54658d9b48cad4
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Sat May 20 16:45:59 2023 +0300

    removing services file

commit 556e7c677e6767808c3c9ebeba20b8b0ab7cc202
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 20:49:58 2023 +0300

    new team page

commit aef25f10c1745e140283380a4312422c5608e5d9
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 16:09:18 2023 +0300

    The Gym git Exercise

    Bundle 2 bash commands

commit cb781ef2299a58b0d66d6815f1766a3f16770013 (origin/ft/service-redesign)
Merge: 0eb6ff1 2d30dc8
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:49:55 2023 +0300

    resolve merge conflict

commit 2d30dc88b500f496383ae07190c83ee4439b03a2
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:18:20 2023 +0300

    inline modification of service page

commit 741c0b735616b4fc674379afcd16c805089ffd5b
Merge: 9985d31 0eb6ff1
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 15:10:50 2023 +0300

    Merge pull request #4 from DidierShemaGatete/ft/service-redesign

    change on services page

commit 0eb6ff1d19230e968c2ba85776e0ebb430fa41ba
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 15:08:09 2023 +0300

    modification on services page

commit 9985d311f61a0263198b8fa4a0ccc670c8b2e25e
Merge: 0218952 357d631
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 14:58:45 2023 +0300

    Merge pull request #3 from DidierShemaGatete/ft/bundle-2

    html page

commit 357d631b192b8695c1a5e054c9ddbf43d59726d0 (origin/ft/bundle-2, ft/bundle-2)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 14:51:50 2023 +0300

    ceated and modified a service page

commit 021895247b548f0e2f2d503311c0939861035e5c
Merge: 08fb554 743778d
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:33:45 2023 +0300

    Merge branch 'main' of https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.

commit 08fb55473abaf8a7449b4019e6a36b970ff51b29
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 11:21:48 2023 +0300

    changes in services page

commit 743778d08030d646cefb1f740921d6eb39481af3
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 09:58:18 2023 +0300

    Git Exercise

    bash preview of The Gym Git Exercise Solutions Bundle 1 Exercise 2

commit e57acbc26b7bad641acf65c3c207f8a0493c7b8b
Author: DidierShemaGatete <122377873+DidierShemaGatete@users.noreply.github.com>
Date:   Tue May 16 09:51:48 2023 +0300

    Update README.md

    Terminal preview of The Gym Git Exercise Solutions Bundle 1 Exercise 1

commit b2f85fe8cc0b79cf7431449f9ef5af02e627d000 (origin/master)
Author: DidierShemaGatete <didiershemagate01@gmail.com>
Date:   Tue May 16 06:54:38 2023 +0300

    first commit on Git Exercises Bundle 1 Exercise 1

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git cherry-pic 50e295bde1ae369305e2a5c3851dbb9d967088de
git: 'cherry-pic' is not a git command. See 'git --help'.

The most similar command is
        cherry-pick

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git cherrypic 50e295bde1ae369305e2a5c3851dbb9d967088de
git: 'cherrypic' is not a git command. See 'git --help'.

The most similar command is
        cherry-pick

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git cherry-pick 50e295bde1ae369305e2a5c3851dbb9d967088de
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'
On branch ft/contact-page
You are currently cherry-picking commit 50e295b.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

nothing to commit, working tree clean

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page|CHERRY-PICKING)
$ git commit --allow-empty
[ft/contact-page 120da21] created team page
 Date: Sat May 20 16:59:16 2023 +0300

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ code .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ ls
README.md  contact.html  index.html  services.html  style.css  team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git add .; git commit -m "changes in contact page"
[ft/contact-page 43211f1] changes in contact page
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 641 bytes | 160.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions./pull/new/ft/contact-page
remote:
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 * [new branch]      ft/contact-page -> ft/contact-page

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git commit -am "added faq page"
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git commit -am "added faq page"
[ft/faq-page cb61805] added faq page
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git push ft/faq-page
fatal: 'ft/faq-page' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions./pull/new/ft/faq-page
remote:
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 * [new branch]      ft/faq-page -> ft/faq-page

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git revert 50e295bde1ae369305e2a5c3851dbb9d967088de
[ft/faq-page 7feaaaa] Revert "created team page"
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 280 bytes | 5.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
   cb61805..7feaaaa  ft/faq-page -> ft/faq-page
```

### Exercise 2

```bash 

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/faq-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ ls
README.md  index.html  services.html  style.css  team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git commit -m "changes on the services page"
[main 6f7fbfc] changes on the services page
 1 file changed, 11 insertions(+)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git push
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 3.15 KiB | 17.00 KiB/s, done.
From https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions.
   7e9c446..6719a64  main       -> origin/main
Merge made by the 'ort' strategy.
 README.md | 570 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 570 insertions(+)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 740 bytes | 740.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
   6719a64..847dfe4  main -> main

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (main)
$ git switch ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ git rebase main
CONFLICT (modify/delete): team.html deleted in 7feaaaa (Revert "created team page") and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not apply 7feaaaa... Revert "created team page"
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 7feaaaa... Revert "created team page"

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign|REBASE 4/4)
$ git rebase --continue
team.html: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign|REBASE 4/4)
$ git rebase main
Current branch ft/home-page-redesign is up to date.

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ ls
README.md  contact.html  faq.html  home.html  index.html  services.html  style.css  team.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
Your branch is up to date with 'origin/ft/home-page-redesign'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ git add .

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ git commit -m "changes in the home page"
[ft/home-page-redesign 5b6cfb3] changes in the home page
 1 file changed, 10 insertions(+)
 create mode 100644 home.html

H S Sergio@EngDavidprobook MINGW64 ~/Desktop/GIT_Exercise (ft/home-page-redesign)
$ git push
fEnumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 451 bytes | 451.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DidierShemaGatete/Gym-Git-Exercise-Solutions..git
   68716d2..5b6cfb3  ft/home-page-redesign -> ft/home-page-redesign
```




