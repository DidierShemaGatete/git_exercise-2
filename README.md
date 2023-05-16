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
