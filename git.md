To create a new branch and switch to it at the same time
```
git checkout -b BranchName
```
What has changed in a file before committing to git?
```
git diff HEAD
```
Sync master fork with master base
```
git remote add upstream UpstreamName
git fetch upstream
git merge upstream/master
```
