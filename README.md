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

