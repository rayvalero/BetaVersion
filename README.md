# BetaVersion

Run

$ git config --global user.email "you@example.com"

$ git config --global user.name "Your Name"

$ git init "namefile"

$ cd "namefolder"

$ git clone git://github.com/schacon/ticgit.git

Initialized empty Git repository in /private/tmp/ticgit/.git/
remote: Counting objects: 595, done.
remote: Compressing objects: 100% (269/269), done.
remote: Total 595 (delta 255), reused 589 (delta 253)
Receiving objects: 100% (595/595), 73.31 KiB | 1 KiB/s, done.
Resolving deltas: 100% (255/255), done.

$ cd ticgit
$ git remote

origin

$ git remote -v

origin  git://github.com/schacon/ticgit.git (fetch)
origin  git://github.com/schacon/ticgit.git (push)

$ git add "namefile"

$ git commit -m "namefile"

$ git push origin master


