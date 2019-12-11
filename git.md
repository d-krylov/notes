To create a new branch and switch to it at the same time
```
git checkout -b BranchName
```

What has changed in a file before committing to git?
```
git diff HEAD
```

Diff between two commits
```
git diff OldCommit NewCommit
```

Get diff name changing files
```
git diff --name-only origin
```

Sync master fork with master base
```
git remote add upstream UpstreamName
git fetch upstream
git merge upstream/master
```

Add remote repository
```
git remote add RepositoryName RepositoryURL
```

Enables arbitrary Git commits to be picked by reference and appended to the current working HEAD (-n - no commits)
```
git cherry-pick -n CommitHash
```

Reset changes
```
git reset --hard HEAD^
```
