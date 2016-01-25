# BetaVersion

Run

$ git config --global user.email rayvalero177

$ git config --global user.name RayValero

$ git init ray

$ cd ray

$ cd ..

$ git clone https://github.com/ULAnux/mathematica

Cloning into 'mathematica'...
remote: Counting objects: 46, done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 46 (delta 4), reused 46 (delta 4), pack-reused 0
Unpacking objects: 100% (46/46), done.
Checking connectivity... done.


$ cd mathematica

$ git remote

origin

$ git remote -v

origin  https://github.com/ULAnux/mathematica (fetch)
origin  https://github.com/ULAnux/mathematica (push)

$ git clone https://github.com/rayvalero/BetaVersion

Cloning into 'BetaVersion'...
remote: Counting objects: 14, done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 14 (delta 1), reused 2 (delta 0), pack-reused 0
Unpacking objects: 100% (14/14), done.
Checking connectivity... done.

$ cd BetaVersion/

$ git add README2.md

$ git commit -m README2.md

$ git push origin master

Counting objects: 2, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 270 bytes | 0 bytes/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/rayvalero/BetaVersion
7ebcb51..ba658da  master -> master

$ git fetch origin

remote: Counting objects: 3, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rayvalero/BetaVersion
   ba658da..d684ae7  master     -> origin/master

$ git pull

remote: Counting objects: 3, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rayvalero/BetaVersion
   d684ae7..d6e0c31  master     -> origin/master
Updating ba658da..d6e0c31
Fast-forward
 README.md | 33 +++++++++++++++++++++++++++++++--
 1 file changed, 31 insertions(+), 2 deletions(-)
 



