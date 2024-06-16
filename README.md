
Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo (master)
$ mkdir demo

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo (master)
$ cd demo

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git init
Initialized empty Git repository in C:/Users/Lindelani/demo/demo/demo/.git/

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.txt

nothing added to commit but untracked files present (use "git add" to track)

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git add test.txt

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   test.txt


Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git commit -m "this is my first commit"
[master (root-commit) 0e2a8c4] this is my first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.txt

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git branch
* master

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git remote add origin https://github.com/lindelaani/demo.git

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 227 bytes | 56.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lindelaani/demo.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ vi README.md


[1]+  Stopped                 vi README.md

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ vi README.md

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.swp
        README.md

nothing added to commit but untracked files present (use "git add" to track)

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git fetch
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 983 bytes | 3.00 KiB/s, done.
From https://github.com/lindelaani/demo
   0e2a8c4..86a79ea  master     -> origin/master

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git commit -m "my second commit"
[master 5a2f7f9] my second commit
 2 files changed, 1 insertion(+)
 create mode 100644 .README.md.swp
 create mode 100644 README.md

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git fetch

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git pull
Merge made by the 'ort' strategy.
 author.md | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 author.md

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 864 bytes | 216.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/lindelaani/demo.git
   86a79ea..b2e78ab  master -> master

Lindelani@DESKTOP-7JO8JOO MINGW64 ~/demo/demo/demo (master)
This is my second repository
