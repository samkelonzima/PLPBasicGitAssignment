contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git init
Initialized empty Git repository in C:/Users/contr/PLPBasicGitAssignment/.git/

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git add remote ^[[200~https://github.com/samkelonzima/PLPBasicGitAssignment~
fatal: pathspec 'remote' did not match any files

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/samkelonzima/PLPBasicGitAssignment

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -u
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello

nothing added to commit but untracked files present (use "git add" to track)

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -u origin main
error: pathspec 'origin' did not match any file(s) known to git
error: pathspec 'main' did not match any file(s) known to git

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -u main
error: pathspec 'main' did not match any file(s) known to git

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -u master
error: pathspec 'master' did not match any file(s) known to git

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -u first commit
error: pathspec 'first' did not match any file(s) known to git
error: pathspec 'commit' did not match any file(s) known to git

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (master)
$ git branch -m main

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git add hello.txt

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git commit -m add hello.txt with a greeting
error: pathspec 'with' did not match any file(s) known to git
error: pathspec 'a' did not match any file(s) known to git
error: pathspec 'greeting' did not match any file(s) known to git

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git commit -m helo.txt
[main (root-commit) 0cd9951] helo.txt
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 222 bytes | 13.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/samkelonzima/PLPBasicGitAssignment
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

contr@DESKTOP-2GKBD38 MINGW64 ~/PLPBasicGitAssignment (main)
$
