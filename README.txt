To create single pager temporary website, untill regular dynamic site with blog articles is ready for AON Agency.

To change the master branch to live (rename) use commands below
git branch -m master live
git fetch origin
git branch -u origin/live live
git remote set-head origin -a
