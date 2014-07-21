rails-base
====================
Skeleton for new Rails based projects

Quick start
--------------------
Clone application as new project with original repository named "rails-base"
```
git clone git://github.com/yaeda/rails-base.git --origin rails-base [NEW-PROJECT]
```

Create new repo on GitHub and push master into it. Make sure master branch is tracking origin repo.
```
git remote add origin git@github.com:yaeda/[NEW-PROJECT].git
git push -u origin master
```

How to update existing project with new changes from rails-base repository
--------------------
Fetch latest changes from rails-base repo and merge or cherry-pick commits
```
git fetch rails-base
git checkout -b rails-base-update
git merge rails-base/master

# fix conflicts
# commit
# test

git checkout master
git merge rails-base-update
git branch -d rails-base-update
```
